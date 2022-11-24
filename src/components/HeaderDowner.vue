<template>
  <div id="header-downer">
    
    <div id="jumbotron"></div>
    
    <div id="cards-container">
      <CardComp />
    </div>
  </div>
</template>

<script>
import CardComp from './CardComp.vue'

export default {
  name: 'HeaderDowner',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

#header-downer{
    background-color: #1C1C1C;
    color: white;

      #jumbotron{
        height: 40vh;
        background-image: url('../assets/img/jumbotron.jpg');
        background-size: cover;
        object-fit: cover;
        background-position: top;
      }
    
}

</style>