<template>
    <header>
      <img alt="Vue logo" src="@/assets/img/la-molisana-logo.png">s
      <nav>
        <a href="#">Home</a>
        <a class="active" href="#">Prodotti</a>
        <a href="#">Chi siamo</a>
        <a href="#">Contatti</a>
      </nav>
    </header>
</template>

<style lang="scss" scoped>
header{
    text-align: center;
}
nav{
    margin: 2rem 0;

    a{
        text-decoration: none;
        padding: 0.5rem 1rem;
        font-size: 0.9rem;
        color: #333;
        font-weight:600 ;

        &.active{
             background-color: lightblue;
        }
        &:hover{
            background-color: rgb(206, 240, 251);
        }
    }
}

</style>