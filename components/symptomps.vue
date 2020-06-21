<template>
  <div class="symptomps">
    <div class="covid">
      <h3>Covid-19</h3>
      <h2>Symptomps</h2>
      <p>
        Corona viruses are a type of virus. There are many different kinds, and
        some cause disease. A newly identified type has caused a recent outbreak
        of respiratory
      </p>
    </div>
    <img src="@/static/Group 15444.svg" alt="symptomps" />
  </div>
</template>
<style lang="scss" scoped>
.covid {
  margin-top: 100px;
  width: 50%;
}
.symptomps {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
@media (max-width: 576px) {
  .covid {
    width: 100%;
  }
  .symptomps {
    img {
      width: 118%;
    }
  }
}
@media (min-width: 576px) {
  .covid {
    width: 100%;
  }
  .symptomps {
    img {
      width: 118%;
    }
  }
}

// Средние девайсы («таблетки», >= 768px)
@media (min-width: 768px) {
  .covid {
    width: 100%;
  }
  .symptomps {
    img {
      width: 118%;
    }
  }
}

// Большие девайсы (десктопы, >= 992px)
@media (min-width: 992px) {
  .covid {
    width: 100%;
  }
  .symptomps {
    img {
      width: 100%;
    }
  }
}

// Экстрабольшие девайсы (большие десктопы, >= 1200px)
@media (min-width: 1200px) {
  .covid {
    width: 50%;
  }
  .symptomps {
    img {
      width: 100%;
    }
  }
}
</style>
