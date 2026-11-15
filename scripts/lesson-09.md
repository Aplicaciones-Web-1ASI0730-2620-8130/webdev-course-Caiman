# Lección 9 — Proyecto: página de perfil

Duración objetivo: 7 a 8 minutos. Ajustar los tiempos después de grabar.

**[0:00–0:45] Presentación.** «Llegamos al proyecto integrador. Ya vimos cómo usar HTML para estructurar contenido y CSS para diseñarlo. Hoy construiremos una página de perfil que reúne imagen, textos, una lista y enlaces. Mira el resultado completo; al terminar podrás poner tus propios datos».

**[0:45–1:45] Estructura del documento.** Abrir `starter-files/lesson-09/index.html`. «`<!DOCTYPE html>` indica HTML moderno; `lang="es"` declara el idioma. En `head`, `charset` permite tildes, `viewport` adapta la página a distintos anchos, `title` nombra la pestaña y `link` conecta `styles.css`. Todo lo visible irá en `body`. En el editor actual de CodePen conserva los dos archivos con estos mismos nombres».

**[1:45–3:30] Contenido HTML.** Escribir `main.tarjeta-perfil`, imagen con `src` y `alt`, `h1` con el nombre ficticio Alex Rivera, subtítulo y biografía. «`main` contiene el contenido principal. El texto alternativo describe el avatar si no puede verse y ayuda a quienes utilizan lectores de pantalla». Añadir dos `section`: pasatiempos con `ul`/`li` y enlaces con `a`. Explicar `href`; si se usa `target="_blank"`, conservar `rel="noopener noreferrer"`. Mostrar que los enlaces llevan a recursos reales de aprendizaje.

**[3:30–3:55] Pausa.** «Detén el video y cambia el nombre, la biografía y los tres pasatiempos por información ficticia o propia que quieras compartir».

**[3:55–5:50] CSS: fondo y tarjeta.** Abrir `styles.css`. Crear reglas para `body` y `.tarjeta-perfil`. «El punto identifica una clase. `max-width` limita el ancho y `margin: 0 auto` centra la tarjeta horizontalmente. `padding` deja aire dentro; `border` y `border-radius` definen el contorno». Añadir `.foto-perfil`, `h1`, `h2`, `.subtitulo` y `.biografia`.

**[5:50–7:15] CSS: lista y botones.** Quitar viñetas con `list-style: none` y dar fondo y espacio a cada `li`. Estilizar `.boton` y añadir `:hover` y `:focus-visible`. «El cambio de color también aparece al navegar con teclado». Mostrar la vista previa completa y probar ambos enlaces.

**[7:15–7:45] Cierre y reto.** «Personaliza los colores y revisa cómo se ve en una ventana angosta. Compara tu página con `completed-examples/lesson-09/`. En la siguiente lección aprenderemos a detectar errores habituales».
