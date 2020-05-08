<template>
  <div class="shouldWeDo">
    <div class="covid">
      <h3>Covid-19</h3>
      <h2>What should we do</h2>
      <p>
        Corona viruses are a type of virus. There are many different kinds, and
        some cause disease. A newly identified type has caused
      </p>
    </div>
    <div class="do">
      <el-row type="flex" justify="center">
        <el-col
          ><div class="do_content">
            <div class="number">
              <span>1</span>
              <h5>wear masks</h5>
            </div>
            <p>
              Continually seize impactful vortals rather than future-proof
              supply chains. Uniquely exploit emerging niches via fully tested
              meta-services. Competently pursue standards compliant leadership
              skills vis-a-vis pandemic "outside the box" thinking. Objectively
            </p>
          </div></el-col
        >
        <el-col><img src="@/static/Masklike.svg" alt="mask"/></el-col>
      </el-row>
    </div></div
></template>
<style lang="scss" scoped>
.shouldWeDo {
  margin-top: 160px;
}
.do_content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 100%;
  p {
    margin-left: 100px;
    font-size: 18px;
    line-height: 221%;
  }
}
.do {
  margin-top: 70px;
}
.number {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  text-align: center;
  span {
    background: rgba(250, 85, 82, 0.15);
    width: 75px;
    height: 75px;
    border-radius: 50%;
    font-size: 44px;
    color: #fa5652;
    margin-right: 20px;
    font-family: "Red Hat Display", sans-serif;
  }
}
</style>
