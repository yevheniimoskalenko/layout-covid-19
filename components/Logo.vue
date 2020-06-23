<template>
  <div class="logo-content">
    <div class="logo">
      <img src="@/static/Grouplogo.svg" alt="logo" />
      <span>covid-19</span>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.logo {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  width: 153px;
  span {
    margin-left: 14px;
    color: #035755;
    font-size: 19px;
    line-height: 25px;
  }
  img {
    background-size: cover;
  }
}

@media (max-width: 576px) {
  .logo {
    span {
      font-size: 14px;
      line-height: 25px;
    }
    img {
      width: 30px;
    }
  }
}
@media (min-width: 576px) {
  .logo {
    span {
      font-size: 14px;
      line-height: 25px;
    }
    img {
      width: 30px;
    }
  }
}

@media (min-width: 768px) {
  .logo {
    span {
      font-size: 14px;
      line-height: 25px;
    }
    img {
      width: 50px;
    }
  }
}

@media (min-width: 992px) {
  .logo {
    span {
      font-size: 19px;
      line-height: 25px;
    }
  }
}

@media (min-width: 1200px) {
  .logo {
    span {
      font-size: 19px;
      line-height: 25px;
    }
  }
}
</style>
