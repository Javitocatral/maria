<script>
  import comedor from "/src/lib/images/comedor1.jpg";
  // import "https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700;900&display=swap";
  // import "https://fonts.googleapis.com/css2?family=DM+Sans:opsz,wght@9..40,300;9..40,400;9..40,500;9..40,600;9..40,700;9..40,800&family=Lato:wght@300;400;700;900&display=swap";
</script>

<dir class="container">
  <div class="iamge">
    <img class="fondo" src={comedor} alt="salon" />
    <div class="header">
      <div class="logo"><h3>María la torre</h3></div>
      <div class="electionButton">
        <div class="button">Quién soy</div>
        <div class="button">Servicios</div>
        <div class="button">Contacto</div>
      </div>
      <div class="lengua">
        <img
          class="instagram"
          src="/src/lib/images/instagram.png"
          alt="instagram"
        />
        <h2>ES EN</h2>
        <a href="#" />
      </div>
    </div>
    <div class="text">
      <h1>Tu espacio puede ser tu aliado</h1>
      <p>
        Tanto tu hogar como tu espacio de trabajo puede ofrecerte la suerte que
        necesitas o todo lo contrario, yo te ayudo a conocerlo y armonizarlo
      </p>
    </div>
  </div>
</dir>

<style>
  .lengua {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
    padding-right: 20px;
  }
  .electionButton {
    display: flex;
    padding: 70px 0;
    padding-right: 100px;
    gap: 30px;
  }
  .container {
    position: relative;
  }
  .button { font-weight: 
    background-color: #fd9c9b;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 50px;
    font-family: "DM Sans", sans-serif;
    transition: all 0.2s ease-out;
  }
  .button:hover {
    scale: 1.1;
  }
  .logo {
    background-color: rgb(240, 255, 255);
    padding: 40px;
    margin: 25px;
    margin-right: 50px;
  }
  .header {
    justify-content: space-between;
    display: flex;
  }
  h2 {
    font-family: "DM Sans", sans-serif;
  }
  h1 {
    font-family: "Lato", sans-serif;
    font-size: 80px;
    z-index: 10;
    padding-right: 628px;
    padding-left: 80px;
  }
  p {
    font-family: "DM Sans", sans-serif;
    z-index: 10;
    padding-left: 80px;
    font-size: 35px;
    padding-right: 628px;
  }
  .instagram {
    width: 25px;
  }
  .fondo {
    opacity: 0.5;
    display: flex;
    width: 100vw;
    height: 100vh;
    object-fit: cover;
    position: absolute;
    top: 0;
    left: 0;
    z-index: -1;
  }
</style>
