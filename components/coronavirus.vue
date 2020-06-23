<template>
  <div class="coronovirus" id="nav_1">
    <el-row class="cont">
      <el-col :xs="24" :sm="12" :md="12" :lg="12" :xl="12">
        <div class="image">
          <img src="@/static/Group 18557.svg" alt />
        </div>
      </el-col>
      <el-col :xs="24" :sm="12" :md="12" :lg="12" :xl="12">
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
          <el-button round class="learn">Learn More</el-button>
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
  display: flex;
  justify-content: center;
  align-items: center;
  img {
    background-size: cover;
    width: 100%;
    max-width: 100%;
    display: block;
  }
}
.el-button {
  color: #fa5652;
  background: rgba(250, 86, 82, 0.15);
}
.el-button:active {
  border: 1px solid rgba(250, 86, 82, 0.15);
}
@media (max-width: 576px) {
  .container {
    h3,
    p,
    h2 {
      text-align: center;
    }
    h3 {
      font-size: 20px;
    }
  }
  .container {
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    p {
      font-size: 16px;
      line-height: 30px;
    }
  }
}

// Малые девайсы («ландшафтные телефоны», >= 576px)
@media (min-width: 576px) {
  .container {
    h3,
    p,
    h2 {
      text-align: center;
    }
  }
  .container {
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
    p {
      font-size: 16px;
      line-height: 30px;
    }
    h3 {
      font-size: 20px;
    }
  }
}

// Средние девайсы («таблетки», >= 768px)
@media (min-width: 768px) {
  .cont {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .container {
    p {
      font-size: 16px;
      line-height: 30px;
    }
  }
  .image {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
    img {
      flex: auto;
      margin: auto;
    }
  }
}

// Большие девайсы (десктопы, >= 992px)
@media (min-width: 992px) {
  .container {
    display: flex;
    p {
      font-size: 20px;
      line-height: 40px;
    }
  }
}

// Экстрабольшие девайсы (большие десктопы, >= 1200px)
@media (min-width: 1200px) {
  .container {
    display: flex;
    p {
      font-size: 20px;
      line-height: 40px;
    }
  }
}
</style>
