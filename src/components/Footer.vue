<template>
  <footer>
    <div class="main-wrap">
      <div class="details list-items">
        <ul>
          <li>
            <a href="#">Каталог курсов</a>
          </li>
          <li>
            <a href="#">Методология</a>
          </li>
          <li>
            <a href="#">Вакансии</a>
          </li>
          <li>
            <a href="#">Обратная связь</a>
          </li>
          <li>
            <a href="#">Тренеры</a>
          </li>
          <li>
            <a href="#">О проекте</a>
          </li>
          <li>
            <a href="#">Контакты</a>
          </li>
          <li>
            <a href="#">Стать тренером</a>
          </li>
        </ul>
      </div>
      <nav class="contacts list-items">
        <ul>
          <li>
            <a href="#">Условия соглашения</a>
          </li>
          <span>/</span>
          <li>
            <a href="#">Политика конфиденциальности</a>
          </li>
          <li>© Jooby 2020. Все права защищены.</li>
        </ul>
      </nav>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
  props: {},
};
</script>

<style scoped>
.main-wrap {
  position: absolute;
  bottom: 0px;
  background-color: #000000;
  display: flex;
  align-items: center;
  justify-content: space-between;
  color: #ffffff;
}
.list-items {
  margin-bottom: 26px;
  margin-top: 20px;
}
.list-items > ul > li {
  display: inline-block;
  cursor: pointer;
  font-style: normal;
  align-self: center;
  height: 40px;
}
.list-items > ul > li > a {
  text-decoration: none;
  color: #ffffff;
}
.list-items > ul > li > a:hover {
  color: #003687;
}
.details {
  font-style: normal;
  font-weight: 450;
  font-size: 18px;
  line-height: 22px;
}
.details > ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}
.details > ul > li {
  margin-right: 100px;
  width: 130px;
}
.contacts {
  font-size: 14px;
  line-height: 22px;
  opacity: 0.5;
  width: 50%;
}
.contacts > ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.contacts span {
  margin-left: 24px;
  margin-right: 24px;
  height: 40px;
}
.contacts li:last-child {
  cursor: auto;
}
</style>
