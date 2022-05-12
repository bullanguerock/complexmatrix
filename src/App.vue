<template> 
  <div id="app">
    <h1>Matriz de Complejidad</h1>
    

    <h1>Negocio</h1>
    
    <table class="table is-bordered is-striped is-narrow is-hoverable is-fullwidth">
      <thead>
        <tr>
          <th>Atributo de Negocio</th>
          <th>Zona I Complejidad Baja</th>
          <th>Zona II Complejidad Media</th>
          <th>Zona III Complejidad Alta</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Cuantos ejecutivos de la organización poseen conocimientos en esa rama del negocio</td>
          <td><label><input type="radio" name="mn1" value="1" v-model="mn1"></label></td>
          <td><label><input type="radio" name="mn1" value="2" v-model="mn1"></label></td>
          <td><label><input type="radio" name="mn1" value="3" v-model="mn1"></label></td>
          
        </tr>
        <tr>
          <td>Definición de Objetivos del negocio</td>
          <td><label><input type="radio" name="mn2" value="1" v-model="mn2"></label></td>
          <td><label><input type="radio" name="mn2" value="2" v-model="mn2"></label></td>
          <td><label><input type="radio" name="mn2" value="3" v-model="mn2"></label></td>
        </tr>
        <tr>
          <td>Procesos de negocio</td>
          <td><label><input type="radio" name="mn3" value="1" v-model="mn3"></label></td>
          <td><label><input type="radio" name="mn3" value="2" v-model="mn3"></label></td>
          <td><label><input type="radio" name="mn3" value="3" v-model="mn3"></label></td>
        </tr>
        <tr>
          <td>Políticas del negocio</td>
          <td><label><input type="radio" name="mn4" value="1" v-model="mn4"></label></td>
          <td><label><input type="radio" name="mn4" value="2" v-model="mn4"></label></td>
          <td><label><input type="radio" name="mn4" value="3" v-model="mn4"></label></td>
        </tr>
        <tr>
          <td>Regulaciones del negocio (Superintendencia o SII)</td>
          <td><label><input type="radio" name="mn5" value="1" v-model="mn5"></label></td>
          <td><label><input type="radio" name="mn5" value="2" v-model="mn5"></label></td>
          <td><label><input type="radio" name="mn5" value="3" v-model="mn5"></label></td>
        </tr>
        <tr>
          <td>Personal</td>
          <td><label><input type="radio" name="mn6" value="1" v-model="mn6"></label></td>
          <td><label><input type="radio" name="mn6" value="2" v-model="mn6"></label></td>
          <td><label><input type="radio" name="mn6" value="3" v-model="mn6"></label></td>
        </tr>
        <tr>
          <td>Ámbito geográfico del negocio</td>
          <td><label><input type="radio" name="mn7" value="1" v-model="mn7"></label></td>
          <td><label><input type="radio" name="mn7" value="2" v-model="mn7"></label></td>
          <td><label><input type="radio" name="mn7" value="3" v-model="mn7"></label></td>
        </tr>
        <tr>
          <td>Reglas internas del negocio</td>
          <td><label><input type="radio" name="mn8" value="1" v-model="mn8"></label></td>
          <td><label><input type="radio" name="mn8" value="2" v-model="mn8"></label></td>
          <td><label><input type="radio" name="mn8" value="3" v-model="mn8"></label></td>
        </tr>
        
      </tbody>
    </table>

    <h1>Tecnología</h1>
    
    <table class="table">
      <thead>
        <tr>
          <th>Atributo de la Tecnología</th>
          <th>Zona I Complejidad Baja</th>
          <th>Zona II Complejidad Media</th>
          <th>Zona III Complejidad Alta</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Arquitectura tecnológica del proyecto</td>
          <td><label><input type="radio" name="mt1" value="1" v-model="mt1"></label></td>
          <td><label><input type="radio" name="mt1" value="2" v-model="mt1"></label></td>
          <td><label><input type="radio" name="mt1" value="3" v-model="mt1"></label></td>
          
        </tr>
        <tr>
          <td>Proveedores de Tecnología y telecomunicaciones</td>
          <td><label><input type="radio" name="mt2" value="1" v-model="mt2"></label></td>
          <td><label><input type="radio" name="mt2" value="2" v-model="mt2"></label></td>
          <td><label><input type="radio" name="mt2" value="3" v-model="mt2"></label></td>
        </tr>
        <tr>
          <td>Localización de los dispositivos a controlar</td>
          <td><label><input type="radio" name="mt3" value="1" v-model="mt3"></label></td>
          <td><label><input type="radio" name="mt3" value="2" v-model="mt3"></label></td>
          <td><label><input type="radio" name="mt3" value="3" v-model="mt3"></label></td>
        </tr>
        <tr>
          <td>Personal de áreas tecnológicas</td>
          <td><label><input type="radio" name="mt4" value="1" v-model="mt4"></label></td>
          <td><label><input type="radio" name="mt4" value="2" v-model="mt4"></label></td>
          <td><label><input type="radio" name="mt4" value="3" v-model="mt4"></label></td>
        </tr>
        <tr>
          <td>Cantidad de plataformas</td>
          <td><label><input type="radio" name="mt5" value="1" v-model="mt5"></label></td>
          <td><label><input type="radio" name="mt5" value="2" v-model="mt5"></label></td>
          <td><label><input type="radio" name="mt5" value="3" v-model="mt5"></label></td>
        </tr>
        <tr>
          <td>Nivel de integración de las distintas plataformas, actualmente</td>
          <td><label><input type="radio" name="mt6" value="1" v-model="mt6"></label></td>
          <td><label><input type="radio" name="mt6" value="2" v-model="mt6"></label></td>
          <td><label><input type="radio" name="mt6" value="3" v-model="mt6"></label></td>
        </tr>
        <tr>
          <td>Plataformas tolerantes a fallas o redundantes</td>
          <td><label><input type="radio" name="mt7" value="1" v-model="mt7"></label></td>
          <td><label><input type="radio" name="mt7" value="2" v-model="mt7"></label></td>
          <td><label><input type="radio" name="mt7" value="3" v-model="mt7"></label></td>
        </tr>
        <tr>
          <td>Obsolescencia de tecnología</td>
          <td><label><input type="radio" name="mt8" value="1" v-model="mt8"></label></td>
          <td><label><input type="radio" name="mt8" value="2" v-model="mt8"></label></td>
          <td><label><input type="radio" name="mt8" value="3" v-model="mt8"></label></td>
        </tr>
        
      </tbody> 
    </table>

    <button class="button is-success" v-on:click="sumMatrix">Calcular</button>

    <div v-if="sum!=0">
      <h3 v-if="sum<=24" style="color: lightgreen">{{sum}} Dificultad Baja</h3>
      <h3 v-if="sum>24&&sum<40" style="color: rgb(255, 243, 114)">{{sum}} Dificultad Media</h3>
      <h3 v-if="sum>=40" style="color: lightcoral">{{sum}} Dificultad Alta</h3>

      <h2>Grafica</h2>
      <div class="column">
        <div class="row vertical-text">tecnología</div>
        <div class="row">
          <div id="grid">
            <div class="grid-item"></div>
            <div class="grid-itemsal"></div>
            <div class="grid-itemsal"></div>
            <div class="grid-item4"></div>
            <div class="grid-itemred"></div>

            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-itemsal"></div>
            <div class="grid-itemsal"></div>
            <div class="grid-item4"></div>

            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-itemsal"></div>
            <div class="grid-itemsal"></div>

            <div class="grid-item2"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-itemsal"></div>

            <div class="grid-item1"></div>
            <div class="grid-item2"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
            <div class="grid-item"></div>
          </div>
        </div>
      </div>
      <div class="column neg">
        <div class="row"></div>
        <div class="row negocio-text">negocio</div>
      </div>
    </div>
    


  </div> 
</template>

<script>
export default {
  name: 'App',
  beforeCreate() {
    localStorage.clear();
  },
  data: function() {
    return {
      mn1 : 0,
      mn2 : 0,
      mn3 : 0,
      mn4 : 0,
      mn5 : 0,
      mn6 : 0,
      mn7 : 0,
      mn8 : 0,

      mt1 : 0,
      mt2 : 0,
      mt3 : 0,
      mt4 : 0,
      mt5 : 0,
      mt6 : 0,
      mt7 : 0,
      mt8 : 0,

      sum : 0,
      mtec: 0,
      mneg: 0,
    };
  },
  methods: {
    sumMatrixN: function () {
      if (this.mn1!=0 && this.mn2!=0 && this.mn3!=0 && this.mn4!=0 && this.mn5!=0 && this.mn6!=0 && this.mn7!=0 && this.mn8!=0){
        return alert(parseInt(this.mn1) + parseInt(this.mn2) + parseInt(this.mn3) + parseInt(this.mn4) + parseInt(this.mn5) +
                      parseInt(this.mn6) + parseInt(this.mn7) + parseInt(this.mn8));
      } else {
        alert('Debe seleccionar todos los campos de la matriz de negocio')
      }
    },
    sumMatrix: function () {
      if (this.mt1!=0 && this.mt2!=0 && this.mt3!=0 && this.mt4!=0 && this.mt5!=0 && this.mt6!=0 && this.mt7!=0 && this.mt8!=0){
        var tec = (parseInt(this.mt1) + parseInt(this.mt2) + parseInt(this.mt3) + parseInt(this.mt4) + parseInt(this.mt5) +
                      parseInt(this.mt6) + parseInt(this.mt7) + parseInt(this.mt8));
      } else {
        alert('Debe seleccionar todos los campos de la matriz de tecnología')
      }
      if (this.mn1!=0 && this.mn2!=0 && this.mn3!=0 && this.mn4!=0 && this.mn5!=0 && this.mn6!=0 && this.mn7!=0 && this.mn8!=0){
        var nego = (parseInt(this.mn1) + parseInt(this.mn2) + parseInt(this.mn3) + parseInt(this.mn4) + parseInt(this.mn5) +
                      parseInt(this.mn6) + parseInt(this.mn7) + parseInt(this.mn8));
      } else {
        alert('Debe seleccionar todos los campos de la matriz de negocio')
      }
      let suma = tec+nego
      this.sum = suma
      this.mtec = tec
      this.mneg = nego

      return suma
    }
  }
}
</script>

<style>
body {
  background: #20262E;
  padding: 20px;
  font-family: Helvetica;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background: #fff;
  border-radius: 4px;
  padding: 20px;
  transition: all 0.2s;
}
#grid {
  margin: auto;
  display: flex;
  flex-wrap: wrap;
  width: 250px;
  box-shadow: -5px 0px 0px 0px black, 0px 5px 0px 0px black;
  
}

.grid-item {
  width: 50px;
  height: 50px;
  overflow: hidden;
  outline: 1px solid white;
  background-color: rgb(255, 243, 114);
  
}
.grid-item4 {
  width: 50px;
  height: 50px;
  overflow: hidden;
  outline: 1px solid white;
  background-color: lightcoral;
}
.grid-itemsal {
  width: 50px;
  height: 50px;
  overflow: hidden;
  outline: 1px solid white;
  background-color: lightsalmon;
}
.grid-itemred{
  width: 50px;
  height: 50px;
  overflow: hidden;
  outline: 1px solid white;
  background-color: red;
}
.grid-item2 {
  width: 50px;
  height: 50px;
  overflow: hidden;
  outline: 1px solid white;
  background-color: lightgreen;
}
.grid-item1 {
  width: 50px;
  height: 50px;
  overflow: hidden;
  outline: 1px solid white;
  background-color: green;
  justify-content: center;
  align-self: center;
}
.column{
  display: flex;
  justify-content: center;
}
.vertical-text {
  transform: rotate(-90deg);
  align-self: center;
}
.negocio-text {
  align-self: center;
}
.neg {
  margin: 5px;
}
h3{
  text-shadow: 1px 1px 1px #000;
}
</style>
