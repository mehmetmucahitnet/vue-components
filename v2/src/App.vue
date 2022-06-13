<template>
  <div class="container">
    <div class="components">
      <div class="component-item">
        <Tabs />
      </div>
    </div>
  </div>
</template>

<script>
import Tabs from "./components/Tabs.vue";
export default {
  components: { Tabs },
};
</script>

<style lang="scss">
@import "@/assets/scss/main";
</style>