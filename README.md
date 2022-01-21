# Repaso

## Position

Manejar la posición de los elementos de html de una forma nueva.

### Relativa

NO ROMPE modelo de cajas

Mover un elemento en base a su posición original (del modelo de cajas) en la dirección deseada (top, left, right, bottom)

### Absoluta

position: absolute
`
SI ROMPE modelo de cajas

Mover un elemento en base a la posición de su elemento padre posicionado (elemento padre con position: relative)

div padre = position: relative

div hijo = position: absolute

### Fija

position: fixed

SI ROMPE modelo de cajas

Mover un elemento en base a la posición del BODY

Se queda fijo en la pantalla

### Z Index

Nos permite manejar PROFUNDIDAD de los elementos de HTML, es decir hablar en 3 dimensiones en lugar de 2.

Los elementos deben estar posicionados (deben tener position absolute, relative o fixed) y un valor mayor significará que el elemento estará más arriba
