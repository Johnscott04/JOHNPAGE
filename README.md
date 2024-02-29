<!DOCTYPE html>
<html>
<title>Mayonesa - Lomos y Pizzas</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
body {font-family: "Times New Roman", Georgia, Serif;}
h1, h2, h3, h4, h5, h6 {
  font-family: "Playfair Display";
  letter-spacing: 5px;
}
</style>
<body>
  <!-- Navbar (sit on top) -->
  <div class="w3-top">
    <div class="w3-bar w3-white w3-padding w3-card" style="letter-spacing:4px;">
      <a href="index.html" class="w3-bar-item w3-button">Mayonesa - Lomos y Pizzas</a>
      <!-- Right-sided navbar links. Hide them on small screens -->
      <div class="w3-right w3-hide-small">
        <a href="./HTML/retroalimentacion.html" class="w3-bar-item w3-button">Tu opinión</a>
        <a href="./HTML/menu.html" class="w3-bar-item w3-button">Menú</a>
        <a href="./HTML/sucursales.html" class="w3-bar-item w3-button">Sucursales</a>
      </div>
    </div>
  </div>
  <!-- Header -->
  <header class="w3-display-container w3-content w3-wide" style="max-width:1600px;min-width:500px" id="home">
    <link rel="icon" href="./IMAGENES/favicon.png" type="FORMATO-FAV" sizes="32x32">
    <img class="w3-image" src="./IMAGENES/banner.png" width="1920">
    <div class="w3-display-bottomleft w3-padding-large w3-opacity">
      <h1 class="w3-xxlarge">Modo Mayonesa</h1>
    </div>
  </header>
  <!-- Page content -->
  <div class="w3-content" style="max-width:1100px">
     <!-- About Section -->
    <div class="w3-row w3-padding-64" id="about">
      <div class="w3-col m6 w3-padding-large w3-hide-small">
       <img src="./IMAGENES/186515174_2892306887763724_1441701266052329109_n.png" class="w3-round w3-image w3-opacity-min" alt="Table Setting" width="600" height="750">
      </div>
      <div class="w3-col m6 w3-padding-large">
        <h1 class="w3-center">Un poco de nuestra historia...</h1><br>
        <h5 class="w3-center">Desde 2009</h5>
        <p class="w3-large">Mayonesa fue fundado por sus actuales dueños, Cristian Gomez y Daniela Negrette. Con el paso de los años y la eleccion de la gente nos permitio abrir mas sucursales en diferentes zonas de la provincia de La Rioja contando actualmente con 7 sucursales y complementado con el servicio a delivery.</p>
        <p class="w3-large w3-text-grey w3-hide-medium">Contamos con la mejor tecnologia en cocina para ofrecer productos de caldidad y buen savor a un precio accesible para quien opta por nosotros y por una buena degustacion. Ofrecemos un menu amplio que incluye comidas para desayuno, almuerzo, merienda, cena y postres.</p>
      </div>
    </div>
    <hr>
    <!-- Menu Section -->
    <div class="w3-row w3-padding-64" id="menu">
      <div class="w3-col l6 w3-padding-large">
        <h1 class="w3-center">Promociones de la Semana</h1><br>
        <h4>Lomo especial + Papas</h4>
        <p class="w3-text-grey">Pan, carne o pollo, lechuga, tomate, lomo, jamon, queso y huevo + papas fritas. $500,00</p><br>
        <h4>Lomoluco + Papas</h4>
        <p class="w3-text-grey">Pan cubierto de muzzarella, carne o pollo, lechuga, tomate, lomo, jamón, queso y huevo + papas fritas. $600,00</p><br>      
        <h4>2 Pizzas especiales + Cerveza</h4>
        <p class="w3-text-grey">Masa casera, salsa de tomate, queso muzzarella y jamón + cerveza quilmes (1L). $700,00</p><br>      
        <h4>Cuarto de Libra + Papas + Bebida</h4>
        <p class="w3-text-grey">Pan, medallón de carne, doble cheddar, cebolla suave, mayonesa, ketchup y savora, con papas + bebida (500mL). $350,00</p><br>
        <h4>Papas Cheddar + Bebida</h4>
        <p class="w3-text-grey">Papas fritas con queso cheddar, panceta y verdeo + bebida (500mL). $480,00</p>    
      </div>
      <div class="w3-col l6 w3-padding-large">
        <img src="./IMAGENES/184191738_2887944658199947_6460430989015027781_n.jpeg" class="w3-round w3-image w3-opacity-min" alt="Menu" style="width:100%">
      </div>
    </div>
    <hr>
    <!-- Contact Section -->
    <div class="w3-container w3-padding-64" id="contact">
      <h1>Contacto</h1>
      <h4 style="color: violet;"><a href="https://www.instagram.com/modomayonesa/">Instagram</a></h4>
      <h4 style="color: blue;"><a href="https://www.facebook.com/MODOMAYONESA">Facebook</a></h4>
      <h4 style="color: green;"><a href="https://wa.me/c/5493804218090">Whatsapp</a></h4>

      <p>Ofrecemos servicio de delivery y take away.</p>

      <p>Puedes contactarte tambien por whatsapp al +54 9 3804218090 o al mail mayonesalomosypizzas@gmail.com, o puedes dejar un mensaje aquí abajo:</p>
      <form action="/action_page.php" target="_blank">
        <p><input class="w3-input w3-padding-16" type="text" placeholder="Nombre" required name="Name"></p>
        <p><input class="w3-input w3-padding-16" type="number" placeholder="Cantidad de personas" required name="People"></p>
        <p><input class="w3-input w3-padding-16" type="datetime-local" placeholder="Fecha y hora" required name="date" value="2020-11-16T20:00"></p>
        <p><input class="w3-input w3-padding-16" type="text" placeholder="Mensaje/ Pedido" required name="Message"></p>
        <p><button class="w3-button w3-light-grey w3-section" type="submit">Enviar Mensaje</button></p>
      </form>
    </div>
  <!-- End page content -->
  </div>

  <!-- Footer -->
  <footer class="w3-center w3-light-grey w3-padding-32">
    <p class="w3-text-blue-grey w3-large"><b>Avenida Facundo Quiroga 1001, La Rioja, Argentina - +54 9 3804218090 (Whatsapp)</b></p>
  </footer>
</body>
</html>
