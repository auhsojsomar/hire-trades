<template>
  <Navbar />
  <div class="container">
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
@import 'bootstrap/scss/bootstrap.scss'
@import '~@fortawesome/fontawesome-free/css/all.min.css'

body
  font-family: Helvetica, Arial, serif
</style>
