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
      <el-row class="left">
        <el-col :sm="24" :xs="24" :xl="12" :md="8" :lg="8">
          <div class="image">
            <img src="@/static/Masklike.svg" alt="mask" />
          </div>
        </el-col>
        <el-col :sm="24" :xs="24" :xl="12" :md="8" :lg="8">
          <div class="do_content">
            <div class="number">
              <span>1</span>
              <h5>wear masks</h5>
            </div>
            <div class="text__content">
              <p>
                Continually seize impactful vortals rather than future-proof
                supply chains. Uniquely exploit emerging niches via fully tested
                meta-services. Competently pursue standards compliant leadership
                skills vis-a-vis pandemic "outside the box" thinking.
                Objectively
              </p>
            </div>
          </div>
        </el-col>
      </el-row>
      <el-row class="right">
        <el-col :sm="24" :xs="24" :xl="12" :md="8" :lg="8">
          <div class="image">
            <img src="@/static/Mask girlwash.svg" alt="mask" />
          </div>
        </el-col>
        <el-col :sm="24" :xs="24" :xl="12" :md="8" :lg="8">
          <div class="do_content">
            <div class="number">
              <span>2</span>
              <h5>wear masks</h5>
            </div>
            <div class="text__content">
              <p>
                Continually seize impactful vortals rather than future-proof
                supply chains. Uniquely exploit emerging niches via fully tested
                meta-services. Competently pursue standards compliant leadership
                skills vis-a-vis pandemic "outside the box" thinking.
                Objectively
              </p>
            </div>
          </div>
        </el-col>
      </el-row>
      <el-row class="left">
        <el-col :sm="24" :xs="24" :xl="12" :md="8" :lg="8" class="left">
          <div class="image">
            <img src="@/static/Group 15454.svg" alt="mask" />
          </div>
        </el-col>
        <el-col :sm="24" :xs="24" :xl="12" :md="8" :lg="8" class="right">
          <div class="do_content">
            <div class="number">
              <span>3</span>
              <h5>wear masks</h5>
            </div>
            <div class="text__content">
              <p>
                Continually seize impactful vortals rather than future-proof
                supply chains. Uniquely exploit emerging niches via fully tested
                meta-services. Competently pursue standards compliant leadership
                skills vis-a-vis pandemic "outside the box" thinking.
                Objectively
              </p>
            </div>
          </div>
        </el-col>
      </el-row>
      <el-row class="right">
        <el-col :sm="24" :xs="24" :xl="12" :md="8" :lg="8">
          <div class="image">
            <img src="@/static/Mask.svg" alt="mask" />
          </div>
        </el-col>
        <el-col :sm="24" :xs="24" :xl="12" :md="8" :lg="8">
          <div class="do_content">
            <div class="number">
              <span>4</span>
              <h5>wear masks</h5>
            </div>
            <div class="text__content">
              <p>
                Continually seize impactful vortals rather than future-proof
                supply chains. Uniquely exploit emerging niches via fully tested
                meta-services. Competently pursue standards compliant leadership
                skills vis-a-vis pandemic "outside the box" thinking.
                Objectively
              </p>
            </div>
          </div>
        </el-col>
      </el-row>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.shouldWeDo {
  margin-top: 160px;
}

.text__content {
  display: flex;
  align-items: center;
  justify-content: center;
}
.do_content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 100%;
  p {
    margin-left: 100px;
    font-size: 18px;
    line-height: 35px;
  }
}

.do {
  margin-top: 70px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-direction: column;
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

@media (max-width: 576px) {
  .number {
    display: none;
  }
  .covid {
    width: 100%;
    text-align: center;
    p {
      font-size: 16px;
      line-height: 30px;
    }
  }
  .do_content {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 20px;
    width: 100%;
    text-align: center;
    p {
      margin-left: 0;
      font-size: 16px;
      line-height: 30px;
    }
  }
  .image {
    display: flex;
    justify-content: center;
    align-items: center;
    img {
      width: 90%;
      min-width: auto;
    }
  }
}
@media (min-width: 576px) {
  .number {
    display: none;
  }
  .covid {
    text-align: center;
    width: 100%;
    p {
      font-size: 16px;
      line-height: 30px;
    }
  }
  .do_content {
    margin-bottom: 20px;
    width: 100%;
    text-align: center;
    p {
      margin-left: 0;
      font-size: 16px;
      line-height: 30px;
    }
  }
  .image {
    display: flex;
    justify-content: center;
    align-items: center;
    img {
      width: 90%;
      min-width: auto;
    }
  }
}

@media (min-width: 768px) {
  .do_content {
    p {
      font-size: 18px;
      line-height: 35px;
    }
  }
}

@media (min-width: 992px) {
  .do_content {
    p {
      font-size: 18px;
      line-height: 35px;
    }
  }
  .left {
    flex-direction: row;
  }
  .right {
    flex-direction: row-reverse;
  }

  .el-row {
    margin-bottom: 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
}

@media (min-width: 1200px) {
  .do_content {
    display: flex;
    justify-content: center;
    align-items: center;
    p {
      font-size: 18px;
      line-height: 35px;
    }
  }
  .text__content {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .left {
    flex-direction: row;
  }
  .right {
    flex-direction: row-reverse;
  }
  .el-row {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
}
</style>
