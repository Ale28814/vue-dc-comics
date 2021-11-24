<template>
  <header>
    <div class="container">
        <a href="">
            <img src="../assets/dc-logo.png" alt="logodc">
        </a>
    
        <nav>
            <ul>
                <li v-for="(link, index) in Navi" :key="`Navi-${index}`">
                    <a href="`${link.url}`">{{link.text}}</a>
                </li>
            </ul>
        </nav>
    </div>
        
   
  </header>
</template>

<script>
export default {
    name: 'Header',
    data(){
        return {
            Navi: [
                {
                    text: 'Characters',
                    url: '/Characters',
                    current: true,
                },
                {
                    text: 'Comics',
                    url: '/Comics',
                    current: false,
                },
                {
                    text: 'Movies',
                    url: '/Movies',
                    current: false,
                },
                {
                    text: 'Characters',
                    url: '/Characters',
                    current: false,
                },
                {
                    text: 'Tv',
                    url: '/Tv',
                    current: false,
                },
                {
                    text: 'games',
                    url: '/games',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '/Collectibles',
                    current: false,
                },
                {
                    text: 'videos',
                    url: '/videos',
                    current: false,
                },
                {
                    text: 'fans',
                    url: '/fans',
                    current: false,
                },
                {
                    text: 'shop',
                    url: '/shop',
                    current: false,
                },
            ]
        }
    }
}


</script>

<style scoped lang="scss">
@import '@/Styles/preset';
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