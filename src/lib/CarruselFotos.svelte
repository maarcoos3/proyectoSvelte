<script>
    import fotoIniesta from "../images/fotoiniesta.png";
    import fotoMaradona from "../images/fotomaradona.png";
    import fotoMilan from "../images/fotomilan.png";
    import fotoPele from "../images/fotopele.png";
  </script>
  
  <div class="contendor-carrusel-principal">
    <div class="contendor-titulo-carrusel">
      <h1>Carrusel de fotos históricas</h1>
    </div>
    <div class="contendor-imagenes-carrusel">
      <div class="contenedor-imagen-1">
        <div class="imagen-contenedor-1">
          <img src={fotoIniesta} alt="Andrés Iniesta celebrando el gol decisivo en Sudáfrica 2010" />
        </div>
        <div class="info-contenedor-1">
          <h2>Andrés Iniesta, Sudáfrica 2010</h2>
          <p>
            Andrés Iniesta en el momento decisivo del Mundial 2010, justo antes de rematar 
            el balón que daría el gol de la victoria a España en la final contra Países Bajos. 
            Su gol en el minuto 116 aseguró la primera Copa del Mundo para España.
          </p>
        </div>
      </div>
      <div class="contenedor-imagen-2">
        <div class="imagen-contenedor-2">
          <img src={fotoMaradona} alt="Diego Maradona celebrando el Mundial 1986" />
        </div>
        <div class="info-contenedor-2">
          <h2>Diego Maradona, Argentina 1986</h2>
          <p>
            Diego Maradona, el genio del fútbol, levantando la Copa del Mundo de 1986 después 
            de liderar a Argentina con actuaciones memorables. En ese torneo, se recordará 
            para siempre su gol conocido como "La Mano de Dios" y su legendaria jugada 
            del "Gol del Siglo" contra Inglaterra.
          </p>
        </div>
      </div>
  
      <div class="contenedor-imagen-3">
        <div class="imagen-contenedor-3">
          <img src={fotoMilan} alt="Marco Materazzi y Rui Costa en San Siro" />
        </div>
        <div class="info-contenedor-3">
          <h2>San Siro: Materazzi y Rui Costa</h2>
          <p>
            Una icónica imagen de respeto en el fútbol: Marco Materazzi y Rui Costa observando juntos el caos 
            de bengalas y humo que invadió el estadio de San Siro durante un derbi entre Inter de Milán y AC Milán. 
            Un momento que simboliza la pasión y emoción del fútbol italiano.
          </p>
        </div>
      </div>
  
      <div class="contenedor-imagen-4">
        <div class="imagen-contenedor-4">
          <img src={fotoPele} alt="Pelé celebrando un gol en la final del Mundial de 1970" />
        </div>
        <div class="info-contenedor-4">
          <h2>Pelé, Brasil 1970</h2>
          <p>
            Pelé, el rey del fútbol, celebra con el puño en alto tras marcar en la final del 
            Mundial de 1970, liderando a Brasil hacia su tercer campeonato mundial. Ese torneo 
            consolidó a Pelé como uno de los mejores jugadores de la historia.
          </p>
        </div>
      </div>
    </div>
  </div>
  
  <style>
    /* body {
      font-family: 'LV', sans-serif;
      margin: 0;
      padding: 0;
    } */
  
    .contendor-carrusel-principal {
      max-width: 90%;
      margin: 0 auto;
      margin-bottom: 25px;
      padding: 20px;
      background-color: #f8f8f8a4;
      border-radius: 8px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
    }
  
    .contendor-titulo-carrusel {
      margin: 15px;
      display: flex;
      justify-content: center;
      align-items: center;
    }
  
    .contendor-titulo-carrusel h1 {
      font-size: 2.5rem;
      color: #333;
    }
  
    .contendor-imagenes-carrusel {
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
  
    .contenedor-imagen-1,
    .contenedor-imagen-3 {
      display: flex;
      align-items: center;
      gap: 20px;
      flex-direction: row-reverse;
    }
  
    .contenedor-imagen-2,
    .contenedor-imagen-4 {
      display: flex;
      align-items: center;
      gap: 20px;
    }
  
    .contendor-imagenes-carrusel img {
      width: 100%;
      height: auto;
      max-width: 400px;
      object-fit: cover;
      margin: 10px;
      border-radius: 10px;
    }
  
    .info-contenedor-1,
    .info-contenedor-2,
    .info-contenedor-3,
    .info-contenedor-4 {
      flex: 1;
      text-align: left;
    }
  
    h2 {
      font-size: 1.8rem;
      margin-bottom: 5px;
      color: #444;
    }
  
    p {
      font-size: 1rem;
      line-height: 1.5;
      color: #666;
    }
  
    @media (max-width: 768px) {
      .contenedor-imagen-1,
      .contenedor-imagen-2,
      .contenedor-imagen-3,
      .contenedor-imagen-4 {
        flex-direction: column;
        text-align: center;
      }
  
      .info-contenedor-1,
      .info-contenedor-2,
      .info-contenedor-3,
      .info-contenedor-4 {
        text-align: center;
      }
  
      img {
        max-width: 100%;
      }
  
      .contendor-titulo-carrusel h1 {
        text-align: center;
      }
    }
  </style>
  