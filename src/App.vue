<template>
  <div id="app">
    <h1>Integra-chat</h1>
    <Chat />
  </div>
</template>

<script>
import Chat from "./containers/Chat.vue"
//import axios from 'axios'
import _ from './env'

export default {
  name: 'app',
  components: {
    Chat
  },
  data: () => {
    return {
      message: '',
      intent: '',
      time: '',
      url: _,
    }
  },
  mounted: () => {

  },
}
</script>

<style>
#app {
  max-width: 350px;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  border: 1px solid green;
  border-radius: 5px;
  background-color: #ededed;
}
</style>
