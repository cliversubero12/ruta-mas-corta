# Requerimientos

## 1. Características Generales del Proyecto

+ Grilla cuadrada variable (máximo 32 celdas).
+ Inicio y fin estáticos.
+ Vecindad contada por orientación cardinal (Norte, Sur, Este, oeste).
+ Pinta celdas cada segundo.
+ Obstáculos variables.
+ Notificaciones de error (recorrido finalizado, no se encontró ruta).
+ Exportar grilla y solución (en formato JSON).
+ Orden de exploración (Este -> Sur -> Oeste -> Norte).

## 2. Historias de usuario.

+ [ ] Como usuario, quiero ver una grilla cuadrada, es decir, con el mismo número de filas y de columnas, donde cada celda sea cuadrada de 10 píxeles de lado.
+ [ ] Como usuario, quiero modificar las dimensiones de la grilla (en escala cuadrada).
+ [ ] Como usuario, quiero ver marcada una celda como **inicial** en color verde y otra celda como **final** en color rojo. Dichas celdas corresponden con la esquina superior izquierda y la esquina inferior derecha de la grilla respectivamente, independientemente de las dimensiones de la grilla
+ [ ] Como usuario, quiero señalar y borrar *obstáculos* en color gris, haciendo click en cualquier celda. Al hacer click en una celda que no sea la inicial ni la final, ésta se pintará de color gris. Al volver a hacer click sobre una celda marcada como *obstáculo*, ésta se desmarcará.
+ [ ] Como usuario, quiero ver el recorrido de las celdas a una velocidad de 1 celda por segundo.
+ [ ] Como usuario, quiero ver una notificación en caso de que no sea posible encontrar la ruta de **inicial** a **final**, también en caso de que se haya logrado encontrar la ruta
+ [ ] Como usuario, quiero un botón para iniciar el proceso de recorrido. Dicho botón debe deshabilitar tanto la posibilidad de incluir nuevos obstáculos como la posibilidad de modificar el tamaño de la grilla.
+ [ ] Como usuario, quiero ver el recorrido empleado por el algoritmo de exploración, con las celdas visitadas en color azul.
+ [ ] Como usuario, quiero ver, en caso de no encontrar una ruta posible de **inicial** a **final**, que las celdas recorridas por el algoritmo sean de color amarillo.
+ [ ] Como usuario, quiero tener la posiblidad de guardar el estado de la grilla (en formato JSON) cuando el recorrido haya finalizado.
