<template>
    <main>
      <h1>Lista prodotti</h1>
      <product-list></product-list>

    </main>
</template>

<script>
import ProductList from '@/components/ProductList.vue'
export default {
    name: 'MainComponent',
    components:{
        ProductList
    },

}
</script>

<style lang="scss" scoped>


</style>