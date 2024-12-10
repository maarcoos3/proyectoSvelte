<script>
    import certificacionImg from '../images/certificacion.png';
  </script>
  
  <div class="div-externo-certificacion">
    <div class="div-interno-certificacion">
      <img src={certificacionImg} alt="marca-certificacion" id="img-certificacion" />
    </div>
  </div>
  
  <style>
    .div-externo-certificacion {
      width: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
  
    .div-interno-certificacion {
      background-color: #57578D;
      width: 100%;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
  
    #img-certificacion {
      width: 300px;
      height: auto;
    }
  </style>
  