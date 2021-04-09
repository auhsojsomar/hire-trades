<template>
  <div class="navbar navbar-expand-lg p-1">
    <div class="container-fluid">
      <a href="#" class="navbar-brand pr-lg-4">
        <img src="../assets/images/logo-brand.png" alt="logo-brand" />
        <img src="../assets/images/logo-name.png" alt="logo-name" />
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collpase navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a href="#" class="nav-link">Trades</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link">Cost Guides</a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link">Blogs</a>
          </li>
        </ul>
        <ul class="navbar-nav">
          <li class="nav-item">
            <a href="#" class="nav-link">Get Quotes</a>
          </li>
          <li class="nav-item my-lg-auto">
            <button class="btn">Register Business</button>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link">Login</a>
          </li>
        </ul>
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
  border-bottom: 1px solid #dfe3e7
  .navbar-toggler-icon
    color: red
  ul
    li
      padding: 0 .7rem
    a
      font-weight: 700
      color: $gray
      border-bottom: 2px solid transparent
      position: relative
      &:hover
        color: $secondary
        &::after
          content: ''
          position: absolute
          bottom: -10px
          left: 0
          width: 100%
          height: 2px
          background: $secondary
    button
      color: $secondary
      border: 1px solid $secondary
      padding: .4rem 1.5rem
      &:hover
        background: $secondary
        color: white
  img:last-child
    margin: .5rem 0 0 1rem
</style>
