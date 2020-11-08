<template>
  <div id="app" class="container">
    <h1>Checkout</h1>
    <div class="row">
      <Resume />
      <Form />
    </div>
     <footer>
          <p>juanmiguelruiz @ DevChallenges.io</p>
        </footer>
  </div>
</template>

<script>
import Resume from "./components/Resume";
import Form from "./components/Form";

export default {
  name: "App",
  components: {
    Resume,
    Form,
  },
};
</script>

<style src="./App.css">

</style>
