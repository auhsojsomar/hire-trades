<template>
  <div class="navbar">
    <div class="nav-item">
      <div class="logo">
        <img src="../assets/images/logo-brand.png" alt="logo-brand" />
        <img src="../assets/images/logo-name.png" alt="logo-name" />
      </div>
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
  border-bottom: 1px solid #dfe3e7;
  .nav-item
    padding: 0px 15px;
    margin: auto
    .logo
      display: inline-block
      padding: 10px 0
      margin: auto
      img:last-child
        margin: 0 0 5px 10px
</style>
