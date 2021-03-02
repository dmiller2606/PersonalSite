<template>
  <div>
    <img class="background" ref="background" src="../assets/background.jpg" />
    <div class="shadow section" />
    <div class="section section-1" ref="first">
      <div>
        <h1 class="section-1"> David Miller </h1>
      </div>
    </div>
  </div>
</template>

<script>
import {ref} from 'vue';
export default {
  name: 'landing',
  setup() {
    const background = ref(null);
    const first = ref(null);
    return {
      background,
      first,
    };
  },
};
</script>
