<template>
<header>
    <nav class="navegacion">
        <div>
            <img src="@/assets/logo.png" alt="WgetDc">
            <span class="nombre">Carlos Orellana</span>
            <span class="subnombre">Ingeniero Informático - Docente - Profesor de Matemática</span>
        </div>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">Projects</a></li>
            <li>
                <a href="https://twitter.com/WgetDc" target="_blank">
                    <i class="fab fa-twitter"></i>
                </a>                 
                <a href="https://www.instagram.com/wgetdc/" target="_blank">
                    <i class="fab fa-instagram"></i>
                </a>
            </li>
        </ul>
    </nav>
</header>
    
</template>

<style scoped>

img{
    width: 50px;
    margin-left: 40px;
}

ul, li{
    display: flex;
    margin-right: 20px;
    margin-bottom: 10px;
    
}

ul li:last-child {
    margin-left: auto;
}



a{
    text-decoration: none;
    color: #cfcfcf;
    font-size: 16px;
}

nav{
    margin-top: 50px;
    margin-left: 300px;
    margin-right: 300px;
    margin-bottom: 30px;
}

hr{
    margin-left: 40px;
    margin-bottom: 40px;
}

i{
    color: #ffffff;
    margin-left: 10px;
}



.nombre{
    color: #ffffff;
    margin-left: 12px;
    position: absolute;
    font-size: 22px;
    font-weight: bold;
}

.subnombre{
    color: #cfcfcf;
    margin-left: 12px;
}

.push {
    margin-left: auto;
}




</style>