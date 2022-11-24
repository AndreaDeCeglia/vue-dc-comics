<template>
  <div id="card">
    <img :src="comicsDetails.thumb" alt="">
    <h6> {{ comicsDetails.series }} </h6>
  </div>
</template>

<script>
export default {
  name: 'CardComp',
  props: {
    comicsDetails: Object,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

#card{
  width: calc(100% / 6);
  padding: 1%;

    img{
      width: 100%;
      aspect-ratio: 1/1;
    }
}

</style>