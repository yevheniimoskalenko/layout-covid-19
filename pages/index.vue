<template>
  <div class="container">
    <app-header />
    <app-coronovirus />
    <app-contagion />
  </div>
</template>
<script>
import appHeader from "@/components/header";
import appContagion from "@/components/contagion";
import appCoronovirus from "@/components/coronavirus";
export default {
  components: { appCoronovirus, appHeader, appContagion },
  head() {
    return {
      title: "Covid 19"
    };
  }
};
</script>
<style lang="scss" scoped></style>
