<template>
  
  <NavBarComp/>
  <router-view/>

</template>
<script>
import NavBarComp from './components/NavBar-comp.vue';

export default {

  components: {NavBarComp}
  
}

</script>
