<template>
    <footer>
        <FooterUpper />
        <FooterDowner />
    </footer>
</template>

<script>
import FooterUpper from './FooterUpper.vue'
import FooterDowner from './FooterDowner.vue'

export default {
  name: 'FooterComp',
  props: {
    msg: String
  },
  components: {
    FooterUpper,
    FooterDowner
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>