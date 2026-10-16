# Proyecto 02: Explorando la cultura en la web

Este repositorio contiene el código fuente y los recursos del sitio web informativo desarrollado para presentar los resultados de la recopilación de datos de los asistentes del evento cultural **"Chancho Fest 2026"** (Parque Samanes). 

El sitio se construye a partir de una plantilla HTML5 UP personalizada con contenido propio. Los datos se obtuvieron durante la visita al evento el día 4 de octubre, fecha en la que se realizaron las encuestas *in situ*. La información cuantitativa y cualitativa (basada en una muestra de 5 asistentes) proviene del archivo de análisis: **"Encuesta para los asistentes del Festival Gastronómico _Chancho Fest 2026_(1-5).xlsx"**.

## 1. Análisis y Organización del Contenido

Para garantizar una navegación lógica y una excelente experiencia de usuario (UX), el sitio web se ha estructurado en un formato *One-Page* (de una sola página), dividido en las siguientes cinco secciones secuenciales:

*   **Sección 1: Inicio / Acerca del Estudio**
    *   **Propósito y contenido:** Contextualizar al visitante sobre la naturaleza del evento, la fecha y el objetivo de la investigación. Se incluye como dato destacado que el **80% respondió que sí** a la pregunta *"¿Recomendaría asistir a este festival a sus amigos o familiares?"* como gancho inicial.
    *   **Justificación:** Todo reporte de datos necesita una introducción clara para que el usuario entienda el alcance y la relevancia de la información.
*   **Sección 2: El Evento en Cifras (Resultados Cuantitativos)**
    *   **Propósito y contenido:** Visualizar de manera directa los datos de las preguntas cerradas (80% de satisfacción, 80% considera precios accesibles, 60% asistencia primeriza, 60% se enteró por amigos).
    *   **Justificación:** Los usuarios escanean visualmente la web; presentar las estadísticas duras al principio y con elementos visuales capta la atención inmediatamente.
*   **Sección 3: Motivos de Visita y Experiencia Gastronómica**
    *   **Propósito y contenido:** Profundizar en las respuestas abiertas sobre las motivaciones personales (compartir en familia) y destacar lo positivo de la organización (variedad de locales, platillos y abundancia de mesas).
    *   **Justificación:** Humaniza los datos presentados en la sección anterior, dando voz a la experiencia real de los asistentes.
*   **Sección 4: Impacto Local y Comunitario**
    *   **Propósito y contenido:** Destacar el valor social y económico del evento, resaltando cómo une a la comunidad, crea lazos y da ventas/reconocimiento a los emprendedores locales.
    *   **Justificación:** Responde a la necesidad de evaluar el impacto cultural y económico de la actividad en la ciudad.
*   **Sección 5: Oportunidades de Mejora**
    *   **Propósito y contenido:** Exponer las críticas constructivas identificadas (exceso de calor) junto con las soluciones sugeridas por el público (carpas, mayor espacio, mejor decoración).
    *   **Justificación:** Otorga objetividad e imparcialidad al estudio, mostrando no solo los aspectos positivos, sino también los puntos de fricción para futuras ediciones.

## 2. Análisis comparativo de plantillas

Durante la primera semana de trabajo (*sprint*) fue necesario elegir una plantilla base sobre la cual construir el sitio. Antes de decidir, se revisaron tres opciones disponibles en [HTML5 UP](https://html5up.net), realizando una lectura superficial de la estructura del encabezado, número de secciones, menú de navegación, tipografías, paleta de colores y comportamiento en distintos tamaños de pantalla.

### Plantillas evaluadas
1.  **[Prologue](https://html5up.net/prologue):** Pensada para portafolios personales. Presenta una barra lateral fija. Su punto fuerte es que el menú siempre está visible, pero ese mismo elemento lateral obliga a reservar espacio en pantallas pequeñas, dificultando la lectura de datos.
2.  **[Verti](https://html5up.net/verti):** Orientada a páginas corporativas y organizada en bloques horizontales a ancho completo. Ofrece una navegación clara, pero su cantidad de bloques, páginas múltiples y estilos la vuelve algo más pesada de personalizar.
3.  **[Miniport](https://html5up.net/miniport):** Plantilla minimalista de una sola página, dividida en pocas secciones apiladas verticalmente. Fue diseñada específicamente para transmitir un mensaje corto y directo sin necesidad de varias páginas.

### Aspectos comunes evaluados
Las tres plantillas compartían características aptas para el proyecto:
*   **Estructura de menú + secciones:** Permiten personalización de contenido propio.
*   **Navegación intuitiva:** El usuario siempre sabe en qué parte del sitio se encuentra.
*   **Diseño adaptable (*Responsive*):** Se adaptan a distintos tipos de dispositivos (escritorio, tableta y celular), reordenando columnas y apilando bloques.
*   **Paleta de colores propia:** Proveen una estética coherente desde el inicio.

## 3. Selección y justificación de la plantilla

Se seleccionó la plantilla **[Miniport](https://html5up.net/miniport)** por su practicidad, simplicidad y facilidad de modificación técnica durante el *sprint*:

*   **Todo en una misma sección (One-Page / Storytelling):** El contenido se organiza en una sola página. No es necesario gestionar rutas ni enlaces externos, lo que permite que el usuario consuma el reporte como una historia continua mediante *scroll*.
*   **Sin cambios bruscos en el menú móvil:** En dispositivos móviles, la barra de navegación se mantiene de forma compacta y estable con respecto a la versión de escritorio, mejorando drásticamente la experiencia de uso (UX).
*   **Curva de aprendizaje baja:** Al ser la más sencilla arquitectónicamente, permitió concentrar el esfuerzo del *sprint* en el análisis del contenido y la personalización, en lugar de lidiar con la estructura técnica del sitio.

## 4. Referencias

*   **Datos y encuestas:**
    *   [Resumen de las respuestas de encuesta realizada a asistentes del Festival gastronómico "Chancho Fest 2026"](https://forms.cloud.microsoft/Pages/AnalysisPage.aspx?AnalyzerToken=yNiUQeBtZyCambhiOltvicKPdZT7u3iZ&id=r4yvt9iDREaFrjF8VFIjwS85X59c6IFHpmtwJKN3iTdUNklST1dJUUxRRjkyUFdYWEQ4UFRDS1RXSC4u)
*   **Información sobre el evento:**
    *   [Chancho Fest 2026 - Publicación Oficial (Instagram)](https://www.instagram.com/p/Dd7Cdw8Itaw/)
    *   [Chancho Fest 2026 llega a Guayaquil con gastronomía, música y entrada gratuita (Entretenidos EC)](https://entretenidosec.com/chancho-fest-2026-llega-a-guayaquil-con-gastronomia-musica-y-entrada-gratuita/)
*   **Plantillas consideradas:**
    *   [Prologue - HTML5 UP](https://html5up.net/prologue)
    *   [Verti - HTML5 UP](https://html5up.net/verti)
    *   [Miniport - HTML5 UP](https://html5up.net/miniport)