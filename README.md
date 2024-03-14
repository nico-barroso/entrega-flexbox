![Logo](https://framerusercontent.com/images/zJBgnto0UuieHjFzX0KB4xPLrLk.png)


# ThePower - Entrega Flexbox

El objetivo de la siguiente entrega es poner en práctica los conceptos aprendidos de Flexbox. En este caso se han tenido en cuenta los siguientes puntos:

 1. Aprovechar la oportunidad para generar un acabado lo más fiel posible.
 2. Generar un código limpio y escalable.
 3. Mejorar las técnicas de uso de media querys y el diseño responsive.


## Fase 1 - Preparaciones
Para comenzar, se ha seleccionado replicar el diseño de Kryston Schwarze de MNTN, una landing sobre senderismo.

En primer lugar antes de comenzar el proyecto se ha realizado un esquema visual del los posibles contenedores necesarios para realizar el proyecto

<div style="
      display:flex;
        width:100%
        justify-content:space-between;
gap:100px;
">
<div>
<h3 style="
border-bottom: .1px solid;
padding-bottom:8px;">Layout</h3>
<p>Enn primer lugar, se ha simulado el desarrollo de las cajas necesarias en Figma para jerarquizar la información simplificando el proceso de desarrollo.</p>
<p></p>
</div>
<img src="./assets/md-img.jpg" style="
width:40%;">
</div>

## Fase 2 - Desarrollo

Para el desarrollo se ha propuesto una metodología "de fuera hacia dentro" no solo atacando a los contenedores más grande hasta los pequeños detalles, sino que además se han estructurado los estilos siguiendo la misma metodología, empezando por:

1. Displays.
2. Posiciones.
3. Tamaños.
4. Márgenes.
5. Paddings.
6. Estilos de los elementos siguiendo un órden lógico.


### Accesibilidad y diferencias diseño original
Para la accesibilidad hay que tener en cuenta unos puntos importantes en este proyecto:

El diseño cuenta con limitaciones en su diseño, en este canto cuenta con un **aside** que no otorga mucho contexto semántico, al ser puramente estético se ha optado por aplicarle un **aria-disabled** para que no sea leído por los lectores de pantalla.

Se ha corregido unos 