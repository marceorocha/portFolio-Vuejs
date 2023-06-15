<template>
  
  <PaginaPrincipal msg="My Portfolio"/>
  <ProjectsCard></ProjectsCard>
  
</template>

<script>
import PaginaPrincipal from './components/PaginaPrincipal.vue'
import ProjectsCard from './components/ProjectsCard.vue';


export default {
  name: 'App',
  components: {
    PaginaPrincipal,
    ProjectsCard
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
