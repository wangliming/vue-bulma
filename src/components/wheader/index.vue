<template>
<section id="nav-section" class="hero is-primary">
    <nav class="nav">
    <div class="nav-left">
        <a class="nav-item is-brand" href="#">
        <img src="http://bulma.io/images/bulma-type.png" alt="Bulma logo">
        </a>
        <a class="nav-item" href="/admin/index">
        首页
        </a>
        <a class="nav-item" href="/admin/chat">
        聊天
        </a>
        <a class="nav-item" href="/admin/set">
        设置
        </a>
    </div>

    <div class="nav-left nav-menu">

        <div id="nav-menu" class="nav-right nav-menu" :class="{'is-active': status}">
            <router-link class="nav-item" to="/"><figure class="image is-24x24 is-right-5"><img class="is-circle" src="../../assets/photo.jpg"></figure><span>James Bond</span></router-link>
            <a class="nav-item" @click="logout()"><span class="icon is-small"><i class="fa fa-power-off"></i></span>注销</a>
        </div>
    </div>
    </nav>
</section>
</template>
<script>
export default {
  data () {
    return {
      status: false
    }
  },
  methods: {
    toggle () {
      this.status = !this.status
    },
    logout () {
      // 询问
      // this.$emit('closemodal')
      this.$parent.showModal('logout', '注销', '您确定要注销吗？', 300)
    }
  }
}
</script>
<style lang="less">
    .nav-item{
        font-weight: 500;
    }
</style>
