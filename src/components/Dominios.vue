<template>
 <div class="contenedor">
     <ul class="dominios">
         <li><span class="punto">.</span><span class="dominio">com</span><span class="anio">$8.99/yr</span></li>
         <li><span class="punto">.</span><span class="dominio">net</span><span class="anio">$8.99/yr</span></li>
         <li><span class="punto">.</span><span class="dominio">org</span><span class="anio">$8.99/yr</span></li>
        <li><span class="punto">.</span><span class="dominio">gov</span><span class="anio">$8.99/yr</span></li>
     </ul>
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
     font-size: 24px;
 }
 span.dominios {
     color:#000;
     font-size:50px;
     font-weight: bold;
 }
 span.anio {
     color:#999;
     font-size: 14px;
 }
</style>