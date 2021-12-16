<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" width="25%" />
    <Hello msg="Приветствуем наших клиентов!" />
    <Links
      msg="Подробнее о нас"
      lnk1="https://www.youtube.com"
      lnkName1="Наш канал"
      lnk2="https://www.instagram.com"
      lnkName2="Наш Инстаграмм"
    />
    <Links
      msg="Наши партнеры"
      lnk1="https://www.youtube.com"
      lnkName1="Вася"
      lnk2="https://www.instagram.com"
      lnkName2="Петя"
    />
    <Links
      msg="Сайт разработал"
      lnk1="https://www.youtube.com"
      lnkName1="Алексей"
    />
  </div>
</template>

<script>
import Hello from "./components/Hello.vue";
import Links from "./components/Links.vue";

export default {
  name: "App",
  components: {
    Hello,
    Links,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
