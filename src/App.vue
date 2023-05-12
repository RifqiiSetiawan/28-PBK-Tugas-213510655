<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/Mytodolistapp">Apps</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Helvetica;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body{
  margin: 0;
}
body::-webkit-scrollbar {
  display: none;
}
nav {
  padding: 5px;
  background-color: #E08E6D;
  display: flex;
  justify-content: center;
  margin-bottom: 40px;
}

nav a {
  font-size: 20px;
  color: #2c3e50;
  text-decoration: none;
  margin: 20px;
}

nav a.router-link-exact-active {
  color: #E5F9DB;
}

</style>
