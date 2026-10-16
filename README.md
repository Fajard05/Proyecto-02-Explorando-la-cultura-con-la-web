# Proyecto-02-Explorando-la-cultura-con-la-web

Explorando la cultura con la web: sitio informativo construido a partir de una plantilla HTML5 UP, personalizada con contenido propio del proyecto.

---

## Comparación de plantillas y decisiones tomadas durante el sprint

Durante la primera semana de trabajo (sprint) fue necesario elegir una plantilla base sobre la cual construir el sitio. Antes de decidir, se revisaron tres opciones disponibles en [HTML5 UP](https://html5up.net), un repositorio de plantillas HTML5/CSS gratuitas y de código abierto, y se realizó una lectura superficial de los elementos que compone cada una de las páginas: estructura del encabezado, número de secciones, menú de navegación, tipografías, paleta de colores y comportamiento en distintos tamaños de pantalla.

### Plantillas evaluadas

1. **[Prologue](https://html5up.net/prologue)**
   Plantilla de una sola página pensada para portafolios personales. Presenta una barra lateral fija con el nombre y el menú de secciones, y el contenido se despliega en un panel a la derecha. Su punto fuerte es que el menú siempre está visible, pero ese mismo elemento lateral obliga a reservar espacio en pantallas pequeñas.

2. **[Verti](https://html5up.net/verti)**
   Plantilla orientada a páginas corporativas o de producto, organizada en bloques horizontales a ancho completo (encabezado, hero, características, testimonios, precios, pie de página). Ofrece una navegación clara y más de una página, aunque su cantidad de bloques y estilos la vuelve algo más pesada de personalizar.

3. **[Miniport](https://html5up.net/miniport)** ✅ *(elegida)*
   Plantilla minimalista de una sola página, dividida en pocas secciones apiladas verticalmente (inicio, trabajo, portafolio y contacto). Fue diseñada específicamente para transmitir un mensaje corto y directo sin necesidad de varias páginas.

### Aspectos comunes evaluados

Las tres plantillas comparten características que las hacen aptas para el proyecto:

- **Estructura de menú + secciones:** todas presentan un menú de navegación acompañado de varias secciones listas para ser personalizadas con contenido propio.
- **Navegación intuitiva:** en cualquiera de las tres es fácil de entender y seguir el hilo de lectura; el usuario siempre sabe en qué parte del sitio se encuentra y a dónde puede ir.
- **Diseño adaptable:** las tres son *responsive*, es decir, su diseño se adapta a distintos tipos de dispositivos (escritorio, tableta y celular) y realiza ciertas modificaciones —reordenar columnas, reducir tamaños de fuente, apilar bloques— para acomodarse al ancho disponible.
- **Paleta de colores propia:** cada plantilla trae una gama de colores característica que define su identidad visual desde el inicio, lo que permite empezar a trabajar con una estética coherente y ajustarla después al proyecto.

### Decisión final

Se escogió **[Miniport](https://html5up.net/miniport)** por su practicidad y simplicidad, y por su alta facilidad a la hora de modificarla:

- **Todo en una misma sección:** el contenido se organiza en una sola página con secciones cortas, por lo que no es necesario gestionar rutas, enlaces entre páginas ni un nivel de complejidad adicional.
- **Sin cambios bruscos en el menú móvil:** en dispositivos móviles la barra de navegación se mantiene de forma compacta y estable, sin presentar un cambio brusco con respecto a la versión de escritorio, lo que mejora la experiencia de uso.
- **Curva de aprendizaje baja:** al ser la más sencilla de las tres, permitió concentrar el esfuerzo del sprint en el contenido y la personalización, en lugar de en la estructura del sitio.

A partir de esta decisión, se continuó con la personalización de `index.html`, los estilos de `assets/css` y los scripts de `assets/js` incluidos en la plantilla.
