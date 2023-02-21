<script>
import data from './../assets/datos.json'
import Elementoli from '../components/Elementoli.vue'

export default{
    data(){
        return{
            lista:data
        }
        
    },
    components: {
            Elementoli
        }
}
</script>


<template>
    <div class="">
 
  <div class="px-6 py-4">

    <section class="w-120 rounded overflow-hidden shadow-lg p-12 m-10 snap-start bg-teal-400" v-for="etapa in lista.etapas">
    <ul>
        <ul class="font-semibold font-titular text-3xl">Sección {{etapa.id}}. {{etapa.nombre}} </ul> 
        <ul class="text-xl font-semibold"> 1 de {{etapa.pasos.length}}</ul> 
        
    </ul>

    <ul class="px-5 py-3 py-3 rounded-md">
         <Elementoli v-for="paso in etapa.pasos" :paso="paso"></Elementoli>
         
    </ul>


</section>




    <p class="text-gray-700 text-base">
    
    </p>
  </div>
  
</div>
    
   

</template>



