<template>
  <div>
    Cointerner html  
    <home-component></home-component>
    
    <maps-component></maps-component>
  </div>
</template>
<script>
import HomeComponent from './components/Home'
import MapsComponent from './components/Maps'
export default {
  components:{
    HomeComponent,
    MapsComponent
  }
  
}
</script>