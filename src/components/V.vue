<template>
    <div id="cuadro2">
        <span  id="texto"> {{letra2}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra2: String   
    }
}
</script>

<style scoped>
    #cuadro2{
        position: absolute;
        left: 120px;
        top: 80px;
        width: 70px;
        height: 68px;
        background-color:#f4b1b1;
        border: 2px solid #b85551;
        z-index: 2;
    }

    #texto{
    font-size: 30px;
    position: absolute;
    left: 24px;
    top: 17px;
    }
</style>