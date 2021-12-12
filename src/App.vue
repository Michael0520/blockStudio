<template>
    <!-- <router-link to="/">Home</router-link> |
    <router-link to="/branding">Branding</router-link> -->
  <router-view/>
</template>

<style lang="scss">
@import "~bootstrap/dist/css/bootstrap.css";
@import "./assets/scss/main.scss";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  // padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

body{
  margin: 0;
  overflow-x: hidden;
  width: 100%;
}
</style>
