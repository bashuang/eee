<template>
  <div id="app">
    这是dev分支
<<<<<<< HEAD
    <Login></Login>
=======
    <router-view/>
>>>>>>> 2bd740250cac4c35f5aa59aac37994eeb189619d
  </div>
</template>
<script>
  import Login from './components/login.vue'
    export default {
        name: 'App',
        components:{
            Login
        }
    }
</script>
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
