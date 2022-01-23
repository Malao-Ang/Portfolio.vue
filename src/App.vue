<template>
  <div class="tap">
    <tap/>
    <router-view></router-view>
  </div>
</template>

<script>
import tap from "@/components/tap.vue"
export default{
  name: "Tap",
  components:{
    tap
  }
}
</script>

<style>
</style>