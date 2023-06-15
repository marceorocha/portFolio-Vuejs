<template>
<div class="main-container">
    <div class="project-card" v-for="(items, index) in projectData.ProjectsArray" v-bind:key="items">
    <h2>{{ projectData.ProjectsArray[index].Title }}</h2>
    <img :src="projectData.ProjectsArray[index].Image" alt="">
    <p>{{ projectData.ProjectsArray[index].About }}</p>
    <div class="links">
        <a href=""><img src="../assets/GitHub.png" alt="githubLogo" style="height: 1rm; size: 0.5rm;"></a>
        <a href=""><img src="../assets/flecha.jpeg" alt="flechita" style="height: 1rm;"></a>

    </div>
    </div>
</div>
  </template>
  
  <script>
    import jsonData from "/projects.json"
    export default {
        data() {
            return {
                projectData: jsonData,
                // mySource: '<PDF-URL>'   
                
            }
        }
    }
  </script>
  
  <style scoped>
    .project-card img {
        height: 5rem;
    }
    .main-container {
        display: flex;
        justify-content: center;
        align-items: center;
        
    }
    .project-card {
        margin: 10px;
        padding: 10px;
        flex-wrap: 0 0 40%;
        background-color: white;
        box-shadow: rgba(0, 0, 0, 24)0px 3px 9px;
    }
    .links{
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: flex-end;
    }
  </style>
  