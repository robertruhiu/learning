<template>
  <div id="app">
    <!--<app-message></app-message>-->
    <h4>Lets go somewhere</h4>
    <hr>
    <router-link to="/" >Home</router-link>
    <router-link to="/users/10" >Users</router-link>
    <hr>
    <router-view></router-view>

  </div>
</template>

<script>
export default {

  data () {
    return {

    }
  }
}
</script>

<style>

</style>
