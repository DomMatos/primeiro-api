<template>
 <div id="app">
   <Header />
   <Casa />
   
   
    
   
 </div>
  
</template>

<script>
import './components/styles/global.css';
import Header from './components/Header';
import Casa from './pages/Casa.vue'




export default {
  name: 'App',
  components: {
    Header,
    Casa 
    
     
  }
}
</script>

<style>

</style>
