<template>
<div class="page-container">
<nav-menu></nav-menu>
<transition name="fade">
<router-view></router-view>
</transition>
</div>
</template>
<script>
import { NavMenu } from './../components/page'
export default {
  components: {
    NavMenu
  }
}
</script>