<template>
    <div>
        <div class="contenedor">
            <div class="contenedor-1 contenedor-div">                                
                <img src="https://www.w3schools.com/css/img_5terre_wide.jpg" alt="">      
                <h3>Título</h3>          
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolores, dolorum.</p>
            </div>
            <div class="contenedor-2 contenedor-div">                                
                <img src="https://www.w3schools.com/css/img_5terre_wide.jpg" alt="">      
                <h3>Título</h3>          
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolores, dolorum.</p>
            </div>
        </div>
    </div>
</template>

<style scoped>
*{
    color: white;
    
}

.contenedor{
    display: grid;
    grid-template-columns: repeat(6, 1fr);
    gap: 4em;
}

.contenedor-div{
    background: #141F2D;
    color: #ffffff;
    border-radius: 5px;
    padding: 0px;
    /* border: 2px solid white; */
}
.contenedor div:hover{
    border: 1px solid yellow;
}

.contenedor img{
    background: #141F2D ;
    max-width: 100%;
    height: auto;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
}

.contenedor p, h3{
    margin: 10px;
    background: #141F2D ;
    max-width: 95%;
    max-height: auto;
}


.contenedor-1{
    grid-column: 2/4;
}

.contenedor-2{
    grid-column: 4/6;
}
</style>