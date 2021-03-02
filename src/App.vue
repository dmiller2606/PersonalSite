<template>
  <div class="root">
    <navbar/>
    <landing/>
  </div>
</template>

<script>
import landing from './components/landing.vue';
import navbar from './components/navbar.vue';

export default {
  name: 'App',
  components: {
    navbar,
    landing,
  },
};
</script>
