<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
} */

body {
  background-color: #e9ecef;
  font-family: "Montserrat", sans-serif;
  display: grid;
  grid-template-rows: auto;
  justify-items: center;
  /* align-items: center; */
  padding-top: 50px;
}

body,
html {
  margin: 0;
  height: 100%;
}

#app {
  width: 50%;
}

/* #nav {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
} */

#nav {
  padding: 20px 20px 20px 0;
}

#nav a {
  padding: 10px;
  text-decoration: none;
  background: #fff;
  border-radius: 3px;
  color: rgb(0, 110, 225);
  font-weight: bold;
  margin-right: 15px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
