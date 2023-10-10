<template>
  <div id="app">
    <nav>
      <img src="./assets/logoEstigma.png" alt="">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/services">Services</router-link> |
      <router-link to="/store">Store</router-link> |
      <router-link to="/login">Login</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style>
:root{
    --dark-blue: #1d273b;
    --middle-blue: #2570ff;
    --light-blue: #5D6678;
    --purple-blue: #667db6;
    --gray:#adb6c7;
    --light-green: #1FDE82;
    --white: #fff;
    --light-gray: #f2f2f2;
    --white-gray: #f2f5fc;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}

nav {
  padding: 30px;
  display: flex;
  align-items: center;
  justify-content: center;
  
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  
}

nav a.router-link-exact-active {
  color: #42b983;
}

img {
  margin: 2px;
  width: 100px;
  gap: 2px;
 
}
</style>
