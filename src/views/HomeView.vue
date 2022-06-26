<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
<div id="sectionone">
<div class="card">
<div class="logo-area">
<img class="dc-logo" src="@/assets/unknown.png">
</div>
<div class="dc-name">
    <p><i class='bx bxl-discord-alt' ></i> Abraxas#7040</p>
    <a class="github-link" href="https://github.com/Hakkerikakkeri"><i class='bx bx-link'></i> github.com/Hakkerikakkeri</a>
</div>
<p>Developer or something like that :)</p>
</div>
</div>
<p class="cut-text"></p>

<section id="sectiontwo">
<div class="project-area">
<div class="project-cards">
<img class="project-img" src="@/assets/project1.png">
<p class="project-info">Login-page ui</p>
<div class="button-area">
    <a target="_blank" class="seeiton" href="https://github.com/Hakkerikakkeri/Drinking-game-website">Github</a>
</div>
</div>



<div class="project-cards">
    <img class="project-img" src="@/assets/project2.png">
    <p class="project-info">Fivem base website</p>
    <div class="button-area">
        <a target="_blank" href="https://github.com/Hakkerikakkeri/Fivembased-Website" class="seeiton">Github</a>
</div>
</div>

<div class="project-cards">
    <img class="project-img" src="@/assets/project3.png">
    <p class="project-info">Drinking Game Website</p>
    <div class="button-area">
        <a target="_blank" href="https://github.com/Hakkerikakkeri/Fivembased-Website" class="seeiton">Github</a>
</div>
</div>

</div>
</section>
<p class="cut-text"></p>
<footer class="bottom-footer">
    <div class="footer-about">
    <p>Abraxas Homepage</p>
    </div>
    <div class="footer-icons">
    <a><i id="icon" class='bx bxl-github'></i></a>
    <a><span><i id="icon" class='bx bxl-discord' ></i></span></a>
    </div>
</footer>
<button onclick="topbutton()" id="top-button"><i class='bx bx-chevron-up'></i></button>
</template>

<style>
:root{
    --main: #121212;
    --secondary: #1d1d1d;
    --accent: #7b1dff;
    --font: 'DM Sans', sans-serif;
    --color: white;
}

body{
    background-color: var(--main);
    padding: 0;
    margin: 0;
}

.bx {
    font-size: 22px;
}

#sectionone{
    width: 100%;
    height: 100%;
    color: var(--color);
    font-family: 'DM Sans', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
}

.cut-text{
    text-align: center;
    border-bottom: 2px dashed grey;
    font-size: 18px;
    color: var(--color);
    font-family: var(--font);
}

#sectiontwo{
    width: 100%;
    height: 100%;
    color: var(--color);
    font-family: 'DM Sans', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
}

.card{
    display: inline;
    background-color: var(--secondary);
    padding: 18px 18px;
    border-radius: 4px;
}

.logo-area{
    display: flex;
    align-items: center;
    justify-content: center;
}

.dc-logo{
    width: 85px;
    height: 85px;
    border-radius: 50%;
    border: 2px solid grey;
}

.dc-name{
    text-align: center;
}

.github-link{
    color: var(--color);
}

.project-area{
    display: inline-flex;
}

.project-cards{
    margin: 8px;
    background-color: var(--secondary);
    padding: 18px 18px;
    border-radius: 4px;
}

.project-img{
    width: 325px;
    height: 175px;
    border-radius: 4px;
}

.project-info{
    text-align: center;
}

.button-area{
    display: flex;
    align-items: center;
    justify-content: center;
}

.seeiton{
    text-decoration: none;
    cursor: pointer;
    outline: 0;
    border: 0;
    border-radius: 4px;
    background-color: var(--accent);
    font-family: var(--font);
    font-size: 15px;
    color: var(--color);
    padding: 12px 32px;
}

.github-buttonarea{
    display: flex;
    align-items: center;
    justify-content: center;
}

.bottom-footer{
    width: 100%;
    height: 22%;
    font-family: var(--font);
    color: var(--color);
}

.footer-about{
    display: flex;
    justify-content: center;
}

#icon{
    font-size: 34px;
    cursor: pointer;
}

span{
    color: white;
    cursor: pointer;
}

span:hover{
    color: #7289da;
    transition: 250ms;
}



.footer-icons{
   display: flex;
   justify-content: center; 
}

#top-button {
    animation: fadeInUp 0.8s ease-in-out;
    display: none; 
    position: fixed; 
    bottom: 20px; 
    right: 30px;
    z-index: 99; 
    border: none;
    outline: none; 
    background-color: var(--secondary); 
    color: var(--color); 
    cursor: pointer; 
    padding: 15px;
    border-radius: 4px; 
    font-size: 18px;
}
  
#top-button:hover {
    background-color: var(--accent);
}

@media screen and (max-width: 600px) {
    .project-area{
        display: inline;
    }
    .project-cards{
        padding: 10px 10px;
    }
    .project-img{
        width: 275px;
        height: 155px;
    }
}
</style>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}


</script>
