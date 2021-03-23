<template>
  <div id="cuadro"> Ejercicio 1.- Darián Lucia Celaya Silva
    <W letra="W"/>
    <br>
    <V letra2="V"/>
    <br>
    <L letra3="L"/>
    <br>
    <E letra4="E"/>
    <br>
    <P letra5="P"/>
    <br>
    <N letra6="N"/>
    <br>
    <Y letra7="Y"/>
    <br>
    <F letra8="F"/>
    <br>
    <N2 letra9="Ñ"/>
    <br>
    <D letra10="D"/>
    <br>
    <C letra11="C"/>
    <br>
    <G letra12="G"/>
    <br>
    <A letra13="A"/>
    <br>
    <B letra14="B"/>
  </div>
</template>

<script>
import W from './components/W.vue';
import V from './components/V.vue';
import L from './components/L.vue';
import E from './components/E.vue';
import P from './components/P.vue';
import N from './components/N.vue';
import Y from './components/Y.vue';
import F from './components/F.vue';
import N2 from './components/N2.vue';
import D from './components/D.vue';
import C from './components/C.vue';
import G from './components/G.vue';
import A from './components/A.vue';
import B from './components/B.vue';




export default {
  name: 'App',
  components: {
    W,
    V,
    L,
    E,
    P,
    N,
    Y,
    F,
    N2,
    D,
    C,
    G,
    A,
    B
  }
}
</script>

<style> 
  #cuadro{
    text-align: center;
    align-content: center;
    margin: 15px;
  }
</style>
