<template>
  <div id="app">
    <div id="nav">
      DevHost
      <ul id="nav-links" style="list-style-type:none">
        <li ><router-link to="/">Home</router-link></li>
        <li><router-link to="/events">Events</router-link></li>
        <li><router-link to="/sponsors">Sponsors</router-link></li>
        <li><router-link to="/about">About Us</router-link></li>
      </ul>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: white;
 /* margin-top: 30px; */
  font-size: 40px;
  background-color: #080331;
}
#nav-links a{
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: right;
  color: white;
  margin-top: 30px;
  font-size: 20px;
  background-color: #2c3e50;
}
</style>
