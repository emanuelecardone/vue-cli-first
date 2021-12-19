<template>

    <section class="banner_wrapper">
        <h1>{{bannerTitle}}</h1>
        <p>{{bannerText}}</p>
    </section>

</template>

<script>
export default {
    name: 'MyNewBanner',
    data: function(){
        return {
            bannerTitle: 'La Casa de Papel',
            bannerText: 'La casa di carta narra di un gruppo di rapinatori composto da nove persone. L’obiettivo è una super rapina alla zecca di stato spagnola a Madrid, la Fabrica Nacional de Moneda y Timbre. L’ideatore del colpo è un uomo chiamato il Professore. Ha selezionato altri 8 componenti a cui viene dato il nome di una città: Tokyo, Mosca, Denver, Berlino, Nairobi, Rio, Helsinki ed Oslo.'
        };
    }
}
</script>

<style scoped>
    .banner_wrapper{
        width: 100%;
        height: 50%;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
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
        align-self: center;
    }
    p{  
        align-self: flex-end;
        font-size: 20px;
        max-width: 50%;
        color: red;
        text-align: center;
    }
</style>