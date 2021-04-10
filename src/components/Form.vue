<template>
  <div class="row flex-column align-items-center">
    <div class="col-md-5 text-center">
      <h1>Australia's most trusted trades provider</h1>
    </div>
    <div class="col-md-5 mt-5 px-md-4 position-relative">
      <span>What trade do you need?</span>
      <i class="fas fa-tag position-absolute"></i>
      <input
        class="form-control w-100"
        type="text"
        placeholder="e.g Plumber, Electricians"
      />
    </div>
    <div class="col-md-5 mt-5 px-md-4 position-relatve">
      <span>Postcode or Suburb:</span>
      <i class="fas fa-map-marker-alt position-absolute"></i>
      <input class="form-control w-100" type="text" placeholder="e.g Sydney" />
    </div>
    <button class="btn btn-danger mt-5 shadow-sm">Post a Job</button>
  </div>
</template>

<script>
export default {
  name: "Form",
};
</script>

<style lang="sass" scoped>
.row
  margin-top: 4em
h1,span,input,i
  color: $light-blue
  &:focus
    color: $light-blue
    border: 1px solid $secondary
    outline:0px !important
    -webkit-appearance: none
    -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102,175,233,.6)
    box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102,175,233,.6)
h1
    font-size: 4.0625rem
    font-weight: 600
span
    display: block
    font-weight: bold
    font-size: 1.125rem
input
    width: 80%
    margin: 0 auto
    font-size: 1.171875rem
    padding: 1.4em 0
    padding-left: 2.4em
    padding-right: 1em
i
  top: 2.9em
  left: 2.6em
button
  padding: 1em 7.2em
  &:hover
    background: lighten(#dc3545,10%)
    -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102,175,233,.6)
    box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102,175,233,.6)
</style>
