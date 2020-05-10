<template>
    <div class="flex-container">
        <div class="tarjeta">
            <div>
                <img src="https://pbs.twimg.com/media/C9DICr-XYAAcdTO.jpg" alt="">
                <h2>Titulo</h2>
                <h3>Subtitulo</h3>
            </div>
        </div>
        <div class="tarjeta">2</div>
        <div class="tarjeta">3</div>
    </div>    
</template>

<style scoped>
*{
    color: #ffffff;
    
}

.tarjeta{
    border: 0px solid #ffffff;
    margin: 30px;
    background: #19222f;
}

.tarjeta img{
    width: 450px;
    border-radius: 6px;
}

.flex-container {
  display: flex;
  flex-wrap: wrap;
}


</style>