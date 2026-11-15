# Lección 5: CSS y selectores

Duración objetivo: 8 minutos. Se usa el editor en línea CodePen y las diapositivas del curso. Código de partida: `starter-files/lesson-05/`. Resultado esperado: `completed-examples/lesson-05/`.

**[0:00-0:20] Apertura.** Mostrar la diapositiva de la lección. «Esta es la lección 5 de 10. Hasta ahora escribiste HTML y tu página quedó simple: texto negro sobre fondo blanco. Hoy aprendes CSS, el lenguaje que le da estilo a tu página, todo en el navegador y sin instalar nada».

**[0:20-1:00] HTML y CSS.** «HTML es el contenido y CSS es la apariencia. Hoy aprendemos lo más importante de CSS: los selectores. Un selector le dice al navegador a qué elemento quieres cambiarle el estilo».

**[1:00-2:00] Anatomía de una regla.** Mostrar la diapositiva de la regla CSS. Explicar selector, propiedad y valor con `h1 { color: tomato; }`. Señalar los dos puntos entre propiedad y valor y el punto y coma final.

**[2:00-2:45] Abrir el editor en línea.** Cambiar a CodePen con el código inicial. Explicar los paneles HTML y CSS (JS queda vacío) y que cada cambio aparece al instante. Mencionar que en un archivo propio el CSS se conecta con la etiqueta `link` dentro de `head`.

**[2:45-4:00] Selector de etiqueta.** Escribir `h1 { color: tomato; }` y `h2 { color: teal; }`. Mostrar que cambian todas las etiquetas de ese tipo a la vez.

**[4:00-5:30] Selector de clase.** Agregar `class="tarjeta"` a las dos etiquetas `section` y escribir `.tarjeta { background-color: lightyellow; }`. Explicar que el punto es obligatorio y que una clase se puede repetir.

**[5:30-6:30] Selector de id.** Agregar `id="perfil"` al `div` principal y escribir `#perfil { background-color: lavender; }`. Explicar que el id es único en la página.

**[6:30-7:00] Resumen.** Etiqueta sin símbolo y afecta a todas; clase con punto y reutilizable; id con numeral y único. Si dos reglas chocan, gana el id, luego la clase y al final la etiqueta.

**[7:00-7:30] Práctica.** «Pausa el video y haz tres cosas: cambia el color de los párrafos con un selector de etiqueta; crea la clase `destacado` y aplícala a un solo elemento de la lista; cambia el color de fondo de tu id. Si algo no funciona, revisa el punto, la llave y el punto y coma».

**[7:30-8:00] Cierre.** «Ya sabes apuntar a lo que quieres estilizar. En la siguiente lección vemos qué cambiar: colores y tipografía».
