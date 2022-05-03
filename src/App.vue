<template>
  <div id="app">
    <SiteHeader/>
    <main>
      <h1>Lista prodotti</h1>
    </main>
    <SiteFooter/>

  </div>
</template>

<script>
import SiteHeader from '@/components/HeaderComponent.vue';
import SiteFooter from '@/components/FooterComponent.vue';


export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteFooter,
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}

main{
  background-image: url('@/assets/img/fondo-pag-speciali.jpg');
  min-height: 50vh;
  background-size: cover;
}

/* Grid System */

.container{
  margin: auto;
  max-width: 1440px;
}

.row{
  display: flex;
  flex-wrap: wrap;
}
.col{
  flex-grow:1;
}
</style>
