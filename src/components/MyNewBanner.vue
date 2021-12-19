<template>

    <section class="banner_wrapper">
        <h1>{{bannerTitle}}</h1>
    </section>

</template>

<script>
export default {
    name: 'MyNewBanner',
    data: function(){
        return {
            bannerTitle: 'La Casa de Papel'
        };
    }
}
</script>

<style scoped>
    .banner_wrapper{
        width: 100%;
        height: 50%;
        background-image: url('../assets/img/la-casa-di-carta-jumbo.jpg');
        background-position: center;
        background-size: cover;
        background-repeat: no-repeat;
    }
    h1{
        text-transform: uppercase;
        font-size: 40px;
        color: red;
        letter-spacing: 2rem;
        text-indent: 2rem;
        font-weight: bold;
    }
</style>