<template>
    <div id="cuadro10">
        <span id="texto"> {{letra10}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra10: String   
    }
}
</script>

<style scoped>
    #cuadro10{
        position: absolute;
        left: 120px;
        top: 360px;
        width: 70px;
        height: 70px;
        background-color: #fdfea7;
        border: 2px solid #cbb366;
        z-index: 3;
    }
    #texto{
        font-size: 30px;
        position: absolute;
        left: 25px;
        top: 20px;
    }
</style>