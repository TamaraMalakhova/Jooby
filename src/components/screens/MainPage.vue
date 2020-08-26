<template>
  <div class="main-wrap">
    <div class="advert">
      <h1>Бесплатный курс для тебя от jooby</h1>
      <div class="advert__button">Получить бесплатный курс</div>
    </div>
    <div class="popular-courses">
      <div class="popular-courses__header">
        <h2>Популярные курсы</h2>
        <div class="popular-courses__button">Смотреть все курсы</div>
      </div>
      <div class="popular-courses__cards">
        <div class="popular-courses__card">
          <div class="popular-courses__card__category">Фотография</div>
          <div class="popular-courses__card__title">iPhone Photography от А до Я</div>
          <div class="popular-courses__card__price">2 800 ₽</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainPage",
  components: {},
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.main-wrap {
  margin-top: 50px;
}
.main-wrap h2 {
  font-weight: 600;
  font-size: 36px;
  line-height: 46px;
  margin-top: 0px;
  margin-right: 30px;
}
.advert {
  background: url(../../assets/advert.png) no-repeat;
  height: 380px;

  padding-left: 80px;
}
.advert h1 {
  padding-top: 78px;
  color: #ffffff;
  font-weight: 800;
  font-size: 44px;
  line-height: 56px;
  width: 359px;
}
.advert__button {
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 500;
  font-size: 18px;
  line-height: 22px;
  border: 1px solid #ffffff;
  background-color: #ffffff;
  box-sizing: border-box;
  border-radius: 4px;
  width: 300px;
  height: 40px;
  cursor: pointer;
  padding: 17px 30px;
}
.popular-courses__header {
  display: flex;
}
.popular-courses__button {
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 450;
  font-size: 16px;
  line-height: 24px;
  border: 1px solid #000000;
  box-sizing: border-box;
  border-radius: 4px;
  width: 171px;
  height: 40px;
  cursor: pointer;
}
.popular-courses__cards {
  display: flex;
  color: #ffffff;
}
.popular-courses__card__category{
  color:#000000;
  background-color: #ffffff;
}
.popular-courses__card__title {
  font-weight: 450;
  font-size: 18px;
  line-height: 22px;
}
</style>
