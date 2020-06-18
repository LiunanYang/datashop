<template>
  <div id="contain">
    <div @click.ctrl="fn">按住ctrl并点击</div>
  </div>
</template>

<script>
export default {
  data () {
    return {

    }
  },
  methods: {
    fn () {
      alert('1')
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
