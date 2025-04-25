<!DOCTYPE html>
<html lang="no">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Watch Nordic</title>
    <style>
        body {
            background-color: #091c1f; /* Mørk bakgrunnsfarge for hele siden */
            margin: 0; /* Fjerner standard margin */
            font-family: Arial, sans-serif; /* Setter skrifttype */
            overflow-x: hidden; /* Hindrer horisontal rulling */
        }

        header {
            position: fixed; /* Fikserer headeren til toppen av siden */
            top: 0; /* Plasserer headeren øverst */
            left: 0; /* Plasserer headeren til venstre */
            width: 100%; /* Fyller hele bredden */
            display: flex; /* Bruker flexbox for layout av header */
            align-items: center; /* Justerer innholdet vertikalt */
            position: fixed; /* Fikserer headeren til toppen av siden */
            top: 0; /* Plasserer headeren øverst */
            left: 10; /* Plasserer headeren til venstre */
            width: 100%; /* Fyller hele bredden */
            display: flex; /* Bruker flexbox for layout av header */
            align-items: center; /* Justerer innholdet vertikalt */
            padding: 20px 10px; /* Innvendig avstand i header */
            background-color: rgba(9, 27, 30, 0.9); /* Gjennomsiktig bakgrunn for fade-effekt */
            color: white; /* Hvit tekstfarge */
            z-index: 1000; /* Sørger for at headeren er over annet innhold */
        }

        .logo {
            width: 150px; /* Bredde på logoen */
            height: auto; /* Bevarer høyde-bredde-forholdet */
            left: 20px;
            margin-right: 30px; /* Avstand mellom logoen og navigasjonen */
            position: relative; /* Gjør logoen uavhengig av andre elementer */
            z-index: 1001; /* Sørger for at logoen er over headeren */
        }
        nav a {
            margin-left: 20px; /* Avstand mellom navigasjonslenkene */
            color: white; /* Hvit tekstfarge for lenkene */
            text-decoration: none; /* Fjerner understreking på lenkene */
            transition: all 0.3s ease; /* Animasjon for overgangseffekten */
        }
        nav a:hover,
        nav a:active {
            color: #00FFCC; /* Endrer farge på lenkene ved hover */
        }

         </style>


</head>
<body>
    <header>
        <img src="https://static.wixstatic.com/media/fd2fb2_ffc42d7c2709469483441fbf9e0f5ec5~mv2.png" alt="Watch Logo" class="logo">
        <nav>
            <a href="index.html">Startsiden</a>
            <a href="Filmer">Filmer</a>
            <a href="Serier">Serier</a>
            <a href="Min liste">Min liste</a>
        </nav>
    </form>
        
    </header>


<main>
    <!-- Innholdet på siden går her -->
</main>




<div class="innhold">
    <div class="fixed-content"></div>
    
</div>

<main>
    <section id="home">
       
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Min Galleri</title>
        <style>
            body {
                margin: 20px;
                padding: 10px;
            }
            .container {
    position: relative;
    margin-top: 70px;
    margin-left: 2%;
    margin-right: 2%;
    background-image: url('https://static.wixstatic.com/media/fd2fb2_4b8f443cd8b9486e99d36832ebc82a19~mv2.jpg');
    background-size: cover;
    background-position: center;
    height: 65vh; /* Containerens høyde */
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    border: 2px solid #00FFCC;
    border-radius: 8px;
}

.min-logo {
    width: 50%; /* Endre dette til ønsket prosent */
    height: auto; /* Beholder proporsjoner */
    max-width: 400px; /* Setter en maksimal bredde for logoen */
    right: 30%;
    position: relative; /* Endret fra absolute til relative */
}
        </style>
    </head>
    <body>
        <div class="container">
            <img src="https://static.wixstatic.com/media/fd2fb2_ffc42d7c2709469483441fbf9e0f5ec5~mv2.png" alt="Logo" class="min-logo">
        </div>
        

    </section>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Filmer på Watch<title>
    <style>
        .title {
            color: white; /* Endrer fargen på teksten til blå */
            font-size: 24px; /* Endrer størrelsen på teksten */
            position: absolute; /* Gjør at vi kan plassere teksten hvor som helst */
            top: 20px; /* Endrer hvor langt ned teksten skal være */
            left: 20px; /* Endrer hvor langt til venstre teksten skal være */
        }
</style>
</section>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nye filmer på Watch</title>
<style>
    .tittel {
        position: relative; /* Du kan endre til 'absolute' eller 'fixed' hvis du vil */
        font-size: 18px; /* Endre størrelsen her */
        color: #00FFCC; /* Endre fargen her */
        top: 20px; /* Juster høyden her */
        left: 30px; /* Juster posisjonen her */
        font-family: 'Arial', sans-serif; /* Endre skriftstype her */
    }
</style>
    

</section>
<!DOCTYPE html>
<html lang="no">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Galleri 1 – Toppfilmer</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .tittel {
      position: relative;
      font-size: 18px;
      color: #00FFCC;
      top: 20px;
      left: 35px;
      font-family: 'Arial', sans-serif;
    }

    .galleri1-wrapper {
      margin-top: 30px;
      width: 100%;
      position: relative;
    }

    .galleri1-container {
      width: 96%;
      height: 150%;
      margin: auto;
      position: relative;
      overflow: hidden;
    }

    .galleri1 {
      display: flex;
      scroll-behavior: smooth;
      white-space: nowrap;
      width: 100%;
      overflow: hidden;
      pointer-events: none;
    }

    .galleri1-item {
      flex: 0 0 auto;
      margin: 10px;
      position: relative;
      pointer-events: all;
    }

    .galleri1-item img {
      width: 300px;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
      display: block;
    }

    .galleri1-nav-knapper {
      position: absolute;
      top: 50%;
      width: 100%;
      display: flex;
      justify-content: space-between;
      transform: translateY(-50%);
      pointer-events: none;
      z-index: 10;
    }

    .galleri1-nav-knapp {
      background: none;
      border: none;
      cursor: pointer;
      pointer-events: all;
      opacity: 0.7;
      transition: opacity 0.3s ease;
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      z-index: 11;
    }

    #venstrePil1 {
      left: -20px;
    }

    #hoyrePil1 {
      right: -20px;
    }

    .galleri1-nav-knapp:hover {
      opacity: 1;
    }

    .galleri1-nav-knapp img {
      width: 50px;
    }

    .hidden {
      display: none;
    }

    h2 {
      margin-left: 2%;
    }
  </style>
</head>
<body>

  <h1 class="tittel">Nye filmer på Watch</h1>

  <div class="galleri1-wrapper">
    <div class="galleri1-container">
      <div class="galleri1-nav-knapper">
        <button id="venstrePil1" class="galleri1-nav-knapp" onclick="scrollGalleri1(-1)">
          <img src="https://static.wixstatic.com/media/fd2fb2_59ea5a2a1ff34303a71a369537dd62c3~mv2.png" alt="Venstre pil">
        </button>
        <button id="hoyrePil1" class="galleri1-nav-knapp" onclick="scrollGalleri1(1)">
          <img src="https://static.wixstatic.com/media/fd2fb2_6db270eb8d574d43996955e0a2331ae1~mv2.png" alt="Høyre pil">
        </button>
      </div>

      <div id="galleri1" class="galleri1" onscroll="oppdaterPiler1()">
        <div class="galleri1-item"><a href="Kaptein Sabeltann.html"><img src="https://static.wixstatic.com/media/fd2fb2_7efb81bf956d477fae1458d7238325cf~mv2.webp" alt="Toppfilm 1"></a></div>
        <div class="galleri1-item"><a href="Hakkebakkeskogen.html"><img src="c:\Users\Elev\Downloads\IMG_9627.jpeg" alt="Toppfilm 2"></a></div>
        <div class="galleri1-item"><a href="#"><img src="https://via.placeholder.com/300x180?text=Film+3" alt="Toppfilm 3"></a></div>
        <div class="galleri1-item"><a href="#"><img src="https://via.placeholder.com/300x180?text=Film+4" alt="Toppfilm 4"></a></div>
        <div class="galleri1-item"><a href="#"><img src="https://via.placeholder.com/300x180?text=Film+5" alt="Toppfilm 5"></a></div>
        <div class="galleri1-item"><a href="#"><img src="https://via.placeholder.com/300x180?text=Film+6" alt="Toppfilm 6"></a></div>
      </div>
    </div>
  </div>

  <script>
    function scrollGalleri1(direction) {
      const gallery = document.getElementById("galleri1");
      const scrollAmount = 400;
      gallery.scrollBy({ left: direction * scrollAmount, behavior: 'smooth' });

      setTimeout(oppdaterPiler1, 400);
    }

    function oppdaterPiler1() {
      const gallery = document.getElementById("galleri1");
      const venstrePil = document.getElementById("venstrePil1");
      const hoyrePil = document.getElementById("hoyrePil1");

      if (gallery.scrollLeft > 0) {
        venstrePil.classList.remove('hidden');
      } else {
        venstrePil.classList.add('hidden');
      }

      if (gallery.scrollLeft + gallery.clientWidth < gallery.scrollWidth - 1) {
        hoyrePil.classList.remove('hidden');
      } else {
        hoyrePil.classList.add('hidden');
      }
    }

    window.onload = oppdaterPiler1;
    window.onresize = oppdaterPiler1;
  </script>

</body>
</html>

   </script>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Topp filmer i Watch</title>
 <style>
     .tittel {
         position: relative; /* Du kan endre til 'absolute' eller 'fixed' hvis du vil */
         font-size: 18px; /* Endre størrelsen her */
         color: #00FFCC; /* Endre fargen her */
         top: 20px; /* Juster høyden her */
         left: 30px; /* Juster posisjonen her */
         font-family: 'Arial', sans-serif; /* Endre skriftstype her */
     }
 </style>
 </head>
 <body>
 <h1 class="tittel">Top filmer i Watch</h1>
 </body>
 </html>
     
</script>
</body>
</html>
</script>
<!DOCTYPE html>
<html lang="no">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Galleri 2 – Toppfilmer</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .galleri2-wrapper {
      margin-top: 30px;
      width: 100%;
      position: relative;
    }

    .galleri2-container {
      width: 96%;
      margin: auto;
      position: relative;
      overflow: hidden;
    }

    .galleri2 {
      display: flex;
      scroll-behavior: smooth;
      white-space: nowrap;
      width: 100%;
      overflow: hidden;
      pointer-events: none;
    }

    .galleri2-item {
      flex: 0 0 auto;
      margin: 10px;
      position: relative;
      pointer-events: all;
    }

    .galleri2-item img {
      width: 180px;
      height: 300px;
      object-fit: cover;
      border-radius: 8px;
      display: block;
    }

    .galleri2-nav-knapper {
      position: absolute;
      top: 50%;
      width: 100%;
      display: flex;
      justify-content: space-between;
      transform: translateY(-50%);
      pointer-events: none;
      z-index: 10;
    }

    .galleri2-nav-knapp {
      background: none;
      border: none;
      cursor: pointer;
      pointer-events: all;
      opacity: 0.7;
      transition: opacity 0.3s ease;
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      z-index: 11;
    }

    #venstrePil2 {
      left: -20px;
    }

    #hoyrePil2 {
      right: -20px;
    }

    .galleri2-nav-knapp:hover {
      opacity: 1;
    }

    .galleri2-nav-knapp img {
      width: 50px;
    }

    .hidden {
      display: none;
    }

    h2 {
      margin-left: 2%;
    }
  </style>
</head>
<body>

  <div class="galleri2-wrapper">
    <div class="galleri2-container">
      <div class="galleri2-nav-knapper">
        <button id="venstrePil2" class="galleri2-nav-knapp" onclick="scrollGalleri2(-1)">
          <img src="https://static.wixstatic.com/media/fd2fb2_59ea5a2a1ff34303a71a369537dd62c3~mv2.png" alt="Venstre pil">
        </button>
        <button id="hoyrePil2" class="galleri2-nav-knapp" onclick="scrollGalleri2(1)">
          <img src="https://static.wixstatic.com/media/fd2fb2_6db270eb8d574d43996955e0a2331ae1~mv2.png" alt="Høyre pil">
        </button>
      </div>
      <div id="galleri2" class="galleri2" onscroll="oppdaterPiler2()">
        <!-- Gallerielementer uten nummer -->
        <div class="galleri2-item"><a href="Kaptein Sabeltann.html"><img src="https://static.wixstatic.com/media/fd2fb2_9d4c291f30eb471bbc4fe9992e8d2573~mv2.webp" alt="Toppfilm 1"></a></div>
        <div class="galleri2-item"><a href="Hakkebakkeskogen.html"><img src="https://static.wixstatic.com/media/fd2fb2_dc79801c7c5d4cd4908ac2a650ccf0b1~mv2.jpg" alt="Toppfilm 2"></a></div>
        <div class="galleri2-item"><a href="#"><img src="https://via.placeholder.com/180x300?text=Film+4" alt="Toppfilm 3"></a></div>
        <div class="galleri2-item"><a href="#"><img src="https://via.placeholder.com/180x300?text=Film+5" alt="Toppfilm 4"></a></div>
        <div class="galleri2-item"><a href="#"><img src="https://via.placeholder.com/180x300?text=Film+6" alt="Toppfilm 5"></a></div>
        <div class="galleri2-item"><a href="#"><img src="https://via.placeholder.com/180x300?text=Film+7" alt="Toppfilm 6"></a></div>
        <div class="galleri2-item"><a href="#"><img src="https://via.placeholder.com/180x300?text=Film+8" alt="Toppfilm 7"></a></div>
      </div>
    </div>
  </div>

  <script>
    function scrollGalleri2(direction) {
      const gallery = document.getElementById("galleri2");
      const scrollAmount = 400;
      gallery.scrollBy({ left: direction * scrollAmount, behavior: 'smooth' });

      setTimeout(oppdaterPiler2, 400);
    }

    function oppdaterPiler2() {
      const gallery = document.getElementById("galleri2");
      const venstrePil = document.getElementById("venstrePil2");
      const hoyrePil = document.getElementById("hoyrePil2");

      if (gallery.scrollLeft > 0) {
        venstrePil.classList.remove('hidden');
      } else {
        venstrePil.classList.add('hidden');
      }

      if (gallery.scrollLeft + gallery.clientWidth < gallery.scrollWidth - 1) {
        hoyrePil.classList.remove('hidden');
      } else {
        hoyrePil.classList.add('hidden');
      }
    }

    window.onload = oppdaterPiler2;
    window.onresize = oppdaterPiler2;
  </script>

</body>
</html>

  </script>

</body>
</html>

  </script>

</body>
</html>


  </script>

</body>
</html>

</script>
</script>
        <div style="text-align: center; padding: 10px; background-color: none;">
            <p style="color: #00FFCC;">© 2025 Watch Nordic Grupe. </p>
        </div>
    </footer>
</script>
</div>

</body>
</html>

