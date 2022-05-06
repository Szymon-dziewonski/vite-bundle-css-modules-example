<template>
  <component1></component1>
  <component2></component2>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import component1 from "./components/component1.vue";
import component2 from "./components/component2.vue";

export default defineComponent({
  name: 'App',
  components: {
    component1, component2
  },
});
</script>

