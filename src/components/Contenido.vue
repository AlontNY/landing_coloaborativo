<template>
 <div class="contenedor">
     
     <main>
        <ul class="dominios p-0">
            <li><span class="punto">.</span><span class="dominio">com</span><span class="anio">$8.99/yr</span></li>
            <li><span class="punto">.</span><span class="dominio">net</span><span class="anio">$8.99/yr</span></li>
            <li><span class="punto">.</span><span class="dominio">org</span><span class="anio">$8.99/yr</span></li>
            <li><span class="punto">.</span><span class="dominio">gov</span><span class="anio">$8.99/yr</span></li>
        </ul>
     </main>

     <section>
          <code v-if="datos">

            <code v-for="(dato,index_) in datos.forms" :key="index_">
                {{dato.name}}
            </code>
            
            <hr>

            <code v-for="(indice,ind) in datos.game_indices" :key="ind">
            {{indice.version.name}}
            </code>
            
            <hr>
       
            <!-- {{datos.abilities}} -->
            <code v-for="(date,i) in datos.abilities" :key="i">
                <p>{{date.ability.name}}</p>
            </code>
            
        </code>
        
        <!-- <button class="btn btn-primary" @click="activador">activar</button> -->
     </section>
    
    <section id="servicios">
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
     <div class="container">
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
    </div>
        
    <div class="contenedor features-3">
        <div class="container">
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
      </div>
         </section>  

    <section class="pricing" id="pricing">
        
        <div class="contenedor">
            <h2>PRICING</h2>
            <h3>Web Hosting Plans & Pricing</h3>
        </div>
    <div class="contenedor-precios">
        <div class="tabla" id="one">
            <ul>
                <li>Shared Hosting</li>
                <li><span class="dolar">$</span><span class="numero">3.99</span><span class="mes">/month</span></li>
                <hr>
                <li class="item"><span>25000 visits per month</span></li>
                <li class="item"><span>1 Site</span></li>
                <li class="item"><span>50GB Storage</span></li>
                <li class="item"><span>256 GB Bandwidth/mo</span></li>
                <li class="gris"><span>24/7 Support</span></li>
                <li class="gris"><span>Unlimited Email Addresses</span></li>
            </ul>
            <a href="">GET STARTED</a>
        </div>
        <div class="tabla" id="two">
            <ul>
                <li>Shared Hosting</li>
                <li><span class="dolar">$</span><span class="numero">3.99</span><span class="mes">/month</span></li>
                <hr>
                <li class="item"><span>25000 visits per month</span></li>
                <li class="item"><span>1 Site</span></li>
                <li class="item"><span>50GB Storage</span></li>
                <li class="item"><span>256 GB Bandwidth/mo</span></li>
                <li class="item"><span>24/7 Support</span></li>
                <li class="gris"><span>Unlimited Email Addresses</span></li>
            </ul>
            <a href="">GET STARTED</a>
        </div>
        <div class="tabla" id="three">
            <ul>
                <li>Shared Hosting</li>
                <li><span class="dolar">$</span><span class="numero">3.99</span><span class="mes">/month</span></li>
                <hr>
                <li class="item"><span>25000 visits per month</span></li>
                <li class="item"><span>1 Site</span></li>
                <li class="item"><span>50GB Storage</span></li>
                <li class="item"><span>256 GB Bandwidth/mo</span></li>
                <li class="item"><span>24/7 Support</span></li>
                <li class="item"><span>Unlimited Email Addresses</span></li>
            </ul>
            <a href="">GET STARTED</a>
        </div>
    </div>
    </section>

    <section class="file" id="file">
        <div class="container">
         <div class="contenedor">
            
                <div class="titular">
                    <h2>FILE MANAGEMENT</h2>
                    <h3>Safe and Secure Web Hosting & Backups</h3>
                    <div class="iconos">

                        <div class="item">
                            <div class="icono">
                                <img src="~@/assets/imagenes/filemanagement.png" alt="">
                            </div>
                            <div class="texto">
                                <h4>Mauris dignissim vive</h4>
                                <p>Donec sollicitudin molestie malesuada. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Vivamus magna</p>
                            </div>
                        </div>

                        <div class="item">
                            <div class="icono">
                                <img src="~@/assets/imagenes/filemanagement.png" alt="">
                            </div>
                            <div class="texto">
                                <h4>Mauris dignissim vive</h4>
                                <p>Donec sollicitudin molestie malesuada. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Vivamus magna</p>
                            </div>
                        </div>

                        <div class="item">
                            <div class="icono">
                                <img src="~@/assets/imagenes/filemanagement.png" alt="">
                            </div>
                            <div class="texto">
                                <h4>Mauris dignissim vive</h4>
                                <p>Donec sollicitudin molestie malesuada. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Vivamus magna</p>
                            </div>
                        </div>

                    </div>
                </div>
                <div class="imagen">
                    <img src="~@/assets/imagenes/file-grande.png">
                    <a class="boton" href="">LEARN MORE</a>
                </div>
            </div>
         </div> 
    </section>

    <section class="expert">
        <div class="contenedor">
            <h2>Talk With an Expert to Get Started Today!</h2>
            <p>Quisque velit nisi, pretium ut lacinia in, elementum id enim. Cras ultricies ligula sed magna dictum porta. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Cras ultricies ligula sed magna dictum porta.</p>
            <a href="">LIVE CHAT</a>
        </div>
    </section>
    
    <section class="easy">
        <div class="contenedor">
            <div class="imagen">
                <img src="~@/assets/imagenes/easy.png" alt="">
            </div>
            <div class="titular">
                <h2>EASY SETUP</h2>
                <h3>One Click Installs</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla pulvinar libero eget enim imperdiet, et finibus tortor tristique. Lorem ipsum dolor sit amet, consectetur adipiscing elit</p>
                <div class="lista">
                    <ul>
                        <li><i class="fas fa-check"></i><p>Mauris dignissim viverra mauris non laoreet.</p></li>
                        <li><i class="fas fa-check"></i><p>Mauris dignissim viverra mauris non laoreet.</p></li>
                        <li><i class="fas fa-check"></i><p>Mauris dignissim viverra mauris non laoreet.</p></li>
                        <li><i class="fas fa-check"></i><p>Mauris dignissim viverra mauris non laoreet.</p></li>
                    </ul>
                </div>
                <a href="">ALL SERVICES</a>
            </div>
        </div>
    </section>

    <section class="testimonios" id="testimonios" >
        <div class="contenedor">
            <div class="titular">
                <h2>WHAT THEY’RE SAYING</h2>
                <h3>Customer Testimonials</h3>
            </div>
           <div class="testimonio">
               <div class="apartado">
                    <img src="~@/assets/imagenes/testimonial.png" alt="">
                    <p>Your content goes here. Edit or remove this text inline or in the module Content settings. You can also style every aspect of this content in the module Design settings and even apply custom CSS to this text in the module Advanced settings.</p>
                    <p class="nombre_tes">Jane Smith</p>
                    <p class="uno">Dev Lead, Divi Corner</p>
                </div>
                <div class="apartado">
                    <img src="~@/assets/imagenes/testimonial.png" alt="">
                    <p>Your content goes here. Edit or remove this text inline or in the module Content settings. You can also style every aspect of this content in the module Design settings and even apply custom CSS to this text in the module Advanced settings.</p>
                    <p class="nombre_tes">Jane Smith</p>
                    <p class="uno">Dev Lead, Divi Corner</p>
                </div>
                <div class="apartado">
                    <img src="~@/assets/imagenes/testimonial.png" alt="">
                    <p>Your content goes here. Edit or remove this text inline or in the module Content settings. You can also style every aspect of this content in the module Design settings and even apply custom CSS to this text in the module Advanced settings.</p>
                    <p class="nombre_tes">Jane Smith</p>
                    <p class="uno">Dev Lead, Divi Corner</p>
                </div>
           </div>
        </div>
    </section>

    <section class="satisfaction">
        <div class="contenedor">
            <div class="titular">
                <h3>Satisfaction Guaranteed</h3>
            </div>
            <div class="tarjetas">
                <div class="tarjeta">
                    <h4>24/7 Award Winning Support</h4>
                    <p>Donec rutrum congue leo eget malesuada. Nulla porttitor accumsan tincidunt. Nulla quis lorem ut libero malesuada feugiat. Donec sollicitudin molestie malesuada.</p>
                    <a href="">CONTACT US</a>
                </div>
                <div class="tarjeta" id="tarjeta_2">
                    <h4>24/7 Award Winning Support</h4>
                    <p>Donec rutrum congue leo eget malesuada. Nulla porttitor accumsan tincidunt. Nulla quis lorem ut libero malesuada feugiat. Donec sollicitudin molestie malesuada.</p>
                    <a href="">CONTACT US</a>
            </div>
            </div>
        </div>
    </section>

    <section class="treinta">
        <h2>30 Days of Free Hosting</h2>
        <p>Donec sollicitudin molestie malesuada. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia</p>
        <a href="">LEARN HOW</a>
    </section>
    </div>
</template>

<script>

export default({
   data: () => {
        return{
            datos: null
        }
    },
    methods:{
        activador: async function(){
            await axios.get("https://pokeapi.co/api/v2/pokemon/ditto").then(result =>{
                this.datos = result.data;
            })        
        }

    },
    created(){
        this.activador();
    }
})
</script>



<style scoped>
/*.contenedor{
    max-width: 1100px;
    margin: auto;
}*/
 /*responsivo*/
 @media screen and (max-width: 900px){
        main .dominios {
            text-align: center;
            max-width: 490px;
            margin: auto;
            flex-direction: column; 
            
        }
        main .dominios li {
            margin:0px 9px;  
            
        }
        /* .dominios li span.dominio{
            font-size:29px;
        }
        .dominios li span.anio{
            font-size: 6px; */
        /* } */
        #servicios .contenedor{
        flex-direction: column;
        }
        #servicios .contenedor .titular{
        width: 100%;
        padding: 0px 10px;
        }
        #servicios .contenedor .titular h3{ font-size:1.5rem; }

        .contenedor #servicios #uno{
        margin-left: 20px;
        }
        .contenedor #servicios #dos{
            top:0px;
        }
        .contenedor #servicios h3 , .contenedor .pricing h3 , .contenedor .file h3, .contenedor .easy h3, .contenedor .testimonios h3{
            font-size: 36px;
        }
        .contenedor #servicios .servicios , .contenedor .testimonios .apartado, .contenedor .satisfaction .tarjeta {
            width:91%;
        }
        .contenedor .file .contenedor, .contenedor .easy .contenedor ,.contenedor .testimonios .testimonio ,.contenedor .satisfaction .tarjetas{
        flex-direction: column;
        }
        .contenedor .satisfaction .tarjeta {
            margin: 24px;
        }
        .contenedor-precios{
            flex-direction: column;
        }
        .contenedor .file .imagen , .contenedor .easy .imagen{
            width: 100%;
            padding-bottom: 20%;
        }
        .contenedor .easy .titular{
        padding-top: 20%;
        }
        .contenedor .expert{
            padding: 56px 0;
            background-position: 42% 50%;
        }
        .contenedor .file h3 {
            width: 100%;
        }
        #features .container .contenedor {
        flex-direction: column;
        }
        .contenedor #features .imagen{
        width: 100%;
        }
        #features .container .contenedor .titular{
        width: 100%;
        margin-right: 0;
        }
        .pricing .contenedor-precios .tabla{
            padding: 19px 145px;
                margin: 20px;
        }
        .container  .features-1 .features-2{
        flex-direction: column;
        }
        .container .feature{
            width: 100%;
        }
        .easy .contenedor .titular{
            width: 74%;
        }

        .expert .contenedor h2{ width: 100%; font-size: 45px; padding-top:2.5rem}
        /* .expert .contenedor p, .treinta p { width: 90%; padding-bottom: 3rem; } */
 }
 /**********/
 .dominios{
     display:flex;
     margin-left: 355px;
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
     padding-top: 5rem;
 }
 #servicios .contenedor{
     display:flex;
     justify-content: center;
     max-width: 1550px;
     margin: auto;
 }
 #servicios .titular{
     font-family:'Poppins';
     width: 49%;
 }
 #servicios .servicios , .testimonios .apartado, .satisfaction .tarjeta{
     margin-top: 30px;
     margin-left: 20px;
     width:25%;
     background-color:#fff;
     box-shadow: 0px 90px 160px  0px rgba(0,0,0,0.1);
     border-radius:24px;
     padding: 20px 30px;
 }
 #servicios h2 , .pricing h2,  .file h2 , .easy h2, .testimonios h2 {
     font-family: 'Rubik';
     font-weight: 500;
     font-size: 14px;
     color: #ff8f00;
     letter-spacing: 1px;
     text-transform: uppercase;
 }
 #servicios h3 , .pricing h3 , .file h3, .easy h3, .testimonios h3{
     font-weight: 500px;
     font-size: 38px;
 }
 #servicios .boton , .file .boton, .expert a, .easy a , .satisfaction a {
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
#features h3 , .satisfaction .titular h3{
    font-weight: bold;
    font-size: 38px;
    margin:0;
}
#features p {
 color:#666;
 line-height: 30px;
}
#features .contenedor:nth-child(1){
    display: flex;
    justify-content: center;
    /* max-width: 1100px; */
    padding-bottom: 40px;
    border-bottom:1px solid #cccccc40;
}
#features .titular  {
    width:40%;
    margin-right: 77px;
}
#features .imagen{
    width: 49%;
}
#features .imagen img{
    width: 100%;
}
.features-3{
    display:flex;
    flex-direction: column;
    padding-top:40px ;
    
}
.features-1, .features-2{
    display:flex;
    flex-wrap:wrap;
}
.feature{
    width: 30%;
    margin: auto;
}
.feature ul{
    display: flex;
    padding: 0;
}
.feature li{
    list-style: none;
}
.feature li:nth-child(2){
    margin-left: 20px;
    color:#666;
    font-size:14px;
}
/*precios*/
.pricing{
    padding-top: 90px;
}
.pricing h2, .pricing h3, .testimonios h2 , .testimonios h3, .satisfaction .titular h3{
    text-align: center;
}
.pricing h3{
    font-weight: bold;
}
.contenedor-precios{
    display: flex;
    justify-content: space-around;
    max-width: 1100px;
    margin: auto;
}
.pricing .tabla{
    background: #fff;
    border-radius: 24px;
    box-shadow: 0px 90px 160px 0px rgb(0,0,0,0.1);
    padding: 20px 59px;
}
.pricing ul{
    padding: 0;
}
.pricing .tabla li:nth-child(1) {
    font-family: 'Rubik';
    list-style: none;
    margin-bottom: 20px;
    font-size: 18px;
    font-weight: bold;
    margin-left: -21px;
}
.pricing  #one li:nth-child(1) {
    color: #ff8f00;  
}
.pricing  #two li:nth-child(1) {
 color: #2970fa;
}
.pricing  #three li:nth-child(1) {
 color: #2ACF8D;
}
.pricing .tabla .dolar{
    position: absolute;
    color:#999;
    font-size: 18px;
}

.pricing .contenedor-precios .tabla{
  padding: 19px 4rem;
}
.pricing .tabla .numero{
    font-family: 'Rubik';
    font-weight: bold;
    font-size: 3rem;
    margin-left: 14px;
}
.pricing .mes{
    color: #999;
}
.pricing .tabla li:nth-child(2){
    list-style: none;
    margin-bottom: 48px;
    margin-left: -19px;
}

.pricing #one .item  {
    color:#ff8f00;
    margin-bottom: 27px;
}

.pricing #two .item  {
    color:#2970fa;
    margin-bottom: 27px;
}
.pricing #three .item  {
    color:#2ACF8D;
    margin-bottom: 27px;
}
.pricing #one .gris , .pricing #two .gris{
   color: #ccc;
   margin-bottom: 27px;
}
/*.pricing #two .item {
 color:#296FFA;
}*/
.pricing .item span{
    color:#666;
}
.pricing .tabla a {
    text-decoration: none;
    padding: 15px 30px;
    border-radius: 5px;
    font-size: 14px;
    box-shadow: 0px 20px 30px 0px rgb(0 0 0 / 20%);
    margin-top: 20px;
    display: inline-block;
     }
.pricing #one a {
    color: #ff8f00;
    background: rgba(255,143,0,0.1);
}
.pricing #two a {
    color:#fff ;
    background: #296FFA;
}
.pricing #three a {
    color: #29cf8d;
    background: rgba(41,207,141,0.1);
}
.pricing .tabla{
    position: relative;
}
.pricing hr{
    position: absolute;
    top: 145px;
    left: 0;
    width: 100%;
    border-color: #2423232e;
}

    /* file*/
.file{
    padding-top: 90px;
}
.file .contenedor, .easy .contenedor , .testimonios .testimonio ,.satisfaction .tarjetas {
display: flex;
justify-content: center;

}
.file .iconos .icono {
    margin-right: 15px;
}
.file .iconos h4 ,.file .iconos p {
    margin:0;
}
.file .iconos h4 {
    font-weight: bold;
}
.file .iconos p {
    margin-top: 10px;
    color:#666;
    font-size: 14px;
    margin-bottom: 30px;
    line-height: 30px;
    font-family: "poppins";
}
.file .item{
    display: flex;
}
.file .titular {
    margin-right: 60px;
    text-align: none;
}
/* el contenedor se le da un tamaño de 40 y la iamgen lo ocupara completo */
.file .imagen , .easy .imagen{
    width: 40%;
}
.file .imagen  img , .easy .imagen img {
 width: 100%;
}
.file .imagen .boton {
    padding: 15px 40px;
    font-family: 'Rubik';
}
.file h3 {
    font-size: 34px;
    width: 68%;
    margin: 0;
    margin-top: 15px;
    font-weight: bold;
    font-family:"poppins";
}
.file h2{
    margin: 0;
}
.file .iconos{
    margin-top: 30px;
}
/*expert */
.expert{
    padding: 196px 0;
    width: 100%;
    background-image: url(~@/assets/imagenes/expert4.png), linear-gradient(150deg,#ffba61 0%, #ffe970 100%);
    background-size: 1521px 975px;
    background-position: 50% 50%;
    text-align: center;
}
.expert h2 , .treinta h2{
    font-family: 'Rubik';
    font-size: 52px;
    color:#fff;
    text-shadow: 1px 2px 13px #61605d;
    width: 50%;
    margin: auto;
}

.expert p , .treinta p{
    width: 50%;
    margin:auto;
    color: #fff;
    margin-top: 30px;
}
.expert a{
    padding: 15px 50px;
    letter-spacing: 1px;
}

/*easy*/
.easy{
    padding-top: 90px;
    padding-bottom: 90px;
}
.easy .titular{
    width:40%;
    margin: auto;
    font-family: 'Poppins';
}
.easy .titular h3{
    font-weight: bold;
    margin: 0;
}
.easy .lista li {
 display: flex;
}
.easy .titular ul{
    padding: 0;
    margin-bottom: 37px;
    margin-top: 30px;
}
.easy p{
    color: #666;
    line-height: 30px;

}
.easy .lista p {
    margin-left: 20px;
    font-weight: bold;
}
.easy i {
    background: #FF8F00;
    color: #fff;
    border-radius: 50%;
    width: 25px;
    height: 25px;
    text-align: center;
    line-height: 25px;
}
.easy .contenedor{
    width: 90%;
    max-width: 1280px;
    margin: auto;
}
/* testimonios*/
.testimonios .apartado{
    background-image: url(~@/assets/imagenes/testimonial-back.png);
    background-repeat:no-repeat;
    background-position: bottom;
    background-position-x: right;
}
.testimonios, .satisfaction{
    padding-bottom: 90px;
}
/*satifaction*/
.satisfaction .tarjeta{
    margin-left: 55px;
}
.satisfaction .tarjeta {
    background-image:url(~@/assets/imagenes/tarjeta1.png), linear-gradient(
    237deg, #46b3ff 0%, #0752fe 100%);
       background-position: bottom left;
    background-size: cover;
    border-radius: 24px;
    width: 40%;
    padding:  27px 40px 26px 33px;
}
.satisfaction #tarjeta_2 {
    background-image:url(~@/assets/imagenes/tarjeta2.png), linear-gradient(
    150deg, #ffba61 0%, #ffdc71 100%);
}
.satisfaction h3{
    font-weight: bold;
    font-size: 38px;
   }
.satisfaction p{
    color: #fff;
    line-height: 34px;
    margin: 0;
}
.satisfaction a , .treinta a{
    background: #253547;
    color: #fff;
    text-decoration: none;
    padding: 15px 30px;
    border-radius: 5px;
    font-size: 14px;
    box-shadow: 0px 20px 30 px 0 px rgba(0,0,0,0.2);
    margin-top: 20px;
    display: inline-block;
}
/*treinta*/
.treinta{
    background-image: url(~@/assets/imagenes/30.png), linear-gradient(
    237deg, #46b3ff 0%, #0752fe 100%);
    background-size: contain;
    background-position: top center;
    background-repeat: no-repeat;
    padding: 310px 0 155px 0;
    text-align: center;
}
.treinta{
    margin-top: 30px;
    line-height: 30px;
}
.treinta a{
    padding: 15px 50px;
    letter-spacing: 1px;
}
</style>