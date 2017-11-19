<template>
  <div class="tile">
    <div class="tile is-parent is-vertical chatCont is-9" id="main-content">
        <i class="chatContBg js-chatContBg" style="display:none;"></i>
        <!-- <div class="tile is-parent is-vertical">
            <div class="tile is-child" style="max-height:50px;border:1px solid red;">
                header
            </div>
            <div class="tile is-child" style="overflow-y:auto;height:100px;">
                <div style="height:400px;border:1px solid blue;">center1111</div>
                <div style="height:400px;border:1px solid blue;">center1111</div>
                <div style="height:400px;border:1px solid blue;">center1111</div>
            </div>
            <div class="tile is-child" style="max-height:200px;border:1px solid black;">
                bottom
            </div>
        </div> -->
        <div class="col-md-8 col-xs-8 chat js-TextArea" style="padding: 0px; min-width: 575px;" id="chatcontent">
            <header class="clearfix chat-detail-header">
                <div class="trace-content-outer zc-scroll js-trace-outer disabled" style="">
                    <div class="js-outer-empty outer-empty"><img class="" src="//static.sobot.com/chat/admins/img/loading-0e6e0f46d7.gif">正在加载</div>
                    <ul class="js-trace-ul-outer outer-ul"></ul>
                </div><span class="trace-outer js-trace-btn-outer" style="width: 268px;"><span class="js-trace-title-time"></span> <a class="trace-show-title js-trace-show-title" style="max-width: 258px;">--</a> <a href="#0" class="trace-btn js-trace-btn"></a></span>
                <div class="addButton js-addButton"><a href="javascript:;" class="js-goOut goOut js-star-add" data-type="star" data-handle="add"><i class="goOutIcn addstar"></i>星标 </a><a href="javascript:;" class="js-goOut goOut hide js-star-del" style="color:#09aeb0" data-type="star" data-handle="del"><i class="goOutIcn deldestar"></i>已标记 </a></div>
            </header>
            <div class="scrollBoxParent zc-scroll" id="chat_daijm" style="overflow: auto; outline: none;">
                <div class="js-panel-body panel-body scrollBox">
                    <div class="systeamTextBox js-zc-loadmore">
                        <p class="systeamText loadmore">点击加载更多</p>
                    </div>
                    <div class="day_divider">
                        <p class="systeamText" style="background-color: transparent"> <span class="zc-c-chat-date-line-left"></span> <span class="zc-c-chat-date-line-text">2017-11-15</span> <span class="zc-c-chat-date-line-right"></span> </p>
                    </div>
                    <div class="systeamTextBox">
                        <p class="systeamText">用户和机器人建立会话 18:35:05</p>
                    </div>
                    <div class="msg userCus" data-msg-id="null">
                        <div class="msg_user fl"> <img src="http://wx.qlogo.cn/mmopen/DYqn7TU9icq2E5x9fhOqoVP06pl882y6vgwJqnribxCklficXzVOL9JB8Vxxccr7eKKmkylLiaAutjQibKW5yUB2viaA/0" class="msg_user_img"> </div>
                        <div class="msgContBox fl"> <span class="msg_name">品客微商城</span> <span class="msg_time ml">品客微商城</span> <span class="msg_time" style="margin-left: 0px;">18:35:05</span>
                            <div style="clear:both;"></div>
                            <div class="msgBg fl" style="display: inline-flex;margin: 0px;max-width: 100%"> <i class="angleLeft"></i>
                                <div class="msg_content formUser"> 哈哈 </div>
                            </div>
                        </div>
                    </div>
                    <div class="msg workOrderCus" data-msg-id="null">
                        <div class="msg_user fr"> <img src="https://img.sobot.com/console/common/face/robot.png" class="msg_user_img"> </div>
                        <div class="msgContBox fr"> <span class="msg_name">小智机器人</span> <span class="msg_time">小智机器人</span> <span class="msg_time">18:35:05</span>
                            <div style="clear:both;"></div>
                            <div class="msgBg" style="display: inline-flex;float: right;margin: 0px;max-width: 92%;"> <i class="angleRight"></i>
                                <div class="msg_content">你高兴我就快乐了，(*^__^*)嘻嘻…… </div>
                            </div>
                        </div>
                    </div>
                    <div class="systeamTextBox">
                        <p class="systeamText">用户转人工服务 18:35:20</p>
                    </div>
                    <div class="systeamTextBox">
                        <p class="systeamText">用户和客服 李 建立了会话 18:35:20</p>
                    </div>
                    <div class="msg workOrderCus" data-msg-id="650ecbd5d47f351bde96f7e8ac9fe2f11510742437556">
                        <div class="msg_user fr"> <img src="https://img.sobot.com/console/common/face/admin.png" class="msg_user_img"> </div>
                        <div class="msgContBox fr"> <span class="msg_name">李</span> <span class="msg_time">李</span> <span class="msg_time">18:40:38</span>
                            <div style="clear:both;"></div>
                            <div class="msgBg" style="display: inline-flex;float: right;margin: 0px;max-width: 92%;"> <i class="angleRight"></i>
                                <div class="msg_content">213 </div>
                            </div>
                            <div class="zc-c-chat-admin-ready-error ok" data-token="undefined" data-usermsgid="undefined"><img src="http://www.sobot.com/chat-web/admins_new/img/static/loading.gif"></div>
                        </div>
                    </div>
                    <div class="msg userCus" data-msg-id="409c7c9a01354e998fd68249710998d2">
                        <div class="msg_user fl"> <img src="http://wx.qlogo.cn/mmopen/DYqn7TU9icq2E5x9fhOqoVP06pl882y6vgwJqnribxCklficXzVOL9JB8Vxxccr7eKKmkylLiaAutjQibKW5yUB2viaA/0" class="msg_user_img"> </div>
                        <div class="msgContBox fl"> <span class="msg_name">品客微商城</span> <span class="msg_time ml">品客微商城</span> <span class="msg_time" style="margin-left: 0px;">18:43:50</span>
                            <div style="clear:both;"></div>
                            <div class="msgBg fl" style="display: inline-flex;margin: 0px;max-width: 100%"> <i class="angleLeft"></i>
                                <div class="msg_content formUser"> c </div>
                            </div>
                        </div>
                    </div>
                    <div class="day_divider">
                        <p class="systeamText" style="background-color: transparent"> <span class="zc-c-chat-date-line-left"></span> <span class="zc-c-chat-date-line-text">2017-11-17</span> <span class="zc-c-chat-date-line-right"></span> </p>
                    </div>
                    <div class="systeamTextBox">
                        <p class="systeamText">用户和客服 李 的会话已结束 18:43:13</p>
                    </div>
                </div>
                <div class="js-load-model zc-c-chat-body-load-model hide">
                    <div class="zc-c-chat-body-load-model-icon"></div>
                </div>
            </div>
            <div style="position: absolute; bottom: 0px; width: 100%;" class="botTextBox js-botTextBox">
                
                <p class="userTextNow"></p><span class="faceButton"><a href="#" class="fa face faceIcon js-emotion"></a> <i id="maskFace"></i> </span><span class="picButton"><i id="maskPhoto"></i><form class="js-fileinfo" enctype="multipart/form-data" method="post"><input value="" type="file" class="js-upload" style="opacity:0;position:absolute;left:0;top:0;z-index:10;width:30px;cursor:pointer"><p style="opacity:0;position:absolute;left:30px;top:0;z-index:11;width:300px;height:30px;background:green"></p><i class="photoTag fa upload" style="font-size: 20px"></i></form></span>
                <div style="position:relative">
                    <div id="js-sendMessage" contenteditable="true" class="animatedTextArea form-control msg-send-input sendMessage js-sendMessage zc-scroll" placeholder="请输入.." style="resize: none;max-height: 54px" robot="other"></div><span class="inputPlaceholder js-inputPlaceholder" style="display: block;">输入“#”号键可以快速搜索快捷回复及智能回复内容</span></div>
                <div>
                    <div class="tipNosend js-tipNosend" style="display: none;">
                        <p>内容上限1024字符，已超出0字符</p>
                    </div>
                    <div class="tipArea">
                        <p class="enterTip">按下ctrl+enter换行</p>
                        <button class="js-btnSend btnSend" id="btnSend" type="button" style="display: none;">发送</button>
                        <button class="js-btnSendNoEable btnSendNoEable" type="button" style="display: block;">发送</button>
                    </div>
                </div>
            </div>
        </div>

    </div>
    <div class="tile is-parent">
        <div class="rightBox">
            
        </div>
    </div>
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
#main-content .chat .clearfix {
    height: 52px;
    border-bottom: 1px solid #e6eeec;
    background-color: #fff;
}
article, aside, details, figcaption, figure, footer, header, hgroup, main, nav, section, summary {
    display: block;
}
header.chat-detail-header .trace-content-outer.disabled {
    height: 0px;
    opacity: 0;
}
header.chat-detail-header .trace-content-outer {
    width: 100%;
    height: 405px;
    position: absolute;
    overflow-y: auto;
    display: none;
    box-sizing: border-box;
    opacity: 1;
    -webkit-transition: height 0.2s ease-in-out, opacity 0.2s ease-in-out;
    transition: height 0.2s ease-in-out, opacity 0.2s ease-in-out;
    z-index: 100;
    top: 50px;
    background-color: white;
    border: 1px solid #dee8e9;
    box-shadow: 0px 0px 12px 0px rgba(15, 66, 76, 0.2);
}
header.chat-detail-header .trace-content-outer .outer-empty {
    text-align: center;
    padding: 10px 0px;
}
header.chat-detail-header .trace-content-outer .outer-empty img {
    height: 20px;
    width: 20px;
    vertical-align: middle;
}
header.chat-detail-header .trace-content-outer ul {
    list-style-type: none;
    list-style-position: inside;
    padding: 0px;
    box-sizing: border-box;
    margin: 10px;
}
header.chat-detail-header .trace-outer {
    display: inline-block;
    height: 100%;
    display: none;
    padding: 0px 20px;
    max-width: 500px;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    color: #555556;
    line-height: 51px;
}
header.chat-detail-header .trace-outer span, header.chat-detail-header .trace-outer a {
    margin: 0px 2px;
    font-size: 13px;
}
header.chat-detail-header .trace-show-title {
    max-width: 230px;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    display: inline-block;
    vertical-align: middle;
}
header.chat-detail-header .trace-outer a {
    color: #09aeb0;
}
header.chat-detail-header .trace-outer .trace-btn {
    background-image: url(http://static.sobot.com/chat/admins/assets/images/newChat1.png);
    display: inline-block;
    width: 10px;
    background-position: -157px -51px;
    height: 10px;
}
header.chat-detail-header .trace-outer span, header.chat-detail-header .trace-outer a {
    margin: 0px 2px;
    font-size: 13px;
}
#main-content .chat .clearfix .addButton {
    height: 52px;
    line-height: 52px;
    float: right;
    margin-right: 0px;
    padding: 0 10px;
    border-left: 1px solid #e6eeec;
}
#main-content .chat .clearfix .addButton .goOut {
    margin: 0 5px 0 0;
    position: relative;
    padding-left: 28px;
    font-size: 14px;
    text-decoration: none;
    font-weight: normal;
    color: #a4b2b3;
}
#main-content .chat .clearfix .addButton .goOut .addstar {
    background: url(http://static.sobot.com/chat/admins/img/workOrder-59056a0a7d.png) no-repeat 0px 0;
}
#main-content .chat .clearfix .addButton .goOut .goOutIcn {
    position: absolute;
    left: 5px;
    top: -1px;
    width: 20px;
    height: 20px;
}
.hide {
    display: none!important;
}
#main-content .chat .clearfix .addButton .goOut .deldestar {
    background: url(http://static.sobot.com/chat/admins/img/workOrder-59056a0a7d.png) no-repeat -47px 0;
}


.rightBox {
    border-left: 1px solid #dee8e9;
    width: 100%;
}
.rightBox .panel-body {
    padding: 0;
    min-height: 100px;
}
.chatCont {
    position: relative;
    background-color: #f7fafa;
}
.chatCont .chatContBg {
    position: absolute;
    width: 138px;
    height: 67px;
    top: 390px;
    left: 280px;
    background: url(http://static.sobot.com/chat/admins/assets/images/bgspirt.png) no-repeat;
    background-position: -286px;
}
#chatcontent .scrollBoxParent {
    width: 100%;
    height: 380px;
    /* overflow: hidden; */
    overflow: auto;
    outline: none;
    background-color: #f7fafa;
}
#chatcontent .scrollBoxParent .scrollBox {
    padding: 30px;
}
.scrollBox {
    width: 100%;
}
#chatcontent .systeamTextBox {
    text-align: center;
    margin: 15px auto;
}
#chatcontent .scrollBoxParent .scrollBox .systeamText.loadmore {
    background: none;
    cursor: pointer;
}
#chatcontent .scrollBoxParent .scrollBox .systeamText {
    /* color: #0d81c0; */
    font-size: 12px;
    text-align: center;
    background: #e6eef0;
    display: inline-block;
    margin: 0 auto;
    padding: 2px 15px;
    border-radius: 4px;
}
#chatcontent .systeamText {
    color: #8b898f;
    font-size: 12px;
    text-align: center;
    background: #EAE4E4;
    display: inline-block;
    margin: 0 auto;
    padding: 2px 15px;
    border-radius: 15px;
}
#chatcontent .scrollBoxParent .scrollBox .day_divider {
    background: #f7fafa;
    margin: 1.5rem 0;
    line-height: 1.2rem;
    font-size: 1rem;
    font-family: 'Lato', sans-serif;
    color: #555459;
    font-weight: 900;
    text-align: center;
    cursor: default;
    clear: both;
    position: relative;
    margin-top: 10px;
}
#chatcontent .scrollBoxParent .scrollBox .systeamText {
    /* color: #0d81c0; */
    font-size: 12px;
    text-align: center;
    background: #e6eef0;
    display: inline-block;
    margin: 0 auto;
    padding: 2px 15px;
    border-radius: 4px;
}
#chatcontent .systeamText {
    color: #8b898f;
    font-size: 12px;
    text-align: center;
    background: #EAE4E4;
    display: inline-block;
    margin: 0 auto;
    padding: 2px 15px;
    border-radius: 15px;
}
.zc-c-chat-date-line-left {
    background: url(http://static.sobot.com/chat/admins/img/noReadLine-e069a48492.png);
    width: 177px;
    height: 4px;
    float: left;
    margin-top: 13px;
    background-position: 0px -9px;
}
.zc-c-chat-date-line-text {
    line-height: 30px;
    color: #999999;
    float: left;
    margin-left: 10px;
}
.zc-c-chat-date-line-right {
    background: url(http://static.sobot.com/chat/admins/img/noReadLine-e069a48492.png);
    width: 177px;
    height: 4px;
    float: left;
    margin-top: 13px;
    background-position: 0px -20px;
}
#chatcontent .systeamTextBox {
    text-align: center;
    margin: 15px auto;
}
.msg {
    display: inline-block;
}
.msg {
    margin-top: 20px;
    width: 100%;
}
#chatcontent .scrollBoxParent .scrollBox .userCus .msg_user {
    width: 40px;
    height: 40px;
}
#chatcontent .scrollBoxParent .scrollBox .userCus .fl {
    float: left;
}
.msg_user {
    height: 36px;
    width: 36px;
    float: left;
    margin-right: 10px;
    overflow: hidden;
    border-radius: 50%;
}
#chatcontent .scrollBoxParent .scrollBox .userCus .msg_user .msg_user_img {
    width: 100%;
    height: 100%;
}
#chatcontent .scrollBoxParent .scrollBox .userCus .msgContBox {
    margin-left: 5px;
    max-width: 68%;
}
#chatcontent .scrollBoxParent .scrollBox .userCus .msgContBox .msg_name {
    display: none;
}

.msg_name {
    font-weight: 900;
}
#chatcontent .scrollBoxParent .scrollBox .userCus .msgContBox .msg_time {
    float: left;
    max-width: 290px;
}
.ml {
    margin-right: 10px;
    margin-left: 0px;
}
#chatcontent .scrollBoxParent .scrollBox .workOrderCus .msgContBox .msgBg {
    background-color: #97e6dc;
    line-height: 16px;
    padding: 14px;
    border-radius: 4px;
    margin-top: 15px;
    position: relative;
}
#chatcontent .scrollBoxParent .scrollBox .workOrderCus .msgContBox .msgBg .angleRight {
    width: 0;
    border-style: solid;
    border-color: transparent #97e6dc;
    top: 12px;
    content: "";
    position: absolute;
    border-width: 0px 0px 12px 12px;
    right: -10px;
}
#chatcontent .scrollBoxParent .scrollBox .workOrderCus .msgContBox .msgBg .msg_content {
    margin: 0;
    font-size: 14px;
    line-height: 16px;
}
.zc-c-chat-admin-ready-error {
    float: right;
    width: 18px;
    height: 18px;
    margin-top: 12px;
    margin-right: 12px;
}
.zc-c-chat-admin-ready-error.err img, .zc-c-chat-admin-ready-error.ok img {
    display: none;
}
.zc-c-chat-admin-ready-error img {
    height: 20px;
    width: 20px;
}
.msg_time {
    color: #babbbf;
    margin-left: 10px;
    font-size: 12px;
}
#chatcontent .scrollBoxParent .scrollBox .userCus .msgContBox .msg_time {
    float: left;
    max-width: 290px;
}
.msg_time {
    color: #babbbf;
    margin-left: 10px;
    font-size: 12px;
}
#chatcontent .scrollBoxParent .scrollBox .userCus .msgContBox .msgBg {
    background-color: #fff;
    line-height: 16px;
    padding: 14px;
    border-radius: 4px;
    margin-top: 15px;
    position: relative;
    border: 1px solid #dce5e5;
}
#chatcontent .scrollBoxParent .scrollBox .userCus .msgContBox .msgBg .angleLeft {
    width: 11px;
    height: 10px;
    background: url(http://static.sobot.com/chat/admins/img/leftangle-0eb93e361a.png);
    top: 12px;
    position: absolute;
    left: -10px;
}
#chatcontent .scrollBoxParent .scrollBox .userCus .msgContBox .msgBg .msg_content {
    margin: 0;
    font-size: 14px;
    line-height: 16px;
}
#chatcontent .scrollBoxParent .scrollBox .workOrderCus .msg_user {
    width: 40px;
    height: 40px;
}
#chatcontent .scrollBoxParent .scrollBox .workOrderCus .fr {
    float: right;
}

#chatcontent .scrollBoxParent .scrollBox .workOrderCus .msg_user .msg_user_img {
    width: 100%;
    height: 100%;
}
#chatcontent .scrollBoxParent .scrollBox .workOrderCus .msgContBox {
    margin-right: 20px;
    max-width: 68%;
}

.formUser {
    cursor: pointer;
}
.msg_content {
    margin-top: 5px;
    word-wrap: break-word;
    word-break: break-all;
    white-space: moz-pre-wrap;
    overflow: hidden;
}

#chatcontent .botTextBox {
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
#chatcontent .botTextBox {
    width: 100%;
    position: absolute;
    bottom: 0;
    z-index: 100;
    min-height: 190px;
    background-color: #f7fafa;
    border-top: 1px solid #e6eeec;
    outline: none;
}
#chatlist .botTextBox .userTextNow {
    margin: 0;
    position: absolute;
    top: -30px;
    height: 30px;
    line-height: 30px;
    width: 100%;
    opacity: 0.7;
    padding-left: 12px;
    color: #fff;
    background: rgba(123, 100, 100, 0.5);
    display: none;
    z-index: 999;
    overflow: hidden;
    white-space: nowrap;
}
#chatcontent .botTextBox .faceButton {
    position: absolute;
    left: 20px;
    top: 20px;
}
#chatcontent .botTextBox .faceButton .faceIcon {
    background: url(http://static.sobot.com/chat/admins/assets/images/newChat2.png);
    width: 30px;
    height: 20px;
    background-position: -182px -371px;
    display: inline-block;
    font-size: 20px;
    cursor: pointer;
    -webkit-user-select: none;
    outline: none;
}
.fa {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    -webkit-transform: translate(0, 0);
    transform: translate(0, 0);
}
#chatcontent .botTextBox .faceButton #maskFace {
    width: 35px;
    height: 30px;
    z-index: 1000;
    display: block;
    position: absolute;
    top: -1px;
    left: -3px;
    display: none;
}
#chatcontent .botTextBox .picButton {
    position: absolute;
    left: 55px;
    top: 20px;
}
#chatcontent .botTextBox .picButton #maskPhoto {
    width: 30px;
    height: 25px;
    z-index: 1000;
    display: block;
    position: absolute;
    top: -2px;
    left: -2px;
    display: none;
}
#chatcontent .botTextBox .picButton i.photoTag {
    background: url(http://static.sobot.com/chat/admins/assets/images/newChat2.png);
    width: 25px;
    height: 20px;
    background-position: -221px -371px;
    display: inline-block;
    cursor: pointer;
}
#chatcontent .botTextBox .msg-send-input {
    background-color: rgb(247, 250, 250);
    margin-top: 55px;
    height: 120px;
    min-height: 130px;
    resize: none;
    overflow-y: auto;
    overflow-x: hidden;
    white-space: pre-wrap;
    line-height: 20px;
    font-family: 微软雅黑;
    outline: none;
    border-width: 0px;
    border-style: initial;
    border-color: initial;
    border-image: initial;
}
.inputPlaceholder {
    position: absolute;
    top: 8px;
    left: 4px;
    z-index: 102;
    color: #adb1b1;
    box-sizing: border-box;
    padding: 0 82px 0 10px;
    white-space: pre;
    white-space: pre-wrap;
    word-wrap: break-word;
    font-size: 12px;
    resize: none;
    border: none;
    font-family: "Microsoft Yahei";
}
.tipArea {
    float: right;
    overflow: hidden;
}
.enterTip {
    float: left;
    width: 116px;
    height: 30px;
    line-height: 30px;
    margin-top: 5px;
    color: rgb(191, 191, 191);
    font-size: 12px;
    font-family: 微软雅黑;
}
.btnSend {
    display: none;
    background-color: #09aeaf;
}
.btnSend, .btnSendNoEable {
    float: left;
    margin: 5px 10px 10px 0;
    border: 0;
    width: 80px;
    height: 30px;
    color: #fff;
    font-size: 14px;
    border-radius: 3px;
}
.btnSendNoEable {
    background-color: #e0e8e8;
}
.btnSend, .btnSendNoEable {
    float: left;
    margin: 5px 10px 10px 0;
    border: 0;
    width: 80px;
    height: 30px;
    color: #fff;
    font-size: 14px;
    border-radius: 3px;
}
.form-control {
    display: block;
    width: 100%;
    height: 34px;
    padding: 6px 12px;
    font-size: 14px;
    line-height: 1.42857143;
    color: #555;
    background-color: #fff;
    background-image: none;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-shadow: inset 0 1px 1px rgba(0,0,0,.075);
    -webkit-transition: border-color ease-in-out .15s,-webkit-box-shadow ease-in-out .15s;
    -webkit-transition: border-color ease-in-out .15s,box-shadow ease-in-out .15s;
    transition: border-color ease-in-out .15s,box-shadow ease-in-out .15s;
}

</style>