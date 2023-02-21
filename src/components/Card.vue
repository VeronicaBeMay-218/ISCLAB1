<template>
 
 <div id="mi-componente">
 
    <div class="flex items-center font-bold ... w-120 rounded overflow-hidden shadow-lg p-12 m-10 snap-start bg-teal-400">

        <p class="text-gray-900 font-bold text-6xl mb-2">¿Qué hacemos en isclab? </p>
        <div class="text-sm"> 
        <p class="text-gray-700 font-bold text-3xl mb-2">{{ parrafo1}}</p>
        <p class="text-gray-700 font-bold text-3xl mb-2">{{ parrafo2 }}</p>
        <p class="text-gray-700 font-bold text-3xl mb-2">{{ parrafo3 }}</p>
        </div>

    </div>
  </div>
</template>

<script>
export default {
    name: 'Micomponente',
    data(){
        return{
            parrafo1:'- Desarrollamos aplicaciones con fines de práctica, investigación y responsabilidad social',
            parrafo2:'- Buscamos el desarrollo de nuestros estudiantes a través de la creación de proyectos que sean útiles a la sociedad.',
            parrafo3:'- ¿Tienes un proyecto en mente? Compártelo con nosotros y buscaremos la manera de ayudarte.'
        }
    }
}
</script>
