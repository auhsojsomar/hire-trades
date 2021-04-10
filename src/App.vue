<template>
  <div class="container-fluid">
    <Navbar />
    <Form />
    <Works />
    <InspirationPanel />
    <Testimonials />
    <MobileApp />
    <TopTrades />
    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/Navbar";
import Form from "./components/Form";
import Works from "./components/Works";
import InspirationPanel from "./components/InspirationPanel";
import Testimonials from "./components/Testimonials.vue";
import MobileApp from "./components/MobileApp.vue";
import TopTrades from "./components/TopTrades.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Form,
    Works,
    InspirationPanel,
    Testimonials,
    MobileApp,
    TopTrades,
    Footer,
  },
};
</script>

<style lang="sass">
@import '../node_modules/bootstrap/scss/bootstrap.scss'

body
  font-family: Helvetica, Arial, serif
</style>
