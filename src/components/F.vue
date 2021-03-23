<template>
    <div id="cuadro8">
        <span id="texto"> {{letra8}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra8: String   
    }
}
</script>

<style scoped>
    #cuadro8{
        position: absolute;
        left: 260px;
        top: 220px;
        width: 260px;
        height: 140px;
        background-color: #d1fea7;
        border: 2px solid #8eba75;
        z-index: 2;
    }
    #texto{
    font-size: 30px;
    position: absolute;
    left: 120px;
    top: 47px;
}
</style>