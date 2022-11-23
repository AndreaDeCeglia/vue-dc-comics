<template>
    <footer>
        <FooterUpper />
    </footer>
</template>

<script>
import FooterUpper from './FooterUpper.vue'

export default {
  name: 'FooterComp',
  props: {
    msg: String
  },
  components: {
    FooterUpper,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>