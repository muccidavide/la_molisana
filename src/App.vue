<template>
  <div id="app">
    <SiteHeader/>
    <SiteMain/>
    <SiteFooter/>

  </div>
</template>

<script>
import SiteHeader from '@/components/HeaderComponent.vue';
import SiteMain from '@/components/MainComponent.vue';
import SiteFooter from '@/components/FooterComponent.vue';


export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteFooter,
    SiteMain,
  },


}
</script>

<style lang="scss">


/* Utility */
@import '@/assets/sass/_common.scss';
@import '@/assets/sass/_common.scss';

.text-center{
  text-align: center;
}

main{
  background-image: url('@/assets/img/fondo-pag-speciali.jpg');
  min-height: 50vh;
  background-size: cover;
  padding-bottom:2rem;
  
h1{
  text-align: center;
  padding: 2rem 0;
}
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}



@import '@/assets/sass/_grid_system.scss'
</style>
