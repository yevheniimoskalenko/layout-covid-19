<template>
  <div class="contagion">
    <div class="covid">
      <h3>Covid-19</h3>
      <h2>Contagion</h2>
      <p>
        Corona viruses are a type of virus. There are many different kinds, and
        some cause disease. A newly identified type
      </p>
    </div>
    <div class="covid__contant">
      <el-row :gutter="30">
        <el-col :sm="24" :xl="12" :xs="24" :md="8" :lg="8">
          <el-card shadow="always" class="card">
            <div class="covid__item">
              <div class="covid_head">
                <img src="@/static/Group 18544.svg" alt />
              </div>
              <div class="covid_main">
                <span>Air Transmission</span>
                <p>
                  Objectively evolve tactical expertise before extensible
                  initiatives. Efficiently simplify
                </p>
              </div>
            </div>
          </el-card>
        </el-col>
        <el-col :sm="24" :xl="12" :xs="24" :md="8" :lg="8">
          <el-card shadow="always" class="card">
            <div class="covid__item">
              <div class="covid_head">
                <img src="@/static/Group 18542.svg" alt="hand" class="hend" />
              </div>
              <div class="covid_main mrt">
                <span>Human Contacts</span>
                <p>Washing your hands is one of thesimplest ways you can protect</p>
              </div>
            </div>
          </el-card>
        </el-col>
        <el-col :sm="24" :xs="24" :xl="12" :md="8" :lg="8">
          <el-card shadow="always" class="card">
            <div class="covid__item">
              <div class="covid_head">
                <img src="@/static/Group 18540.svg" alt="coup" />
              </div>
              <div class="covid_main">
                <span>Containted Objects</span>
                <p>
                  Use the tissue while sneezing,In this way, you can protect
                  your droplets.
                </p>
              </div>
            </div>
          </el-card>
        </el-col>
      </el-row>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.el-card.is-always-shadow,
.el-card.is-hover-shadow:focus,
.el-card.is-hover-shadow:hover {
  box-shadow: 0px 35px 87px rgba(0, 0, 0, 0.11);
}
.el-card {
  border: none;
  border-radius: 10px;
}
.contagion {
}
.covid {
  margin-bottom: 60px;
  h2 {
    margin-top: 0em;
    margin-bottom: 0em;
    font-size: 42px;
  }
  p {
    font-size: 16px;
    line-height: 30px;
  }
}

.card {
}
.covid__item {
  padding: 0px 20px;
}
.covid_head {
  display: flex;
  justify-content: center;
  margin-top: 45px;
  img {
    background-size: cover;
    max-width: 100%;
    width: auto;
  }
}
.covid_main {
  margin-top: 55px;
  display: flex;
  flex-direction: column;
  align-items: center;
  span {
    font-style: normal;
    font-weight: 500;
    font-size: 36px;
    color: #035755;
  }
  p {
    text-align: center;
    font-size: 18px;
    font-style: normal;
    font-weight: normal;
    line-height: 32px;
  }
}
.hend {
  position: relative;
  bottom: 25px;
}
.el-card {
  margin: 10px 0;
}
.covid_main.covid_cnt {
}

@media (max-width: 576px) {
  .card {
  }
}

@media (min-width: 576px) {
  .el-card {
    margin: 10px;
  }
}

// Средние девайсы («таблетки», >= 768px)
@media (min-width: 768px) {
  .el-card {
    margin: 10px;
  }
}

// Большие девайсы (десктопы, >= 992px)
@media (min-width: 992px) {
  .covid_main {
    padding: 0px 10px;
    overflow: hidden;
    span {
      font-size: 25px;
      text-align: center;
    }
    p {
      font-size: 16px;
      line-height: 30px;
    }
  }
  .covid__item {
    display: flex;
    flex-direction: column;
    align-content: space-between;
    justify-content: center;
  }
  .mrt {
    margin-top: 35px;
  }
  .el-card {
    max-height: auto;
    height: 560px;
    padding: 10px;
    border-bottom: 2px solid #fff;
    &:hover {
      border-bottom: 2px solid #fa5652;
      border-radius: 0px 0px 10px 10px;
    }
  }
  .covid {
    width: 100%;
  }
}

// Экстрабольшие девайсы (большие десктопы, >= 1200px)
@media (min-width: 1200px) {
  .covid {
    width: 41%;
  }
  .covid_main {
    padding: 0px 10px;
    span {
      font-size: 30px;
      text-align: center;
    }
  }
  .covid__item {
    display: flex;
    flex-direction: column;
    align-content: space-between;
    justify-content: center;
  }
  .mrt {
    margin-top: 15px;
  }
  .el-card {
    max-height: auto;
    height: 560px;
    padding: 10px;
    border-bottom: 2px solid #fff;
    &:hover {
      border-bottom: 2px solid #fa5652;
      border-radius: 0px 0px 10px 10px;
    }
  }
}
</style>
