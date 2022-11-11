<template>
<div id="sectionone">
<div class="card">
<p>Hakkerikakkeri</p>
<img class="dc-logo" src="https://avatars.githubusercontent.com/u/88773115?v=4">
<p>17 years old programmer from finland<br> who likes to <span>code</span>!:)</p>
<a class="seeiton" href="https://github.com/Hakkerikakkeri">Github</a>
</div>
</div>
<p class="cut-text"></p>
<p class="header">My Skills</p>
<section id="sectionfour">
<div class="skills">
  <i id="skill-icon" class='bx bxl-html5'></i>
</div>
<div class="skills">
  <i id="skill-icon" class='bx bxl-css3' ></i>
</div>
<div class="skills">
  <i id="skill-icon" class='bx bxl-javascript' ></i>
</div>
<div class="skills">
  <i id="skill-icon" class='bx bxl-vuejs' ></i>
</div>
</section>
<p class="cut-text"></p>
<p class="header">My Services</p>
<section id="sectionthree">

<div class="servicebox">
  <i id="icon-back" class='bx bx-code-alt'></i>
  <p class="title">Web Developement</p>
  <p class="desc">I make good lookin sites:)</p>
</div>

<div class="servicebox">
  <i id="icon-back" class='bx bxs-paint' ></i>
  <p class="title">Brand Desing</p>
  <p class="desc">I can make thread desing:)</p>
</div>

<div class="servicebox">
  <i id="icon-back" class='bx bxs-palette' ></i>
  <p class="title">Web Desing</p>
  <p class="desc">I know how to desing:)</p>
</div>

</section>
<p class="cut-text"></p>
<footer class="bottom-footer">
    <div class="footer-about">
    <p>2022 | Hakkerikakkeri Portfolio</p>
    </div>
    <div class="footer-icons">
    <a><i id="icon" class='bx bxl-github'></i></a>
    </div>
</footer>
<button @click="goup()" id="topbutton"><i class='bx bx-chevron-up'></i></button>
</template>

<script>
// @ is an alias to /src
import { defineComponent } from "vue";
 
export default defineComponent({

methods: {

goup: function() {
  document.body.scrollTop = 0; 
  document.documentElement.scrollTop = 0; 
  }
}
});

</script>
