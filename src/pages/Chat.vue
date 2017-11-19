<template>
<div class="tile is-ancestor">
  <chatlist></chatlist>
  <chatcontent></chatcontent>
</div>
</template>
<script>
import chatlist from './../wcomponents/chatlist'
import chatcontent from './../wcomponents/chatcontent'
export default{
  components: {
    chatlist,
    chatcontent
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
.tile.is-parent{
  padding: 0 !important;
}
.is-ancestor{
  height: 100%;
}
.tile.is-ancestor{
  margin: 0;
}
</style>