<template>
  <div id="app">
    <img src="./images/logo.png">
    <div>work内容</div>
    <div @click="goin">点击跳转主页</div>
    <a href="./pro.html">点击跳转pro页面</a>
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
