<template>
  <html>
  <div class="topic">
    <aboutme/>
    <router-view/>
  </div>
  </html>
</template>

<script>
import aboutme from '@/components/AboutMe.vue'

export default {
  name: 'AboutMe',
  components: {
    aboutme
  }
}
</script>

<style>



</style>
