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

<style>
@import "~bootstrap/dist/css/bootstrap.min.css";
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: Helvetica, Arial, serif;
}
</style>
