<template>
  <Header></Header>
  <div class="container mx-atuo">
    <router-view/>
  </div>
</template>


<script>
import Header from './components/Header.vue'
export default {
  name: 'App',
  components:{
    Header
  }
}
</script>

<style>

</style>
