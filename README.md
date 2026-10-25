# ESCUELA SUPERIOR POLITÉCNICA DEL LITORAL
## FACULTAD DE INGENIERÍA EN ELECTRICIDAD Y COMPUTACIÓN

**Fecha:** 23 de octubre de 2026

**Materia:** Desarrollo de Aplicaciones Web y Móviles

**Código:** SOFG1006

**Proyecto:** Proyecto 02: Explorando la cultura en la web

**Estudiantes:** Angel Fajardo, Hillary Merino

---

### Contenido
1. [Análisis y Organización del Contenido](#1-análisis-y-organización-del-contenido)
2. [Análisis comparativo de plantillas](#2-análisis-comparativo-de-plantillas)
3. [Selección y justificación de la plantilla](#3-selección-y-justificación-de-la-plantilla)
4. [Diseño](#4-diseño)
5. [Implementación](#5-implementación)
6. [Despliegue](#6-despliegue)
7. [Referencias](#7-referencias)

---

### 1. Análisis y Organización del Contenido

Este repositorio contiene el código fuente y los recursos del sitio web informativo desarrollado para presentar los resultados de la recopilación de datos de los asistentes del evento cultural **"Chancho Fest 2026"** (Parque Samanes). 

El sitio se construye a partir de una plantilla HTML5 UP personalizada con contenido propio. Los datos se obtuvieron durante la visita al evento el día 3 de octubre, fecha en la que se realizaron las encuestas *in situ*. La información cuantitativa y cualitativa (basada en una muestra de 5 asistentes) se obtuvo de: [Resumen de las respuestas de encuesta realizada a asistentes del Festival gastronómico "Chancho Fest 2026"](https://forms.cloud.microsoft/Pages/AnalysisPage.aspx?AnalyzerToken=yNiUQeBtZyCambhiOltvicKPdZT7u3iZ&id=r4yvt9iDREaFrjF8VFIjwS85X59c6IFHpmtwJKN3iTdUNklST1dJUUxRRjkyUFdYWEQ4UFRDS1RXSC4u).

Para garantizar una navegación lógica y una excelente experiencia de usuario (UX), el sitio web se ha estructurado en un formato *One-Page* (de una sola página), dividido en las siguientes cinco secciones secuenciales:

- **Sección 1: Inicio / Acerca del Estudio**
  * **Propósito:** Contextualizar al visitante sobre la naturaleza del evento ("Chancho Fest 2026" en Parque Samanes) y el objetivo de la investigación (recopilación de datos mediante encuestas *in situ* realizadas el 4 de octubre).
  * **Justificación:** Todo reporte de datos necesita una introducción clara para que el usuario entienda el alcance y la relevancia de la información que está a punto de leer.
- **Sección 2: El Evento en Cifras (Resultados Cuantitativos)**
  * **Propósito:** Visualizar de manera directa los datos de las preguntas cerradas (ej. 80% de satisfacción, 60% de asistencia primeriza).
  * **Justificación:** Los usuarios escanean visualmente la web; presentar las estadísticas duras al principio y con elementos visuales capta la atención inmediatamente.
- **Sección 3: Motivos de Visita y Experiencia Gastronómica**
  * **Propósito:** Profundizar en las respuestas abiertas sobre las motivaciones personales (compartir en familia) y la valoración de la organización (variedad de locales y abundancia de mesas).
  * **Justificación:** Humaniza los datos presentados en la sección anterior, dando voz a la experiencia real de los asistentes.
- **Sección 4: Impacto Local y Comunitario**
  * **Propósito:** Destacar la percepción social y económica del evento, resaltando cómo ayuda a los emprendedores locales y une a la comunidad.
  * **Justificación:** Responde a la necesidad de evaluar el impacto cultural y económico de la actividad en la ciudad.
- **Sección 5: Oportunidades de Mejora**
  * **Propósito:** Exponer las críticas constructivas y problemas identificados (exceso de calor) junto con las soluciones sugeridas por el público (carpas, mayor espacio).
  * **Justificación:** Otorga objetividad e imparcialidad al estudio, mostrando no solo los aspectos positivos, sino también los puntos de fricción para futuras ediciones.

---

### 2. Análisis comparativo de plantillas

Durante la primera semana de trabajo (sprint) fue necesario elegir una plantilla base sobre la cual construir el sitio. Antes de decidir, se revisaron tres opciones disponibles en [HTML5 UP](https://html5up.net), un repositorio de plantillas HTML5/CSS gratuitas y de código abierto, y se realizó una lectura superficial de los elementos que compone cada una de las páginas: estructura del encabezado, número de secciones, menú de navegación, tipografías, paleta de colores y comportamiento en distintos tamaños de pantalla.

#### Plantillas evaluadas
1. **[Prologue](https://html5up.net/prologue):** Pensada para portafolios personales. Presenta una barra lateral fija. Su punto fuerte es que el menú siempre está visible, pero ese mismo elemento lateral obliga a reservar espacio en pantallas pequeñas, dificultando la lectura de datos.
2. **[Verti](https://html5up.net/verti):** Orientada a páginas corporativas y organizada en bloques horizontales a ancho completo. Ofrece una navegación clara, pero su cantidad de bloques, páginas múltiples y estilos la vuelve algo más pesada de personalizar.
3. **[Miniport](https://html5up.net/miniport):** Plantilla minimalista de una sola página, dividida en pocas secciones apiladas verticalmente. Fue diseñada específicamente para transmitir un mensaje corto y directo sin necesidad de varias páginas.

#### Aspectos comunes evaluados
Las tres plantillas compartían características aptas para el proyecto:
- **Estructura de menú + secciones:** Permiten personalización de contenido propio.
- **Navegación intuitiva:** El usuario siempre sabe en qué parte del sitio se encuentra.
- **Diseño adaptable (*Responsive*):** Se adaptan a distintos tipos de dispositivos (escritorio, tableta y celular), reordenando columnas y apilando bloques.
- **Paleta de colores propia:** Proveen una estética coherente desde el inicio.

---

### 3. Selección y justificación de la plantilla

Se seleccionó la plantilla **[Miniport](https://html5up.net/miniport)** por su practicidad, simplicidad y facilidad de modificación técnica durante el *sprint*:

- **Todo en una misma sección:** el contenido se organiza en una sola página con secciones cortas, por lo que no es necesario gestionar rutas, enlaces entre páginas ni un nivel de complejidad adicional.
- **Sin cambios bruscos en el menú móvil:** en dispositivos móviles la barra de navegación se mantiene de forma compacta y estable, sin presentar un cambio brusco con respecto a la versión de escritorio, lo que mejora la experiencia de uso.
- **Curva de aprendizaje baja:** al ser la más sencilla de las tres, permite concentrar el esfuerzo del sprint en el contenido y la personalización, en lugar de en la estructura del sitio.

---

### 4. Diseño

La interfaz del proyecto fue diseñada basándose en principios heurísticos y de usabilidad para garantizar una experiencia centrada en el usuario:

*   **Paleta de Colores:** Se aplicó una paleta de colores cálidos y neutros, descartando los azules tecnológicos originales de la plantilla. Se utilizó el color coral (`#ff7f50`) como acento para hipervínculos y botones, el cual transmite energía y se alinea con la temática gastronómica. Para los fondos, se optó por un minimalismo estético empleando colores neutros (`#F9F6EE`, `#FFFDF0`, `#FFF4F0`) que mejoran el contraste y la legibilidad sin abrumar al usuario.
*   **Tipografía y Legibilidad:** Se ajustaron los tamaños y el interlineado (`1.5`) de los párrafos para reducir la fatiga visual. Los títulos principales se destacaron con un tono oscuro (`#61301E`) y un mayor grosor para establecer una clara jerarquía visual. 
*   **Señales Exógenas:** Se implementaron "datos clave" con bordes llamativos (ej. `#4FFFDC`) y fondos contrastantes para dirigir la atención inmediata del lector hacia las estadísticas más importantes sin que tenga que buscarlas.
*   **Consistencia y Retroalimentación:** Todos los elementos interactivos, como los botones redondeados, responden de manera consistente al pasar el cursor (*hover*) o al hacer clic (*active*), cambiando ligeramente su tono para ofrecer retroalimentación inmediata sobre el estado del sistema.

---

### 5. Implementación

El proyecto se implementó modificando los archivos base de la plantilla Miniport:

*   **HTML (`index.html`):** 
    *   Se estructuró el contenido en cinco secciones semánticas utilizando las etiquetas `<article>` y `<section>`.
    *   Se reemplazaron los textos de relleno (Lorem Ipsum) con los hallazgos reales de la investigación de campo del "Chancho Fest".
    *   Se implementaron imágenes representativas en formato `.jpg` y `.png` dentro de las tarjetas de contenido para ilustrar visualmente las métricas y áreas de mejora.
    *   Se ajustaron los hipervínculos de navegación superior e inferior (`#inicio`, `#cifras`, etc.) para permitir un desplazamiento fluido a lo largo del sitio *One-Page*.

*   **CSS (`main.css`):**
    *   Se ajustaron las variables globales de color y tipografía para aplicar la nueva identidad visual.
    *   Se modificaron las clases de los contenedores globales (`.container`, `.contenido-centrado`) expandiendo su ancho a `1500px` para aprovechar mejor el espacio en pantallas grandes.
    *   Se añadieron reglas personalizadas al final de la hoja de estilos para manipular los fondos de los banners principales (`.wrapper.banner-inicio`, `.wrapper.banner-impacto`), aplicándoles gradientes oscuros sobre las imágenes para garantizar un óptimo contraste con el texto en blanco.
    *   Se redefinió la apariencia de los botones (`border-radius: 50px`) y sus estados interactivos (`:hover`, `:active`) removiendo las sombras excesivas en favor de un diseño más plano y moderno.
    *   Se depuró la hoja de estilos: se eliminaron las reglas que ningún elemento del sitio utilizaba (formularios, tablas, iconos, copyright, variantes de grid y sus media queries), así como los duplicados y los `!important` innecesarios. El resultado se verificó comparando los estilos calculados de las 179 elementos del DOM antes y después, sin diferencias fuera del botón reestilizado.
    *   Se eliminó la dependencia de FontAwesome: el `@import` de `fontawesome-all.min.css` y la carpeta `assets/webfonts/` (aproximadamente 2,9 MB) ya que ningún icono se usaba en el sitio.
    *   El botón "Volver al Inicio" de la sección 5 ahora reutiliza las clases de la plantilla (`class="button alt"`) en lugar de una regla escrita a mano.
    *   Se añadió un media query móvil (`max-width: 736px`) para el `h1` de `.wrapper.banner-inicio`, cuyo `font-size: 5.5em` ganaba por especificidad al `h1` móvil y desbordaba en pantallas de 360 px.

*   **Nota sobre Sass:** los estilos viven directamente en `assets/css/main.css`. La carpeta `assets/sass/` fue eliminada porque contenía el Sass original de la plantilla Miniport (paleta azul `#43B3E0`, `h2` de `2em`), nunca sincronizado con la personalización del sitio; compilarlo habría revertido toda la identidad visual del proyecto.

---

### 6. Despliegue

El sitio web fue desarrollado y versionado inicialmente utilizando **GitHub Codespaces** como entorno de desarrollo en la nube, lo que permitió realizar el control de versiones y las pruebas preliminares de manera ágil mediante su terminal integrada. 

Para el paso a producción y garantizar un acceso público ininterrumpido, el despliegue final se configuró a través de **GitHub Pages**. El repositorio remoto sirve la rama principal de manera automática, permitiendo que el proyecto web esté siempre actualizado, estable y accesible a través de su URL oficial y permanente:

**Enlace al proyecto:** [https://fajard05.github.io/Proyecto-02-Explorando-la-cultura-con-la-web/](https://fajard05.github.io/Proyecto-02-Explorando-la-cultura-con-la-web/)

---

### 7. Referencias

- **Datos y encuestas:**
  * [Resumen de las respuestas de encuesta realizada a asistentes del Festival gastronómico "Chancho Fest 2026"](https://forms.cloud.microsoft/Pages/AnalysisPage.aspx?AnalyzerToken=yNiUQeBtZyCambhiOltvicKPdZT7u3iZ&id=r4yvt9iDREaFrjF8VFIjwS85X59c6IFHpmtwJKN3iTdUNklST1dJUUxRRjkyUFdYWEQ4UFRDS1RXSC4u)
- **Información sobre el evento:**
  * [Chancho Fest 2026 - Publicación Oficial (Instagram)](https://www.instagram.com/p/Dd7Cdw8Itaw/)
  * [Chancho Fest 2026 llega a Guayaquil con gastronomía, música y entrada gratuita (Entretenidos EC)](https://entretenidosec.com/chancho-fest-2026-llega-a-guayaquil-con-gastronomia-musica-y-entrada-gratuita/)
- **Plantillas consideradas:**
  * [Prologue - HTML5 UP](https://html5up.net/prologue)
  * [Verti - HTML5 UP](https://html5up.net/verti)
  * [Miniport - HTML5 UP](https://html5up.net/miniport)