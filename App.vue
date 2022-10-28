<template>
  <div class="container py-4">
    <navbar></navbar>
    <router-view></router-view>
  </div>
</template>

<script>
import navbar from "./components/Navbar.vue";
export default {
  name: "App",
  components: {
    navbar,
  },
};
</script>

<style>
* {
  transition: all 0.3s;
}

*::-webkit-scrollbar {
  display: none;
}
</style>
