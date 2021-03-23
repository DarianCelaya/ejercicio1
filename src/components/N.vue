<template>
    <div id="cuadro6">
        <span id="texto"> {{letra6}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra6: String   
    }
}
</script>

<style scoped>
    #cuadro6{
        position: absolute;
        left: 120px;
        top: 150px;
        width: 70px;
        height: 70px;
        background-color: #d1fea7;
        border: 2px solid #8cb973;
        z-index: 1;
    }

    #texto{
    font-size: 30px;
    position: absolute;
    left: 25px;
    top: 17px;
}
</style>