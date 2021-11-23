<template>
  <div class="navigation">
      <div class="sx">
        <ul>
          <li> <h3>DC COMICS</h3> </li>
          <li>characters</li>
          <li>comics</li>
          <li>movies</li>
          <li>tv</li>
          <li>games</li>
          <li>videos</li>
          <li>news</li>
          <li><h3>SHOP</h3></li>
          <li>shop dc</li>
          <li>shop dc collectibles</li>
        </ul>
      </div>
      <div class="cent">
        <ul>
          <li><h3>DC</h3></li>
          <li>termes of use</li>
          <li>privacy polici</li>
          <li>add choices</li>
          <li>advertising</li>
          <li>jobs</li>
          <li>subscription</li>
          <li>talent workshops</li>
          <li>cpsc certificate</li>
          <li>rating</li>
          <li>shop help</li>
          <li>contact us</li>
        </ul>
          
      </div>
    <div class="dx">
        <ul>
            <li><h3>SITES</h3></li>
            <li>dc</li>
            <li>mad magazine</li>
            <li>dc kids</li>
            <li>dc universe</li>
            <li>dc power visa</li>
        </ul>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Main',
}
</script>

<style scoped lang="scss">
    .navigation{
        font-weight: 100;
        background-image: url(../assets/footer-bg.jpg);
        color: honeydew;
        display: flex;
        flex-direction: row;
        justify-content: start;
        .sx{
            margin-left: 140px;
        }
    }
    ul{
        list-style: none;
    }
</style>