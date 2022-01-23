<template>
    <div class="footer_">
        <div class="contenedor">
            <div class="copy">Designed by Elegant Themes | Powered by me xd</div>
            <div class="redes">
                <ul>
                    <li><i class="fab fa-facebook-f"></i></li>
                    <li><i class="fab fa-twitter"></i></li>
                    <li><i class="fab fa-instagram"></i></li>
                </ul>
            </div>
        </div>
    </div>
</template>
<style scoped>

    .footer_{
        background-color: #161616;
        color: #666;
        display: flex;
        justify-content: center;
    }
    .contenedor{
        padding: 1rem .5rem;
        display: flex;
        justify-content: space-between;
        max-width: 1050px;
    }
    .footer_ .copy{
        font-size: 14px;
        /* font-family: 'Open Sans'; */
        display: flex;
        align-items: center;
    }

    .footer_ .redes ul{
        padding: 0;
        margin: 0;
        display: flex;
        align-items: center;
    }

    .footer_ .redes ul li{
        display: inline-block;
        margin: 0 10px;
        font-style: normal;
    }
    .footer_ .redes i{
        font-size: 1.4rem;
    }
</style>