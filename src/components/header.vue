<template>
    <div class="m-0 p-0">
        <div class="p-5 bg-dark text-light">
           <header>
        <div class="menu">
            <div class="contenedor">
            <p class="logo">Hosting Company</p>
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
                    <div class="imagen">
                        <img src="~@/assets/imagenes/header.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </header>
        </div>
    </div>
    
</template>

<style scoped>
body{
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
}
.contenedor{
    width: 90%;
    max-width: 1280px;
    margin: auto;
}
header{
    background-image: url(~@/assets/imagenes/ondas.png),linear-gradient(273deg, #46b3ff 0%, #0752fe 100%);
    background-repeat: no-repeat;
    background-position: bottom center;
    height: 850px;
}
.menu{
    background: white;
    padding: 9px 20px;
}
.menu .contenedor{
    display: flex;
    justify-content: space-around;
    align-items: center;
}
header.logo{
    font-size: 23px;
    font-weight: bold;
}
nav ul li{
    display: inline-block;
    margin: 0 20px;
}
nav ul li a{
    text-decoration: none;
    color: black;
}

</style>