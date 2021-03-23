<template>
    <div id="cuadro14">
        <span id="texto"> {{letra14}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra14: String   
    }
}
</script>

<style scoped>
    #cuadro14{
        position: absolute;
        left: 190px;
        top: 430px;
        width: 70px;
        height: 70px;
        background-color: #b1eef4;
        border: 2px solid #7a9ac7;
        z-index: 3;
    }

    #texto{
    font-size: 30px;
    position: absolute;
    left: 25px;
    top: 20px;
}
</style>