<template>
  <div class="app">
    <h2>Hello {{ name }}</h2>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "App",
  components: {},
  data() {
    return {
      name: "Akkas",
    };
  },
});
</script>

<style>
</style>
