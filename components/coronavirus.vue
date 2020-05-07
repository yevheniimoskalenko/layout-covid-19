<template>
  <div class="coronovirus">
    <el-row type="flex" justify="center" align="middle">
      <el-col :span="12">
        <div class="image">
          <img src="@/static/Group 18557.svg" alt="" />
        </div>
      </el-col>
      <el-col :span="12">
        <div class="container">
          <h3>What Is Covid-19</h3>
          <h2>Coronavirus</h2>
          <p>
            Corona viruses are a type of virus. There are many different kinds,
            and some cause disease. A newly identified type has caused a recent
            outbreak of respiratory illness now called COVID-19.Lauren Sauer,
            M.S., the director of operations with the Johns Hopkins Office of
            Critical Event Preparedness and Response
          </p>
          <el-button round="">Learn More</el-button>
        </div>
      </el-col>
    </el-row>
  </div>
</template>
<style lang="scss" scoped>
.container {
  h3 {
    color: #fa5652;
  }
  p {
    font-size: 20px;
    line-height: 40px;
  }
}
.coronovirus {
  margin-top: 25px;
}
.image {
  img {
    background-size: cover;
    width: 100%;
  }
}
.el-button {
  color: #fa5652;
  background: rgba(250, 86, 82, 0.15);
}
.el-button:active {
  border: 1px solid rgba(250, 86, 82, 0.15);
}
</style>
