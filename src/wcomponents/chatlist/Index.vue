<template>
  <div class="tile is-vertical is-3 chatlist" id="main-container">
    <section id="left-navigation" style="height: 100%;">
        <header class="dropdown header-box-yy">
            <div id="user_menu">
                <div data-toggle="dropdown" class="menuDropdown js-menuDropdown">
                    <div id="current_user_avatar"><img class="member_image thumb_48 logo js-my-logo" src="https://img.sobot.com/console/common/face/admin.png" id="mylogo"></div><span id="current_user_name" class="overflow_ellipsis js-customer-service" title="李">李</span> <i class="connection_icon js-status-image online"></i> <span id="connection_style" class="js-server-group">超级管理员</span> <span id="connection_status" style="display:none">离线</span></div>
                <div class="dropdown-menu dropdown-menu-right menu status-user js-status-menu">
                    <ul class="js-statusList">
                        <li class="js-status" data-status="1"><span class="user-icon-online">在线</span></li>
                        <li class="js-status" data-status="2"><span class="user-icon-busy">忙碌</span></li>
                        <li class="js-status js-offlineStatus" data-status="0"><span class="user-icon-offine">离线</span></li>
                    </ul>
                </div>
            </div>
        </header>
        <div class="tab-content">
            <div class="tab-pane js-history-outer zc-scroll" id="history" style="overflow-y: hidden; outline: none; padding: 0px; height: 298px; display: block;">
                <div class="js-history-search-tab history-search-tab">
                    <div class="search-input js-search-input-wrap">
                        <input name="" placeholder="搜索客户昵称/聊天记录" class="input js-search-input" value=""> <span class="close-icon js-search-close-icon hide"></span> <span class="search-btn js-search-btn" type="button" name="button"></span></div>
                </div>
                <div class="js-search-list-wrap search-list-wrap hide">
                    <div class="search-menu js-search-menu-wrap">
                        <ul>
                            <li><span class="active js-search-menu">全部</span></li>
                            <li><span class="js-search-menu">客户</span></li>
                            <li><span class="js-search-menu">会话</span></li>
                        </ul>
                    </div>
                    <div class="user-list-wrap js-search-user-list">
                        
                        <div class="data-list none-tips-wrap js-none-tips-wrap"><span class="js-none-tips none-tips">输入关键词，按回车开始搜索</span></div>
                    </div>
                </div>
                <div class="js-normal-list-wrap normal-list-wrap">
                    <div class="radio-inline radio-box-yy">
                        <label class="radio-inline js-switch-label active switch-first-label" data-key="history"><span id="optionsRadios3" value="1" class="js-history-item history-item">全部</span></label>
                        <label class="radio-inline js-switch-label switch-second-label" data-key="star"><span id="optionsRadios3" value="2" class="js-history-item history-item">星标</span></label>
                        <label class="radio-inline js-switch-label switch-second-label" data-key="blacklist"><span id="optionsRadios3" value="3" class="js-history-item history-item">黑名单</span></label>
                    </div>
                    <div id="historylist" class="leftScroll zc-scroll" tabindex="1" style="height: 174px;">
                        <ul class="history-list js-history-list js-users-list js-removeActive" style="border-top: 0px solid #ddd">
                            <li titemle="品客微商城" class="user-list-item history" id="chat650ecbd5d47f351bde96f7e8ac9fe2f1" data-uid="650ecbd5d47f351bde96f7e8ac9fe2f1" data-cid="d3a7cfc5861f44908eef543b5cefbef7"> <i class="icon face js-icon offline">  <img src="http://wx.qlogo.cn/mmopen/DYqn7TU9icq2E5x9fhOqoVP06pl882y6vgwJqnribxCklficXzVOL9JB8Vxxccr7eKKmkylLiaAutjQibKW5yUB2viaA/0" class="js-image-face" style="display: inline-block;">  <span class="badge badge-red js-unread-count" style="padding:2px 5px">1</span></i>
                                <div class="item-detail">
                                    <div class="unameWidely"> <span class="uname js-user-name"> 品客微商城</span> <span class="sortNum">  </span> </div> <span class="chat-detail js-last-message "></span>
                                    <div class="funIco"> <i class="starUser starUserHide js-starUser"></i> <i class="startopIcon js-startopIcon hidestartopIcon"></i> <span class="status js-user-status"></span> </div> <i class="user-del js-remove" data-cid="d3a7cfc5861f44908eef543b5cefbef7" data-uid="650ecbd5d47f351bde96f7e8ac9fe2f1"> <span class="newIcon"></span> </i> </div>
                                <p class="receiveTime js-receiveTime">undefined</p>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>
  </div>
</template>
<script>
export default{
  components: {
  },
  data () {
    return {}
  },
  computed: {
  },
  methods: {

  },
  mounted () {

  }
}
</script>
<style lang="less">
#main-container {
    overflow: hidden;
}
#main-container #left-navigation {
    background: #f2f7f7;
    // width: 291px;
    // position: absolute;
    // left: 0;
    border-right: 1px solid #dee8e9;
    overflow: hidden !important;
}
#main-container #left-navigation .header-box-yy {
    // width: 290px;
    height: 80px;
    background: #f2f7f7;
    position: relative;
    border-bottom: 1px solid #e0e8e8;
}
#main-container #left-navigation .header-box-yy #user_menu {
    font-size: 16px;
    font-weight: 900;
    color: white;
    width: 180px;
    height: 80px;
    float: left;
    cursor: pointer;
    background: #f2f7f7;
    border-top: 2px solid #f2f7f7;
    padding: 20px 0 20px 20px;
}
#user_menu {
    float: left;
    width: 200px;
    cursor: pointer;
    background: #3e313c;
    border-top: 2px solid #372c36;
    padding: 7px 0 9px 8px;
    height: 4rem;
    position: absolute;
    bottom: 0;
    left: 0;
}
#main-container #left-navigation .header-box-yy #user_menu .menuDropdown {
    height: 40px;
    margin: 0;
    position: relative;
}#main-container #left-navigation .header-box-yy #user_menu .menuDropdown #current_user_avatar {
    width: 40px;
    border-radius: 50%;
    overflow: hidden;
    margin-right: 12px;
    float: left;
}
ul, div, p, h1, img {
    list-style: none;
    padding: 0;
    margin: 0;
    -webkit-user-drag: none;
}
#main-container #left-navigation .header-box-yy #user_menu .menuDropdown #current_user_avatar .member_image {
    width: 40px;
    height: 40px;
}
#main-container #left-navigation .header-box-yy #user_menu .menuDropdown #current_user_name {
    color: #555556;
    /* font-size: 16px; */
    font-size: 14px;
    /* font-weight: 900; */
    /* font-family: 'Lato', sans-serif; */
    font-family: 'Microsoft YaHei';
    position: absolute;
    display: inline-block;
    max-width: 100px;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    left: 53px;
    top: 3px;
    line-height: 16px;
}
#current_user_name {
    color: white;
    font-weight: 900;
    font-family: 'Lato', sans-serif;
    line-height: 1.5rem;
    margin-top: .2rem;
    max-width: 120px;
}
#user_menu i {
    position: absolute;
    color: #a09a9f;
    top: 1.5rem;
    right: 1rem;
    font-size: 1rem;
    -webkit-transitionDISABLED: color .1s ease-out;
    -moz-transitionDISABLED: color .1s ease-out;
    -o-transitionDISABLED: color .1s ease-out;
    transitionDISABLED: color .1s ease-out;
}
#user_menu i.connection_icon {
    height: 14px;
    width: 14px;
    position: absolute;
    top: 30px;
    left: 30px;
}
#user_menu i.connection_icon.online {
    background-image: url(http://static.sobot.com/chat/admins/img/online-c97ca574c5.png);
}
#main-container #left-navigation .header-box-yy #user_menu .menuDropdown #connection_style {
    position: absolute;
    left: 53px;
    bottom: 2px;
    font-size: 12px;
    font-family: 'Microsoft YaHei';
    color: #999;
}
#connection_status {
    margin-left: 1rem;
    line-height: 1.1rem;
    position: absolute;
    top: 28px;
    left: 63px;
}
#main-container #left-navigation .header-box-yy #user_menu .status-user {
    height: 0px !important;
    display: block;
    overflow: hidden;
    box-sizing: border-box;
    border-width: 0px;
    -webkit-transition: height 0.2s ease-in-out, border-width 0.2s ease-in-out;
    transition: height 0.2s ease-in-out, border-width 0.2s ease-in-out;
}
#main-container #left-navigation .header-box-yy #user_menu .status-user {
    min-width: 66px;
    width: 66px;
    left: 52px;
    top: 68px;
    height: 92px;
    border: 1px solid #09aeb0;
    padding: 0;
    border-radius: 2px;
}
.dropdown-menu {
    position: absolute;
    top: 100%;
    left: 0;
    z-index: 1000;
    display: none;
    float: left;
    min-width: 160px;
    padding: 5px 0;
    margin: 2px 0 0;
    font-size: 14px;
    text-align: left;
    list-style: none;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid #ccc;
    border: 1px solid rgba(0,0,0,.15);
    border-radius: 4px;
    box-shadow: 0 6px 12px rgba(0,0,0,.175);
}
#main-container #left-navigation .header-box-yy #user_menu .status-user li {
    padding: 0;
    height: 30px;
    line-height: 30px;
    color: #555555;
    font-size: 12px;
}
.menu ul li {
    text-align: center;
    display: block;
    background: white;
    color: #645563;
    font-weight: 400;
    text-decoration: none;
    padding: .3rem 1.4rem .3rem 2.5rem;
    overflow: hidden;
    white-space: nowrap;
    border-bottom: 1px solid white;
    outline: 0;
    color: #645563;
}
#main-container #left-navigation .header-box-yy #user_menu .status-user li .user-icon-online {
    background-image: url(http://static.sobot.com/chat/admins/img/online-c97ca574c5.png);
    background-repeat: no-repeat;
    padding: 1px 0px 1px 16px;
    color: #3d4966;
    font-size: 12px;
}
#main-container #left-navigation .header-box-yy #user_menu .status-user li .user-icon-busy {
    background-image: url(http://static.sobot.com/chat/admins/img/busy-25230f2270.png);
    background-repeat: no-repeat;
    padding: 1px 0px 1px 16px;
    color: #3d4966;
    font-size: 12px;
}
#main-container #left-navigation .header-box-yy #user_menu .status-user li {
    padding: 0;
    height: 30px;
    line-height: 30px;
    color: #555555;
    font-size: 12px;
}
#main-container #left-navigation .header-box-yy #user_menu .status-user li .user-icon-offine {
    background-image: url(http://static.sobot.com/chat/admins/img/offline-8c87a1672e.png);
    background-repeat: no-repeat;
    padding: 1px 0px 1px 16px;
    font-size: 12px;
    color: #3d4966;
}
#main-container #left-navigation .tab-content {
    background-color: #f2f7f7;
}
#left-navigation .tab-pane {
    overflow-x: hidden;
}
#main-container #left-navigation .tab-content #history .history-search-tab {
    width: 100%;
    height: 58px;
    font-size: 14px;
    border-bottom: 1px solid rgba(88,89,91,0.1);
}
#main-container #left-navigation .tab-content #history .history-search-tab .search-input {
    width: 90%;
    height: 30px;
    background: #E4EDED;
    margin: 0 auto;
    position: relative;
    margin-top: 14px;
    margin-left: 14px;
    border: 1px solid #e4eded;
}
#main-container #left-navigation .tab-content #history .history-search-tab .input {
    outline: none;
    border: none;
    text-indent: 10px;
    height: 30px;
    line-height: 30px;
    box-shadow: none;
    // width: 200px;
    background: transparent;
}
#main-container #left-navigation .tab-content #history .history-search-tab .close-icon {
    width: 20px;
    height: 20px;
    line-height: 26px;
    display: inline-block;
    cursor: pointer;
    background-image: url(http://static.sobot.com/chat/admins/img/search-history-4b0fce4d05.png);
    background-position: 22px 4px;
    position: absolute;
    top: 5px;
    right: 30px;
}
#main-container #left-navigation .tab-content #history .history-search-tab .search-btn {
    width: 20px;
    height: 20px;
    line-height: 26px;
    display: inline-block;
    cursor: pointer;
    background-image: url(http://static.sobot.com/chat/admins/img/search-history-4b0fce4d05.png);
    background-position: 3px 2px;
    position: absolute;
    top: 6px;
    right: 6px;
}
#main-container #left-navigation .tab-content #history .search-list-wrap {
    font-size: 14px;
}
.hide {
    display: none!important;
}
#main-container #left-navigation .tab-content #history .search-list-wrap .search-menu {
    width: 100%;
    height: 38px;
    border-bottom: 1px solid #ddd;
}
#main-container #left-navigation .tab-content #history .search-list-wrap .search-menu ul {
    padding: 0;
    margin: 0;
}
#main-container #left-navigation .tab-content #history .search-list-wrap .search-menu ul li {
    padding: 0;
    margin: 0;
    display: inline-block;
    width: 32%;
    text-align: center;
    line-height: 36px;
}
#main-container #left-navigation .tab-content #history .search-list-wrap .search-menu ul li span.active {
    border-bottom: solid 3px #0DAEAF;
    -webkit-transition: ease-in-out all .3s;
    transition: ease-in-out all .3s;
    color: #0DAEAF;
}
#main-container #left-navigation .tab-content #history .search-list-wrap .search-menu ul li span {
    width: 80%;
    display: inline-block;
    line-height: 31px;
    cursor: pointer;
}
.zc-scroll {
    overflow-y: auto;
}
#main-container #left-navigation .tab-content #history .search-list-wrap .user-list-wrap .tab-wrap.active {
    display: block;
}
#main-container #left-navigation .tab-content #history .radio-box-yy {
    padding: 12px 16px;
    height: 48px;
    line-height: 18px;
    width: 290px;
    /* text-align: center; */
    padding-left: 14px;
    border-bottom: 1px solid #e0e8e8;
}
.radio-inline, .checkbox-inline {
    display: inline-block;
    padding-left: 20px;
    margin-bottom: 0;
    font-weight: 400;
    vertical-align: middle;
    cursor: pointer;
}
#main-container #left-navigation .tab-content #history .radio-box-yy label.switch-first-label {
    margin-left: 0;
    padding-left: 0;
}
#main-container #left-navigation .tab-content #history .radio-box-yy label {
    /* padding-left: 18px; */
    padding-right: 0;
    /* margin-left: 8px; */
    font-size: 14px;
}
.radio-inline, .checkbox-inline {
    display: inline-block;
    padding-left: 20px;
    margin-bottom: 0;
    font-weight: 400;
    vertical-align: middle;
    cursor: pointer;
}
#main-container #left-navigation .tab-content #history .radio-box-yy label.active .history-item {
    background: #0DAEAF;
    color: #fff;
}
#main-container #left-navigation .tab-content #history .radio-box-yy label .history-item {
    color: #999;
    font-size: 12px;
    padding: 3px 10px;
    border-radius: 10px;
}
#main-container #left-navigation .tab-content #history .radio-box-yy label.switch-second-label {
    margin-left: 10px;
    padding-left: 0;
}
#main-container #left-navigation .tab-content #history .leftScroll {
    overflow-y: scroll;
    padding: 0;
    outline: none;
    height: 549px;
}
ul.history-list {
    overflow-x: hidden;
    width: 100%;
}
#main-container #left-navigation .tab-content #history .leftScroll ul li {
    // width: 290px;
    height: 90px;
}
.tab-content li.user-list-item {
    position: relative;
}
.tab-content li.user-list-item {
    width: 100%;
    /* height: 90px; */
    cursor: pointer;
    position: relative;
    background-color: #f2f7f7;
    border-bottom: 1px solid rgba(88,89,91,0.1);
    overflow: hidden;
    -webkit-transition: background 0.3s linear, border-width 0.1s linear;
    transition: background 0.3s linear, border-width 0.1s linear;
}
.tab-content li.user-list-item .icon.face {
    background-color: #60adf6;
    background-position: -98px -235px;
}
.tab-content li.user-list-item.history .icon {
    background-color: #ccc !important;
}
.tab-content li.user-list-item .icon {
    float: left;
    height: 40px;
    width: 40px;
    display: block;
    border-radius: 50%;
    position: relative;
    margin-top: 14px;
    margin-left: 14px;
    background-image: url(http://static.sobot.com/chat/admins/assets/images/newChat1.png);
}
.tab-content li.user-list-item .icon.offline img, .tab-content li.user-list-item .icon.offline.weixin img, .tab-content li.user-list-item .icon.offline.app img, .tab-content li.user-list-item .icon.offline.face img, .tab-content li.user-list-item .icon.offline.weibo img, .tab-content li.user-list-item .icon.offline.rongyun img {
    -webkit-filter: grayscale(100%);
    -moz-filter: grayscale(100%);
    -ms-filter: grayscale(100%);
    -o-filter: grayscale(100%);
    filter: grayscale(100%);
    -webkit-filter: gray;
    filter: gray;
}
.tab-content li.user-list-item .icon img {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    display: none;
}
.tab-content li.user-list-item .icon .badge {
    position: absolute;
    visibility: hidden;
    right: -5px;
    font-family: "Microsoft YaHei";
    font-style: normal;
    top: -4px;
    padding-top: 2px;
}
.badge.badge-red {
    background: #ff7878;
}
.badge {
    display: inline-block;
    min-width: 10px;
    padding: 3px 7px;
    font-size: 12px;
    font-weight: 700;
    line-height: 1;
    color: #fff;
    text-align: center;
    white-space: nowrap;
    vertical-align: baseline;
    background-color: #777;
    border-radius: 10px;
}
.tab-content li.user-list-item .item-detail {
    height: 100%;
    margin-left: 62px;
    padding-top: 12px;
    min-height: 68px;
}
.unameWidely .uname {
    /* float: left; */
    max-width: 130px;
    height: 20px;
    line-height: 20px;
    overflow: hidden;
    display: inline-block;
    vertical-align: bottom;
    text-overflow: ellipsis;
    white-space: nowrap;
    color: #555556;
    font-size: 14px;
    font-family: "Microsoft YaHei";
}
.unameWidely .sortNum {
    color: #b6bebf;
    font-size: 12px;
}
.tab-content li.user-list-item .item-detail .chat-detail {
    color: #999;
    display: block;
    width: 130px;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    margin: 4px 0 8px 0;
    height: 20px;
    font-size: 13px;
}
.starUser {
    display: block;
    float: left;
    width: 20px;
    height: 20px;
    background: url(http://static.sobot.com/chat/admins/img/userListIco-5c38f007fc.png) no-repeat 0px -26px;
    /* background-size: 350px 18px; */
}
.startopIcon {
    width: 10px;
    height: 10px;
    background: url(http://static.sobot.com/chat/admins/img/userListIco-5c38f007fc.png) no-repeat 0px 0px;
    position: absolute;
    top: 0;
    left: 0;
}
.tab-content li.user-list-item .user-del {
    height: 20px;
    width: 20px;
    position: absolute;
    display: block;
    cursor: pointer;
    top: 0px;
    display: none;
    right: 0px;
    background: url(http://static.sobot.com/chat/admins/img/userListIco-5c38f007fc.png) 6px -128px no-repeat;
}
.chatlist{
    max-width: 290px;
}
</style>