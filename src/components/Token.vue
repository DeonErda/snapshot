<template>
  <img
    :src="
      `https://curve.fi/logo.png`
    "
    class="d-inline-block v-align-middle line-height-0"
    :style="{
      width: `${size || 22}px`,
      height: `${size || 22}px`
    }"
  />
</template>

<script>
export default {
  props: ['namespace', 'size']
};
</script>
