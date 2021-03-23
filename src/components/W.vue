<template>
    <div id="cuadro1">
        <span id="texto"> {{letra}} </span>
    </div>
</template>

<script>
export default {
    props:{
        letra: String
    }
}
</script> 

<style scoped>
    #cuadro1{
        position: absolute;
        left: 50px;
        top: 80px;
        width: 70px;
        height: 70px;
        background-color: #b1eef4;
        border: 2px solid #6d8fbf;
        z-index: 0;
    }

    #texto{
        font-size: 30px;
        position: absolute;
        left: 21px;
        top: 17px;
    }
</style>









