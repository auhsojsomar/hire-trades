<template>
  <div class="container-fluid">
    <Navbar />
    <Form />
  </div>
</template>

<script>
import Navbar from "./components/Navbar";
import Form from "./components/Form";

export default {
  name: "App",
  components: {
    Navbar,
    Form,
  },
};
</script>

<style lang="sass">
@import '../node_modules/bootstrap/scss/bootstrap.scss'

body
  font-family: Helvetica, Arial, serif
</style>
