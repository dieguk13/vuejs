
<script>
export default{
  data() {
    return {
      name: "prueba dinamico"
    }
  },
   created(){
    alert ("created") 
   },
   mounted(){
    alert ("mounted") 
   },
   updated(){
    alert ("updated") 
   },
   destroyed(){
    alert ("destroyed") 
   },
   computed:{

   },
   methods: {
    
   },
   //watch
}

</script>
<template>
  <h1>esto es un merge con {{ name}}</h1>
</template>

<style>
h1 {
color: blue;
} 

</style>