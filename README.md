![Logo](https://framerusercontent.com/images/zJBgnto0UuieHjFzX0KB4xPLrLk.png)


# ThePower - Entrega Flexbox

 En trega de landing page responsive hecha con flexbox.
<style>
    .prueba{
        display:flex;
        width:100%;
        justify-content:space-between;
gap:100px;
    }

    .prueba img{
        width:30%;
    }
    </style>
## Fase 1 - Preparaciones
Para comenzar, se ha seleccionado replicar el diseño de Kryston Schwarze de MNTN, una landing sobre senderismo.

En primer lugar antes de comenzar el proyecto se ha realizado un esquema visual del los posibles contenedores necesarios para realizar el proyecto

<div class="prueba">
<div>
<h3>Layout</h3>
<p>Enn primer lugar, se ha simulado el desarrollo de las cajas necesarias para </p>
</div>
<img src="./assets/md-img.jpg">
</div>

### Optimizaciones
Se han generado los textos alt con inteligencia artificial, sin embargo al pasarlo por la extensión WAVE y Lighthouse, se ha visto que es recomendable por accesibilidad que cuenten con menos de 100 caracteres
"A hiker walking on a mountain trail, surrounded by lush greenery and towering peaks."

   <!-- <main>
        <div class="bg-image">
        <img src="./assets/bg-sky.png" alt="" >>
        <img src="./assets/bg-mountains.png" alt="" >
        <img src="./assets/bg-grass.png" alt="" >
        <span class="bg-gradient"></span>
    </div> -->

    .sky{
    
    background-image: url(./assets/bg-sky.png);
   width:100%;
  height:600px;
   background-size: cover;
   position:absolute;
}


.mountains{
    background-image: url(./assets/bg-mountains.png);
    top:20%;
    width:100%;
    height: 1300px;
    background-size: cover;
   position:absolute;
   background-overflow: visible;
    }

.grass{
    background-image: url(./assets/bg-grass.png);
    top:45%;
    width:100%;
    background-size: cover;
height:800px;
   z-index: 2;
   position:absolute;
}