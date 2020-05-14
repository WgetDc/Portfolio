<template>
    <div>
        <div class="contenedor">
            <div class="contenedor-1 contenedor-div">                
                <img src="https://i.picsum.photos/id/1060/536/354.jpg" alt="">                
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolores, dolorum.</p>
            </div>
            <div class="contenedor-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Architecto voluptatibus quas autem earum deleniti neque enim incidunt, nihil eaque iusto.</div>
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
    gap: 1em;
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

.contenedor p, img{
    background: #141F2D ;
}

.contenedor p{
    margin: 10px;
}


.contenedor-1{
    grid-column: 2/5;
}

.contenedor-2{
    grid-column: 5/7;
}
</style>