<template>
  <button
    :style="{
      padding: '15px',
      fontSize: '20px',
      background: background,
      color: color,
    }"
  >
    {{ text }}
  </button>
</template>

<script>
export default {
  name: "VueElegantButton",
  props: {
    background: {
      default: "#456099",
    },
    color: {
      default: "#fff",
    },
    text: {
      default: "My  github testing Button",
    },
  },
};
</script>
