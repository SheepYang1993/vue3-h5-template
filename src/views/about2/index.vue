<script setup lang="ts" name="About2">
import { onMounted, onUnmounted, onActivated, onDeactivated } from "vue";
onMounted(() => {
  console.log("About2 onMounted");
});
onActivated(() => {
  console.log("About2 onActivated");
});
onDeactivated(() => {
  console.log("About2 onDeactivated");
});
onUnmounted(() => {
  console.log("About2 onUnmounted");
});
</script>

<template>
  <div>about2</div>
</template>
