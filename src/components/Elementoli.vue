<script>

export default {
  props: ['paso'],
  
}

</script>

<template>
    <li class="font-xl font-medium mb-3 border-b-0 ">
    <input type="checkbox" v-model="paso.hecho" class="v-6 h-6 align-middle">
    <span class="text-primario">{{paso.titulo}}</span><br>
    <p class="font-medium ml-9 italic text-secundario">Entregable</p>

    </li>
</template>
