SFC 
Single File Components

HTML 
CSS
JS

template
style 
script  

<script>
  export default{
    data: () => ({
      contador : 500,
    }),
    methods: {
      saludar(){
        console.log("HOLA 4A");
      },
      incrementar(){
        this.contador++;
      },
      decrementar(){
        this.contador--;
      },
      reset(){
        this.contador = 500
      }
    },
  };
</script>





<template> 
<div class="container">
  <img src="./assets/logo.svg" alt="Logo VUE" width="125" height="125">
  <small>
    <h1>Hola desde VUE.js 3</h1>
  </small>
<hr>

<h2>Contador {{contador}}</h2>
<button @click="incrementar()"> +1 </button>
<button @click="decrementar()">-1</button>
<button @click="reset()">Reset</button>
</div>
</template>

<style scoped>
  .container {
    text-align: center;
  }
  small{
    color: #666;
  }
  h1{
    font-weight: bolder;
  }
  button{
    cursor: pointer;
    font-size: 1.5rem;
    margin: 0px 8px;
  }
</style> 

