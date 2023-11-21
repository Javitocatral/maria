<script>
  import comedor from "/src/lib/images/comedor1.jpg";
  // import "https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700;900&display=swap";
  // import "https://fonts.googleapis.com/css2?family=DM+Sans:opsz,wght@9..40,300;9..40,400;9..40,500;9..40,600;9..40,700;9..40,800&family=Lato:wght@300;400;700;900&display=swap";
</script>

<div class="container">
  <div class="image" style="background-image: url('{comedor}')">
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
        necesitas o todo lo contrario, yo te ayudo a conocerlo y armonizarlo.
      </p>
    </div>
  </div>
</div>

<style>
  .image {
    position: relative;
    height: 100vh;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
  }
  .lengua {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
    padding-right: 20px;
    font-size: 20px;
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
  .button {
    background-color: #fd9c9b;
    color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 50px;
    font-family: "DM Sans", sans-serif;
    transition: all 0.2s ease-out;
    font-size: 20px;
  }
  .button:hover {
    scale: 1.1;
  }
  .logo {
    background-color: rgb(240, 255, 255);
    padding: 40px;
    margin: 25px;
    padding-right: 50px;
  }
  .header {
    justify-content: space-between;
    display: flex;
  }
  .text {
    width: 50%;
    padding-left: 180px;
  }
  .text p,
  h1 {
    padding-right: 80px;
  }
  h2 {
    font-family: "DM Sans", sans-serif;
  }
  h1 {
    font-family: "Lato", sans-serif;
    font-size: 80px;
    z-index: 10;
  }
  p {
    font-family: "DM Sans", sans-serif;
    z-index: 10;

    font-size: 35px;
  }
  .instagram {
    width: 30px;
  }
  .fondo {
    opacity: 0.8;
    display: flex;
    width: 100%;
    height: 100vh;
    object-fit: cover;
    position: absolute;
    top: 0;
    left: 0;
    z-index: -1;
  }
</style>
