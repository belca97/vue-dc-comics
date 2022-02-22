<template>
    <main>
    <div class="container">
        <h3> --> Content goes here -- </h3>
    </div>
    </main>
</template>

<script>
export default {
  name: 'MyMain',
}
</script>

<style scoped>

    main{
        background-color: rgb(48, 45, 45);
        color: white;
        height: 150px;
        display: flex;
        align-items: center;
    }

    .container{
        width: 70%;
        margin: 0 auto;
    }

    h3{
        font-size: 50px;
    }
</style>
