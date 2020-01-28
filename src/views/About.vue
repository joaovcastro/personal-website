<template>
  <div class="work">
    <Card />

    <div class="card">
      <h1>Trialbee AB</h1>
    </div>

    <div class="card">
      <h1>OPT</h1>
    </div>

  </div>
</template>

<script>
import Card from '@/components/Card.vue';

export default {
  name: 'home',
  components: {
    Card,
  },
};
</script>

<style scoped>
  .work {
    text-align: center;
  }

</style>
