# Plantilla03
Plantilla que usaremos para realizar los ejercicios de JavaScript
# 1. Archivo HTML: `index.html` (principal)

### Explicación:

1. `<!DOCTYPE html>`: Declara el tipo de documento como HTML5. Esto le dice al navegador que use las reglas estándar para interpretar el contenido.
2. `<html lang="es">`: Inicia el documento HTML y define el idioma como español.
3. `<head>`: Contiene metadatos y enlaces a recursos externos.
4. `<meta charset="UTF-8">`: Define la codificación de caracteres como UTF-8 para soportar caracteres especiales y acentuados.
5. `<meta http-equiv="X-UA-Compatible" content="IE=edge">`: Asegura que el navegador use la última versión de su motor de renderizado para evitar problemas de compatibilidad con versiones antiguas de IE.
6. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Hace que el contenido se ajuste al tamaño del dispositivo, mejorando la experiencia en móviles.
7. `<title>Javascript</title>`: Define el título de la pestaña del navegador.
8. `<link href="./img/favicon.ico" rel="icon" type="image/x-icon">`: Enlaza el icono de la página que aparece en la pestaña del navegador.
9. `<link href="./css/styles.css" rel="stylesheet" type="text/css" />`: Enlaza el archivo CSS que define el estilo de la página.
10. `<body>`: Contiene el contenido visible de la página.
11. `<div class="header">`: Sección del encabezado con información sobre el proyecto.
12. `<div class="topnav">`: Menú de navegación con enlaces externos.
13. `<div class="container">`: Contenedor principal para los ejercicios. Usa una clase `container` para aplicar estilos de diseño flexible.
14. `<div class="card">`: Tarjeta para cada ejercicio. Contiene un título, una descripción, y un enlace a la solución.
15. `<div class="footer">`: Pie de página con información de derechos de autor.

---

# 2. Archivo CSS: `styles.css` (principal)

### Explicación:

1. **`body`**:
   - `background: url(../img/bgblanco.png) repeat;`: Establece una imagen de fondo que se repite en toda la página.
   - `text-align: justify;`: Justifica el texto para alinear los márgenes.
   - `font-family: Tahoma, Geneva, sans-serif;`: Define la fuente del texto.
   - `font-size: 14px;`: Establece el tamaño de la fuente.

2. **`.header`**:
   - `background: url(../img/bgblue2.png) repeat;`: Imagen de fondo para el encabezado.
   - `opacity: 0.5;`: Establece la opacidad del fondo.
   - `text-align: center;`: Centra el texto en el encabezado.
   - `color: rgb(255,250,250,0.90);`: Color del texto con un poco de transparencia.
   - `text-shadow: 2px 2px 4px rgb(0,0,0,0.75);`: Agrega una sombra al texto para mejor visibilidad.

3. **`.topnav`**:
   - `overflow: hidden;`: Evita que los elementos flotantes se salgan del contenedor.
   - `background-color: rgb(210,105,30,0.5);`: Color de fondo del menú con transparencia.
   - `opacity: 0.85;`: Ajusta la opacidad del menú.

4. **`.topnav a`**:
   - `float: left;`: Hace que los enlaces se alineen a la izquierda.
   - `display: block;`: Hace que cada enlace ocupe el ancho completo.
   - `color: rgb(255,250,250,0.90);`: Color del texto de los enlaces.
   - `text-shadow: 2px 2px 4px rgb(0,0,0,0.75);`: Agrega una sombra al texto del enlace.
   - `text-align: center;`: Centra el texto en cada enlace.
   - `padding: 14px 16px;`: Espacio interno en cada enlace.
   - `text-decoration: none;`: Elimina el subrayado de los enlaces.

5. **`.topnav a:hover`**:
   - `background-color: rgb(128,128,128,0.25);`: Cambia el color de fondo cuando el usuario pasa el cursor sobre el enlace.
   - `color: rgb(255,215,0,0.75);`: Cambia el color del texto cuando se pasa el cursor sobre el enlace.

6. **`.container`**:
   - `display: flex;`: Usa Flexbox para organizar los elementos.
   - `justify-content: center;`: Centra los elementos en el contenedor.
   - `flex-wrap: wrap;`: Permite que los elementos se envuelvan en múltiples líneas.
   - `gap: 16px;`: Espacio entre los elementos.

7. **`.card`**:
   - `display: flex;`: Usa Flexbox para organizar el contenido de la tarjeta.
   - `flex-direction: column;`: Organiza los elementos hijos en una columna.
   - `justify-content: space-between;`: Distribuye el espacio entre los elementos de la tarjeta.
   - `width: auto;`: Ajusta el ancho automáticamente.
   - `border: 1px solid rgb(211,211,211,0.5);`: Agrega un borde con un color ligeramente transparente.
   - `box-shadow: 2px 2px 8px 4px #d3d3d3d1;`: Añade una sombra a la tarjeta.
   - `border-radius: 15px;`: Redondea las esquinas de la tarjeta.

8. **`.cardTitle`**:
   - `font-size: 24px;`: Define el tamaño de la fuente del título de la tarjeta.
   - `padding: 10px 10px 0 10px;`: Espaciado interno en el título.

9. **`.cardBody`**:
   - `padding: 10px;`: Espaciado interno en el cuerpo de la tarjeta.
   - `flex: 1 1 100%;`: Hace que el cuerpo de la tarjeta se expanda para ocupar el espacio disponible.

10. **`.cardFooter`**:
   - `background: rgb(50,205,50,0.25);`: Color de fondo con transparencia.
   - `border-radius: 0 0 15px 15px;`: Redondea las esquinas inferiores de la tarjeta.
   - `padding: 10px;`: Espaciado interno en el pie de la tarjeta.
   - `text-align: center;`: Centra el texto en el pie de la tarjeta.

11. **`.cardFooter a`**:
   - `text-decoration: none;`: Elimina el subrayado del enlace en el pie de la tarjeta.
   - `color: rgb(0,0,255,0.80);`: Color del texto del enlace con transparencia.
   - `text-shadow: 2px 2px 4px rgb(0,0,0,0.25);`: Agrega una sombra al texto del enlace.

12. **`@media screen and (max-width: 600px)`**:
   - **`@media`**: Define reglas específicas para diferentes tamaños de pantalla.
   - `.container { width: 100%; }`: Ajusta el ancho del contenedor al 100% en pantallas pequeñas (móviles).

13. **`.footer`**:
   - `background: url(../img/bgblue2.png) repeat;`: Imagen de fondo para el pie de página.
   - `opacity: 0.5;`: Establece la opacidad del fondo.
   - `text-align: center;`: Centra el texto en el pie de página.
   - `padding: 20px;`: Espaciado interno en el pie de página.
   - `color: rgb(255,250,250,0.90);`: Color del texto con transparencia.
   - `text-shadow: 2px 2px 4px rgb(0,0,0,0.75);`: Agrega una sombra al texto del pie de página.

---

# 3. Archivo HTML: `index.html` (ejercicio 1)

### Explicación:

1. `<input id="boton" type="button" value="Pulsame">`: Crea un botón que el usuario puede hacer clic. El atributo `id="boton"` permite referirse a este botón en el código JavaScript.
2. `<p id="resultado">`: Un párrafo donde se mostrará el resultado después de hacer clic en el botón. El atributo `id="resultado"` permite que el JavaScript actualice su contenido.

---

# 4. Archivo JavaScript: `script.js`

### Explicación:

1. `"use strict"`: Activa el modo estricto en JavaScript, que ayuda a evitar errores comunes y malas prácticas.
2. `const boton = document.getElementById("boton");`: Obtiene el elemento del DOM con el id `boton`.
3. `const resultado = document.getElementById("resultado");`: Obtiene el elemento del DOM con el id `resultado`.
4. `boton.onclick = mostrar;`: Asigna la función mostrar al evento onclick del botón. Cuando el botón es clicado, se ejecuta la función mostrar.

---

# 5. Archivo JavaScript: `funciones.js`

### Explicación:

1. `"use strict"`:
   - Activa el modo estricto de JavaScript. Este modo ayuda a identificar errores y malas prácticas en el código al hacer que ciertas acciones que normalmente se pasarían por alto sean errores.

2. `function mostrar()`:
   - Define una función llamada `mostrar`. Las funciones en JavaScript son bloques de código que se pueden reutilizar y ejecutar cuando se llaman.

3. `resultado.innerHTML = "Estoy mostrando el resultado del ejercicio 01";`:
   - **`resultado`**: Es una variable que contiene una referencia al elemento HTML con el id `resultado`, obtenido previamente en `script.js`.
   - **`innerHTML`**: Es una propiedad de los elementos del DOM que se utiliza para cambiar el contenido HTML dentro de un elemento.
   - La línea de código establece el contenido del elemento `resultado` al texto `"Estoy mostrando el resultado del ejercicio 01"`. Cada vez que se llama a la función `mostrar`, este texto será mostrado en el elemento correspondiente.

---

# 6. ¿Cómo se enlazan `.html` y `.js`?

### Explicación:

1. `<script defer src="./js/funciones.js" type="text/javascript"></script>`:
   - `<script>`: Etiqueta HTML utilizada para enlazar archivos JavaScript.
   - `defer`: Atributo que indica al navegador que debe esperar a que el HTML se haya cargado completamente antes de ejecutar el script. Esto evita el bloqueo del renderizado.
   - `src="./js/funciones.js"`: Especifica la ubicación del archivo JavaScript que contiene las funciones. La ruta es relativa al archivo HTML.

2. `<script defer src="./js/script.js" type="text/javascript"></script>`:
   - Similar al archivo anterior, pero en este caso, enlaza con `script.js`, que contiene la lógica para asignar eventos a los elementos del DOM.

---

# 7. DOM (Document Object Model)

### Explicación:

- **DOM** es una interfaz de programación que representa la estructura de un documento HTML o XML como un árbol de nodos. Cada nodo en el árbol corresponde a un elemento, atributo o texto del documento.

- **Estructura del DOM**: En un documento HTML, el DOM representa la estructura jerárquica del documento. Por ejemplo, el `<body>` del HTML es un nodo que contiene varios nodos hijos, como `<div>`, `<p>`, `<h1>`, etc.

- **Manipulación del DOM**: JavaScript puede acceder y modificar el DOM, lo que permite cambiar el contenido y el estilo de una página web de manera dinámica.

---

# 8. Métodos y Atributos DOM

### Explicación (`script.js`):

1. `document.getElementById("boton")`:
   - Método que selecciona un elemento del DOM basado en su id. En este caso, `boton` es el elemento HTML con el id `"boton"`.

2. `document.getElementById("resultado")`:
   - Selecciona el elemento del DOM con el id `"resultado"`.

3. `boton.onclick = mostrar;`:
   - Asigna la función `mostrar` al evento `onclick` del botón. Esto significa que cuando el botón es clicado, la función `mostrar` será ejecutada.

### Explicación (`funciones.js`):

1. `function mostrar()`:
   - Define la función que será ejecutada cuando el botón sea clicado.

2. `resultado.innerHTML = "Estoy mostrando el resultado del ejercicio 01";`:
   - **`innerHTML`**: Es un atributo de los elementos del DOM que se usa para obtener o establecer el contenido HTML del elemento.

---

# Cómo Construir la Aplicación Web Paso a Paso

1. **Crea los Archivos**:
   - Crea los archivos `index.html`, `styles.css`, `script.js`, y `funciones.js` en las carpetas correspondientes.

2. **Estructura HTML**:
   - Define el HTML básico en `index.html`. Incluye etiquetas como `<html>`, `<head>`, `<body>`, y organiza el contenido en `<div>` con clases específicas.

3. **Estilos CSS**:
   - Define estilos en `styles.css`. Usa selectores de clases (`.header`, `.topnav`, `.card`, etc.) para aplicar estilos a los elementos HTML. Configura colores, fuentes, y diseño usando Flexbox y RGBA para transparencia.

4. **JavaScript**:
   - **`script.js`**: Usa `document.getElementById` para seleccionar elementos y asigna eventos a estos elementos, como `onclick`.
   - **`funciones.js`**: Define funciones que manipulan el DOM, como actualizar el contenido de los elementos.

5. **Enlace de Archivos**:
   - Enlaza los archivos CSS y JavaScript en el HTML usando `<link>` y `<script>`. Asegúrate de usar `defer` para cargar scripts después de que el HTML se haya cargado.

6. **Prueba y Depura**:
   - Abre `index.html` en un navegador y prueba la funcionalidad. Usa herramientas de desarrollo en el navegador para depurar y ajustar el código si es necesario.

---

# Resumen Final

1. **Codificación UTF-8**:
   - Asegura la correcta visualización de caracteres especiales en el documento HTML.

2. **Etiquetas Meta**:
   - Configuran el comportamiento del documento en navegadores y dispositivos.

3. **Codificación RGBA**:
   - Permite definir colores con transparencia en CSS.

4. **Disposición Flex**:
   - Utiliza Flexbox para crear diseños flexibles y adaptativos en CSS.

5. **Etiquetas CSS**:
   - Definen el estilo y la presentación de los elementos HTML.

6. **Enlazado de `.html` y `.js`**:
   - Los archivos JavaScript se enlazan en el HTML mediante la etiqueta `<script>`, usando el atributo `defer` para asegurar la correcta carga y ejecución.

7. **DOM**:
   - Representa el documento HTML como un árbol de nodos, permitiendo la manipulación dinámica con JavaScript.

8. **Métodos y Atributos DOM**:
   - Permiten acceder y modificar los elementos del documento. Métodos como `getElementById` seleccionan elementos, y atributos como `innerHTML` permiten cambiar su contenido.
