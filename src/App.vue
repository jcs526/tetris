<template>
  <div id="app">
    <router-view/>
    <nav>
      <router-link to="/">Tetris</router-link> |
      <router-link to="/particle">particle</router-link> |
      <router-link to="/cube">cube</router-link>|
      <router-link to="/oracle">oracle</router-link>|
      <router-link to="/excel">excel</router-link>
    </nav>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
