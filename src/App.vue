<template>
  <Navbar title="Title" />
</template>

<script>
import Navbar from "./components/Navbar";

export default {
  name: "App",
  components: {
    Navbar,
  },
};
</script>

<style lang="sass">
@import '../node_modules/bootstrap/scss/bootstrap.scss'

body
  font-family: Helvetica, Arial, serif;
</style>
