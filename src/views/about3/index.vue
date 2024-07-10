<script setup lang="ts" name="About3">
import { onMounted, onUnmounted, onActivated, onDeactivated } from "vue";
onMounted(() => {
  console.log("About3 onMounted");
});
onUnmounted(() => {
  console.log("About3 onUnmounted");
});
onActivated(() => {
  console.log("About3 onActivated");
});
onDeactivated(() => {
  console.log("About3 onDeactivated");
});
</script>

<template>
  <div>about3</div>
</template>
