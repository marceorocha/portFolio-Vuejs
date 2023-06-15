<template>
        <h1>Portfolio</h1>
    <div class="wrapper">
    <div class="main-container">
        <div class="container1">
            <div class="perfil">
                <img src="../assets/MiPhoto.jpg" alt="fotoMia" class="perfil">
                <h3>Marcelo Rocha</h3>
                <p>Software developer</p>
                <div class="social-links">
                    <a href="https://github.com/marceorocha?tab=repositories">
                        <div class="link">
                            <img src="../assets/GitHub.png" alt="logoGitHub" class="logo" >
                            <h2>GitHub</h2>
                        </div>
                    </a>
                    <a href="https://www.linkedin.com/in/marcelo-rocha-82993b26a/">
                        <div class="link" >
                            <img src="../assets/LinkedIn.png" alt="logoLinkedIn" class="logo">
                            <h2>LinkedIn</h2>
                        </div>
                    </a>
                    <a href="https://www.instagram.com/marceorocha/">
                        <div class="link" >
                            <img src="../assets/Instagram.png" alt="logoInstagram" class="logo">
                            <h2>Instagram</h2>
                        </div>
                    </a>
                </div>
            </div>
        </div>
    
    <div class="container2">
    <div class="skills">
        <h1>Tecnologies</h1>
        <div>
            <p>HTML, CSS, JavaScript, NodeJS, VUE</p>
            <p>GitHub</p>
            <p>UX UI concepts</p>
            <p>Agile - scrum</p>
            <p>Postman</p>
            <p>Kubernetes</p>
            <p>Docker</p>
            <p>React basics</p>
            <p>Firebase basics</p>
            <p>IBM web services basics</p>
        </div>
    </div>
    <div class="sobreMi">
        <div>
            <h1>About Me</h1>
            <p>I have worked for myself all the time along with my salary jobs, that allowed me now to do what i always wanted and what i love witch is software developing.</p>
            <p>I have a passion for technology, travelling and sports</p>
            <p></p>
        </div>
    </div>
    <div class="curriculum">
         <h1>My resume</h1>
         <p>Bachelor Degree in International Relationships</p>
            <p>Advanced english, fluent portuguese and native Spanish</p>
            <!-- <vue-pdf-embed :source="src/assets/myResume.pdf" /> -->
            <!-- <PDFViewer src="src/assets/myResume.pdf" >1</PDFViewer> -->
         
    </div>
</div>
</div>
</div>
  </template>
  
  <script>
//   import VuePdfEmbed from 'vue-pdf-embed'
// import { PDFViewer } from 'pdfjs-dist/es5/web/pdf_viewer';
  
  export default {
    components: {
        // VuePdfEmbed
        // PDFViewer
    }
  }
  </script>
  
  <style scoped>
    .logo {
        width: 50px;
        height: 50px;
    }
    .perfil{
        width: 10rem;
        height: 18rem;
        border-radius: 50%;
        /* display: flex; */
        justify-content: center;
        flex-direction: row;
        /* flex-wrap: 10% 20% 40% 20%; */
        padding-left: 1rem;
        


    }
    .container1{
        padding: 2%;
        background-color: #cdd5db;
        width: 30%;
        border-radius: 30px;

    }
    .main-container {
        margin-top: 5%;
        margin-bottom: 10%;
        display: flex;
        justify-content: center;
        flex-direction: row;
        background-color: #a5c9e7;
        border-radius: 30px;
        width: 80%;

    }
    .container2 {
        margin: 2%;
        width: 75%;
        border-radius: 30px;
    }
    .link a{
        text-decoration: none;
        color: #8b9bad;
        font-size: 10px;
        border-radius: 30px;

    }
    .link img {
        height: 3rem;
    }
    .sobreMi {
        flex-wrap: wrap;
    }
    .wrapper {
        display: flex;
        justify-content: center;
        flex-wrap: 0 0 40%;
        background-color: white;
        box-shadow: rgba(0, 0, 0, 24)0px 3px 9px;
    }
  </style>