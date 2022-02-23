<template>
    <div>
        <header>
            <div class="container">
                <div class="logo-header">
                    <img src="../assets/dc-logo.png" alt="">
                </div>

                <div class="menu-header">
                    <ul>
                        <li>character</li>
                        <li>comics</li>
                        <li>movies</li>
                        <li>tv</li>
                        <li>games</li>
                        <li>collectibles</li>
                        <li>videos</li>
                        <li>fans</li>   
                        <li>news</li>
                        <li>shop</li>                           
                    </ul>
                </div>
            </div>

        </header>
    </div>
</template>

<script>
export default {
  name: 'MyHeader',
}
</script>

<style scoped>
    header{
        height: 150px;
        display: flex;
        align-items: center;      
    }
    .container{
        width: 70%;
        margin: 0 auto;
        display: flex;
    }
    .container::after{
        clear: both;
        display: table;
        content: '';
    }
    .logo-header{
        float: left;
        width: 10%;
    }
    .logo-header img{
        width: 100px;
        height: 100px;
    }
    .menu-header{
        float: right;
        width: 90%;
        text-align: right;
        display: flex;
        align-items: center;
    }
    ul li{
        display: inline-block;
        margin: 0px 10px;
        font-weight: bold;
        font-size: 20px;
    }

    ul li.active, ul li:hover{
        color: blue;
        border-bottom: 3px solid blue;
    }
</style>