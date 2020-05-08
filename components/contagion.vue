<template
  ><div class="contagion">
    <div class="covid">
      <h3>Covid-19</h3>
      <h2>Contagion</h2>
      <p>
        Corona viruses are a type of virus. There are many different kinds, and
        some cause disease. A newly identified type
      </p>
    </div>

    <div class="covid__contant">
      <el-row :gutter="40" type="flex">
        <el-col>
          <el-card shadow="always">
            <div class="covid__item">
              <img src="@/static/Group 18544.svg" alt="" />
              <h4>Air Transmission</h4>
              <p>
                Objectively evolve tactical expertise before extensible
                initiatives. Efficiently simplify
              </p>
            </div>
          </el-card></el-col
        >
        <el-col>
          <el-card shadow="always">
            <div class="covid__item">
              <img src="@/static/Group 18542.svg" alt="" />
              <h4>Human Contacts</h4>
              <p>
                Washing your hands is one of thesimplest ways you can protect
              </p>
            </div>
          </el-card></el-col
        >
        <el-col>
          <el-card shadow="always">
            <div class="covid__item">
              <img src="@/static/Group 18540.svg" alt="" />
              <h4>Containted Objects</h4>
              <p>
                Use the tissue while sneezing,In this way, you can protect your
                droplets.
              </p>
            </div>
          </el-card></el-col
        >
      </el-row>
    </div>
  </div></template
>
<style lang="scss" scoped>
.contagion {
  display: flex;
  justify-content: center;
  flex-direction: column;
}
.el-card {
  border-bottom: 3px solid #fff;
}
.el-card:hover {
  border-bottom: 3px solid #fa5652;
}
.covid {
  margin-bottom: 112px;
}
.covid__item {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 575px;
  padding: 20px;
}
</style>
