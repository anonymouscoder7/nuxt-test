<template>
    <nav>
      <ul>
        <li><nuxt-link to="/">Home</nuxt-link></li>
        <li><nuxt-link to="/about">About</nuxt-link></li>
        <li><nuxt-link to="/contact">Contact</nuxt-link></li>
        <li><nuxt-link to="/user">User</nuxt-link></li>
        <li><nuxt-link to="/admin">Admin</nuxt-link></li>
      </ul>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'Navbar'
  }
  </script>
  
  <style scoped>
  nav {
    background-color: #333;
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
  