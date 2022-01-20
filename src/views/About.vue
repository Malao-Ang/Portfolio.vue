<template>
  <div class="topic">
    <aboutme/>
    <router-view></router-view>
  </div>
</template>

<script>
import home from '../components/home.vue'
import aboutme from '@/components/AboutMe.vue'

export default {
  name: 'Home',
  components: {
    home
  },
  name: 'AboutMe',
  components: {
    aboutme
  }
}
</script>

<style>

</style>
