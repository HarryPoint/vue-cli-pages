<template>
  <div id="app">
    <img src="./images/logo.png">
    <hello></hello>
    <p>{{hah}}</p>
  </div>
</template>

<script>
  import 'common/css/reset.css';
  import Hello from 'components/Hello/Hello'

  export default {
    name: 'app',
    data:function(){
      return {
        hah:'xx'
      }
    },
    components: {
      Hello
    }
  }
</script>

<style lang="less">
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
    p{
      display: flex;
    }
  }
</style>
