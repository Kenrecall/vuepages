<template>
  <div id="app">
    <img src="./images/logo.png">
    <br>
    <a href="./detail.html">点击跳转详情页面</a>
    <br>
    <a href="./document.html">点击跳转document</a>
    <br>
    <a href="./pro.html">点击跳转pro</a>
    <br>
    <a href="./work.html">点击跳转work</a>
  </div>
</template>

<script>
//  import 'common/css/reset.css';
  import Hello from 'components/Hello/Hello'
  export default {
    name: 'app',
    components: {
      Hello
    },
    methods:{
      gode(){
          window.location.href ='./detail.html'
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
    font-size: 12px;
  }
</style>
