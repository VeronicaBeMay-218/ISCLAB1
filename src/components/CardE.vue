<template>
 
 <div id="mi-componente">
 
    <div class="flex items-center font-bold ... w-120 rounded overflow-hidden shadow-lg p-12 m-10 snap-start bg-teal-400">
        <div class="text-sm"> 
        <p class="text-gray-700 font-bold text-3xl mb-2">{{ parrafo1}}</p>
        <p class="text-gray-700 font-bold text-3xl mb-2">{{ parrafo2 }}</p>
        <p class="text-gray-700 font-bold text-3xl mb-2">{{ parrafo3 }}</p>
        </div>
        
            <p class="text-gray-900 font-bold text-6xl mb-2"> ¿Pueden crear un sitio web gratuito para mi proyecto? </p>
        

    </div>
  </div>
</template>

<script>
export default {
    name: 'Micomponente',
    data(){
        return{
            parrafo1:'- La respuesta corta es sí.',
            parrafo2:'- Claro que necesitamos saber en qué consiste el sitio que necesitas y tu historia para valorar el apoyo gratuito en la creación y publicación de tu sitio.',
            parrafo3:'- Averigua las condiciones de un sitio web gratuito para nosotros será un placer apoyarte.'
        }
    }
}
</script>