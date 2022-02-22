<template>

  <footer>
      <div class="container">
          <div class="menu-footer-left margin-right">
              <ul>
                  <li>DC COMICS</li>
                  <li>Character</li>
                  <li>Comics</li>
                  <li>Movies</li>
                  <li>TV</li>
                  <li>Games</li>
                  <li>Video</li>
                  <li class="style-shop">SHOP</li>
                  <li>Shop DC</li>
                  <li>Shop DC Collectbles</li>
              </ul>
          </div>
                <ul class="margin-right">
                  <li>DC</li>
                  <li>Terms of use</li>
                  <li>Privacy policy</li>
                  <li>Add choses</li>
                  <li>Advertising</li>
                  <li>Job</li>
                  <li>Subscription</li>
                  <li>Talent workshop</li>
                  <li>CPSC Certification</li>
                  <li>Ratings</li>
                  <li>Shop Help</li>
                  <li>Contact Us</li>
              </ul>              
                <ul>
                  <li>SITES</li>
                  <li>DC</li>
                  <li>MAD Magazine</li>
                  <li>DC</li>
                  <li>DC</li>
                  <li>DC</li>
              </ul> 

      </div>
  </footer>
</template>

<script>
export default {
  name: 'MyFooterSecond',
}
</script>

<style scoped>
    footer{
        height: 360px;
        background-image: url('../assets/footer-bg.jpg');
    }
    .container{
        width: 70%;
        padding: 30px 0px;
    }

    ul{
        display: inline-block;
    }
    
    ul li{
        list-style: none;
        color: rgb(85, 81, 81);
        font-weight: bold;
    }
    ul li:first-child{
        margin-bottom: 15px;
        font-size: 30px;
        color: WHITE;
        font-weight: bold;
    }
    .margin-right{
        margin-right: 20px;
        display: inline-block;
    }
    .style-shop{
        margin-bottom: 15px;
        font-size: 30px;
        color: WHITE;
        font-weight: bold;        
    }
</style>