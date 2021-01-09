<template>
  <label>
    {{ label }}
    <input type="date" name="date" />
  </label>
</template>

<script>
export default {
  props: {
    type: String,
    required: true,
  },
};
</script>

<style scoped>
</style>