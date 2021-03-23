<template>
    <div id="cuadro13">
        <span id="texto"> {{letra13}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra13: String   
    }
}
</script>

<style scoped>
    #cuadro13{
        position: absolute;
        left: 120px;
        top:430px;
        width: 70px;
        height: 70px;
        background-color:#d1fea7;
        border: 2px solid #8dba74;
        z-index: 3;
    }

    #texto{
        font-size: 30px;
        position: absolute;
        left: 25px;
        top: 20px;
    }
</style>