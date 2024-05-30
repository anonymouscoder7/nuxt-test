<template>
  <div>
    <Navbar />
    <main>
      <NuxtPage />
    </main>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue';

export default {
  name: 'default',
  components: {
    Navbar,
  }
}
</script>

<style scoped>
main {
  min-height: calc(100vh - 60px);
  padding: 1rem;
  box-sizing: border-box;
}
</style>
