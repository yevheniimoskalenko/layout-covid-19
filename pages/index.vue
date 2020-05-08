<template>
  <div class="container">
    <app-header />
    <app-coronovirus />
    <app-contagion />
    <app-symptoms />
  </div>
</template>
<script>
import appHeader from "@/components/header";
import appContagion from "@/components/contagion";
import appCoronovirus from "@/components/coronavirus";
import appSymptoms from "@/components/symptomps";
export default {
  components: { appCoronovirus, appHeader, appContagion, appSymptoms },
  head() {
    return {
      title: "Covid 19"
    };
  }
};
</script>
<style lang="scss" scoped></style>
