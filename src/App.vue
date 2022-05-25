<template>
 <div id="app">
   <message v-if="showMsg" msg="vue.js lifecycle hooks"></message>
  <button @click="showMsg = false">Hide message</button>
 </div>
</template>

<script>
import Message from './components/Message';
export default {
  name:'App',
  components: {
    Message
  },
  data(){
    return{ 
      showMsg: true
    }
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
