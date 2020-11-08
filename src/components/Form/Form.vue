<template>
  <div class="col s12 l6 form">
    <div class="row">
      <form method="GET">
      <div class="col s12">
        <h3>Contact information</h3>
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
                <h3>Shipping address</h3>

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
          grid="col s5 m5 divided"
        />
        
        <Field
          label="Postal code"
          placeholder="Postal code"
          icon="markunread_mailbox"
          grid="col s5 m5 postal-code divided"
        />
        
      </div>
      <div class="col s12 form__checkbox">
        <label>
          <input type="checkbox" class="filled-in" />
          <span class="form__checkbox__span">
            Save this information for next time</span
          >
        </label>
        <button class="form__continue">Continue</button>
       
      </div>
      </form>
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
