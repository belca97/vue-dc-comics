<template>

  <footer>
    <div class="container">

      <ul>
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
        </li>
        <li>
          <img src="../assets/buy-comics-digital-comics.png" alt="">
          <span>wewe</span>
        </li>
        <li>
          <img src="../assets/buy-comics-digital-comics.png" alt="">
          <span>wewe</span>
        </li>
      </ul>

    </div>
  </footer>
</template>

<script>
export default {
  name: 'MyFooterFirst',
}
</script>

<style scoped lang='scss'>

@import "../assets/style/variable.scss";

  footer{
    height: 150px;
    background-color: $colorFooterFirst;
    color: white;
  }
  .container{
    width: 80%;
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