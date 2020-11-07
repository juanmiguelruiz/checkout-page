<template>
  <div class="field">
    <h3>{{ title }}</h3>
    <div :class="['field__grid', grid]">
      <i class="material-icons field__icon">{{ icon }}</i>
      <input
        :placeholder="placeholder"
        class="valdidate field__input"
      />
    </div>
  </div>
</template>

<script >
export default {
  name: "Field",
  props: {
    title: String,
    label: String,
    icon: String,
    grid: String,
    placeholder: String,
  },
};
</script>

<style src="./styles.css"/>
