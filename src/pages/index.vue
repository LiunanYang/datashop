<template>
  <div class="hello">
    <nav-header></nav-header>
    <slideshow></slideshow>
    <nav-footer></nav-footer>
  </div>
</template>

<script>
import NavHeader from '@/components/NavHeader'
import NavFooter from '@/components/NavFooter'
import SlideShow from '@/components/SlideShow'
export default {
  name: 'index',
  data () {
    return {

    }
  },
  components: {
    NavHeader,
    NavFooter,
    SlideShow
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
