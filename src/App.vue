<template>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: black;
}

nav {
  padding: 30px; 
}

nav a {
  font-weight: bold;
  color: #42b983;
  margin: 0 10px;
}

nav a.router-link-exact-active {
  color: #ffffff;
}

</style>