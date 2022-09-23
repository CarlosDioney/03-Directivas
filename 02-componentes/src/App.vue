<template>
  <h1>Componentes</h1>
  <hr/>
  <Card url="https://cdn.svgporn.com/logos/vue.svg?response-content-disposition=attachment%3Bfilename%3Dvue.svg" nombre="Vue.js"/>
  <Card url="https://cdn.svgporn.com/logos/vuetifyjs.svg?response-content-disposition=attachment%3Bfilename%3Dvuetifyjs.svg" nombre="Vuetify"/>
  <Card url="https://cdn.svgporn.com/logos/angular-icon.svg?response-content-disposition=attachment%3Bfilename%3Dangular-icon.svg" nombre="Angular"/>
  <Card url="https://cdn.svgporn.com/logos/react.svg?response-content-disposition=attachment%3Bfilename%3Dreact.svg" nombre="React"/>
</template>


<script>
  import Card from "./components/Card.vue"
  export default {
    components:{
      Card,
    },
  };
</script>
