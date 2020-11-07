<template>
  <div class="row">
    <div class="col s12">
      <Field
        title="Contact infomation"
        label="E-mail"
        placeholder="Enter your email.."
        icon="email"
        grid="col s12"
      />
      <Field
        label="Phone"
        placeholder="Enter your phone.."
        icon="phone"
        grid="col s12"
      />
    </div>
    <div class="col s12">
      <Field
        title="Shipping address"
        label="Full name"
        placeholder="Your name.."
        icon="person"
        grid="col s12"
      />
      <Field
        label="Address"
        placeholder="Your address.."
        icon="home"
        grid="col s12"
      />
      <Field
        label="City"
        placeholder="Your city.."
        icon="location_city"
        grid="col s12"
      />
      <Field
        label="Country"
        placeholder="Country"
        icon="location_city"
        grid="col s4 m5"
      />
      <Field
        label="Postal code"
        placeholder="Postal code"
        icon="markunread_mailbox"
        grid="col s4 m5 postal-code"
      />
    </div>
    <div class="col s12 form__checkbox">
      <label>
        <input type="checkbox" class="filled-in" />
        <span class="form__checkbox__span">
          Save this information for next time</span>
      </label>
      <button class="form__continue">Continue</button>
      <footer>
        <p>juanmiguelruiz @ DevChallenges.io</p>
      </footer>
    </div>
  </div>
</template>

<script>
import Field from "../Field/Field";

export default {
  name: "Form",
  components: {
    Field,
  },
};
</script>

<style>
h3 {
  font-family: Montserrat;
  font-weight: 600;
  font-size: 14px;
  line-height: 17px;
  color: #333333;
}

.form__checkbox {
  margin-top: 5%;
}

.form__checkbox__span {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 600;
  font-size: 1.3em !important;
  line-height: 15px;
  color: #4f4f4f;
}

.form__continue {
  margin-top: 10%;
  width: 150px;
  height: 50px;
  background-color: #f2994a;
  border: 1px transparent;
  color: white;
  font-family: Montserrat;
  font-weight: 500;
  font-size: 1.2em;
  border-radius: 12px;
  float: right;
}

footer {
  text-align: center;
  padding-top: 50%;
  font-family: Montserrat;
  font-weight: 600;
  font-size: 1em;
  line-height: 0px;
  color: #a9a9a9;
}

[type="checkbox"].filled-in:checked + span:not(.lever):after {
  border: 2px solid #f2994a;
  background-color: #f2994a;
}
</style>
