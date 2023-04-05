<template>
  <h1 @click="handler(arg, event)"></h1>
</template>

<script>
export default {
  props: {
    propName: {
      type: Number,
      default: null,
    },
  },
  data() {
    return {
      key: 'value',
    }
  },
}
</script>

<style></style>
