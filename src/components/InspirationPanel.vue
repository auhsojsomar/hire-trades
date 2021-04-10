<template>
  <section class="mt-5">
    <h1 class="text-center">Inspirational Panel</h1>
    <div class="row">
      <div class="col-9">
        <div class="row">
          <div class="col-3">
            <img
              src="https://hiretrades2.s3.amazonaws.com/htweb-assets/homepage/accounting-balance-banking.webp"
              alt=""
            />
          </div>
          <div class="col-9">
            <h2>Cost Guides</h2>
            <p>Research to assist consumers with Trades pricing.</p>
            <a href="#">View prices</a>
          </div>
        </div>
        <div class="row">
          <div class="col-9">
            <img
              src="https://hiretrades2.s3.amazonaws.com/htweb-assets/homepage/organise.webp"
              alt=""
            />
          </div>
          <div class="col-3">
            <h2>Blogs</h2>
            <p>Articles of interest and great ideas.</p>
            <a href="#">Discover more</a>
          </div>
        </div>
      </div>
      <div class="col-3">
        <img
          src="https://hiretrades2.s3.amazonaws.com/htweb-assets/homepage/blueprint-designing-diagram.webp"
          alt=""
        />
        <h2>Ask a Tradie</h2>
        <p>Our network of Tradies can help answer your questions.</p>
        <a href="#">What's your question?</a>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "InspirationalPanel",
};
</script>
<style lang="sass" scoped>
section
  color: $light-blue
</style>
