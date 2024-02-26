<template>
  <div class="home">
    <NavBar />
    <h1>Home Page</h1>
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar.vue";

export default {
  name: "HomeView",
  components: {
    NavBar,
  },
};
</script>
