<template>
  <div class="tile is-vertical is-3 chatlist">
    <div class="tile">
      <div class="tile is-parent">
        <article class="tile is-child notification is-info">
          <p class="title">Middle tile</p>
          <p class="subtitle">With an image</p>
          <figure class="image is-4by3">
            <img src="http://placehold.it/640x480">
          </figure>
        </article>
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
.chatlist{
    max-width: 260px;
}
</style>