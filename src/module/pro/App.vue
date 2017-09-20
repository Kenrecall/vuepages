<template>
  <div id="app">
    <img src="./images/logo.png">
    <div>pro详情内容</div>
    <a href="../index.html">点击跳转主页</a>

  </div>
</template>

<script>
  import 'common/css/reset.css';
  import Hello from 'components/Hello/Hello'

  export default {
    name: 'app',
    components: {
      Hello
    },
    methods:{
      goin(){
        window.location.href= '../index.html'
      }
    }

  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
  .co{
    width:100%;
    height: 300px;
    background:-webkit-linear-gradient(top, rgba(215,155,55,1) 30%, rgba(255,255,255,0));
  }
</style>
