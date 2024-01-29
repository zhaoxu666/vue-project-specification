<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <button @click="demo">ceshi</button>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
  data() {
    return {
      demo: '11',
      demo2: '222',
      message:
        'dsaf12312312312312312dsaf12312312312312312dsaf12312312312312312dsaf12312312312312312dsaf12312312312312312dsaf12312312312312312dsaf12312312312312312',
    };
  },
  methods: {
    demoMethod() {
      const item = {};
      console.log(item);
      return {
        item,
      };
    },
  },
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
