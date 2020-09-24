<template>
  <div class="flex flex-col min-h-screen">
    <appHeader/>
    <appIndex/>
   
    <appFooter/>
  </div>

</template>

<script>

import appHeader from './components/Header.vue';
import appFooter from './components/Footer.vue';
import appIndex from './components/AppIndex.vue';
import appBlock from './components/Block.vue';

export default {
  components:{
    appHeader, appFooter, appIndex, appBlock
  }
}
</script>

<style scoped>

</style>