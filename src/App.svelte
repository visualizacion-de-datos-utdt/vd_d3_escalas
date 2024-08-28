<!-- Script JS -->
<script>
  /* Importamos d3 para tenerlo disponible */
  import * as d3 from "d3"

  let data = [1000, 1500, 2000, 2500, 3000, 3500, 4000, 4500, 5000]
</script>

<!-- Estructura contenido HTML -->
<h2>Ejemplo 1: Altura</h2>
<div class="container">
  <div class="column_wrapper">
    <p class="num">1000</p>
    <div class="column"></div>
  </div>
</div>
<br />
<br />

<h2>Ejemplo 2: Color</h2>
<div class="container_2">
  <div class="column_wrapper">
    <div class="circle"></div>
    <p class="num_2">1000</p>
  </div>
</div>

<!-- Estilos CSS -->
<style>
  /* Estilos CSS */
  .container,
  .container_2 {
    display: flex;
    justify-content: space-between;
    gap: 10px;
    height: 450px;
    border: 1px solid #000;
  }
  .container_2 {
    height: auto;
  }

  .column_wrapper {
    display: flex;
    flex-direction: column;
    justify-content: end;
    align-items: center;
    gap: 10px;
  }
  .column {
    width: 80px;
    height: 100%;
    background-color: #ee0001;
  }
  .num {
    font-size: 21px;
    font-weight: bold;
    margin: 0;
    color: #ee0001;
  }
  .num_2 {
    font-size: 18px;
    margin: 0;
    color: #ee0001;
  }

  .circle {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    background-color: #ee0001;
  }
</style>
