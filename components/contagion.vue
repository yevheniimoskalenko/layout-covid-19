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
      <el-row :gutter="40">
        <el-col :sm="24" :xl="12" :xs="24" :md="8" :lg="8">
          <el-card shadow="always" class="card" :body-style="{padding: '0px'}">
            <div class="covid__item">
              <div class="covid_head">
                <img src="@/static/Group 18544.svg" alt />
              </div>
              <div class="covid_main">
                <h4>Air Transmission</h4>
                <p>
                  Objectively evolve tactical expertise before extensible
                  initiatives. Efficiently simplify
                </p>
              </div>
            </div>
          </el-card>
        </el-col>
        <el-col :sm="24" :xl="12" :xs="24" :md="8" :lg="8">
          <el-card shadow="always" class="card" :body-style="{padding: '0px'}">
            <div class="covid__item">
              <div class="covid_head">
                <img src="@/static/Group 18542.svg" alt="hand" class="hend" />
              </div>
              <div class="covid_main covid_cnt">
                <h4>Human Contacts</h4>
                <p>Washing your hands is one of thesimplest ways you can protect</p>
              </div>
            </div>
          </el-card>
        </el-col>
        <el-col :sm="24" :xs="24" :xl="12" :md="8" :lg="8">
          <el-card shadow="always" class="card" :body-style="{padding: '0px'}">
            <div class="covid__item">
              <div class="covid_head">
                <img src="@/static/Group 18540.svg" alt="coup" />
              </div>
              <div class="covid_main">
                <h4>Containted Objects</h4>
                <p>
                  Use the tissue while sneezing,In this way, you can protect your
                  droplets.
                </p>
              </div>
            </div>
          </el-card>
        </el-col>
      </el-row>
    </div>
  </div>
</template
>
<style lang="scss" scoped>
.card {
  margin-bottom: 30px;
}
.hend {
  margin-bottom: 10px;
}

.contagion {
  display: flex;
  justify-content: center;
  flex-direction: column;
  margin-top: 50px;
}
.covid_head {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 100%;
  height: 100%;
}
.covid_main {
  position: relative;
  bottom: 0;
  left: 0;
  padding: 10px 20px;
  height: 150px;
  margin-bottom: 50px;
  display: flex;
  flex-direction: column;
}
.el-card {
  border-bottom: 3px solid #fff;
}
.el-card:hover {
  border-bottom: 3px solid #fa5652;
}
.covid {
  text-align: center;
  width: 100%;
}
.covid__item {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 550px;
  padding: 20px;
  img {
    width: 80%;
    min-width: auto;
  }
}
@media (max-width: 576px) {
  .covid_head {
    height: 100%;
  }
  .covid__item {
    height: 500px;
    img {
      width: 80%;
      min-width: auto;
    }
  }
  .covid {
    width: 100%;
  }
}

@media (min-width: 576px) {
  .covid_head {
    height: 100%;
  }
}

// Средние девайсы («таблетки», >= 768px)
@media (min-width: 768px) {
  .covid_head {
    height: 100%;
  }

  .covid__item {
    height: 550px;
    padding: 50px;
    img {
      width: 80%;
      min-width: auto;
    }
  }
}

// Большие девайсы (десктопы, >= 992px)
@media (min-width: 992px) {
  .covid_head {
    height: 100%;
  }

  .covid__item {
    height: 400px;
    padding: 50px;

    img {
      width: 80%;
      min-width: auto;
    }
  }
}

// Экстрабольшие девайсы (большие десктопы, >= 1200px)
@media (min-width: 1200px) {
  .covid_head {
    height: 100%;
  }
  .covid {
    width: 50%;
  }
  .covid__item {
    height: 400px;
    padding: 50px;

    img {
      width: 80%;
      min-width: auto;
    }
  }
}
</style>
