<script>
import data from './../assets/datos.json'

export default{
    data(){
        return{
            lista:data
        }
    }
}
</script>

<template>
<ul>
  <li v-for="item in lista.fase.preguntas"> <input type="checkbox"> {{ item.preg }}</li>
</ul>
</template>