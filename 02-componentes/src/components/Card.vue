<template>
    <Grid>
        <img :src="url" :alt="nombre">
        <h2>{{ nombre }}</h2>
        <h4>En venta</h4>
        <a :href="url" target="_blank">Descargar</a>
        <a :href="url" target="_blank">Visitar</a>
    </Grid>
</template>

<script>
    import Grid from "./Grid.vue";
    export default{
    props: {
        url: {
            String,
        },
        nombre: {
            String,
        },
    },
    components: { Grid },
};
</script>

<style scopet>

    img{
        width: 8rem;
        height: 8rem;
        padding: 0.5rem;
        background: snow;
    }
    a{
        text-decoration: none;
        color: snow;
        background: #301675;
        padding: 0.3rem;
        border-radius: 5px;
        border: 1px solid #f2f2f2;
    }
</style>