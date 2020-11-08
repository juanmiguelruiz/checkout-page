<template>
<div class="col s12 l6 resume">
  <div class="row">
    <Article
      id=1
      photo="photo1"
      title="Vintage Backbag"
      price="$54.99"
      price_old="$94,99"
    />
    <Article
      id=2
      photo="photo2"
      title="Levi Shoes"
      price="$74.99"
      price_old="$124,99"
    />
    <div class="col s12 resume__total">
      <hr />
      <span class="resume__total__title">Shipping</span>
      <span class="resume__total__price">$19</span>
      <hr />
      <span class="resume__total__title">Total</span>
      <span class="resume__total__price">$148,98</span>
    </div>
  </div>
  </div>

</template>

<script>
import Article from "./Article";
export default {
  name: "Resume",
  components: {
    Article,
  },
};
</script>

