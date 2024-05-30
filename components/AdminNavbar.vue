<template>
    <nav>
      <ul>
        <li><nuxt-link to="/admin">Admin Home</nuxt-link></li>
        <li><nuxt-link to="/">Frontend Home</nuxt-link></li>
      </ul>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'AdminNavbar'
  }
  </script>
  
  <style scoped>
  nav {
    background-color: #444;
    padding: 1rem;
  }
  ul {
    list-style: none;
    display: flex;
    justify-content: space-around;
    margin: 0;
    padding: 0;
  }
  li {
    margin: 0;
  }
  a {
    color: #fff;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  </style>
  