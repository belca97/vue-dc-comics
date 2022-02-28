.<template>
   <div class="jumbotron">
      <img src="../assets/jumbotron.jpg" alt="">
      <button>CURRENT SERIES</button>
   </div>
</template>

<script>
export default {
    name:'MyJumbotron'
}
</script>

<style scoped lang='scss'>

 @import "../assets/style/variable.scss";

 .jumbotron{
     height: 500px;
     width: 100%;
 }
 .jumbotron img{
    object-position: top;
    object-fit: cover;
    width: 100%;
    height: 100%;
    position: relative;
 }
 button{
     font-size: 20px;
     background-color:  $colorFooterFirst;
     color: white;
     padding: 10px 32px;
     position: absolute;
     left: 15%;
     top: 65%;
     border: 1px solid $colorFooterFirst;
 }
</style>