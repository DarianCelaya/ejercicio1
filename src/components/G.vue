<template>
    <div id="cuadro12">
        <span id="texto"> {{letra12}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra12: String   
    }
}
</script>

<style scoped>
    #cuadro12{
        position: absolute;
        left: 260px;
        top: 360px;
        width: 260px;
        height: 140px;
        background-color:#fdfea7;
        border: 2px solid #e2c87b;
        z-index: 2;
    }

    #texto{
        font-size: 30px;
        position: absolute;
        left: 120px;
        top: 47px;
}
</style>