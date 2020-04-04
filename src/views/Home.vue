<template>
  <div class="home">
    <HomePage msg="Welcome to Resume Builder" />
  </div>
</template>

<script>
import HomePage from '@/components/HomePage.vue';

export default {
  name: 'Home',
  components: {
    HomePage,
  },
};
</script>
