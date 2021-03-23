<template>
    <div id="cuadro4">
        <span id="texto"> {{letra4}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra4: String   
    }
}
</script>

<style scoped>
    #cuadro4{
        position: absolute;
        left: 262px;
        top: 80px;
        width: 258px;
        height: 140px;
        background-color:#b1eef4;
        border: 2px solid #6c8ebf;
        z-index: 4;
    }

    #texto{
    font-size: 30px;
    position: absolute;
    left: 120px;
    top: 47px;
}
</style>