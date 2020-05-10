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
            <li><i class="fa fa-search buscar"></i></li>
        </ul>
        <hr>
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
}

hr{
    margin-left: 40px;
}

i{
    color: #ffffff;
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