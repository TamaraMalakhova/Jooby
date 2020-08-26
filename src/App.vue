<template>
  <div id="app">
    <div class="main-board">
      <Header />
      <MainPage />
    </div>
    <Footer />
  </div>
</template>

<script>
import MainPage from "./components/screens/MainPage";
import Header from "./components/Header";
import Footer from "./components/Footer";

export default {
  name: "App",
  components: {
    MainPage,
    Header,
    Footer
  },
};
</script>

<style>
#app {
  color: #2c3e50;
}
.main-board {
  margin: 32px 138px 0px 118px;
  font-family: Futura PT;
}
</style>
