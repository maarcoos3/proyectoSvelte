
  
  <div class="contenedor-apartados-imagenes">

    <div class="contenedor-apartados-imagen-1">
      <div class="header-contenedor-apartados-imagen-1">
        <h1 class="titulo">RETRO</h1>
      </div>
    </div>

    <div class="contenedor-apartados-imagen-2">
      <div class="header-contenedor-apartados-imagen-2">
        <h1 class="titulo">FIRMADAS</h1>
      </div>
    </div>

    <div class="contenedor-apartados-imagen-3">
      <div class="header-contenedor-apartados-imagen-3">
        <h1 class="titulo">COLABORACIONES</h1>
      </div>
    </div>
  </div>
  
  <style>
    .contenedor-apartados-imagenes {
      display: flex;
      justify-content: space-between;
      align-items: center;
      height: 90vh;
      width: 90vw;
      margin: auto;
      margin-bottom: 70px;
      margin-top: 40px;
    }
  
    .contenedor-apartados-imagen-1,
    .contenedor-apartados-imagen-2,
    .contenedor-apartados-imagen-3 {
      flex: 1;
      margin: 0 10px;
      height: 100%;
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      color: rgb(255, 255, 255);
      border-radius: 5px;
      transition: transform 0.3s ease;
      position: relative;
      box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.15);
      cursor: pointer;
    }
  
    .contenedor-apartados-imagen-1:hover,
    .contenedor-apartados-imagen-2:hover,
    .contenedor-apartados-imagen-3:hover {
      transform: scale(1.02);
      background-color: rgba(0, 0, 0, 0.4);
      box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.15);
    }
  
    .contenedor-apartados-imagen-1 {
      background-image: url('../images/retro.jpg');
    }
  
    .contenedor-apartados-imagen-2 {
      background-image: url('../images/firmadas.jpg');
    }
  
    .contenedor-apartados-imagen-3 {
      background-image: url('../images/colaboraciones.jpg');
    }
  
    .header-contenedor-apartados-imagen-1,
    .header-contenedor-apartados-imagen-2,
    .header-contenedor-apartados-imagen-3 {
      text-align: center;
    }
  
    .titulo {
      margin-top: 7%;
    }
  </style>
  