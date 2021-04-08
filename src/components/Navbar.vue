<template>
  <div class="navbar navbar-expand-lg p-1">
    <div class="container-fluid">
      <a href="#" class="navbar-brand">
        <img src="../assets/images/logo-brand.png" alt="logo-brand" />
        <img src="../assets/images/logo-name.png" alt="logo-name" />
      </a>
    </div>
  </div>
</template>
<script>
export default {
  name: "Navbar",
  props: {
    title: String,
  },
  methods: {
    onClick() {
      alert("onClick");
    },
  },
};
</script>

<style lang="sass" scoped>
.navbar
  border-bottom: 1px solid #dfe3e7
  a
    img:last-child
      margin: 5px 0 0 10px
</style>
