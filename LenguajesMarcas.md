# Guía de Estudio de Lenguajes de Marcas

## Repaso del Material de Origen

Esta sección cubre los conceptos clave presentados en los materiales de origen sobre lenguajes de marcas, centrándose en HTML, XML, CSS, y los fundamentos de JavaScript, SVG y Canvas.

## Lenguajes de Marcas: Clasificación y Características

### Clasificación
Comprender las diferentes categorías de lenguajes de marcas según su propósito (Presentación, Estilo, Datos, Ligero).

### Características
Conocer las propiedades fundamentales de los lenguajes de marcas: Simplicidad/Legibilidad, Extensibilidad y Portabilidad.

## SGML y XML

### SGML
Entender su papel como metalenguaje y precursor de otros lenguajes.

### XML
Comprender su definición como metalenguaje extensible, su objetivo principal (independencia de plataforma y aplicación), y sus características (Extensible, Versátil, Estructurado, Validable, Abierto, Sencillo). Identificar la diferencia clave con HTML en cuanto al significado de las etiquetas.

## HTML

### Introducción y Propósito
Reconocer HTML como el lenguaje de marcado principal para estructurar contenido web.

### Estructura Básica
Identificar las partes fundamentales de un documento HTML (Declaración `<!DOCTYPE>`, `<html>`, `<head>`, `<body>`).

### Etiquetas y Elementos
Comprender el concepto de etiqueta, su formato (`<tagname>`), y la diferencia entre etiquetas de apertura y cierre. Definir un elemento HTML (etiqueta de inicio, contenido, etiqueta de cierre). Identificar elementos vacíos (sin etiqueta de cierre).

### Elementos Básicos
Conocer la función de etiquetas comunes como `<html>`, `<head>`, `<body>`, `<h1>` a `<h6>`, `<p>`, `<br>`, `<hr>`.

### Atributos
Comprender el propósito de los atributos (información adicional) y la sintaxis general (`attribute="value"`). Familiarizarse con atributos como `lang` y `title`.

### Formato de Texto
Identificar las etiquetas y su función para dar formato al texto (`<b>`, `<i>`, `<big>`, `<small>`, `<s>`, `<strike>`, `<u>`, `<strong>`, `<em>`, `<mark>`, `<del>`, `<ins>`, `<sub>`, `<sup>`). Diferenciar entre formato visual (`<b>`, `<i>`) y semántico (`<strong>`, `<em>`).

### Citas y Referencias
Comprender el uso de elementos para citas y referencias (`<blockquote>`, `<q>`, `<abbr>`, `<address>`, `<cite>`, `<bdo>`).

### Enlaces
Entender la creación de hipervínculos con la etiqueta `<a>` y el uso del atributo `href`. Conocer el atributo `target` y sus valores (`_self`, `_blank`, `_parent`, `_top`).

## CSS

### ¿Qué es CSS?
Definir CSS como un lenguaje para dar formato y estilo al diseño de una página web. Entender el concepto de "cascada".

### Uso de CSS
Conocer las tres formas de añadir CSS a documentos HTML (en línea, interno, externo).

#### CSS en Línea
Comprender el uso del atributo `style` dentro de un elemento HTML.

#### CSS Interno
Entender la definición de estilos dentro del elemento `<style>` en la sección `<head>`.

#### CSS Externo
Comprender la vinculación a un archivo `.css` externo usando el elemento `<link>` en la sección `<head>`.

### Propiedades CSS Básicas
Familiarizarse con propiedades comunes como `color`, `font-family`, `font-size`, `border`, `background-color`.

### Colores en HTML/CSS
Conocer las diferentes formas de especificar colores (nombres de color, valores RGB, HEX, HSL, RGBA, HSLA).

## Atributos `class` e `id`

### Atributo `class`
Comprender su uso para especificar una clase para elementos, permitiendo que varios elementos compartan el mismo estilo. Entender la sintaxis CSS para clases (`.classname`). Conocer cómo un elemento puede pertenecer a múltiples clases.

### Atributo `id`
Comprender su uso para especificar un identificador único para un elemento. Entender la sintaxis CSS para IDs (`#idname`). Reconocer que solo puede haber un elemento con el mismo ID en un documento.

## Elementos de Bloque y en Línea

### Elementos de Bloque
Comprender que siempre comienzan en una nueva línea y ocupan todo el ancho disponible.

### Elementos en Línea
Comprender que no comienzan en una nueva línea y solo ocupan el ancho necesario.

## `<div>` y `<iframe>`

### Elemento `<div>`
Entender su función como contenedor genérico de bloque. Conocer sus atributos comunes (`style`, `class`, `id`). Comprender cómo se utiliza para agrupar secciones y aplicar estilos. Conocer métodos para alinear divs (centrar con `margin: auto`, poner uno al lado del otro con `float`, `inline-block`, `flex`, `grid`).

### Elemento `<iframe>`
Comprender su uso para incrustar otro documento dentro de un documento HTML actual. Conocer sus atributos básicos (`src`, `title`). Entender cómo se puede estilizar (`border`). Comprender cómo un iframe puede ser un objetivo para un enlace (`target` y `name`).

## El Modelo de Caja CSS

### Zonas de un Elemento
Identificar las cuatro partes de un elemento en el modelo de caja (Contenido, Relleno/Padding, Borde/Border, Margen/Margin).

### Propiedades de Margen y Relleno
Conocer las propiedades CSS para especificar márgenes y rellenos en cada lado (`margin-top`, `margin-right`, `margin-bottom`, `margin-left`, `padding-top`, `padding-right`, `padding-bottom`, `padding-left`). Entender la sintaxis abreviada.

### Valores de Margen
Comprender los valores `auto` (para centrar) e `inherit`.

### "Margin Collapse"
Entender el comportamiento específico de los márgenes adyacentes.

## Listas y Tablas

### Listas Desordenadas (`<ul>`, `<li>`)
Comprender su uso para crear listas con viñetas. Conocer la propiedad CSS `list-style-type` y sus valores (`disc`, `circle`, `square`, `none`). Entender las listas anidadas.

### Listas Ordenadas (`<ol>`, `<li>`)
Comprender su uso para crear listas numeradas o alfabéticas. Conocer el atributo `type` (`A`, `a`, `I`, `i`, `1`) y el atributo `start`. Entender las listas anidadas.

### Listas de Descripción (`<dl>`, `<dt>`, `<dd>`)
Comprender su uso para listas de términos y descripciones.

### Tablas (`<table>`, `<tr>`, `<th>`, `<td>`)
Comprender cómo organizar datos en filas y columnas. Identificar las etiquetas para tabla, fila, encabezado de celda y celda de datos. Saber cómo agregar bordes usando CSS. Comprender el uso de `colspan` para celdas que abarcan múltiples columnas. Conocer los elementos `<colgroup>` y `<col>` para aplicar estilos a grupos de columnas.

## Formularios HTML y PHP (Mención)

### XAMPP
Entender que es un paquete de software para desarrollar aplicaciones web, incluyendo un servidor web (Apache), base de datos (MySQL), y lenguajes de scripting (PHP, Perl).

### PHP
Reconocerlo como un lenguaje de programación del lado del servidor para procesar datos (como formularios).

## Gráficos en HTML (SVG y Canvas)

### SVG
Entender que `<img>` es un contenedor para gráficos SVG (gráficos vectoriales escalables). Reconocer que SVG utiliza métodos para dibujar formas.

### Canvas
Entender que `<canvas>` es un contenedor para gráficos que se dibujan usando JavaScript. Saber que Canvas tiene métodos para dibujar formas e imágenes.

### Diferencias Clave entre SVG y Canvas
Conocer que SVG se basa en XML (vectorial, se mantiene nítido al escalar, ideal para diagramas interactivos) y Canvas dibuja píxeles (raster, ideal para juegos y animaciones dinámicas).

## JavaScript

### Rol en el Desarrollo Web
Comprender su función para programar el comportamiento de las páginas web (junto con HTML para contenido y CSS para diseño).

### Características
Identificar que es un lenguaje de programación interpretado.

### ¿Java vs. JavaScript?
Comprender que son lenguajes diferentes, con diferencias en ejecución, paradigmas y tipado.

### Implementación
Conocer dónde se inserta el código JavaScript en HTML (etiquetas `<script>`) y las opciones de ubicación (`<head>`, `<body>`). Entender el uso de scripts externos (archivos `.js`) y sus ventajas (separación de código, mantenibilidad, caché).

### Salidas Posibles
Conocer las diferentes formas en que JavaScript puede mostrar datos (escribir en un elemento HTML con `innerHTML`/`innerText`, escribir en la salida HTML con `document.write()`, escribir en un cuadro de alerta con `window.alert()`).

## XML, XSL y XPath

### XML
Repasar su definición como metalenguaje extensible, su estructura jerárquica, la sintaxis básica de elementos, etiquetas y atributos. Entender el prólogo XML y los comentarios. Conocer las reglas de anidamiento y el concepto de documento bien formado y válido.

### XSL
Reconocerlo como un lenguaje para hojas de estilo XML. Conocer sus partes principales: XSLT, XPath y XQuery.

### XSLT
Comprender que se utiliza para transformar documentos XML en otros formatos (XML, HTML, XHTML). Entender su función de transformar elementos XML en elementos (X)HTML. Conocer el elemento `<xsl:template match="/">` y `<xsl:for-each>`.

### XPath
Comprender su uso para navegar en elementos y atributos en documentos XML. Compararlo con la navegación por un sistema de archivos.

---

## Cuestionario

Responde brevemente a las siguientes preguntas (2-3 frases cada una):

1.  ¿Cuál es la principal diferencia entre un lenguaje de marcas de Presentación y uno de Datos?
2.  Explica brevemente qué significa que un lenguaje de marcas sea "Extensible", dando un ejemplo.
3.  ¿Qué es SGML y cómo se relaciona con XML?
4.  Describe la estructura básica de un documento HTML, mencionando las etiquetas principales.
5.  ¿Cuál es la diferencia entre las etiquetas HTML `<b>` y `<strong>`?
6.  Menciona las tres formas en que se puede añadir CSS a un documento HTML.
7.  Explica el propósito del atributo `id` en HTML y CSS.
8.  ¿Cuál es la función principal del elemento `<div>` en HTML?
9.  ¿Cómo se utiliza el elemento `<iframe>`?
10. ¿Qué es XSLT y para qué se utiliza?

---

## Clave de Respuestas del Cuestionario

1.  **¿Cuál es la principal diferencia entre un lenguaje de marcas de Presentación y uno de Datos?**
    Un lenguaje de marcas de Presentación define cómo se muestra la información al usuario (ej: HTML), mientras que uno de Datos se enfoca en describir el significado de los datos independientemente de su visualización (ej: XML).

2.  **Explica brevemente qué significa que un lenguaje de marcas sea "Extensible", dando un ejemplo.**
    Significa que permite crear nuevas etiquetas o ampliar las existentes. XML es extensible porque los desarrolladores pueden definir sus propias etiquetas adaptadas a sus necesidades.

3.  **¿Qué es SGML y cómo se relaciona con XML?**
    SGML es un metalenguaje, un conjunto de normas que permiten crear otros lenguajes de marcas. XML es un lenguaje de marcas creado a partir de las normas de SGML.

4.  **Describe la estructura básica de un documento HTML, mencionando las etiquetas principales.**
    La estructura básica incluye la declaración `<!DOCTYPE>`, seguida de la etiqueta `<html>`. Dentro de `<html>` están las secciones `<head>` (metadatos) y `<body>` (contenido visible).

5.  **¿Cuál es la diferencia entre las etiquetas HTML `<b>` y `<strong>`?**
    Ambas etiquetas hacen que el texto se muestre en negrita por defecto. Sin embargo, `<b>` aplica solo formato visual, mientras que `<strong>` indica que el texto tiene gran importancia semántica.

6.  **Menciona las tres formas en que se puede añadir CSS a un documento HTML.**
    Se puede añadir CSS de forma en línea (atributo `style`), interna (dentro de la etiqueta `<style>` en `<head>`) o externa (vinculando a un archivo `.css` con `<link>`).

7.  **Explica el propósito del atributo `id` en HTML y CSS.**
    El atributo `id` especifica un identificador único para un elemento HTML. Se utiliza en CSS con el carácter `#` para aplicar estilos específicos a ese elemento único.

8.  **¿Cuál es la función principal del elemento `<div>` en HTML?**
    El elemento `<div>` se utiliza principalmente como un contenedor genérico a nivel de bloque para agrupar otros elementos HTML. Es útil para aplicar estilos o manipular secciones de una página.

9.  **¿Cómo se utiliza el elemento `<iframe>`?**
    El elemento `<iframe>` se utiliza para incrustar otro documento HTML dentro del documento actual. Permite mostrar contenido de una página web diferente dentro de un área específica de la página principal.

10. **¿Qué es XSLT y para qué se utiliza?**
    XSLT (Transformaciones XSL) es una parte de XSL que se utiliza para transformar documentos XML en otros formatos, como HTML o XHTML. Permite convertir la estructura de datos de un XML en una presentación visual.

---

## Preguntas de Formato Ensayo

Prepara respuestas detalladas (en formato ensayo) a las siguientes preguntas:

1.  Compara y contrasta HTML y XML. Incluye sus propósitos principales, la naturaleza de sus etiquetas y sus respectivas ventajas y desventajas.
2.  Describe el Modelo de Caja (Box Model) en CSS. Explica cada una de sus partes (contenido, padding, border, margin) y cómo afectan al diseño y espaciado de los elementos HTML.
3.  Explica la importancia de la separación de contenido, estructura y presentación en el desarrollo web. Describe cómo HTML, CSS y JavaScript contribuyen a esta separación y por qué es una buena práctica.
4.  Analiza los diferentes métodos para posicionar elementos `<div>` uno al lado del otro utilizando CSS (Float, Inline-block, Flexbox, Grid). Describe cómo funciona cada método y en qué situaciones podría ser más adecuado uno que otro.
5.  Compara SVG y Canvas para la creación de gráficos en HTML. Explica sus características principales, las tecnologías asociadas (XML/JavaScript), y cuándo sería preferible utilizar uno u otro.

---

## Glosario de Términos Clave

* **Lenguaje de Marcas:** Un sistema para anotar un documento de una manera que es sintácticamente distinguible del texto, con el propósito de definir cómo se debe estructurar, presentar o procesar el texto.
* **Etiqueta (Tag):** Un símbolo en un lenguaje de marcas (como HTML o XML) que aparece entre `<` y `>` y que se utiliza para marcar el inicio o fin de un elemento o para insertar elementos vacíos.
* **Elemento:** En lenguajes de marcas, consiste en una etiqueta de inicio, contenido opcional y una etiqueta de cierre. Algunos elementos son "vacíos" y no tienen contenido ni etiqueta de cierre.
* **Atributo:** Información adicional sobre un elemento, incluida en la etiqueta de inicio como pares nombre-valor entrecomillados.
* **HTML (HyperText Markup Language):** El lenguaje estándar para crear páginas web y estructurar su contenido.
* **XML (eXtensible Markup Language):** Un metalenguaje que permite definir lenguajes de marcado personalizados para describir datos. Se centra en el significado de los datos.
* **SGML (Standard Generalized Markup Language):** Un metalenguaje más antiguo a partir del cual se desarrollaron HTML y XML.
* **CSS (Cascading Style Sheets):** Un lenguaje de hojas de estilo utilizado para describir la presentación (estilo y diseño) de un documento escrito en HTML o XML.
* **CSS en Línea (Inline CSS):** Estilos CSS aplicados directamente a un elemento HTML utilizando el atributo `style`.
* **CSS Interno (Internal CSS):** Estilos CSS definidos dentro de la sección `<head>` de un documento HTML utilizando el elemento `<style>`.
* **CSS Externo (External CSS):** Estilos CSS definidos en un archivo separado (`.css`) y vinculados a un documento HTML utilizando el elemento `<link>`.
* **Atributo `class`:** Atributo HTML utilizado para especificar una clase para uno o varios elementos, permitiendo aplicar el mismo estilo a un grupo de elementos.
* **Atributo `id`:** Atributo HTML utilizado para especificar un identificador único para un elemento. Se usa para apuntar a un elemento específico con CSS o JavaScript.
* **Elemento de Bloque (Block-level element):** Un elemento HTML que siempre comienza en una nueva línea y ocupa todo el ancho disponible (por defecto).
* **Elemento en Línea (Inline element):** Un elemento HTML que no comienza en una nueva línea y solo ocupa el ancho necesario.
* **`<div>`:** Un elemento HTML de bloque genérico utilizado como contenedor para agrupar otros elementos.
* **`<iframe>`:** Un elemento HTML utilizado para incrustar otro documento dentro del documento HTML actual.
* **Modelo de Caja (Box Model):** Un concepto fundamental en CSS que describe cómo se representa un elemento HTML en términos de contenido, padding (relleno), border (borde) y margin (margen).
* **Padding (Relleno):** El espacio transparente alrededor del contenido de un elemento, dentro del borde.
* **Margin (Margen):** El espacio transparente fuera del borde de un elemento, utilizado para crear espacio entre elementos.
* **Margin Collapse:** Un fenómeno en CSS donde los márgenes verticales de elementos adyacentes se fusionan en un único margen cuyo tamaño es el mayor de los dos.
* **`<ul>`:** Etiqueta HTML para definir una lista desordenada (con viñetas).
* **`<ol>`:** Etiqueta HTML para definir una lista ordenada (numerada o alfabética).
* **`<li>`:** Etiqueta HTML para definir un elemento de lista dentro de `<ul>` o `<ol>`.
* **`<table>`:** Etiqueta HTML para crear una tabla.
* **`<tr>`:** Etiqueta HTML para definir una fila en una tabla.
* **`<th>`:** Etiqueta HTML para definir una celda de encabezado en una tabla.
* **`<td>`:** Etiqueta HTML para definir una celda de datos en una tabla.
* **JavaScript:** Un lenguaje de programación interpretado utilizado principalmente para añadir interactividad y comportamiento a las páginas web.
* **SVG (Scalable Vector Graphics):** Un formato de gráficos vectoriales basado en XML para gráficos bidimensionales con soporte para interactividad y animación.
* **`<canvas>`:** Un elemento HTML utilizado para dibujar gráficos, sobre la marcha, a través de JavaScript. Dibuja píxeles.
* **XSL (eXtensible Stylesheet Language):** Un conjunto de lenguajes basados en XML para transformar y dar formato a documentos XML.
* **XSLT (XSL Transformations):** La parte de XSL utilizada para transformar documentos XML en otros documentos.
* **XPath:** Un lenguaje para navegar en elementos y atributos en documentos XML.