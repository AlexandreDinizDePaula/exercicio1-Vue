<template>
  <div id="app">
    <Header/>
    <Menu/>
    <Posts :posts="texts"/>
    <Sidebar/>
  </div>
</template>

<script>

import Header from './components/Header';
import Menu from './components/Menu';
import Sidebar from './components/Sidebar';
import Posts from './components/Posts'

export default {
  name: 'App',
  components: {
    Header,
    Menu,
    Posts,
    Sidebar
  },

  data(){
    return {
      texts: [
        {content: " Texto 1 suadiaudhasiudhas"},
        {content: " Texto 2 suadiaudhasiudhas"},
        {content: " Texto 3 suadiaudhasiudhas"},
        {content: " Texto 4 suadiaudhasiudhas"}
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
