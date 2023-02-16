<template>
  <div id="app">
    <Header/>
    <div class="content">
      <HomeView/>
    </div>
  </div>
</template>

<script>
import HomeView from './components/HomeView.vue'
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header,
    HomeView
  }
}
</script>

<style lang="scss">
body {
  margin: 0;
  min-height: 100vh;
  background-image: url(~@/assets/backgroundHome.jpg);
  background-size: 100% 100%;
  background-repeat: no-repeat;
  
}

 

#app {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100vw;
  flex-direction: column;
  
  
  >.content {
    background-color: white;
    min-height: 100vh;
    max-width: 900px;
    width: 100%;
    padding: 0 15px;
    padding-top: 15px;
  }
}


</style>