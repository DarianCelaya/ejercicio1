<template>
    <div id="cuadro7">
        <span id="texto"> {{letra7}} </span>
    </div> 
</template>

<script>
export default {
    props:{
        letra7: String   
    }
}
</script>

<style scoped>
    #cuadro7{
        position: absolute;
        left: 50px;
        top: 220px;
        width: 210px;
        height: 140px;
        background-color: #b1eef4;
        border: 2px solid #6c8ebf;
        z-index: 3;
    }

    #texto{
        font-size: 30px;
        position: absolute;
        left: 95px;
        top: 50px;
    }
</style>