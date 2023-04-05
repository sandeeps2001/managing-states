
import Cards from './components/Cards.vue';


import Heading from './components/Heading.vue';


import Nav from './components/Nav.vue';
:style="isDarkMode ?{backgroundColor: 'black'} : null"
:style ="isDarkMode ?{backgroundColor: 'black'} : null"


<script setup lang="ts">
const {isDarkMode,toggleDarkMode} = useDarkMode();
</script>
<template> 
  <div :style="isDarkMode ? {backgroundColor:'black'}:null"> 
    <Nav />
    <Heading/>
    <Cards/>
  </div>
</template>

<style >
* {
  margin: 0;
  padding: 0;
  font-family: Georgia;
}
</style>
