<template>
  <header class="border-solid border-4 border-light-blue p-12 text-center">
    <img alt="Vue logo" src="./assets/logo.png" class="inline" />
    <HelloWorld msg="Hello Vue 3.0 + Vite" />
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
  </header>
  <main class="p-12">
    <router-view />
  </main>
  <footer class="border-solid border-4 border-light-blue p-6 text-center">
    this is the footer
  </footer>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>
