<template>
  <div id="app">
    <nav>
      <router-link to="/">Главная</router-link> |
      <router-link to="/catalog">Каталог продукции</router-link>
      <router-link to="/program">подбор программы</router-link>
    </nav>
    <router-view/>
  </div>
</template>


