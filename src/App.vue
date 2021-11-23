<template>
  <div id="app">
    <!--header-->
  <Header />

  <Title />
    <!--main-->
  <Main />
    <!--footer-->

  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Title from '@/components/Title.vue'
import Main from '@/components/Main.vue'

export default {
  name: 'App',
  components: {
    Header,
    Title,
    Main,
  }
}
</script>

<style scoped lang="scss">
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}
</style>
