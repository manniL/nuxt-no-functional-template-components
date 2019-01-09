<template>
  <div>
    <p>Should show: "test functional"</p>
    <functional-component />
  </div>
</template>

<script>
export default {
  components: {
    FunctionalComponent: () => import("~/components/FunctionalComponent.vue")
  }
};
</script>
