<template>
        <div class="box-img">
            <img :src="thumb" :alt="series">
            <h3>{{series}}</h3>
        </div>
</template>

<script>
export default {
    name: 'MyHeroCard',
    props: {
        "series": String,
        "thumb": String
    }
}
</script>

<style lang="scss" scoped>

    .box-img{
        min-height: 350px;
        margin: 10px 15px;
        width: 13%;
    }
    .box-img img{
        width: 100%;
    }

</style>>