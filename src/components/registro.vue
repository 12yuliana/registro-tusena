<template>
    <div class="registro">
      <div class="inicio">
         <div class="iniciar">
          <input  class="input" type="button" value="Iniciar Sesion">
         </div>
         <div class="ayuda">
         <input  class="input" type="button" value="Ayuda">
         </div>
      </div>
      <div class="saludo">
        <p class="p">
         ¡Hola! Bienvenido al registro
        </p>
      </div>
      
       <form class="texto">
       <input  class="input1" type="text" placeholder="Nombres">
       <input  class="input1" type="text" placeholder="Apellidos">
       <input  class="input1" type="text" placeholder="Numero de Identificacion">
       <input  class="input1" type="text" placeholder="Correo Electronico">
       <input  class="input1" type="text" placeholder="Contraseña">
       <input  class="input1" type="text" placeholder="Confirmar Contraseña">
       </form>
    
      <form class="chebots">
          <input  class="chebox" type="checkbox">
          <p class="leer">
            He leido y acepto los terminos y condiciones
          </p>
        </form>
  <form class="registrarse">
    <input  class="input" type="button" value="Registrarse">
  </form>
    </div>
  </template>
  <script>
  export default{
    name:'registro-vue'
  }
</script>
<style scoped >
.chebox{
  margin-left: auto;
}
.leer{
  -webkit-text-stroke: 0.5px white;
 color: black;
font-weight: 1000;
margin-right: auto;
font-size: 20px;
}

.chebots{
  display: flex;
}
.texto{
  display: flex;
  flex-direction: column;
}
.input1{
  margin: auto;

  font-size: 100%;
  background-color: rgba(110, 94, 148, 0.438);
 width:20%;
 height: auto;
 margin: 0 auto 15px auto;
 padding: 5px;
 border: 1px solid transparent;
 -moz-border-radius: 30px;
 -webkit-border-radius: 30px;
 border-radius: 30px;
  -webkit-text-stroke: 0.2px white;
 color: black;
font-weight: 1000; 
}
.input1::placeholder{
  color: black;
  /* font-size: 20px; */
}
.inicio{
  display: flex;
  
}
.input{
  font-size: 20px;
  background-color: rgba(110, 94, 148, 0.438);
 width: 180px;
 height: auto;
 margin: 0 auto 15px auto;
 padding: 5px;
 border: 1px solid transparent;
 -moz-border-radius: 30px;
 -webkit-border-radius: 30px;
 border-radius: 30px;
 /* text-shadow:2px solid  white; */
 -webkit-text-stroke: 0.5px white;
 color: black;
font-weight: 1000;
margin-top: 20px;
}
.iniciar{
  margin-left: auto;
  width: 15%; 
}
 .ayuda{
  margin-right:30px;
} 
.p{
  font-size: 50px;
  -webkit-text-stroke: 2px white;
 color: black;
font-weight: 1000;
}

  

</style>