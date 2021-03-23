<template>
    <div id="cuadro11">
        <span id="texto"> {{letra11}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra11: String   
    }
}
</script>

<style scoped>
    #cuadro11{
        position: absolute;
        left: 190px;
        top: 360px;
        width: 70px;
        height: 70px;
        background-color: #f4b1b1;
        border: 2px solid #bf655b;
        z-index: 3;
    }

    #texto{
    font-size: 30px;
    position: absolute;
    left: 25px;
    top: 20px;
}
</style>