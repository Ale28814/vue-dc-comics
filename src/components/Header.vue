<template>
  <header>
    <div class="container">
        <a href="">
            <img src="../assets/dc-logo.png" alt="logodc">
        </a>
    
        <nav>
            <ul>
                <li><a  href="">characters</a></li>
                <li><a class="active" href="">comics</a></li>
                <li><a  href="">movie</a></li>
                <li><a  href="">tv</a></li>
                <li><a  href="">games</a></li>
                <li><a  href="">collectible</a></li>
                <li><a  href="">video</a></li>
                <li><a  href="">fans</a></li>
                <li><a  href="">news</a></li>
                <li><a  href="">shop</a></li>
            </ul>
        </nav>
    </div>
        
   
  </header>
</template>

<script>
export default {
    name: 'Header',
}


</script>

<style scoped lang="scss">

    .container{
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        vertical-align: middle;
        align-items: center;
        height: 90px;
        img{
            vertical-align: middle;
            max-width: 60px;
        }
    }
   ul {
       display: flex;
       list-style: none;
       justify-content: center;

       a {
           display: inline-block;
           padding: 4px;
           margin-right: 4px;
           text-decoration: none;
           color: #000;
           &.active {
               border-bottom: 4px solid blue;
           }
           &:hover {
               background-color: grey;
           }

       }
   }
</style>