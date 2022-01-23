<template>
 <div class="contenedor">
     <main>
        <ul class="dominios">
            <li><span class="punto">.</span><span class="dominio">com</span><span class="anio">$8.99/yr</span></li>
            <li><span class="punto">.</span><span class="dominio">net</span><span class="anio">$8.99/yr</span></li>
            <li><span class="punto">.</span><span class="dominio">org</span><span class="anio">$8.99/yr</span></li>
            <li><span class="punto">.</span><span class="dominio">gov</span><span class="anio">$8.99/yr</span></li>
        </ul>
     </main>
    <section id="servicios">
     <div class="contenedor">
         <div class="titular">
             <h2>our services</h2>
             <h3>Donec sollicitudin molestie malesuada. Lorem ipsum dolor sit amet, consect adipiscing amet sit dolor</h3>
         </div>
         <div class="servicios">
             <img src="~@/assets/imagenes/safe.png" alt="">
             <h4>Safe & Secure</h4>
             <p>Your content goes here. Edit or remove this text inline or in the module Content settings. You can also style every aspect of this content in the module Design settings and even apply custom CSS to this text in the module Advanced settings.</p>
             <a href="">CLICK HERE ➤</a>
         </div>
     </div>
    </section>
 </div>    
</template>

<style scoped>
 .dominios{
     display:flex;
 }
 .dominios li{
     list-style: none;
     margin:0px 20px;
 }
 span.punto {
     color:#1776FF;
     font-size: 55px;
 }
 span.dominio {
     color:#000;
     font-size:40px;
     font-weight: bold;
 }
 span.anio {
     color:#999;
     font-size: 14px;
 }
</style>