<template>
  <footer>
      <div class="container">
          <div class="row  text-center">
              <div class="col">
                  <img src="@/assets/img/la-molisana-logo.png" alt="">

                  
              </div>
              <div class="col">
                  <h3>Pastificio</h3>
                  <ul>
                      <li>Il Patificio</li>
                      <li>Grano</li>
                      <li>Filiera</li>
                      <li>100 anni di pasta</li>
                      <li>Storia della pasta</li>
                  </ul>
              </div>
              <div class="col">
                  <h3>Pastificio</h3>
                  <ul>
                      <li>Il Patificio</li>
                      <li>Grano</li>
                      <li>Filiera</li>
                      <li>100 anni di pasta</li>
                      <li>Storia della pasta</li>
                  </ul>
              </div>
          </div>
      </div>
  </footer>
</template>

<script>
export default {
    name:'FooterComponent',
}
</script>

<style lang="scss" scoped>
footer{
    background-image: url('@/assets/img/footer-montagne-bottom.jpg');
    background-repeat:no-repeat ;
    background-position: bottom;
    padding-top: 3rem;
    height: 400px;

    h3{
        font-size: 1.5rem;
        margin-bottom:1rem;
    }

    
    ul{
    list-style: none;
    line-height: 1.5rem;
    }
}


</style>