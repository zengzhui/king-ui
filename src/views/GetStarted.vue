<template>
  <article class="markdown-body" v-html="md" />
</template>

<script lang="ts">
import md from "../markdown/get-started.md"
export default {
  data() {
    return {md}
  }
};
</script>

<style lang="scss" scoped>

</style>