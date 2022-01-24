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
        <div class="container">
            <div class="contenedor">
            <div class="titular">
                <h2>our services</h2>
                <h3>Donec sollicitudin molestie malesuada. Lorem ipsum dolor sit amet, consect adipiscing amet sit dolor</h3>
                <a href="" class="boton">ALL SERVICES</a>
            </div>
            <div class="servicios" id="uno">
                <img src="~@/assets/imagenes/safe.png" alt="">
                <h4>Safe & Secure</h4>
                <p>Your content goes here. Edit or remove this text inline or in the module Content settings. You can also style every aspect of this content in the module Design settings and even apply custom CSS to this text in the module Advanced settings.</p>
                <a href="">CLICK HERE ➤</a>
            </div>
         </div>
        </div>
        
     <div class="contenedor servicios_2">
         <div class="servicios">
             <img src="~@/assets/imagenes/safe.png" alt="">
             <h4>Safe & Secure</h4>
             <p>Your content goes here. Edit or remove this text inline or in the module Content settings. You can also style every aspect of this content in the module Design settings and even apply custom CSS to this text in the module Advanced settings.</p>
             <a href="">CLICK HERE ➤</a>
         </div>
         <div class="servicios" id="dos">
             <img src="~@/assets/imagenes/safe.png" alt="">
             <h4>Safe & Secure</h4>
             <p>Your content goes here. Edit or remove this text inline or in the module Content settings. You can also style every aspect of this content in the module Design settings and even apply custom CSS to this text in the module Advanced settings.</p>
             <a href="">CLICK HERE ➤</a>
         </div>
         <div class="servicios">
             <img src="~@/assets/imagenes/safe.png" alt="">
             <h4>Safe & Secure</h4>
             <p>Your content goes here. Edit or remove this text inline or in the module Content settings. You can also style every aspect of this content in the module Design settings and even apply custom CSS to this text in the module Advanced settings.</p>
             <a href="">CLICK HERE ➤</a>
         </div>
     </div>
    </section>

    <section id="features">
     <div class="contenedor">
         <div class="titular">
             <h2>OUR FEATURES</h2>
             <h3>Enjoy Preconfigured Setups or Full Control</h3>
             <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla pulvinar libero eget enim imperdiet, et finibus tortor tristique. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris dignissim viverra mauris non laoreet.</p>
         </div>
         <div class="imagen">
             <img src="~@/assets/imagenes/features-grande.png" alt="">
         </div>
     </div>
         <hr>
    <div class="contenedor features-2">
            <div class="features-1">
                <div class="feature">
                    <ul>
                        <li> <img src="~@/assets/imagenes/features-chica.png" alt=""> </li>
                        <li> <p>Mauris dignissim viverra mauris non laoreet. Curabitur ac consectetur</p></li>
                    </ul>
                </div> 
                 <div class="feature">
                    <ul>
                        <li> <img src="~@/assets/imagenes/features-chica.png" alt=""> </li>
                        <li> <p>Mauris dignissim viverra mauris non laoreet. Curabitur ac consectetur</p></li>
                    </ul>
                </div> 
                 <div class="feature">
                    <ul>
                        <li> <img src="~@/assets/imagenes/features-chica.png" alt=""> </li>
                        <li> <p>Mauris dignissim viverra mauris non laoreet. Curabitur ac consectetur</p></li>
                    </ul>
                </div>   
            </div>

            <div class="features-2">
                <div class="feature">
                    <ul>
                        <li> <img src="~@/assets/imagenes/features-chica.png" alt=""> </li>
                        <li><p>Mauris dignissim viverra mauris non laoreet. Curabitur ac consectetur</p></li>
                    </ul>
                </div> 
                 <div class="feature">
                    <ul>
                        <li> <img src="~@/assets/imagenes/features-chica.png" alt=""> </li>
                        <li><p>Mauris dignissim viverra mauris non laoreet. Curabitur ac consectetur</p></li>
                    </ul>
                </div> 
                 <div class="feature">
                    <ul>
                        <li> <img src="~@/assets/imagenes/features-chica.png" alt=""> </li>
                        <li><p>Mauris dignissim viverra mauris non laoreet. Curabitur ac consectetur</p></li>
                    </ul>
                </div>   
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
 /*servicios*/
 #servicios{
     padding-top: 120px;
 }
 #servicios .contenedor{
     display:flex;
     justify-content: space-around;
 }
 #servicios .titular{
     width: 49%;
 }
 #servicios .servicios{
     width:25%;
     background-color:#fff;
     box-shadow: 0px 90px 160px  0px rgba(0,0,0,0.1);
     border-radius:24px;
     padding: 20px 30px;
 }
 #servicios h2{
     font-family: 'Rubik';
     font-weight: 500;
     font-size: 14px;
     color: #ff8f00;
     letter-spacing: 1px;
 }
 #servicios h3{
     font-weight: 500px;
     font-size: 30px;
 }
 #servicios .boton{
     background: #2970fa;
     padding: 15px 38px;
     letter-spacing: 1px;
     color:white;
     text-decoration: none;
     border-radius: 5px;
     margin-top: 20px;
     display: inline-block;
 }
 .servicios h4 {
     font-size: 23px;
     font-weight: normal;
     font-family: 'Rubik';
 }
 .servicios p {
     color: #787878;
     font-size: 15px;
     line-height: 32px;
 }
 .servicios a {
     color: #2970fa;
     text-decoration: none;
     font-family: 'Rubik';
     letter-spacing: 1px;
     font-size: 13px;
 }
 
 .servicios_2{
     margin-top: 60px;
 }
 .servicios_2 #dos{
     position: relative;
     top:-250px;
 }
 #servicios #uno {
     margin-left: 111px;
 }
/*features*/
#features{
    padding-top: 90px;
    
}
#features h2{
    font-family:'Rubik';
    font-weight: 500;
    text-transform: uppercase;
    font-size:14px;
    color:#ff8f00;
    letter-spacing: 1px;
}
#features h3{
    font-weight: bold;
    font-size: 38px;
    margin:0;
}
#features p {
 color:#666;
 line-height: 30px;
}
#features .contenedor{
    display: flex;
    justify-content: center;
    max-width: 1100px;
}
#features .titular {
    width:40%;
}
</style>