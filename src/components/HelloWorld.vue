<template>
  <div class="hello">
   <div class="outer">
     <div class="inner">
       
     </div>
   </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
  .outer {
    width: 200px;
    height: 200px;
    background: red;
    .inner {
      width: 100px;
      height: 100px;
      background: yellow;
    }
  }
</style>
