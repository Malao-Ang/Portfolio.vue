<template>
  <html>
  <div class="topic">
    <aboutme/>
    <router-view/>
  </div>
  <div class="my-story">
    <div class="story">
        <p>Hello my name is Pim</p>
    </div>
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
