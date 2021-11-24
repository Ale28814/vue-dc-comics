<template>
  <div class="foot">
      <div class="sx">
          <a class="sign">SIGN-UP NOW</a>
      </div>
            <div class="social">
                <ul>
                    <li>
                        <a href="">
                            <img src="../assets/footer-facebook.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="../assets/footer-twitter.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="../assets/footer-youtube.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="../assets/footer-pinterest.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="">
                            <img src="../assets/footer-periscope.png" alt="">
                        </a>
                    </li>
                </ul>
            </div>
      
      
  </div>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped lang="scss">
    .foot{
        background-color: #303030;
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
        width: 100%;

        .sx{
            display: flex;
            flex-direction: row;
            padding-block: 35px;
            justify-content: space-between;
            a.sign{
                display: flex;
                align-items: center;
                //height: fit-content;
                background-color: transparent;
                border: 2px solid #0282f9;
                padding: 7px 17px;
                color: white;
                cursor: pointer;
                transition: all .1s ease;
            }
        }
    }
    .social{
        li{
            display: inline-block;
            margin-left: 15px;
        }
    }
</style>