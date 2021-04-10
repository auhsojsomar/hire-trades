<template>
  <div class="row flex-column align-items-center">
    <div class="col-md-5 text-center">
      <h1>Australia's most trusted trades provider</h1>
    </div>
    <div class="col-md-5">
      <span>What trade do you need?</span>
      <input type="text" />
    </div>
    <div class="col-md-5">
      <span>Postcode or Suburb:</span>
      <input type="text" />
    </div>
    <button class="btn btn-danger">Post a Job</button>
  </div>
</template>

<script>
export default {
  name: "Form",
};
</script>

<style lang="sass" scoped>
h1
    font-size: 4.0625rem
    font-weight: 600
    color: $light-blue
span
    color: $light-blue
    display: block
    font-weight: bold
    font-size: 1.125rem
input
    width: 80%
    margin: 0 auto
</style>
