<template>
  <div class="container">
    <app-header />
    <app-coronovirus />
  </div>
</template>
<script>
import appHeader from "@/components/header";
import appCoronovirus from "@/components/coronavirus";
export default {
  components: { appCoronovirus, appHeader },
  head() {
    return {
      title: "Covid 19"
    };
  }
};
</script>
<style lang="scss" scoped></style>
