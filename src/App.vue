<template>
  <div id="app">

  <h2>Conversor de Moedas</h2>

    <div id="linha">
      <Conversor moedaA="USD" moedaB="BRL"/>
      <Conversor moedaA="BRL" moedaB="USD"/>
    </div>
    <div id="linha">
      <Conversor moedaA="CAD" moedaB="BRL"/>
      <Conversor moedaA="BRL" moedaB="CAD"/>
    </div>
    <div id="linha">
      <Conversor moedaA="EUR" moedaB="BRL"/>
      <Conversor moedaA="BRL" moedaB="EUR"/>
    </div>
  </div>

</template>
 

<script>

import Conversor from './components/Conversor.vue' 

export default {

  name: 'app',
  components: {
     Conversor
   }

}

</script> 

<style>

#app {
   font-family: 'Avenir', Helvetica, Arial, sans-serif;
   -webkit-font-smoothing: antialiased;
   -moz-osx-font-smoothing: grayscale;
   text-align: center;
   color: #2c3e50;
   margin-top: 60px;

} 

#linha{
  display: flex;
  margin-top: 40px;
  justify-content: space-around;
} 

#h2{
  text-align: center;
} 

#app{
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  margin: auto;
  max-width: 900px;
} 

</style>