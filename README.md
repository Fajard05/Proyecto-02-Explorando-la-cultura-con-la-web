# ESCUELA SUPERIOR POLITÉCNICA DEL LITORAL
## FACULTAD DE INGENIERÍA EN ELECTRICIDAD Y COMPUTACIÓN

**Fecha:** 16 de octubre de 2026

**Materia:** Desarrollo de Aplicaciones Web y Móviles

**Código:** SOFG1006

**Proyecto:** Proyecto 02: Explorando la cultura en la web

**Estudiantes:** Angel Fajardo, Hillary Merino

---

### Contenido
1. [Análisis y Organización del Contenido](#1-análisis-y-organización-del-contenido)
2. [Análisis comparativo de plantillas](#2-análisis-comparativo-de-plantillas)
3. [Selección y justificación de la plantilla](#3-selección-y-justificación-de-la-plantilla)
4. [Referencias](#4-referencias)

---

### 1. Análisis y Organización del Contenido

Este repositorio contiene el código fuente y los recursos del sitio web informativo desarrollado para presentar los resultados de la recopilación de datos de los asistentes del evento cultural **"Chancho Fest 2026"** (Parque Samanes). 

El sitio se construye a partir de una plantilla HTML5 UP personalizada con contenido propio. Los datos se obtuvieron durante la visita al evento el día 4 de octubre, fecha en la que se realizaron las encuestas *in situ*. La información cuantitativa y cualitativa (basada en una muestra de 5 asistentes) se obtuvo de: [Resumen de las respuestas de encuesta realizada a asistentes del Festival gastronómico "Chancho Fest 2026"](https://forms.cloud.microsoft/Pages/AnalysisPage.aspx?AnalyzerToken=yNiUQeBtZyCambhiOltvicKPdZT7u3iZ&id=r4yvt9iDREaFrjF8VFIjwS85X59c6IFHpmtwJKN3iTdUNklST1dJUUxRRjkyUFdYWEQ4UFRDS1RXSC4u).

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

### 4. Referencias

- **Datos y encuestas:**
  * [Resumen de las respuestas de encuesta realizada a asistentes del Festival gastronómico "Chancho Fest 2026"](https://forms.cloud.microsoft/Pages/AnalysisPage.aspx?AnalyzerToken=yNiUQeBtZyCambhiOltvicKPdZT7u3iZ&id=r4yvt9iDREaFrjF8VFIjwS85X59c6IFHpmtwJKN3iTdUNklST1dJUUxRRjkyUFdYWEQ4UFRDS1RXSC4u)
- **Información sobre el evento:**
  * [Chancho Fest 2026 - Publicación Oficial (Instagram)](https://www.instagram.com/p/Dd7Cdw8Itaw/)
  * [Chancho Fest 2026 llega a Guayaquil con gastronomía, música y entrada gratuita (Entretenidos EC)](https://entretenidosec.com/chancho-fest-2026-llega-a-guayaquil-con-gastronomia-musica-y-entrada-gratuita/)
- **Plantillas consideradas:**
  * [Prologue - HTML5 UP](https://html5up.net/prologue)
  * [Verti - HTML5 UP](https://html5up.net/verti)
  * [Miniport - HTML5 UP](https://html5up.net/miniport)