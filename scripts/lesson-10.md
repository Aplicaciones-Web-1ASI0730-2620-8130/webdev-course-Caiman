# Lección 10 — Errores comunes y próximos pasos

Duración objetivo: 6 a 8 minutos. Ajustar los tiempos después de grabar.

**[0:00–0:45] Apertura.** «Una imagen que no aparece o un estilo que no se aplica son problemas normales al empezar. Hoy repararemos seis errores intencionales en una página. Abre los archivos de `starter-files/lesson-10/` y mira la vista previa».

**[0:45–1:30] Error 1: CSS desconectado.** Señalar `rel="style"` dentro de `head`. «La relación correcta es `stylesheet`. Si trabajas con archivos, comprueba además que `href="styles.css"` coincida exactamente con el nombre del archivo». Corregir y comprobar la vista previa. Avisar que aún quedan otros errores de CSS.

**[1:30–2:10] Error 2: título sin cierre.** En `body`, cerrar `h1` justo después de «Reto de diagnóstico web». «Las etiquetas de contenido necesitan un cierre. El navegador intenta reparar el HTML, pero el resultado puede variar; revisa siempre la estructura».

**[2:10–2:50] Error 3: atributo de imagen.** Cambiar `scr` por `src`. «El atributo `src` indica de dónde viene la imagen. `alt` describe su contenido cuando no se muestra y para tecnologías de apoyo».

**[2:50–3:20] Práctica.** «Pausa el video e intenta encontrar los tres errores que quedan en `styles.css`: una clase sin punto, un separador que falta y una propiedad mal escrita».

**[3:20–4:45] Errores 4, 5 y 6: CSS.** Cambiar `tarjeta-reto` por `.tarjeta-reto`. Después, separar `color: #14532d` de `font-size: 24px` con `;`. Finalmente, cambiar `background-colour` por `background-color`. Mostrar qué se arregla tras cada edición. «Lee la regla completa: selector, llaves, nombre de propiedad, dos puntos, valor y punto y coma».

**[4:45–5:50] Recomendaciones.** «Mantén una sangría clara; cambia pocas líneas y revisa la vista previa; usa nombres de clase descriptivos. Si algo no funciona, comprueba primero la ortografía de la etiqueta o propiedad y luego la conexión entre archivos». Mostrar el código corregido en `completed-examples/lesson-10/`.

**[5:50–6:50] Cierre del curso.** «Ya puedes crear una página con HTML y darle estilo con CSS. Como siguiente reto, añade una nueva sección a tu perfil y prueba la página en un móvil o en una ventana estrecha. Consulta MDN Web Docs para aprender nuevas etiquetas y propiedades. Cuando domines estas bases, puedes continuar con JavaScript». Invitar a completar el cuestionario final solo si el equipo ya publicó un enlace real en la descripción.
