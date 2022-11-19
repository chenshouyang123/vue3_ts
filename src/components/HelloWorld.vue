<template>
  <div>HelloWorld</div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HelloWorld',
  props: {
    msg: String
  }
});
</script>

<style scoped lang="less"></style>
