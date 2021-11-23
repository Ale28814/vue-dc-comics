<template>
  <div id="app">
    <!--header-->
  <Header />

  <Title />
    <!--main-->

    <!--footer-->

  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Title from '@/components/Title.vue'
export default {
  name: 'App',
  components: {
    Header,
    Title,
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
