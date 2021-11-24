<template>
  <div id="app">
    <!--header-->
    <Header />

    <Title />
    <!--main-->
    <Bonuss />

    <Mained />

    <Newsec />

    <Main />
    <!--footer-->
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Title from '@/components/Title.vue'
import Main from '@/components/Main.vue'
import Footer from '@/components/Footer.vue'
import Bonuss from '@/components/Bonuss.vue'
import Newsec from '@/components/Newsec.vue'
import Mained from '@/components/Mained.vue'

export default {
  name: 'App',
  components: {
    Header,
    Title,
    Main,
    Footer,
    Bonuss,
    Newsec,
    Mained,
  }
}
</script>

<style scoped lang="scss">
@import '@/Styles/preset';
</style>
