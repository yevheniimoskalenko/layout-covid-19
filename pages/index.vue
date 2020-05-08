<template>
  <div class="container">
    <app-header />
    <app-coronovirus />
    <app-contagion />
    <app-symptoms />
    <app-should />
  </div>
</template>
<script>
import appHeader from "@/components/header";
import appContagion from "@/components/contagion";
import appCoronovirus from "@/components/coronavirus";
import appSymptoms from "@/components/symptomps";
import appShould from "@/components/shouldWeDo";

export default {
  components: {
    appCoronovirus,
    appHeader,
    appContagion,
    appSymptoms,
    appShould
  },
  head() {
    return {
      title: "Covid 19"
    };
  }
};
</script>
<style lang="scss" scoped></style>
