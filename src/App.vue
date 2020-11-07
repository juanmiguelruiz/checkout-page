<template>
  <div id="app" class="container">
    <h1>Checkout</h1>
    <div class="row">
      <Resume />
    </div>
  </div>
</template>

<script>
import Resume from "./components/Resume";
export default {
  name: "App",
  components: {
    Resume,
  },
};
</script>

<style>
h1 {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 29px;
  color: #4e5150;
  margin-top:10%;
}
</style>
