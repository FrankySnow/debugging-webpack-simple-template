<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div class="buttons">
      <exception-button></exception-button>
      <breakpoint-button></breakpoint-button>
    </div>
  </div>
</template>

<script>
import exceptionButton from './components/exceptionButton.vue'
import breakpointButton from './components/breakpointButton.vue'

export default {
  name: 'app',
  components: {
    exceptionButton,
    breakpointButton
  },
  mounted(){
    console.log('mounted')
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

body {
  background: white;
}

.buttons {
  display: flex;
  justify-content: center;
}
</style>
