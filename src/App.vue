<template>
  <router-view />
</template>

<style lang="scss">
@import "~bootstrap/dist/css/bootstrap.css";
@import "./assets/scss/main.scss";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  width: 100%;
}
a {
  color: inherit; /* blue colors for links too */
  text-decoration: inherit; /* no underline */
  &:hover {
    color: inherit; /* blue colors for links too */
    font-weight: bold;
  }
}
body {
  margin: 0;
  overflow-x: hidden;
  width: 100%;
}
</style>
