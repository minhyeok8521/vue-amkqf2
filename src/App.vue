<template>
  <Hello msg="Welcome to Your Vue.js App" />
</template>

<script>
// component
import Hello from './views/Hello.vue';

// css
import './assets/css/common.css';

export default {
  name: 'App',
  components: {
    Hello,
  },
};
</script>
