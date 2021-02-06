<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App" class="base-scroll"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
  .base-scroll {
    background: url('../assets/img/scroll-base.png') repeat-y top center;
  }
</style>
