<template>
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-12">
        <div class="home">
          <h1>{{ $store.state.myName }}</h1>
          <img alt="Vue logo" src="../assets/logo.png">
          <HelloWorld msg="Welcome to Your Vue.js App"/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
