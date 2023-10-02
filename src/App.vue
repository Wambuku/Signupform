<template>
<SignupComponent />
</template>


<script>
import SignupComponent from "./components/SignupComponent.vue";
export default {
  name: "App",
  components: { SignupComponent },
};
</script>

<style scoped>
#app {
  font-family: Arial, Helvetica, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: grey;
  margin-top: 60px;
}
body {
  margin: 0;
  background: #eee;
}
</style>
