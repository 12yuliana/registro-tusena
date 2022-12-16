<template>
  <main>
    <registro/>
  </main>

</template>
<script>
import registro from '@/components/registro.vue'
export default{
 
    name:'registro-viem',
    components: { registro } 
    
}
</script>
<style scoped>
main{

  background-image: url(../assets/sena.png);
  height: 95vh;
  background-color: black;
  background-size: cover;
  /* margin: auto; */
}
</style>