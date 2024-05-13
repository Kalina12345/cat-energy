<template>
  <div id="app">
    <TheHeader/>
    <router-view/>
  </div>
</template>

<script>
import TheHeader from '@/components/header.vue'
export default {
  components:{
    TheHeader
  }
}
</script>
