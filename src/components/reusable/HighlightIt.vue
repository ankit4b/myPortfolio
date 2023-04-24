<template>
  <span class="word"><slot></slot></span>
</template>
<script>
export default {
  name: "HiWord",
};
</script>
<style lang="scss" scoped>
.word {
  position: relative;
}

.word:after {
  background-color: #ededed;
  content: " ";
  height: 100%;
  position: absolute;
  left: 0;
  top: 0%;
  width: 100%;
  z-index: -1;
}
</style>
