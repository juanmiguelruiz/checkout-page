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

<style>
h1 {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 600;
  font-size: 2em;
  line-height: 29px;
  color: #4e5150;
  margin-top: 10%;
}
</style>
