<template>
  <v-app>
    <ComposeScreen/>
  </v-app>
</template>

<script>
import ComposeScreen from "@/components/ComposeScreen"

export default {
  name: 'app',
  components: {
    ComposeScreen
  }
}
</script>

<style>

body{
  background-color: #F6F6F8;
}

#app {
  font-family: Avenir, Helvetica, Arial,'Nanum Gothic', sans-serif;
  -webkit-font-smoothing: antialiased;
  text-align: center;
}
</style>