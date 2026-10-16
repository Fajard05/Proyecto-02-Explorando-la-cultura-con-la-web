# Proyecto-02-Explorando-la-cultura-con-la-web

Explorando la cultura con la web: sitio informativo sobre el **Festival Gastronómico Chancho Fest 2026** (Parque Samanes), que se construirá a partir de una plantilla HTML5 UP personalizada con contenido propio del proyecto.

---

## Organización del contenido

El sitio se estructurará en cinco secciones, cada una con un propósito claro y con datos provenientes de una muestra de **5 asistentes encuestados**. La información cuantitativa y cualitativa proviene del archivo **"Encuesta para los asistentes del Festival Gastronómico _Chancho Fest 2026_(1-5).xlsx"**.

**Sección 1: Inicio / Acerca del Estudio**

- *Propósito:* Dar la bienvenida y explicar el objetivo de la página.
- *Qué incluir:* Breve descripción del "Chancho Fest 2026" en Parque Samanes, fecha del evento, y mencionar que los datos provienen de una muestra de 5 asistentes encuestados. Además, se destacará que el **80% respondió que sí** a la pregunta *"¿Recomendaría asistir a este festival a sus amigos o familiares?"*.

**Sección 2: El Evento en Cifras**

- *Propósito:* Mostrar los resultados de las preguntas cerradas con gráficos (barras, pasteles) o números grandes.
- *Qué incluir:*
  - 80% de satisfacción general (buena experiencia).
  - 80% considera los precios accesibles.
  - 60% son asistentes primerizos.
  - 60% se enteró por amigos y 40% por redes sociales.

**Sección 3: Motivos de Visita y Experiencia Gastronómica**

- *Propósito:* Profundizar en las preguntas abiertas sobre qué atrajo a la gente y cómo lo pasaron.
- *Qué incluir:* El deseo de compartir con familia/amigos, el disfrute de la comida, y destacar lo positivo de la organización (variedad de locales, platillos y abundancia de mesas).

**Sección 4: Impacto en la Comunidad**

- *Propósito:* Destacar el valor social y económico del evento.
- *Qué incluir:* El 80% cree que ayuda a la economía local. Mencionar los comentarios sobre cómo une a la comunidad, crea lazos y da ventas/reconocimiento a los emprendedores locales.

**Sección 5: Oportunidades de Mejora**

- *Propósito:* Mostrar el lado crítico y constructivo de las entrevistas.
- *Qué incluir:* El problema identificado (hacía mucho calor) y las soluciones propuestas por el público (mayor espacio, mejor decoración y uso de carpas para evitar el sol).

---

## Análisis comparativo de plantillas

Durante la primera semana de trabajo (sprint) fue necesario elegir una plantilla base sobre la cual construir el sitio. Antes de decidir, se revisaron tres opciones disponibles en [HTML5 UP](https://html5up.net), un repositorio de plantillas HTML5/CSS gratuitas y de código abierto, y se realizó una lectura superficial de los elementos que compone cada una de las páginas: estructura del encabezado, número de secciones, menú de navegación, tipografías, paleta de colores y comportamiento en distintos tamaños de pantalla.

### Plantillas evaluadas

1. **[Prologue](https://html5up.net/prologue)**
   Plantilla de una sola página pensada para portafolios personales. Presenta una barra lateral fija con el nombre y el menú de secciones, y el contenido se despliega en un panel a la derecha. Su punto fuerte es que el menú siempre está visible, pero ese mismo elemento lateral obliga a reservar espacio en pantallas pequeñas.

2. **[Verti](https://html5up.net/verti)**
   Plantilla orientada a páginas corporativas o de producto, organizada en bloques horizontales a ancho completo (encabezado, hero, características, testimonios, precios, pie de página). Ofrece una navegación clara y más de una página, aunque su cantidad de bloques y estilos la vuelve algo más pesada de personalizar.

3. **[Miniport](https://html5up.net/miniport)**
   Plantilla minimalista de una sola página, dividida en pocas secciones apiladas verticalmente (inicio, trabajo, portafolio y contacto). Fue diseñada específicamente para transmitir un mensaje corto y directo sin necesidad de varias páginas.

### Aspectos comunes evaluados

Las tres plantillas comparten características que las hacen aptas para el proyecto:

- **Estructura de menú + secciones:** todas presentan un menú de navegación acompañado de varias secciones listas para ser personalizadas con contenido propio.
- **Navegación intuitiva:** en cualquiera de las tres es fácil de entender y seguir el hilo de lectura; el usuario siempre sabe en qué parte del sitio se encuentra y a dónde puede ir.
- **Diseño adaptable:** las tres son *responsive*, es decir, su diseño se adapta a distintos tipos de dispositivos (escritorio, tableta y celular) y realiza ciertas modificaciones —reordenar columnas, reducir tamaños de fuente, apilar bloques— para acomodarse al ancho disponible.
- **Paleta de colores propia:** cada plantilla trae una gama de colores característica que define su identidad visual desde el inicio, lo que permite empezar a trabajar con una estética coherente y ajustarla después al proyecto.

---

## Selección y justificación de la plantilla

Se escogió **[Miniport](https://html5up.net/miniport)** por su practicidad y simplicidad, y por su alta facilidad a la hora de modificarla:

- **Todo en una misma sección:** el contenido se organiza en una sola página con secciones cortas, por lo que no es necesario gestionar rutas, enlaces entre páginas ni un nivel de complejidad adicional.
- **Sin cambios bruscos en el menú móvil:** en dispositivos móviles la barra de navegación se mantiene de forma compacta y estable, sin presentar un cambio brusco con respecto a la versión de escritorio, lo que mejora la experiencia de uso.
- **Curva de aprendizaje baja:** al ser la más sencilla de las tres, permite concentrar el esfuerzo del sprint en el contenido y la personalización, en lugar de en la estructura del sitio.
