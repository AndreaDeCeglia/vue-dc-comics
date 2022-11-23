<template>
  <header id="header">
    <HeaderUpper />
    <HeaderDowner />
  </header>
</template>

<script>
import HeaderUpper from './HeaderUpper.vue'
import HeaderDowner from './HeaderDowner.vue'

export default {
  name: 'HeaderComp',
  props: {
    msg: String
  },
  components: {
    HeaderUpper,
    HeaderDowner
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

// #header{
//     height: 20%;
// }

</style>