<template>
  <home-component />
</template>

<script>
  import {defineAsyncComponent} from 'vue'

  // import HomeComponent from './components/HomeComponent.vue';

  const  HomeComponent = defineAsyncComponent(()=> import('./components/HomeComponent.vue'));
  
  export default {
    components:{
      HomeComponent
    }
  }

</script>

<style scoped>
</style>
