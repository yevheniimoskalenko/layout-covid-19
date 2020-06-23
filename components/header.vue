<template>
  <div class="header">
    <div class="container">
      <el-row>
        <el-col :sm="10" :xs="10" :xl="10" :md="10" :lg="10">
          <div class="covid">
            <img src="@/static/path216.svg" alt="" />
          </div>
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
        <el-col :sm="14" :xs="14" :xl="14" :md="14" :lg="14" class="cnt hidden">
          <div class="image">
            <img src="@/static/Illustration 01.svg" alt="covid" />
          </div>
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
  display: flex;
  align-content: center;
  justify-content: center;
  flex-direction: column;
  img {
    position: relative;
    right: -20%;
    bottom: 0px;
    background-size: cover;
    width: auto;
    max-width: 100%;
  }
}
.cnt {
  display: flex;
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
.el-row {
  display: flex;
  justify-content: space-between;
}
@media (max-width: 400px) {
  .covid {
    display: block;
  }
  .el-col {
    width: 100%;
  }
  .btn-help {
    font-size: 12px;
    margin: 0 auto;
  }
  .hidden {
    display: none;
  }
  .info {
    text-align: center;
    p {
      font-size: 14px;
      line-height: 25px;
    }
    h2 {
      font-size: 16px;
    }
    h1 {
      font-size: 20px;
      line-height: 25px;
    }
  }
}
@media (min-width: 400px) {
  .covid {
    display: block;
  }
  .el-col {
    width: 100%;
  }
  .btn-help {
    font-size: 12px;
    margin: 0px auto;
  }
  .hidden {
    display: none;
  }
  .info {
    text-align: center;
    p {
      font-size: 14px;
      line-height: 25px;
    }
    h2 {
      font-size: 16px;
    }
    h1 {
      font-size: 20px;
      line-height: 25px;
    }
  }
}
@media (min-width: 576px) {
  .btn-help {
    font-size: 16px;
    margin: 0px auto;
  }
  .info {
    text-align: center;
    p {
      font-size: 16px;
      line-height: 30px;
    }
    h2 {
      font-size: 20px;
    }
    h1 {
      font-size: 25px;
      line-height: 35px;
    }
  }
}

@media (min-width: 768px) {
  .covid {
    display: none;
  }
  .btn-help {
    font-size: 16px;
  }
  .info {
    p {
      font-size: 16px;
      line-height: 30px;
    }
    h2 {
      font-size: 20px;
    }
    h1 {
      font-size: 25px;
      line-height: 35px;
    }
  }
  .hidden {
    display: block;
  }
  .info {
    text-align: left;
  }
  .btn-help {
    margin: 0px 0px;
  }
}

@media (min-width: 992px) {
  .covid {
    display: none;
  }
  .hidden {
    display: block;
  }
  .btn-help {
    font-size: 16px;
  }
  .info {
    p {
      font-size: 22px;
      line-height: 34px;
    }
    h2 {
      font-size: 26px;
    }
    h1 {
      font-size: 30px;
      line-height: 40px;
    }
  }
  .hidden {
    display: block;
  }
}

@media (min-width: 1200px) {
  .covid {
    display: none;
  }
  .hidden {
    display: block;
  }
  .info {
    text-align: left;
  }
  .btn-help {
    margin: 0px 0px;
  }
}
</style>
