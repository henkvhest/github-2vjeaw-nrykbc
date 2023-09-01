<template>
  <ul class="list">
    <slot></slot>
  </ul>
</template>

<script setup>
export default {
  name: 'List',
  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
.list {
  margin: 0;
  padding: 0;

  > li + li {
    margin-top: 16px;
  }
}
</style>
