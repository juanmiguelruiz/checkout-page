<template>
  <div :class="['field__grid field', grid]">
    <label>{{ label }}</label>
    <div :style="{ marginTop: 10 + 'px' }">
      <i class="material-icons field__icon">{{ icon }}</i>
      <input :placeholder="placeholder" class="valdidate field__input" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Field",
  props: {
    label: String,
    icon: String,
    grid: String,
    placeholder: String,
  },
};
</script>

<style src="./styles.css" />
