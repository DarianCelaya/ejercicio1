<template>
    <div id="cuadro9">
        <span id="texto"> {{letra9}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra9: String   
    }
}
</script>

<style scoped>
    #cuadro9{
        position: absolute;
        left: 50px;
        top: 360px;
        width: 70px;
        height: 140px;
        background-color: #f4b1b1;
        text-align: center;
        border: 2px solid #bf655b;
        z-index: 4;
    }
    #texto{
    font-size: 30px;
    position: absolute;
    left: 25px;
    top: 47px;
}
</style>