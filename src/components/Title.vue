<template> 

    <section>
        <h2>{{titleText}}</h2>
    </section>

</template>

<script> 

export default{
    name: 'Title',
    data: function(){
        return {
            titleText: 'La mia prima app con Vue CLI!'
        };
    }
}

</script>

<style scoped> 
    h2{
        color: cyan;
        text-transform: uppercase;
        letter-spacing: 1rem;
        text-indent: 1rem;
    }
</style>