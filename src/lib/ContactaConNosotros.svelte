
<div class="div-externo-contacta">
    <h1 class="texto-contacta-con-nosotros">Contacta con nosotros</h1>
    <div class="container-contacta">
      <div class="container-parte-izquierda">
        <div class="input-nombre">
          <input type="text" placeholder="Nombre" />
        </div>
        <div class="input-correo">
          <input type="email" placeholder="Correo Electrónico" />
        </div>
        <div class="boton-enviar">
          <button>Enviar</button>
        </div>
      </div>
      <div class="container-parte-derecha">
        <textarea placeholder="Escribe tu mensaje aquí..."></textarea>
      </div>
    </div>
  </div>
  
  <style>
    .div-externo-contacta {
      margin-bottom: 50px;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 30px;
    }
  
    .texto-contacta-con-nosotros {
      font-size: 2.5em;
      color: rgb(85, 85, 146);
      margin-top: 10px;
      margin-bottom: 20px;
      text-align: left;
      width: 80%;
      max-width: 800px;
    }
  
    .container-contacta {
      display: flex;
      justify-content: space-between;
      width: 80%;
      max-width: 800px;
      background-color: #fff;
      padding: 30px;
      border-radius: 8px;
      box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.15);
    }
  
    .container-parte-izquierda {
      flex: 1;
      display: flex;
      flex-direction: column;
      margin-right: 15px;
    }
  
    .input-nombre,
    .input-correo {
      margin-bottom: 20px;
    }
  
    .input-nombre input,
    .input-correo input {
      width: 100%;
      padding: 15px;
      font-size: 1.1em;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-sizing: border-box;
    }
  
    .boton-enviar {
      display: flex;
      justify-content: flex-start;
      margin-top: 15px;
    }
  
    .boton-enviar button {
      padding: 12px 25px;
      font-size: 1.2em;
      color: #fff;
      background-color: rgb(85, 85, 146);
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
  
    .boton-enviar button:hover {
      background-color: rgb(76, 76, 137);
    }
  
    .container-parte-derecha {
      flex: 2;
      display: flex;
      flex-direction: column;
      border-radius: 5px;
    }
  
    .container-parte-derecha textarea {
      width: 100%;
      height: 100%;
      resize: none;
      padding: 15px;
      font-size: 1.1em;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-sizing: border-box;
    }
  </style>
  

  