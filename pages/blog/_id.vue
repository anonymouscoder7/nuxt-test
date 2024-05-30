<!-- pages/user/_id.vue -->

<template>
    <div>
      <h1>User Profile</h1>
      <p>User ID: {{ userId }}</p>
      <!-- Display user information -->
    </div>
  </template>
  
  <script>
  export default {
    async asyncData({ params }) {
      const userId = params.id;
      // Fetch user data using the ID from params
      // Example: const userData = await fetchUserData(userId);
      
      // Return data to be used in the component
      return {
        userId
        // userData
      };
    }
  };
  </script>
  
  <style>
  /* Add your styles here */
  </style>
  