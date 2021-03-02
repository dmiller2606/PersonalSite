<template>
  <navbar/>
  <landing/>
</template>

<script>
import landing from './components/landing.vue'
import navbar from './components/navbar.vue'

export default {
  name: 'App',
  components: {
    navbar,
    landing
  }
}
</script>
