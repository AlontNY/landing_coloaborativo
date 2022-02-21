<template>
    <div class="m-0 p-0">
        <div class=" text-light">
        <header style="padding-top:6.1rem">
            <div class="menu ">
                <div class="contenedor">
                <p class="logo p-0 m-0">Hosting Company</p>
                <!-- BARRA DE NAVEGACION PARA MOBIL -->
                <nav id="nav" class="viewPc">
                    <ul class="lista mb-0 pl-0">
                        <li><a @click="home()" href="#home"> Home </a></li>
                        <li><a  href="#servicios">Services</a></li>
                        <li><a  href="#features">Features</a></li>
                        <li><a  href="#pricing">Princing</a></li>
                        <li><a  href="#file">File Managment</a></li>
                        <li><a  href="#testimonios">Testimonials</a></li>
                    </ul>
                </nav>

                <img src="~@/assets/imagenes/menu.png"   @click="mostrar()" class="menu-icon" alt=""> 
                    <nav v-if="ver" id="nav" class="viewMobil"> <!-- -->
                        <ul class="lista mb-0">
                            <li><a @click="home(), ver=false" href="#menu">Home</a></li>
                            <li><a @click="ver=false" href="#servicios">Services</a></li>
                            <li><a @click="ver=false" href="#features">Features</a></li>
                            <li><a @click="ver=false" href="#pricing">Princing</a></li>
                            <li><a @click="ver=false" href="#file">File Managment</a></li>
                            <li><a @click="ver=false" href="#testimonios">Testimonials</a></li>
                        </ul>
                    </nav>
                
                </div>
            </div>
            
            <div class="contenedor">
                <div class="contenedor-inicio">
                    <div class="titular">
                        <h1>Premium Hosting Services</h1>
                        <p>Donec sollicitudin molestie malesuada. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae donec velit neque</p>
                        <a href="" class="boton">GET WEB HOSTING</a>
                    </div>
                    <div class="imagen">
                        <img src="~@/assets/imagenes/header.png" class="img2" alt="">
                    </div>
                </div>
            </div>
        </header>
        </div>
    </div>
    
</template>

<script>
export default {
    data:function() {
        return {
            ver:false
        }
    },
    methods:{
        home(){ return window.scrollTo(0, 0); },
        mostrar(){
            this.ver = !this.ver;
            console.log(this.ver);
        }
    }
}
</script>



<style scoped>

.contenedor{
    width: 90%;
    max-width: 1280px;
    margin: auto;
}
header{
    background-image: url(~@/assets/imagenes/ondas.png),linear-gradient(273deg, #46b3ff 0%, #0752fe 100%);
    background-repeat: no-repeat;
    background-position: bottom center;
    height: 890px;
}
.menu{
    background: white;
    padding: .5rem 20px;
    position: fixed;
    width: 100%;
    top: 0;
    box-shadow: 1px 1px 8px #ccc;
    z-index: 1;
}
.menu .contenedor{
    display: flex;
    justify-content: space-around;
    align-items: center;
}
.menu-icon{
    display: none;
}
header .logo{
    font-size: 23px;
    font-weight: bold;
    color: black;
    
}


nav ul li{
    display: inline-block;
    margin: 0 20px;
    
} 
nav ul li a{
    text-decoration: none;
    color: black;
    font-family: 'Poppins', sans-serif;
}
header .contenedor-inicio {
 display: flex;
 justify-content: space-between;
 margin: 7vh 0;
}

header .titular, header .imagen {
    width: 40%;
}

header h1{
    font-family: 'rubik';
    font-size: 52px;
    color: #fff;
    text-shadow: 1px 2px 50px #000;
}
header p{
    color:#fff;
    line-height: 30px;
}
header .imagen .img2 {
    width: 100%;
}
.boton{
    background: #253547;
    color: #fff;
    text-decoration: none;
    padding: 15px 30px;
    border-radius: 5px;
    font-size: 14px;
    box-shadow: 0px 20px 30px 0px rgba(0,0,0,0.2);
    margin-top: 20px;
    display: inline-block;
}

.viewMobil{ display: none; }
.viewPc{ display: block;  }

/*responsive*/
@media screen and (max-width: 900px){
    .viewMobil{ display: block; }
    .viewPc{ display: none;  }

    nav{
        position:absolute;
        top:100%;
        left:0;
        background: #232220;
        width:100%;
       /* display: none;  */
    }
      nav .lista {
        flex-direction:column;
        display: flex;
        margin:0;
        padding: 0;
    }
    /* nav ul li {
        display:block ;
        margin:23px 20px;
    } */
    nav ul li { padding: 1rem; }
    nav ul li a {
        color:#fff;
    }
    .menu-icon{
        display: block;
        position: absolute;
        right: 31px;
    }
     header .contenedor-inicio{
        flex-direction: column;
        margin:8vh 0;
    }  
    header .titular , header .imagen{
        width: 100% ;
    }
    header .imagen .img2 {
        width: 79% ;
    }
    header h1{
        font-size: 38px;
    }
}

</style>