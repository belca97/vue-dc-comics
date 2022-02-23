<template>

  <footer>
    <div class="container">

      <ul>
        <li v-for="(item, index) in items" :key="index"> 
          <img :src='(item.logo)' alt="">
          <span>{{item.text}}</span>
        </li>
        <!-- <li>
          <img src="../assets/buy-comics-digital-comics.png" alt="">
          <span>wewe</span>
        </li>
        <li>
          <img src="../assets/buy-comics-digital-comics.png" alt="">
          <span>wewe</span>
        </li>
        <li>
          <img src="../assets/buy-comics-digital-comics.png" alt="">
          <span>wewe</span>
        </li>
        <li>
          <img src="../assets/buy-comics-digital-comics.png" alt="">
          <span>wewe</span>
        </li> -->
      </ul>

    </div>
  </footer>
</template>

<script>
export default {
  name: 'MyFooterFirst',
      data(){
        return{


            items : [
              {
                logo : require('../assets/buy-comics-digital-comics.png'),
                text : 'DIGITAL COMICS'
              },
              {
                logo : require('../assets/buy-comics-merchandise.png'),
                text : 'DC MERCHANDISE'
              },
              {
                logo : require('../assets/buy-comics-shop-locator.png'),
                text : 'SHOP LOCATOR'
              },
              {
                logo : require('../assets/buy-comics-subscriptions.png'),
                text : 'DC POWER'
              },
              {
                logo : require('../assets/buy-dc-power-visa.svg'),
                text : 'DC POWER VISA'
              }
            ],
      }
    }
}

</script>

<style scoped lang='scss'>

@import "../assets/style/variable.scss";

  footer{
    height: 150px;
    background-color: $colorFooterFirst;
    color: white;
    z-index: 998;
  }
  .container{
    width: 70%;
    height: 100%;
    margin: 0 auto;
    display: flex;
    align-items: center;
  }

  ul{
    width: 100%;
    display: flex;
    justify-content: center;
  }
  ul li{
    display: flex;
    align-items: center;
  }

  ul li img{
    width: 50px;
    height: 60px;
    margin-right: 10px;    
    }
    span{
      font-size: 18px;
      font-weight: bold;
    }
</style>