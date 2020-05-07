<template>
  <div class="header">
    <div class="container">
      <el-row type="flex" justify="space-between">
        <el-col :span="10">
          <div class="info">
            <h2>COVID-19 Alert</h2>
            <h1>Stay at Home quarantine To stop Corona virus</h1>
            <p>
              There is no specific medicine to prevent or treat coronavirus
              disease (COVID-19). People may need supportive care to .
            </p>
            <div class="info_btn">
              <el-button round class="btn-help btn">Let Us Help</el-button>
            </div>
          </div>
        </el-col>
        <el-col :span="14">
          <img src="@/static/Illustration 01.svg" alt class="image" />
        </el-col>
      </el-row>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.container {
  margin-top: 74px;
}

.info {
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 100%;
  h2 {
    color: #fa5652;
    font-size: 32px;
  }
  h1 {
    font-size: 52px;
    font-weight: bold;
    line-height: 60px;
    margin-top: 20px;
  }
}
.el-button {
  background: none;
  color: #ff383d;
  border: 2px solid #ff383d;
}
.image {
  position: relative;
  right: 22px;
  overflow: hidden;
  display: block;
}
.header {
  display: block;
}
.btn-help {
  display: block;
  background: #ff383d;
  color: #ffffff;
  font-size: 22px;
  border-radius: 65px;
}
</style>
