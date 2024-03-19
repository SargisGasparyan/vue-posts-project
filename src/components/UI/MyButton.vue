<template>
  <button class="btn">
    <slot></slot>
  </button>
</template>

<script>
export default {
  name: "my-button",
};
</script>

<style scoped>
.btn {
  padding: 10px 15px;
  background: none;
  border-radius: 12px;
  color: rgb(136, 9, 98);
  border: 1px solid rgb(136, 9, 98);
}
</style>
