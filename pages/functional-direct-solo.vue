<template>
  <div>
    <p>Should show: "test functional"</p>
    <functional-component />
  </div>
</template>

<script>
import FunctionalComponent from "~/components/FunctionalComponent.vue";
export default {
  components: {
    FunctionalComponent
  }
};
</script>
