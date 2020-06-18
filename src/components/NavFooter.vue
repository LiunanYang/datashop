<template>
  <div id="footer">
    <p class="footer_text">{{footer_text}}</p>
  </div>
</template>

<script>
export default {
  data () {
    return {
      footer_text: '© 2020 liunan'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#footer{
    width: 100%;
    height: 88px;
    background-color: #e3e4e8;
    position: absolute;
    bottom: 0;
    text-align: center;
}
.footer_text{
    line-height: 88px;
    color: #444444;
}
</style>
