<template>

  <HeaderSite />
  <MainApp />
  <TheFooter />
</template>

<script>
import HeaderSite from './components/HeaderSite.vue'
import MainApp from './components/MainApp.vue'
import TheFooter from './components/TheFooter.vue'
export default {
  name: 'App',
  components: { HeaderSite, MainApp, TheFooter },
}
</script>



<style>
@import url('https://fonts.googleapis.com/css2?family=Alumni+Sans:wght@400;500;600&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
  text-decoration: none;
  list-style: none;
}

.container {
  padding: 0px 12px;
  margin: 0 auto;
  max-width: 1200px;
}
</style>
