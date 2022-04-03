<template>
  <nav>
    <router-link to="/">Home</router-link> 
    <router-link to="/sabores">Sabores</router-link>
    <router-link to="/adornos">Adornos</router-link>
    <router-link to="/seleccion">Seleccion</router-link>
    <router-link to="/ordenes">Ordenes</router-link>
    <router-link to="/pastelero">Pastelero</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background: radial-gradient(circle, rgba(255,222,195,1) 0%, rgba(161,137,153,1) 100%);
  height: 100%;
  
}
*{
  margin: 0;
  padding: 0;
}
nav {
    width: 100%;
    height: 50px;
    background: #ffffff;
    margin-top: 2%;
}

nav a {
    width: 200px;
    height: 10px;
    color: #ffffff;
    text-decoration: none;
    margin: 0 20px;
    padding-top: 8px;
    background: #545454;
    padding-left: 10px;
    padding-right: 10px;
    padding-bottom: 10px;
    border-radius: 1rem;
}

nav a.router-link-exact-active {
  color: rgba(255,222,195,1);
}

</style>
