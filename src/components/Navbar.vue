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

<style lang="sass" scoped></style>
