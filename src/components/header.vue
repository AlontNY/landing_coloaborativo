<template>
    <div class="m-0 p-0">
        <div class=" text-light">
           <header>
        <div class="menu">
            <div class="contenedor">
            <p class="logo">Hosting Company</p>
            <!-- BARRA DE NAVEGACION PARA MOBIL -->
            <img src="~@/assets/imagenes/menu.png"  class="menu-icon" alt="">
                <nav>
                    <ul>
                        <li><a href="">Home</a></li>
                        <li><a href="">Services</a></li>
                        <li><a href="">Features</a></li>
                        <li><a href="">Princing</a></li>
                        <li><a href="">File Managment</a></li>
                        <li><a href="">Testimonials</a></li>
                        
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
    padding: 15px 20px;
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

/*responsive*/
@media screen and (max-width: 490px){
    nav{
        position:absolute;
        top:100%;
        left:0;
        background: #232220;
        width:100%;
        display: none;
    }
    nav ul li {
        display:block ;
        margin:23px 20px;
    }
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