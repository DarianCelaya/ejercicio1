<template>
    <div id="cuadro5">
        <span id="texto"> {{letra5}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra5: String   
    }
}
</script> 

<style scoped>
    #cuadro5{
        position: absolute;
        left: 50px;
        top: 150px;
        width: 70px;
        height: 70px;
        background-color: #fdfea7;
        border: 2px solid #d6b656;
        z-index: 1;
    }

    #texto{
    font-size: 30px;
    position: absolute;
    left: 25px;
    top: 17px;
}
</style>