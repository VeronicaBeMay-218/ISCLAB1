<script setup>
//import HelloWorld from './components/HelloWorld.vue'
import boton from './components/boton.vue'
import lista from './components/lista.vue'
import Encabezado from './components/Encabezado.vue'
import Card from './components/Card.vue'
import CardE from './components/CardE.vue'
import Titulo from './components/Titulo.vue'
import Parrafo from './components/Parrafo.vue'
import CardDoble from './components/CardDoble.vue'
import headerE from './components/headerE.vue'
import FooterE from './components/FooterE.vue'



</script>

<template>

  <header>
  <headerE></headerE>
    <Encabezado></Encabezado>
    
  </header>




  <main>
    
    <Card></Card>
    <CardE></CardE>
    <Titulo></Titulo>
    <Parrafo></Parrafo>
    <CardDoble></CardDoble>

    
    
  </main>

  <footer>
  <FooterE></FooterE>

  
  </footer>

</template>