<template>
  <header class="header container">
    <nav class="desktop-nav">
      <img src="../assets/logo-desktop.png" alt="logo" class="animate" />
      <ul class="header-list">
        <li class="header-list__item pointer">
          <router-link to="/">Главная</router-link>
        </li>
        <li class="header-list__item pointer">
          <router-link to="/catalog">каталог продукции</router-link>
        </li>
        <li class="header-list__item pointer">
          <router-link to="/program">подбор программы</router-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "TheHeader",
};
</script>

<style lang="scss" >
.header {
  .desktop-nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1300px;
    width: 100%;
    margin: 0 auto;
    img {
      padding-left: 10px;
    }
    ul{
      padding-right: 10px;
      display: flex;
      justify-content: space-between;
    align-items: center;
    }
  }
  &-list__item{
    font-size: 20px;
    font-weight: 400;
    line-height: normal;
    text-transform: uppercase;
}}

</style>