<template>
  <h1 class="text-5xl">{{ msg }}</h1>
</template>

<script setup>
import { defineProps, reactive } from "vue";

defineProps({
  msg: String,
});

const state = reactive({ count: 0 });
</script>

<style scoped>
</style>