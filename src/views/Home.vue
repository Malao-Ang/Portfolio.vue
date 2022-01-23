<template>
  <div class="homepage">
    <home/>
<router-view/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import home from '../components/home.vue'


export default {
  name: 'Home',
  components: {
    home
  },

}
</script>
