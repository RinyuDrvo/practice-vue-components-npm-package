<template>
  <button :style="styleObject" @click="onClick">
    <slot></slot>
  </button>
</template>

<script>
export default {
  props: {
    color: {
      type: String,
      default: "blue",
    },
    size: {
      type: String,
      default: "medium",
    },
  },
  computed: {
    styleObject() {
      return {
        color: this.color,
        fontSize: this.size === "large" ? "24px" : "16px",
      };
    },
  },
  methods: {
    onClick(event) {
      this.$emit("click", event);
    },
  },
};
</script>
