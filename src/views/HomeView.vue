<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HomeView/>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeView from '@/components/HomeView.vue'

export default {
  name: 'HomeView',
  components: {
    HomeView
  }
}
</script>
