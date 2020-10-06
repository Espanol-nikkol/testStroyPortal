<template>
  <header id='header'>
    <menu-nav></menu-nav>
    <MenuSearch></MenuSearch>
  </header>
</template>

<script>

import MenuNav from '@/components/MenuNav.vue';
import MenuSearch from '@/components/MenuSearch.vue';

export default {
  name: 'App',
  components: {
    MenuSearch,
    MenuNav,
  },
};
</script>

<style lang='scss'>
#header {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
