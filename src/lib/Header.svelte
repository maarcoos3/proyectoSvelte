<script>
    import balonLogo from '../images/LogoTienda.png';

    //ICONOS A PONER
    // import { FaRegHeart } from 'svelte-icons/fa';
    // import { MdOutlineShoppingBag } from 'svelte-icons/md';
    // import { FaRegUser } from 'svelte-icons/fa';
    // import { IoSearchOutline } from 'svelte-icons/io';

  </script>
  
  <div class="header">
    <div class="header-display">
      <div class="imagen-header">
        <img
          class="header-Image"
          src={balonLogo}
          alt="logo"
        />
      </div>
      <div class="header-Search">
        <input type="text" placeholder="Search..." class="header-Search-input" />
        <button class="header-Search-button">
          <!-- <IoSearchOutline /> -->
        </button>
      </div>
      <div class="header-icons">
        <div class="display-header-icons">
          <span>
            <!-- <FaRegHeart class="color-iconos" /> -->
          </span>
          <span>
            <!-- <MdOutlineShoppingBag class="color-iconos" /> -->
          </span>
          <span>
            <!-- <FaRegUser class="color-iconos" /> -->
          </span>
        </div>
      </div>
    </div>
  </div>
  
  <style>
    .header {
      width: 100%;
      background-color: rgb(87, 87, 141);
    }
  
    .header-display {
      display: grid;
      grid-template-columns: 24% 50% 24%;
      align-items: center;
    }
  
    /* @media (max-width: 600px) {
      h1 {
        font-size: 2em;
      }
    } */
  
    .header-Image {
      width: 110px;
      float: left;
      margin-left: 25%;
      box-shadow: none;
      cursor: pointer;
    }
  
    .header-Search {
      display: inline-block;
      position: relative;
      margin-top: 15px;
    }
  
    .header-Search-input {
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 20px;
    }
  
    .header-Search-input:focus {
      outline: none;
      box-shadow: 0 0 10px #aeaeae;
    }
  
    .header-Search-button {
      margin-right: 15px;
      border: none;
      background-color: transparent;
      cursor: pointer;
      padding: 20px 20px;
      border-radius: 20px;
      position: absolute;
      top: 0;
      right: -20px;
      transition: 0.1s ease;
    }
  
    .header-Search-button:hover {
      transform: scale(1.2);
    }
  
    .header-icons {
      margin-top: 15px;
      font-size: 25px;
    }
  
    /* .color-iconos {
      color: white;
      cursor: pointer;
    } */
  
    .display-header-icons {
      display: flex;
      justify-content: space-evenly;
      width: 100%;
    }
  </style>
  