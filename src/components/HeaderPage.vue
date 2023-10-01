<template>
    <header>
      <h1>{{ title }}</h1>
      <nav>
        <ul>
          <li><a href="#aboutpage">About</a></li>
          <li><a href="#contactpage">Contact</a></li>
        </ul>
      </nav>
    </header>
  </template>
  
  <script>
  export default {
    data() {
      return {
        title: 'My Single Page Website',
      };
    },
  };
  </script>
  
  <style scoped>
  /* Add styling for the header if needed */
  </style>
  