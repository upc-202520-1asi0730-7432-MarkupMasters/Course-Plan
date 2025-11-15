# Fundamentos de Desarrollo Web

## Resumen del Curso
Este curso introductorio de 1 hora enseña a estudiantes de secundaria los conceptos básicos del desarrollo web, utilizando exclusivamente herramientas en línea como Replit y JSFiddle.  
No requiere ninguna instalación, solo un navegador web.

Los estudiantes aprenderán qué es un sitio web, cómo se estructura con HTML, cómo estilizarlo con CSS, y finalmente construirán una pequeña página de perfil personal.

**Duración total:** ~60 minutos  
**Público objetivo:** Estudiantes de 12 a 17 años sin experiencia en programación  
**Prerrequisitos:** Ninguno  
**Herramientas necesarias:** ¡Solo tu navegador web!  
**📂 Repositorio de código fuente:** https://github.com/upc-202520-1asi0730-7432-MarkupMasters/Course-Plan

---

## Secuencia de la Lección

### Lección 1: ¿Qué es el desarrollo web? (5 minutos)
- **Descripción:** Presentación general sobre qué son los sitios web, cómo funcionan y qué roles cumplen HTML y CSS.
- **Enlace:** https://www.youtube.com/watch?v=example-link1
- **Consejos clave:**  
  - Los sitios web combinan **estructura (HTML)** y **estilos (CSS)**.  
  - Todo contenido visual comienza como código.  
- **Práctica:** *(CodePen o Replit según el equipo)*

---

### Lección 2: Introducción a HTML (10 minutos)  
**Responsable: Manuel Ignacio Tumi Oliden**

- **Descripción:**  
  Explicación de la estructura base de un archivo HTML: etiquetas, elementos y atributos.  
  Se construye una primera página funcional desde cero usando **Replit** y una plantilla inicial.  
  La lección incluye una demostración práctica en vivo y un reto final para los estudiantes.

- **Enlace del video:** https://www.youtube.com/watch?v=example-link2  
- **Práctica en Replit:**  
  https://replit.com/~ *(Starter que los estudiantes completan)*  

- **Código inicial utilizado en la exposición:**
```html
<!DOCTYPE html>
<html lang="es">
<head>
   <title>Mi primera opagina HTML</title>
</head>
<body>
  <h1>Titulo principal de la página</h1>
  <h2>Seccion Importante</h2>
  <h3>Subsección Importante</h3>
  <p>Este es un párrafo de ejemplo dentro de mi página. Aqui yo puedo escribir una idea completa. Me gustan los deportes, las películas,etc</p>
  <p>Este es el segundo párrado, esto está separado para mantener un orden</p>
</body>
</html>

```
- **Práctica**: [Clic para programar](https://replit.com/@ManuelTumi/HTML-CSS-JS-Static#index.html )
- **Reto:**
- Cambiar el título.
- Agregar tu nombre como ```<h2>```.
- Agregar un párrafo con algo que te guste.
### Lección 3: Añadir más elementos HTML (12 minutos)
**Responsable: Ysaac Ligorio Villanueva Andrade**
- **Descripción**: En esta lección aprenderás a enriquecer tus páginas web utilizando elementos HTML esenciales que permiten organizar mejor la información y hacerla más visual e interactiva. Exploraremos cómo usar listas ordenadas y desordenadas para estructurar contenido, cómo insertar imágenes dentro de una página, y cómo crear enlaces tanto externos como internos para mejorar la navegación. También practicaremos la jerarquía de títulos y el uso correcto de párrafos para construir una estructura clara y atractiva. Al finalizar, serás capaz de crear secciones completas, agregar imágenes, añadir listas de pasos o elementos, y conectar páginas o secciones mediante enlaces.
- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=example-link3)
- **Consejos clave**: 
- ```<ul>``` listas
- ```<a>``` enlaces
- ```<img>``` imágenes
- **Práctica**: [Clic para programar]( https://replit.com/~ ) 👈 **¡Comienza al instante!**
- **Código inicial utilizado en la exposición:**
```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Más Elementos HTML</title>
</head>
<body>

<h1 id="inicio">Titulo de principal</h1>
<h2>Seccion importante</h2>
<h3>Subseccion o detalle</h>

<p> este es un parrafo de ejemplo</p>
<p>este es otro parrafo de ejemplo</p>


<h2> Lista de compras</h2>
<ul>
  <li>Pan</li>
  <li>Huevo</li>
  <li>Carne</li>
</ul>

<h2>Pasos para hacer cafe</h2>
<ol>
  <li>Hervir agua</li>
  <li>Agregar cafe a la taza</li>
  <li>Verter el agua caliente</li>
  <li>Mezclar y servir</li>
</ol>

  
<h2>Mi imagen</h2>
<img src="www.miimagen/gatitos.com" alt="imagen de ejemplo" width="200">


<h2>Enlaces</h2>
<a href="https://www.google.com" target="_blank">Visitar Google</a>
<a href="#inicio">Volver al inicio de la pagina</a>
  
</body>
</html>
```
### Lección 4: Introducción a CSS (12 minutos)
**Responsable: Carlos Alberto Lopez Goitia**

- **Descripción**: En esta lección vinculamos un archivo CSS a nuestro HTML y aplicamos estilos base: colores, tipografías, espaciados, estados `:hover` / `:focus-visible`, listas e imágenes.

- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=682UD1dy1Bs)

- **Consejos clave**: 
- `<link rel="stylesheet" href="style.css">`  conectar CSS
- `body { background-color: #0f172a; color: #e2e8f0; }`  color y tipografía
- `h1, h2, h3 { margin: 0 0 12px; }` · `p { max-width: 65ch; }`  jerarquía y legibilidad
- `a:hover { background-color: #1f2a41; }` · `a:focus-visible { outline: 2px solid #60a5fa; }`  interacción y accesibilidad
- `* { box-sizing: border-box; }`  tamaños predecibles

- **Código inicial utilizado en la lección:**
```html
<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Introducción a CSS</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
</head>

<body>
  <h1 id="inicio">Mi primera página con CSS</h1>
  <h2>Sección importante</h2>
  <h3>Subsección o detalle</h3>

  <p>
    Esta página conecta un archivo <strong>style.css</strong> para controlar colores,
    tipografías y espaciados. Todo el diseño vive fuera del HTML.
  </p>

  <p>
    Observa cómo el CSS ajusta márgenes, el ancho de imágenes y el comportamiento de los
    enlaces al pasar el mouse o navegar con teclado.
  </p>

  <h2>Lista de compras</h2>
  <ul>
    <li>Pan</li>
    <li>Leche</li>
    <li>Huevos</li>
  </ul>

  <h2>Pasos para hacer café</h2>
  <ol>
    <li>Hervir agua</li>
    <li>Agregar café a la taza</li>
    <li>Verter el agua caliente</li>
    <li>Mezclar y servir</li>
  </ol>

  <h2>Imagen de ejemplo</h2>
  <!-- Coloca tu imagen en /img y ajusta el nombre del archivo -->
  <img src="img/cafe.jpg" alt="Taza de café" width="360">

  <h2>Enlaces</h2>
  <p>
    <a href="https://developer.mozilla.org/es/docs/Web/CSS" target="_blank" rel="noopener">Documentación CSS (MDN)</a>
    &nbsp;·&nbsp;
    <a href="#inicio">Volver al inicio</a>
  </p>
</body>
</html>
```
```css
* {
  box-sizing: border-box;
}

body {
  background-color: #0f172a;
  color: #e2e8f0;
  margin: 0;
  font-family: system-ui, Arial, sans-serif;
  line-height: 1.65;
  padding: 24px;
}

h1, h2, h3 {
  margin: 0 0 12px;
}

p {
  margin: 0 0 14px;
  max-width: 65ch;
}

ul, ol {
  padding-left: 24px;
  margin: 0 0 16px;
}

li {
  margin: 4px 0;
}

img {
  display: block;
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 6px 18px rgba(0, 0, 0, .35);
  margin: 8px 0 16px;
}

a {
  color: #93c5fd;
  text-decoration: none;
  border-bottom: 1px dashed rgba(147, 197, 253, 0.5);
  transition: all .15s ease;
}

a:hover {
  color: #bfdbfe;
  background-color: #1f2a41;
  border-bottom-color: transparent;
}

a:focus-visible {
  outline: 2px solid #60a5fa;
  outline-offset: 3px;
  border-bottom-color: transparent;
}

#inicio {
  scroll-margin-top: 16px;
}
```
- **Proyecto Final**: **Lección 4 – Introducción a CSS.** Estiliza tu página con colores, fuentes, márgenes y estados `:hover`/`:focus-visible` usando `style.css`. [Abrir Replit](https://replit.com/@matadorxdm/HTML-CSS-JS-Static)

- **Reto:**
  - Cambia el **color de fondo** y la **tipografía** en `body`.
  - Crea un `:hover` distinto para `a` (subrayado + cambio de color).
  - Añade `:focus-visible` para accesibilidad.
  - Reemplaza la imagen por una propia en `/img` y actualiza `src`.
  - Ajusta **márgenes** y verifica **contraste**.

- **Práctica**: [Clic para programar](https://replit.com/@replit/HTML-CSS-JS-Static?v=1#index.html)



### Lección 5: Crear una página web sencilla (15 minutos)
**Responsable: Schneider Carlos Alberto Delgado Carrasco**
- **Descripción**: En esta lección aplicamos HTML y CSS para darle estilo a una página simple: centrado, colores con buen contraste, tipografías legibles, esquinas redondeadas, sombras y un botón con hover. Al final tendrás una tarjeta de perfil lista para personalizar con tu nombre, foto, hobbies y enlace favorito.

- **Enlace**: [Ver la lección](https://www.youtube.com/watch?v=Vx0Xop0ZgM4)

- **Consejos clave**: 
- ```<link rel="stylesheet" href="style.css">``` conectar CSS
- ```.card { margin: 40px auto; }```  centrar
- ```border-radius``` · ```box-shadow``` · ```line-height```
- ```.btn:hover { … }```  interacción

- **Código inicial utilizado en la lección:**
```html
<!DOCTYPE html>
<html lang = "es">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Mi perfil</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
</head>

<body>
  <main class="card">
    <img
      src="img/perfil.webp"
      alt="Foto de perfil"
      class="avatar">

    <h1>Juan Carlos</h1>
    <h2>Estudiante de secundaria</h2>

    <p class="bio">
      Me gusta la tecnología, los videojuegos y aprender cosas nuevas.
      Este es mi primer sitio web hecho con HTML y CSS.
    </p>

    <h3>Mis hobbies</h3>
    <ul class="hobbies">
      <li> 🎮 Jugar videojuegos</li>
      <li> 📚 Leer</li>
      <li> 🎵 Escuchar música</li>
    </ul>

    <a class="btn" href="#" target="_blank">
      Ver más sobre mí
    </a>
  </main>
</body>
</html>

```

```css
body {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
  background-color: #0f172a;
  color: #e5e7eb;
  margin: 0;
  padding: 20px;
}

.card{
  max-width: 400px;
  margin: 40px auto;
  padding: 24px;
  background-color: #111827;
  border-radius: 16px;
  border: 1px solid #1f2937;
  text-align: center;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.4)
}

.avatar{
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid #38bdf8;
}

h1{
  margin: 16px 0 4px;
  font-size: 26px;
}

h2{
  margin: 0 0 16px;
  font-size: 16px;
  color: #9ca3af;
}

.bio{
  font-size: 14px;
  line-height: 1.6;
  margin-bottom: 16px;
}

.hobbies{
  list-style: none;
  padding: 0;
  margin: 0 0 16px;
}

.hobbies li {
  margin: 4px 0;
}

.btn{
  display: inline-block;
  padding: 10px 18px;
  border-radius: 999px;
  text-decoration: none;
  background-color: #38bdf8;
  color: #0f172a;
  font-weight: 600;
  transition: trasform 0.2s ease, box-shadow 0.2s ease;
}

.btn:hover{
  transform: translateY(-2px);
  box-shadow: 0 6px 16px rgba(56, 189, 248, 0.4);
}

```
- **Proyecto Final**: [Crea tu Perfil]( https://replit.com/join/tfpplvzauc-schneider0104dc )

- **Reto:**
- Cambia el nombre y la descripción por los tuyos.
- Cambia la imagen por una foto o un personaje que te guste.
- Edita los hobbies.
- Pon un enlace real en el botón.

- **Práctica**: [Clic para programar](https://replit.com/@replit/HTML-CSS-JS-Static?v=1#index.html )
### Lección 6: Consejos y Próximos Pasos (10 minutos)
- **Descripción**: Mejores prácticas, errores comunes y dónde aprender más.
- **Enlace**: [Ver Lección](https://www.youtube.com/watch?v=example-link6)
- **Consejos Clave**: Valida el código, explora la Documentación Web de MDN.
- **Comparte tu Trabajo**: [Envía tu Creación](https://forms.gle/your-form)
## Recursos Adicionales
- **Código Fuente Completo**: [Repositorio de GitHub](https://github.com/upc-202520-1asi0730-7432-MarkupMasters/Course-Plan)
- **Todas las Actividades Prácticas**:
## Recursos Adicionales

| Lección | Actividad                         | Editor Online / Enlace |
|--------|------------------------------------|--------------------------|
| 1      | Explorar sitios web                | https://replit.com/~ |
| 2      | Crear página HTML básica           | https://replit.com/~ |
| 3      | Añadir imágenes, enlaces y listas  | https://replit.com/~ |
| 4      | Aplicar estilos básicos con CSS    | https://replit.com/@matadorxdm/HTML-CSS-JS-Static#style.css
| 5      | Crear página de perfil personal    | https://replit.com/join/tfpplvzauc-schneider0104dc |
  
- Cuestionario: [Pon a prueba tus conocimientos](https://forms.gle/your-quiz)
- Compartir: #WebDevBeginners
**¡Gracias por completar el curso!**
---
## 👥 Elaboración
Universidad Peruana de Ciencias Aplicadas
Carrera de Ingeniería de Software
Período 202520
Curso: 1ASI0730 Aplicaciones Web
NRC 7432
**Nombre del equipo**: MarkupMasters
**Líder del equipo**: Fabricio Samir Vega Coronado
**Integrantes del equipo**: Carlos Alberto Lopez Goitia, Manuel Ignacio Tumi Oliden, Schneider Carlos Alberto Delgado Carrasco & Ysaac Ligorio Villanueva Andrade
**Fecha de entrega**: 14/11/25

# Participant Performance Report  
**Startup:** MarkupMasters  
**NRC:** 7432  
**Entrega:** Trabajo Complementario – Course Plan  
**Team Leader:** Fabricio Samir Vega Coronado

| Ítem | Estudiante                                   | Responsabilidades                                                                                                              | Cumplió a tiempo | Cumplió a destiempo | Cumplió parcialmente | No cumplió | Calificación (20/16/13/07/00) |
|------|----------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|------------------|----------------------|------------------------|------------|-------------------------------|
| 1    | Fabricio Samir Vega Coronado *(Líder)*       | Lección 1 y 6 (Introducción, Cierre, Consejos). Coordinación general. Informe del proyecto. Revisión final del documento.       | X                |                      |                        |            | 20                            |
| 2    | Manuel Ignacio Tumi Oliden   | Lección 2 (Estructura HTML básica). Diseño de la estructura general del Course Plan en Markdown. Resumen del curso.             | X                |                      |                        |            | 20                            |
| 3    | Carlos Alberto Lopez Goitia  | Lección 3 (Más elementos HTML). Gestión y creación del repositorio GitHub: carpetas, README.md, subida de código.               | X                |                      |                        |            | 20                            |
| 4    | Schneider Carlos Alberto Delgado Carrasco  | Lección 4 (Introducción a CSS). Preparación de ejemplos online en CodePen/JSFiddle y obtención de enlaces directos. | X | | | | 20 |
| 5    | Ysaac Ligorio Villanueva Andrade  | Lección 5 (Estilizando la página y Proyecto final). Edición de video (calidad de audio/video, texto en pantalla, anotaciones). | X | | | | 20 |
