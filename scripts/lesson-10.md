# Lección 10 — Errores comunes y próximos pasos

**Duración objetivo:** 7 a 8 minutos. Continuación directa del perfil de Alex Rivera construido en la lección 9. El ejercicio inicial contiene seis errores intencionales; el ejemplo completo muestra la versión corregida. Ajusta los tiempos a tu ritmo de grabación.

## [0:00–0:45] Apertura y conexión con la lección 9

**En pantalla:** Mostrar por unos segundos el perfil final de la lección 9 en CodePen: avatar circular, nombre, biografía, pasatiempos y enlaces «Mis proyectos» y «Mi blog». Después abrir `starter-files/lesson-10/index.html` y `styles.css`, donde se ve el mismo perfil con errores. Rótulo: «LECCIÓN 10/10 — Encuentra y corrige los errores».

**Narración:** «En la lección anterior construimos esta página de perfil desde cero. Escribimos la estructura en `index.html` y le dimos forma con `styles.css`: centramos la tarjeta, redondeamos el avatar y convertimos los enlaces en botones. Ahora imagina que vuelves a abrir el proyecto y ya no se ve igual: faltan colores, la foto no aparece o algún texto perdió su estilo. Eso puede pasar por un carácter mal escrito. Hoy aprenderemos a encontrar y corregir seis errores habituales usando la misma página que acabamos de crear. No te preocupes si alguna vez te ocurre: revisar y corregir también forma parte de programar».

## [0:45–1:40] Error 1: la conexión con CSS

**En pantalla:** En `index.html`, señalar el `head` y la línea `<link rel="style" href="styles.css">`. Cambiar `style` por `stylesheet` y esperar a que se actualice la vista previa. Rótulo: «1. Revisa `<link>` y el nombre del archivo».

**Narración:** «Empecemos por el problema más grande: ¿por qué el perfil parece haber perdido sus estilos? En el `head` está la etiqueta que conecta HTML con CSS. El nombre del archivo, `styles.css`, coincide, pero el valor de `rel` dice `style`. El navegador necesita `stylesheet`, que significa hoja de estilos. Lo corregimos y volvemos a mirar. Ya aparece parte del diseño; si todavía hay cosas desordenadas, eso nos indica que debemos seguir revisando. Cuando una página entera pierde el diseño, comprueba primero esta línea y el nombre exacto de tu archivo CSS».

## [1:40–2:30] Error 2: el encabezado sin cierre

**En pantalla:** Buscar `<h1>Alex Rivera` y añadir `</h1>` después del nombre. Comparar el título y los textos siguientes antes y después. Rótulo: «2. Cierra las etiquetas de contenido».

**Narración:** «Ahora miremos el contenido. Aquí abrimos un encabezado `h1` para el nombre de Alex, pero olvidamos cerrarlo. Añadimos `</h1>` justo después de “Alex Rivera”. El navegador intenta interpretar el HTML aunque falte una etiqueta; por eso el efecto visible puede variar. La manera de evitar sorpresas es comprobar que cada etiqueta de contenido tenga su cierre. Recuerda que la imagen `img` es una excepción: esa etiqueta no necesita `</img>`».

## [2:30–3:15] Error 3: el avatar no carga

**En pantalla:** Señalar la etiqueta `img`. Mostrar `scr=` y cambiarlo por `src=`. Dejar visible también `alt="Avatar ilustrado de Alex"`. Rótulo: «3. `src` indica la dirección de la imagen».

**Narración:** «El avatar sigue sin aparecer. Revisemos su etiqueta. El atributo que contiene la dirección de la imagen se llama `src`, abreviatura de *source*, o fuente. Aquí escribimos `scr`: son las mismas letras, pero en otro orden. Lo corregimos y comprobamos la vista previa. Conservamos el atributo `alt`, que describe la imagen para quienes usan tecnologías de apoyo y también sirve cuando la imagen no puede mostrarse. Si tu imagen falla en otro proyecto, revisa `src` y después comprueba que el enlace exista».

## [3:15–3:45] Pausa para practicar

**En pantalla:** Abrir `styles.css` sin corregirlo todavía. Mostrar el aviso: «⏸️ Pausa: encuentra tres errores en CSS». Señalar la vista previa: tarjeta sin estilo correcto, título con tamaño inesperado y botones sin fondo índigo.

**Narración:** «Ya corregimos tres problemas en HTML. Ahora te toca investigar el CSS. Pausa el video y busca otros tres errores: uno está en el nombre de una clase, otro en la separación de dos propiedades y el último en la propiedad que pinta los botones. No hace falta resolverlos de memoria: compara el código con las reglas que usamos en la lección anterior. Cuando tengas tus respuestas, continúa conmigo».

## [3:45–4:35] Error 4: falta el punto en la clase

**En pantalla:** Cambiar `tarjeta-perfil {` por `.tarjeta-perfil {`. Mostrar cómo vuelve el fondo blanco, el borde y el centrado de la tarjeta. Rótulo: «4. Las clases empiezan con `.` en CSS».

**Narración:** «Primer error en CSS: esta regla dice `tarjeta-perfil` sin punto. En HTML escribimos `class="tarjeta-perfil"`, pero en CSS debemos seleccionar esa clase como `.tarjeta-perfil`. Agregamos el punto y la tarjeta vuelve a recibir su fondo blanco, sus espacios y su borde redondeado. Los selectores de etiquetas, como `body` o `h1`, se escriben sin punto; las clases, con punto. Es un detalle pequeño que puede dejar sin efecto toda una regla».

## [4:35–5:20] Error 5: falta un punto y coma

**En pantalla:** En la regla `h1`, mostrar `color: #1e1b4b` seguido de `font-size: 28px;`. Añadir `;` después del color. Rótulo: «5. Separa las propiedades con `;`».

**Narración:** «El título de Alex todavía no toma el tamaño y color que esperábamos. En la regla `h1` escribimos el color y debajo el tamaño, pero falta el punto y coma que separa una declaración de la siguiente. Lo añadimos después del código de color. Ahora CSS puede leer `color` y `font-size` como dos instrucciones distintas. Si una regla parece correcta pero una propiedad no se aplica, revisa la línea anterior: a veces el error está justo allí».

## [5:20–6:05] Error 6: propiedad mal escrita

**En pantalla:** En `.boton`, cambiar `background-colour` por `background-color`. Pasar el cursor y luego usar Tab para mostrar los estados `:hover` y `:focus-visible`. Rótulo: «6. La propiedad correcta es `background-color`».

**Narración:** «Solo falta recuperar el color de los botones. En su regla escribimos `background-colour`, con una `u`. La propiedad que reconoce CSS es `background-color`. Corregimos el nombre y vuelve el fondo índigo. Si pasamos el cursor, el botón cambia de tono. También puedes llegar con la tecla Tab y ver el estado de enfoque. Cuando el navegador ignora una propiedad, comprueba su escritura: incluso una letra extra importa».

## [6:05–7:00] Tres hábitos para detectar errores

**En pantalla:** Alternar entre el HTML y el CSS ya corregidos; mostrar la vista previa final. Rótulo: «Ordena · Cambia poco · Comprueba».

**Narración:** «Antes de terminar, te dejo tres hábitos que me ayudan a encontrar estos problemas. Primero, mantén el código ordenado y con sangría: así reconoces qué elementos están dentro de `main` o de cada `section`. Segundo, cambia una cosa a la vez y observa la vista previa. Si haces muchos cambios juntos, es más difícil descubrir cuál causó el problema. Tercero, compara lo que escribiste en HTML y CSS: el nombre de la clase debe coincidir exactamente, y el `href` del enlace a CSS debe apuntar al archivo correcto. Puedes comparar tus cambios con el ejemplo completo de esta lección».

## [7:00–7:40] Cierre del curso

**En pantalla:** Mostrar el perfil reparado y abrir brevemente uno de sus enlaces. Rótulo: «Reto final: personaliza y comparte tu página».

**Narración:** «En este curso vimos estructura, imagen, listas, enlaces, colores y diseño en ejercicios distintos, y después construimos un perfil completo. Ya tienes las bases para crear otra página por tu cuenta. Como reto, cambia el nombre, los intereses y los colores del perfil, añade una sección nueva y revisa cómo se ve en una ventana estrecha. Si necesitas consultar una etiqueta o una propiedad, visita MDN Web Docs. Y cuando te sientas cómodo con HTML y CSS, puedes seguir con JavaScript. ¡Gracias por acompañarnos hasta la última lección y mucho éxito con tu próxima página!».
