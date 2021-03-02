<template>
  <navbar/>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import navbar from './components/navbar.vue'

export default {
  name: 'App',
  components: {
    navbar,
    HelloWorld
  }
}
</script>
