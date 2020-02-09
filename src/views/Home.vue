<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <HelloWorld secondMsg="Task: Host on Netlify" />
    <div>This page is rendered by views, which holds components with props</div>
    <div>In this example: msg is the prop within the HelloWorld component rendered by Home.vue view.</div>
    <div>{{ message }}</div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

const message = "LOOK";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>
