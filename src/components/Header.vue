<template>
  <header>
    <div class="main-wrapper">
      <div class="info">
        <img src="../assets/logo.png" />
        <nav class="list-items extra-menu">
          <ul>
            <li>
              <a href="#">Онлайн сервис курсов</a>
            </li>
            <span>/</span>
            <li>
              <a href="#">О проекте</a>
            </li>
          </ul>
        </nav>
      </div>

      <div class="search-login">
        <input placeholder="Найти видеокурс" />
        <div class="button_login">Войти</div>
        <i class="fas fa-shopping-bag"></i>
      </div>
    </div>

    <nav class="list-items main-menu">
      <ul>
        <li>
          <a href="#">Бизнес</a>
        </li>
        <li>
          <a href="#">Маркетинг</a>
        </li>
        <li>
          <a href="#">Графика и дизайн</a>
        </li>
        <li>
          <a href="#">Фото, видео и анимация</a>
        </li>
        <li>
          <a href="#">Личностный рост</a>
        </li>
        <li>
          <a href="#">Лайфстайл</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
import * as Icons from "fontawesome";
export default {
  name: "Header",
  props: {
    isLogin: Boolean,
  },
};
</script>

<style scoped>
.main-wrapper {
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.info {
  display: flex;
  align-items: center;
  height: 100%;
}

.search-login {
  display: flex;
}

.search-login input {
  border: 1px solid #000000;
  box-sizing: border-box;
  border-radius: 4px;
  opacity: 0.2;
  height: 50px;
  width: 407px;
  padding-left: 24px;
  margin-right: 24px;
}

.button_login {
  display: flex;
  align-items: center;
  justify-content: center;
  border: 1px solid #000000;
  box-sizing: border-box;
  border-radius: 4px;
  padding: 14px;
  width: 87px;
  height: 50px;
  font-weight: 450;
  font-size: 16px;
  line-height: 24px;
  margin-right: 24px;
  cursor: pointer;
}

header {
  background-color: #ffffff;
  height: 65px;
  position: sticky;
  top: 0;
  z-index: 10;
}
.list-items > ul{
  padding: 0px;
}
.list-items > ul > li {
  display: inline-block;
  cursor: pointer;
}

.list-items > ul > li > a {
  text-decoration: none;
}

.list-items > ul > li > a:hover {
  color: #003687;
}

.extra-menu {
  margin-left: 0px;
  padding-left: 24px;
}

.extra-menu > ul > li > a {
  color: #2d2d30;
  opacity: 0.6;
}

.extra-menu span {
  margin: 24px;
}

.main-menu {
  margin-left: auto;
  margin-top: 30px;
}

.main-menu > ul > li {
  margin-right: 44px;
  font-weight: 500;
  font-size: 18px;
  line-height: 22px;
}

.main-menu > ul > li > a {
  color: #000000;
}
</style>
