<script>
  
  export default{
    data: () => ({
      contador : 500,
    }),
    methods: {
      saludar(){
        console.log("Esto no es musica es droga");
      },
      incrementar(){
        this.contador++;
      },
      disminuir(){
        this.contador--;
      },
      resetear(){
        this.contador = 500;
      }
    },
  };

  // export default{
  //   data(){
  //     return{
  //       contador:200,
  //     };
  //   },
  // };
</script>

<template>
  
  <img src="./assets/logo.svg" alt="logo vue" width="125" height="125">
  <small>
    <h1>Hola desde vue.13</h1>
  </small>
  <hr>
  <h2>Contador {{contador}}</h2>
  <button @click="incrementar()">+1</button>
  <button @click="disminuir()">-1</button>
  <button @click="resetear">reset</button>
  
  <!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
 Uriel Marquez Cruz 4°A
</button>




</template>

<style scoped>
  .container{
    text-align: center;
    
  }
  h1{
    font-weight: center;
  }
  
  small{
    color: #666;
  }

  button{
    cursor: pointer;
    font-size: 1.5 rem;
    margin: 0px 8px;
  }

</style>


  body{
    background-color: #ccc;

  }