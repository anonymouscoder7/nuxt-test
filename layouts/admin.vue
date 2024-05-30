<template>
    <div>
      <AdminNavbar />
      <main>
        <NuxtPage />
      </main>
    </div>
  </template>
  
  <script>
  import AdminNavbar from '~/components/AdminNavbar.vue'
  
  export default {
    name: 'AdminPage',
    components: {
      AdminNavbar,
    }
  }
  
  </script>
  
  <style scoped>
  main {
    min-height: calc(100vh - 60px); /* Adjust based on your header and footer height */
    padding: 1rem;
    box-sizing: border-box;
  }
  </style>
  