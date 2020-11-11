<template>
  <div id="app">
    <div id="nav">
      <ul id="nav-mobile" class="center hide-on-med-and-down">
        <li><router-link to="/">Home</router-link> |</li>
        <li><router-link to="/about">About</router-link></li>
      </ul>
    </div>
    <router-view/>
  </div>
</template>

<script>
  import M from 'materialize-css'

  export default {
    mounted () {
      M.AutoInit()
    }
  }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}
#nav-mobile>li{
  display: inline-block;
}
#nav-mobile>li:last-child{
  padding-left: 2px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
