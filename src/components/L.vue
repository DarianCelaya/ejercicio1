<template>
    <div id="cuadro3">
        <span  id="texto"> {{letra3}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra3: String   
    }
}
</script>

<style scoped>
    #cuadro3{
        position: absolute;
        left: 190px;
        top: 80px;
        width: 70px;
        height: 140px;
        background-color: #fdfea7;
        border: 2px solid #d6b656;
        z-index: 3;
    }

    #texto{
        font-size: 30px;
        position: absolute;
        left: 25px;
        top: 47px;
    }
</style>