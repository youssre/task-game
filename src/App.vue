<template>
  <nav-comp></nav-comp>
  <router-view/>
</template>

<script>
import navComp from './components/Nav.vue'
export default {
  components:{
    navComp,
  }
}
</script>
<style lang="scss">
#app{
  font-family: 'Roboto', sans-serif , "pingFangSC-Regular";
}
 *{
  margin: 0%;
  padding: 0%;
  box-sizing: border-box;
 }
 .img-fluid {
    width: 100%;
    height: auto;
}
</style>

