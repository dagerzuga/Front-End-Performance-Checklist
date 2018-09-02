<h1 align="center">
<br>
  <a href="https://github.com/thedaviddias/Front-End-Performance-Checklist"><img src="https://raw.githubusercontent.com/thedaviddias/Front-End-Performance-Checklist/master/images/logo-front-end-performance-checklist.jpg" alt="Front-End Performance Checklist" width="170"></a>
  <br>
    <br>
  Lista de requerimientos para el rendimiento front-end
  <br>
</h1>

<h4 align="center">🎮 La única lista de requerimientos para el rendimiento del front-end que corre más rápido que otras.</h4>
<h4 align="center">🎮 </h4>
<p align="center">Una regla simple: “Diseña y programa con rendimiento en mente”</p>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>
  <a href="https://discord.gg/btHQRkm">
    <img src="https://img.shields.io/badge/chat-on_discord-4837E2.svg?style=flat-square" alt="Discord">
  </a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="Licence MIT">
  </a>
</p>

<p align="center">
  <a href="#uso">Cómo utilizar</a> • <a href="#contributing">Contribuyendo</a> • <a href="http://feedback.frontendchecklist.io/">Mapa del camino</a> • <a href="https://www.producthunt.com/posts/front-end-performance-checklist">Product Hunt</a>
</p>

<p align="center">
  <a href="https://github.com/JohnsenZhou/Front-End-Performance-Checklist">🇨🇳</a>
  <a href="https://github.com/WilliamDASILVA/Front-End-Performance-Checklist">🇫🇷</a>
  <a href="https://github.com/ParkSB/Front-End-Performance-Checklist">🇰🇷</a>  
  <a href="https://github.com/fernandofawkes/Front-End-Performance-Checklist">🇵🇹</a>
  <a href="https://github.com/lex111/Front-End-Performance-Checklist">🇷🇺</a>
</p>

<p align="center">
    <span>Otras listas de requerimientos:</span>
    <br>
  🗂 <a href="https://github.com/thedaviddias/Front-End-Checklist#---------front-end-checklist-">Lista de requerimientos para front-end</a> • 💎 <a href="https://github.com/thedaviddias/Front-End-Design-Checklist#front-end-design-checklist">Lista de requerimientos para diseño front-end</a>
</p>

## Tabla de contenidos

1. **[HTML](#html)**
2. **[CSS](#css)**
3. **[Fuentes](#fuentes)**
4. **[Imágenes](#imagenes)**
5. **[JavaScript](#javascript)**
6. **[Server](#server) (en progreso)**
7. **[Frameworks JS](#performances-and-js-frameworks) (en progreso)**

## Introducción

El rendimiento es un tema amplio, pero no es siempre un tema del lado del back-end o del administrador. También es responsabilidad del front-end. La lista de requerimientos para el rendimiento front-end, es una lista exhaustiva de elementos que deberías revisar, o al menos ser consciente de ellos, como desarrollador front-end y aplicarla a tu proyecto (personal y profesional).

### Uso

Para cada regla, tendrás un párrafo explicando *el porqué* de la importancia de esta regla y *cómo* puedes arreglarla. Para información más detallada puedes encontrar links que te enviarán a 🛠 herramientas, 📖 artículos o 📹 contenido multimedia que puede completar la lista de requerimientos.

Todos los elementos en **la lista de requerimientos para el rendimiento front-end** son esenciales para lograr el mayor porcentaje de rendimiento, pero encontrarás un indicador para ayudarte a eventualmente priorizar unas reglas sobre otras:

* ![Low][low] significa que el elemento es de prioridad **baja**.
* ![Medium][medium] significa que el elemento es de prioridad **media**. No deberías evitar abordar dicho elemento.
* ![High][high] significa que el elemento tiene una prioridad **alta**. No puedes evitar seguir dicha regla e implementar las correcciones recomendadas.

### Herramientas de rendimiento

Lista de herramientas que puedes utilizar para probar o monitorear tu sitio o aplicación:

 * 🛠 [WebPagetest - Prueba de optimización y rendimiento del sitio web](https://www.webpagetest.org/)
 * 🛠 ☆ [Dareboost: Prueba de velocidad y análisis del sitio web](https://www.dareboost.com/) (usa el cupón WPCDD20 para un -20%)
 * 🛠 [Treo: Control de velocidad de página](https://treo.sh/?ref=perfchecklist)
 * 🛠 [GTmetrix | Optimización de velocidad y rendimiento del sitio web](https://gtmetrix.com/)
 * 🛠 [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
 * 🛠 [Prueba de velocidad del sitio Pingdom](https://tools.pingdom.com)
 * 📖 [Pagespeed - La herramienta y la guía de optimización](https://varvy.com/pagespeed/)
 * 📖 [Haz más rápida la web | Google Developers](https://developers.google.com/speed/)
 * 🛠 [Sitespeed.io - Bienvenido al maravilloso mundo del rendimiento web](https://www.sitespeed.io/)
 * 🛠 [Calibre](https://calibreapp.com/)
 * 🛠 [Prueba de velocidad del sitio web | Verificación del rendimiento web &raquo; Dotcom-Tools](https://www.dotcom-tools.com/website-speed-test.aspx)
 * 🛠 [Monitoreo de actividad del sitio web y del servidor - Pingdom](https://www.pingdom.com/product/uptime-monitoring/) ([Free Signup Link](https://www.pingdom.com/free))
 * 🛠 [Robot de tiempo de actividad](https://uptimerobot.com)
 * 🛠 [SpeedCurve: Monitor de rendimiento front-end](https://speedcurve.com)
 * 🛠 [PWMetrics - Herramienta CLI y librería para recopilar métricas de rendimiento](https://github.com/paulirish/pwmetrics)
 * 🛠 [Varvy - Optimización de velocidad de la página]( https://varvy.com/pagespeed/)
 * 🛠 [Lighthouse - Google]( https://developers.google.com/web/tools/lighthouse/#devtools)
 * 🛠 [Checkbot browser extension - Verifica las mejores prácticas de rendimiento web](https://www.checkbot.io/)
 * 🛠 [Yellow Lab Tools | Prueba en línea para ayudar a acelerar páginas web pesadas](https://yellowlab.tools/)

### Referencias (inglés)

 * 📹 [El costo de JavaScript - YouTube](https://www.youtube.com/watch?v=_bzqF05xsC4) ([versión escrita](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4))
 * 📖 [Comience a analizar el rendimiento en tiempo de ejecución  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/)
 * 📖 [Estado de la web | 2018_01_01](https://httparchive.org/reports/state-of-the-web?start=2018_01_01)
 * 📖 [El peso de la página no importa](https://www.speedshop.co/2015/11/05/page-weight-doesnt-matter.html)
 * 📖 [Lista de requerimiento para rendimiento front-end 2018 [PDF, Apple Pages]](https://www.smashingmagazine.com/2018/01/front-end-performance-checklist-2018-pdf-pages/)
 * 📖 [Diseñando para peso de alto rendimiento, estética y velocidad - Por Lara Callender Hogan [eBook, Print]](http://designingforperformance.com/index.html)
 * 📖 [Varvy - Glosario de rendimiento web](https://varvy.com/performance/)
 * 📖 [fabkrum/web-performance-resources: Recopilación actualizada de valiosos recursos de rendimiento web](https://github.com/fabkrum/web-performance-resources)
 * 📖 [Checkbot - Mejores prácticas de velocidad web](https://www.checkbot.io/guide/speed/)

---

## HTML

![html]

- [ ] **Minificar el HTML:** ![medium] El código HTML se minimiza, los comentarios, espacios en blanco y las nuevas líneas se eliminan de los archivos de producción.

    *¿Por qué?:*
    > La eliminación de todos los espacios innecesarios, comentarios y rupturas reducirá el tamaño de tu HTML y acelerará los tiempos de carga de la página del sitio y, obviamente, aligerará la descarga para su usuario.

    *¿Cómo?:*
    > La mayoría de los frameworks tienen plugins para facilitar la minificación de las páginas web. Puedes utilizar un montón de módulos de NPM que pueden hacer el trabajo por ti automáticamente.

    * 🛠 [HTML minifier | Minify Code](http://minifycode.com/html-minifier/)
    * 🛠 [Online HTML Compressor](http://refresh-sf.com)
    * 📖 [Experimentando con un minificador HTML — Perfection Kills](http://perfectionkills.com/experimenting-with-html-minifier/#use_short_doctype)

- [ ] **Eliminar comentarios innecesarios:** ![low] Asegurate de eliminar los comentarios de tus páginas.

    *¿Por qué?:*
    > Los comentarios no son realmente útiles para el usuario y debería eliminarse de los archivos de producción. Un caso en el que quieras conservar los comentarios podría ser si es necesario conservar el origen de una biblioteca.

    *¿Cómo?:*
    > ⁃ La mayoría de las veces, los comentarios pueden eliminarse utilizando un plugin que minify el HTML.

 * 🛠 [remove-html-comments - npm](https://www.npmjs.com/package/remove-html-comments)

- [ ] **Eliminar atributos innecesarios:** ![low] atributos type como `type="text/javascript"` o `type="text/css"` no son requeridos más y deberían ser eliminados.

    ```html
    <!-- Antes de HTML5 -->
    <script type="text/javascript">
        // código JavaScript
    </script>

    <!-- Hoy -->
    <script>
        // código JavaScript
    </script>
    ```

    *¿Por qué?:*
    > Los atributos type no son necesarios ya que HTML5 aplica text/css y text/javascript como valores por defecto. El código no utilizado debe eliminarse ya que da más peso a las páginas.

    *¿Cómo?:*
    > ⁃ Asegúrese de que todas sus etiquetas `<link>` y `<script>` no tienen el atributo type.

    * 📖 [The Script Tag | CSS-Tricks](https://css-tricks.com/the-script-tag/)
   
- [ ] **Siempre colocar las etiquetas CSS antes que las etiquetas Javascript:** ![high] Asegúrese que tu CSS siempre carga antes que el código Javascript.

    ```html
    <!-- No recomendado -->
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    <link rel="stylesheet" href="foo.css"/>

    <!-- Recomendado -->
    <link rel="stylesheet" href="foo.css"/>
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    ```

    *¿Por qué?:*
    > Tener las etiquetas CSS antes que el Javascript permite una mejor descarga paralela, lo que optimiza el tiempo de carga del navegador.

    *¿Cómo?:*
    > ⁃ Asegúrese que `<link>`  y `<style>` en `<head>`siempre van antes que `<script>`.

    * 📖 [Ordering your styles and scripts for pagespeed](https://varvy.com/pagespeed/style-script-order.html)

- [ ] **Minimiza el número de los iframes:** ![high] Usa iframes solo si no tienes otra posibilidad técnica. Intenta evitar iframes tanto como puedas.

**[⬆ volver arriba](#tabla-de-contenidos)**

## CSS

![css]

- [ ] **Minificación:** ![high] Todos los archivos CSS son minificados, los comentarios, los espacios en blanco y las nuevas líneas se eliminan de los archivos de producción.

    *¿Por qué?:*
    > Cuando se minimizan los archivos CSS, el contenido se carga más rápido y se envían menos datos al cliente. Es importante minimizar siempre los archivos CSS en producción. Es beneficioso para el usuario como lo es para cualquier empresa que desee reducir los costos de ancho de banda y reducir el uso de recursos.

    *¿Cómo?:*
    > ⁃ Utilizando herramientas para minificar los archivos automáticamente o durante el desarrollo o el despliegue.

    * 🛠 [cssnano: A modular minifier based on the PostCSS ecosystem. - cssnano](https://cssnano.co/)
    * 🛠 [@neutrinojs/style-minify - npm](https://www.npmjs.com/package/@neutrinojs/style-minify)
    * 🛠 [Online CSS Compressor](http://refresh-sf.com)


- [ ] **Concatenación:** ![medium] Los archivos CSS son concatenados en un solo archivo *(No siempre válido para HTTP/2)*.

    ```html

    <!-- No recomendado -->
    <link rel="stylesheet" href="foo.css"/>
    <link rel="stylesheet" href="bar.css"/>

    <!-- Recomendado -->
    <link rel="stylesheet" href="foobar.css"/>
    ```

    *¿Por qué?:*
    > Si todavía estás utilizando HTTP/1, puede que necesites concatenar tus archivos, es menos cierto si tu servidor usa HTTP/2 (se deben realizar pruebas).

    *¿Cómo?:*
    > ⁃ Utilizando una herramienta en línea o cualquier plugin antes o durante la compilación o implementación para concatenar los archivos. <br>
    ⁃ Asegúrese, por supuesto, de que la concatenación no rompa el proyecto.

    * 📖 [HTTP: Optimizing Application Delivery - High Performance Browser Networking (O'Reilly)](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)
    * 📖 [Performance Best Practices in the HTTP/2 Era](https://deliciousbrains.com/performance-best-practices-http2/)

- [ ] **No-bloqueantes:** ![high] Los archivos CSS tienen que ser no-bloqueantes para evitar que el DOM demore  tiempo en cargar.

    ```html
    <link rel="preload" href="global.min.css" as="style" onload="this.rel='stylesheet'">
    <noscript><link rel="stylesheet" href="global.min.css"></noscript>
    ```

    *¿Por qué?:*
    > Los archivos CSS pueden bloquear la carga de la página y retrasar el renderizado de la página. El uso de `preload` puede cargar los archivos CSS antes de que el navegador comience a mostrar el contenido de la página.

    *¿Cómo?:*
    > ⁃ Necesitas agregar el atributo `rel` con el valor `preload` y agregar `as =" style "` en el elemento `<link>`.

    * 🛠 [loadCSS by filament group](https://github.com/filamentgroup/loadCSS)
    * 📖 [Example of preload CSS using loadCSS](https://gist.github.com/thedaviddias/c24763b82b9991e53928e66a0bafc9bf)
    * 📖 [Preloading content with rel="preload"](https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content)
    * 📖 [Preload: What Is It Good For? — Smashing Magazine](https://www.smashingmagazine.com/2016/02/preload-what-is-it-good-for/)

- [ ] **Longitud de las clases CSS:** ![low] La longitud de las clases puede tener un (leve) impacto en tus archivos HTML y CSS (eventualmente).

    *¿Por qué?:*
    > Incluso los impactos en el rendimiento puede ser discutibles, tomar una decisión sobre una estrategia de nomenclatura con respecto al proyecto puede tener un impacto sustancial en el mantenimiento de las hojas de estilo. Si estás utilizando BEM, en algunos casos, puede terminar con clases que tengan más caracteres de los necesarios. Siempre es importante elegir sabiamente los nombres y espacios de nombre.

    *¿Cómo?:*
    > Estableciendo un límite en los términos de números de caracteres podría ser interesante para algunas personas,  pero descomponiendo el sitio en componentes puede ayudar a reducir el número de clases (y declaraciones) y la longitud de las mismas.

    * 🛠 [long vs short class · jsPerf](https://jsperf.com/long-vs-short-class)

- [ ] **CSS sin utilizar:** ![medium] Elimina los selectores de CSS no utilizados.

    *¿Por qué?:*
    > Eliminar los selectores de CSS no utilizados puede reducir el tamaño de los archivos finales y luego acelerar la carga de los activos.
    
    *¿Cómo?:*
    > ⁃ ⚠️ Siempre verifica si el framework CSS que quieres utilizar no tiene ya incluido un reset/normalice. Es posible que a veces no necesites todo lo que viene dentro del reset/normalize.

    * 🛠 [UnCSS Online](https://uncss-online.com/)
    * 🛠 [PurifyCSS](https://github.com/purifycss/purifycss)
    * 🛠 [PurgeCSS](https://github.com/FullHuman/purgecss)
    * 🛠 [Chrome DevTools Coverage](https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage)

* [ ] **CSS Crítico:** ![high] El CSS crítico (o "arriba del doblez") recoge todo el CSS utilizado para renderizar la parte visible de la página. Se incrusta antes de su llamada CSS principal y entre `<style> </ style>` en una sola línea (si es posible, se lo minimiza).

    *¿Por qué?:*
    > Enlinear CSS crítico ayuda a acelerar el procesamiento de las páginas web, reduciendo la cantidad de solicitudes al servidor.

    *¿Cómo?:*
    > Generando el CSS crítico con herramientas en línea o usando un complemento como el desarrollado por Addy Osmani.

    * 📖 [Understanding Critical CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/)
    * 🛠 [Critical by Addy Osmani on GitHub](https://github.com/addyosmani/critical) automates this.
    * 📖 [Inlining critical CSS for better web performance | Go Make Things](https://gomakethings.com/inlining-critical-css-for-better-web-performance/)
     * 🛠 [Critical Path CSS Generator - Prioritize above the fold content :: SiteLocity](https://www.sitelocity.com/critical-path-css-generator)
     * 📖 [Reduce the size of the above-the-fold content
](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent)

- [ ] **CSS incrustado o en línea:** ![high] Evitar el uso de CSS incrustado o en línea dentro del  `<body>` *(No válido para HTTP/2)*

    *¿Por qué?:*
    > Una de las principales razones es porque es buena práctica  *separar el contenido del diseño**. También ayuda a tener un código más mantenible y un sitio más accesible. Pero, en relación al rendimiento, es simplemente porque disminuye el tamaño el archivo del HTML y el tiempo de carga.

    *¿Cómo?:*
    > Siempre utilizar hojas de estilo externas o incrustadas en el `<head>` (y seguir las otras reglas de rendimiento de CSS)

    * 📖 [Observe CSS Best Practices: Avoid CSS Inline Styles](https://www.lifewire.com/avoid-inline-styles-for-css-3466846)

- [ ] **Analiza la complejidad de las hojas de estilo:** ![high] Analizar las hojas de estilo puede ayudarte a encontrar problemas, redundancias y sectores CSS duplicados.

    *¿Por qué?:*
    > A veces puedes tener redundancias o errores de validación en el CSS, analizar los archivos y eliminar estas complejidades puede ayudarte a acelerarlos (porque el navegador cargará más rápido)

    *¿Cómo?:*
    > El CSS debe estar organizado, utilizar un preprocesador CSS puede ayudar con eso. Algunas herramientas en línea que se enumeran a continuación, también pueden ayudar a corregir el código.

    * 🛠 [TestMyCSS | Optimize and Check CSS Performance](http://www.testmycss.com/)
    * 📖 [CSS Stats](https://cssstats.com/)
    * 🛠 [macbre/analyze-css: CSS selectors complexity and performance analyzer](https://github.com/macbre/analyze-css)

**[⬆ volver arriba](#tabla-de-contenidos)**

## Fuentes

![fonts]

* 📖 [A Book Apart, Webfont Handbook](https://abookapart.com/products/webfont-handbook)

- [ ] **formatos Webfont:** ![medium] Utilizar WOFF2 en tu proyecto web o aplicación.

    *¿Por qué?:*
    > Según Google, el formato de compresión WOFF 2.0  ofrece un 30% de ganancia sobre el WOFF 1.0. Entonces, es bueno utilizar WOFF 2.0, y WOFF 1.0 y TTF como respaldo.

    *¿Cómo?:*
    > Antes de comprar una nueva fuente, verifique que el proveedor le brinde el formato WOFF2. Si estás utilizando una fuente gratuita, siempre puede utilizar Font Squirrel para generar todos los formatos necesarios.

    * 📖 [WOFF 2.0 – Learn more about the next generation Web Font Format and convert TTF to WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a)
    * 🛠 [Create Your Own @font-face Kits » Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
    * 🛠 [IcoMoon App - Icon Font, SVG, PDF & PNG Generator](https://icomoon.io/app/)
    * 📖 [Using @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Can I use... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **Usar `preconnect` para cargar más rápido las fuentes:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

    *¿Por qué?:*
    > Cuando llegas a un sitio web, tu dispositivo necesita averiguar de dónde es el sitio y a cual servidor necesita conectarse. El navegador necesita contactar con el servidor DNS y esperar que la búsqueda se complete antes de atraer los recursos (fuentes, CSS...). Preatracciones y preconecciones permiten al navegador buscar la información del DNS y establecer una concección TCP con el servidor de la fuente. Esto brinda una mejora en el rendimiento porque para el momento que el navegador termina de parsear los archivos CSS con la información de la fuente y se da cuenta que necesita solicitar el archivo de la fuente del servidor, ya tendrá preresuelta la información del DNS y tendrá conexión abierta con el servidor ya listo en su grupo de conexiones.

    *¿Cómo?:*
    > ⁃ Antes de recuperar las webfonts, utilice webpagetest para evaluar el sitio web <br>
    ⁃ Busque las búsquedas DNS de color verde azulado y tenga en cuenta el host que se solicita <br>
    ⁃ Recupere sus webfonts en su `<head>` y agregue eventualmente estos nombres de host que también debe captar previamente

    * 📖 [Faster Google Fonts with Preconnect - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Make Your Site Faster with Preconnect Hints | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Ultimate Guide to Browser Hints: Preload, Prefetch, and Preconnect - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/)
    * 📖 [A Comprehensive Guide to Font Loading Strategies—zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)
    * 🛠 [typekit/webfontloader: Web Font Loader gives you added control when using linked fonts via @font-face.](https://github.com/typekit/webfontloader)

- [ ] **Tamaño de la Webfont:** ![medium] Los tamaños de las Webfonts no superan los 300kb (incluidas todas las variantes)

 * 📖 [Font Bytes - Page Weight](https://httparchive.org/reports/page-weight#bytesFont)

- [ ] **Evitar texto invisible o flash:** ![medium] Evite texto transparente hasta que se cargue Webfont

 * 📖 [`font-display` for the Masses](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display: The Future of Font Rendering on the Web](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ volver arriba](#tabla-de-contenidos)**

## Imagenes

![images]

 * 📖 [Image Bytes in 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **Optimización de imágenes:** ![high] Las imágenes están optimizadas, comprimidas sin impacto directo en el usuario final.

    *¿Por qué?:*
    > Las imágenes optimizadas se cargan más rápido en el navegador y consumen menos datos.

    *¿Cómo?:*
    > ⁃ Intenta utilizar efectos CSS3 cuando sea posible (en lugar de una imagen pequeña) <br>
    ⁃ Cuando sea posible, utilizar fuentes en lugar de texto codificado en las imágenes <br>
    ⁃ Utilizar SVG <br>
    ⁃ Utilice una herramienta y especifique una compresión de nivel por debajo de 85.

    * 📖 [Image Optimization | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 📖 [Essential Image Optimization - An eBook by Addy Osmani](https://images.guide/)
    * 🛠 [TinyJPG – Compress JPEG images intelligently](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Online Image Optimizer](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - optimize and compress JPEG photos and PNG images](https://compressor.io/compress)
    * 🛠 [Cloudinary - Image Analysis Tool](https://webspeedtest.cloudinary.com)
    * 🛠 [SVGOMG - Optimize SVG vector graphics files](https://jakearchibald.github.io/svgomg/)


* [ ] **Formato de imágenes:** ![high] Seleccione el formato de imagen adecuadamente.

    *¿Por qué?:*
    > Para asegurarse que las imágenes no ralentizan tu sitio web, selecciona el formato que corresponda a la imagen. Si es una foto, JPEG es usualmente más adecuado que PNG o GIF. Pero no olvides revisar los formatos de siguiente generación que pueden reducir el formato de los archivos. Cada formato de imagen tiene ventajas y desventajas, es importante conocerlos para tomar la mejor decisión.

    *¿Cómo?:*
    > ⁃ Utiliza [Lighthouse](https://developers.google.com/web/tools/lighthouse/) para identificar cuales imagenes pueden, eventualmente utilizar **formatos de siguiente generación** (como  JPEG 2000m JPEG XR o WebP). <br>
    ⁃ Compara diferentes formatos, a veces utilizar PNG8 es mejor que PNG16, a veces no lo es.

    * 📖 [Serve Images in Next-Gen Formats  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [What Is the Right Image Format for Your Website? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
    * 📖 [PNG8 - The Clear Winner — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
    * 📖 [8-bit vs 16-bit - What Color Depth You Should Use And Why It Matters - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **Utilizar imagen vectorial vs raster/bitmap:** ![medium] Es preferible utilizar imágenes vectoriales en lugar de imágenes de bitmaps (cuando es posible).

    *¿Por qué?:*
    > Imágenes vectoriales (SVG) tienden a ser más pequeñas que los bitmaps y los SVG se escalan y redimensionan perfectamente. Estas imágenes pueden ser animadas y modificadas mediante CSS.

* [ ] **Dimensiones de las imágenes:** ![medium] Establecer atributos `width` y `height` en los`<img>` si el tamaño final de la imagene es conocido.

    *¿Por qué?:*
    > Si el alto y ancho son establecidos el espacio requerido para la imagen es reservado cuando la página es cargada. Sin embargo, sin estos atributos, el navegador no conoce el tamaño de la imagen y no puede reservar el espacio apropiado para ella. El efecto será que el diseño de la página cambiará durante la carga (mientras se cargan las imágenes).

* [ ] **Evitar el uso de imágenes Base64 :** ![medium] Podrías eventualmente convertir imágenes diminutas a base 64, pero en realidad no es una buena práctica.

    * 📖 [Base64 Encoding & Performance, Part 1 and 2 by Harry Roberts](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [A closer look at Base64 image performance – The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [When to base64 encode images (and when not to) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
   * 📖 [Base64 encoding images for faster pages | Performance and seo factors](https://varvy.com/pagespeed/base64-images.html)

* [ ] **Carga lenta:** ![medium] Las imágenes fuera de pantalla se cargan lentamente (siempre es proporcionado un noscript de respaldo).

    *¿Por qué?:*
    > Mejorará el tiempo de respuesta de la página actual y luego evitará cargar imágenes innecesarias que el usuario puede no necesitar.

    *¿Cómo?:*
    > ⁃ Utiliza [Lighthouse](https://developers.google.com/web/tools/lighthouse/) para identificar cuantas **imágenes están fuera de pantalla**. <br>
    ⁃ Utilizar un plugin de JavaScript como los siguientes para cargar lentamente las imágenes. Asegurate de seleccionar únicamente imágenes fuera de pantalla. <br>
    ⁃ También asegurate de cargar lentamente imagenes alternativas que se muestren al pasar el ratón o sobre otras acciones del usuario.

    * 🛠 [verlok/lazyload: GitHub](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: GitHub](https://github.com/aFarkas/lazysizes/)
    * 📖 [Lazy Loading Images and Video  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 Brilliant Ways to Lazy Load Images For Faster Page Loads - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **Imágenes responsivas:** ![medium] Asegúrate de mostrar imágenes cercanas al tamaño de la pantalla.

    *¿Por qué?:*
    > Los dispositivos pequeños no necesitan imágenes más grandes que su ventana gráfica. Se recomienda tener múltiples versiones de una imagen en diferentes tamaños.

    *¿Cómo?:*
    > ⁃ Crea diferentes tamaños de imagen para los dispositivos a los que quieres enfocar. <br>
    ⁃ Utiliza `srcset` y `picture` para mostrar variaciones de las imagenes.

     * 📖 [Responsive images - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ volver arriba](#tabla-de-contenidos)**

## JavaScript

![javascript]

- [ ] **JS Minification:** ![high] All JavaScript files are minified, comments, white spaces and new lines are removed from production files *(still valid if using HTTP/2)*.

    *¿Por qué?:*
    > Removing all unnecessary spaces, comments and break will reduce the size of your JavaScript files and speed up your site's page load times and obviously lighten the download for your user.

    *¿Cómo?:*
    > ⁃ Use the tools suggested below to minify your files automatically before or during your build or your deployment.

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Online JavaScript Compressor](http://refresh-sf.com)
    * 📖 [Short read: How is HTTP/2 different? Should we still minify and concatenate?](https://scaleyourcode.com/blog/article/28)

* [ ] **No JavaScript inside:** ![medium] *(Only valid for website)* Avoid having multiple JavaScript codes embedded in the middle of your body. Regroup your JavaScript code inside external files or eventually in the `<head>` or at the end of your page (before `</body>`).

    *¿Por qué?:*
    > Placing JavaScript embedded code directly in your `<body>` can slow down your page because it loads while the DOM is being built. The best option is to use external files with `async` or `defer` to avoid blocking the DOM. Another option is to place some scripts inside your `<head>`. Most of the time analytics code or small script that need to load before the DOM gets to main processing.

    *¿Cómo?:*
    > Ensure that all your files are loaded using `async` or `defer` and decide wisely the code that you will need to inject in your `<head>`.

     * 📖 [11 Tips to Optimize JavaScript and Improve Website Loading Speeds](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **Non-blocking JavaScript:** ![high] JavaScript files are loaded asynchronously using `async` or deferred using `defer` attribute.

    ```html
    <!-- Defer Attribute -->
    <script defer src="foo.js"></script>

    <!-- Async Attribute -->
    <script async src="foo.js"></script>
    ```

    *¿Por qué?:*
    > JavaScript blocks the normal parsing of the HTML document, so when the parser reaches a `<script>` tag (particularly is inside the `<head>`), it stops to fetch and run it. Adding `async` or `defer` are highly recommended if your scripts are placed in the top of your page but less valuable if just before your `</body>` tag. But it's a good practice to always use these attributes to avoid any performance issue.

    *¿Cómo?:*
    > ⁃ Add `async` (if the script don't rely on other scripts) or `defer` (if the script relies upon or relied upon by an async script) as an attribute to your script tag. <br>
    ⁃ If you have small scripts, maybe use inline script place above async scripts.

    * 📖 [Remove Render-Blocking JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)
    * 📖 [Defer loading JavaScript](https://varvy.com/pagespeed/defer-loading-javascript.html)

* [ ] **Optimized and updated JS libraries:** ![medium] All JavaScript libraries used in your project are necessary (prefer Vanilla JavaScript for simple functionalities), updated to their latest version and don't overwhelm your JavaScript with unnecessary methods.

    *¿Por qué?:*
    > Most of the time, new versions come with optimization and security fix. You should use the most optimized code to speed up your project and ensure that you'll not slow down your website or app without outdated plugin.

    *¿Cómo?:*
    > If your project use NPM packages, [npm-check](https://www.npmjs.com/package/npm-check) is a pretty interesting library to upgrade / update your libraries.
    > [Greenkeeper](https://greenkeeper.io/) can automatically look for your dependencies and suggest an update evey time a new version is out.

    * 📖 [You may not need jQuery](http://youmightnotneedjquery.com/)
    * 📖 [Vanilla JavaScript for building powerful web applications](https://plainjs.com/)

- [ ] **Check dependencies size limit:** ![low] Ensure to use wisely external libraries, most of the time, you can use a lighter library for a same functionality.

    *¿Por qué?:*
    > You may be tempted to use one of the 745 000 packages you can find on [npm](https://www.npmjs.com/), but you need to choose the best package for your needs. For example, MomentJS is an awesome library but with a lot of methods you may never use, that's why Day.js was created. It's just 2kB vs 16.4kB gz for Moment.

    *¿Cómo?:*
    > Always compare and choose the best and lighter library for your needs. You can also use tools like [npm trends](http://www.npmtrends.com/) to compare NPM package downloads counts or [Bundlephobia](https://bundlephobia.com/) to know the size of your dependencies.

    * 🛠 [ai/size-limit: Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error.](https://github.com/ai/size-limit)
    * 🛠 [webpack-bundle-analyzer - npm](https://www.npmjs.com/package/webpack-bundle-analyzer)
    * 📖 [Size Limit: Make the Web lighter — Martian Chronicles, Evil Martians’ team blog](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter)

- [ ] **JavaScript Profiling:** ![medium] Check for performance problems in your JavaScript files (and CSS too).

    *¿Por qué?:*
    > JavaScript complexity can slow down runtime performance. Identifying these possible issues are essential to offer the smoothest user experience.

    *¿Cómo?:*
    > Use the Timeline tool in the Chrome Developer Tool to evaluate scripts events and found the one that may take too much time.

     * 📖 [Speed Up JavaScript Execution  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
    * 📖 [JavaScript Profiling With The Chrome Developer Tools — Smashing Magazine](https://www.smashingmagazine.com/2012/06/javascript-profiling-chrome-developer-tools/)
    * 📖 [How to Record Heap Snapshots  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/memory-problems/heap-snapshots)
    * 📖 [Chapter 22 - Profiling the Frontend - Blackfire](https://blackfire.io/docs/book/22-frontend-profiling)
    * 📖 [30 Tips To Improve Javascript Performance](http://www.monitis.com/blog/30-tips-to-improve-javascript-performance/)

- [ ] **Use of Service Workers:** ![medium] You are using Service Workers in your PWA to cache datas or execute possible heavy tasks without impacting the user experience of your application.
   
    * 📖 [Service Workers: an Introduction  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/primers/service-workers/)
    * 📖 [Measuring the Real-world Performance Impact of Service Workers  |  Web  |  Google Developers](https://developers.google.com/web/showcase/2016/service-worker-perf)
    * 📖 [What Are Service Workers and How They Help Improve Performance](https://www.keycdn.com/blog/service-workers/)
    * 📖 [How does a service worker work? - YouTube](https://www.youtube.com/watch?v=__xAtWgfzvc)

**[⬆ volver arriba](#tabla-de-contenidos)**

## Server

![server-side]

- [ ] **Your website is using HTTPS:** ![high] 

    *¿Por qué?:*
    > HTTPS is not only for ecommerce websites, but for all websites that is exchanging datas. Datas shared by a user or datas shared to an external entity. Modern browsers today limit functionalities for sites that are not secure. For example: geolocation, push notifications and service workers don't work if your instance is not using HTTPS. And today is much more easy to setup a project with an SSL certificate than it was before (and for free, thanks to [Let's Encrypt](https://letsencrypt.org/)).

 * 📖 [Why Use HTTPS? | Cloudflare](https://www.cloudflare.com/learning/security/why-use-https/)
 * 📖 [Enabling HTTPS Without Sacrificing Your Web Performance - Moz](https://moz.com/blog/enabling-https-without-sacrificing-web-performance)
 * 📖 [How HTTPS Affects Website Performance](https://wp-rocket.me/blog/https-affects-website-performance/)
 * 📖 [HTTP versus HTTPS versus HTTP2 - The real story | Tune The Web](https://www.tunetheweb.com/blog/http-versus-https-versus-http2/)
 * 📖 [HTTP vs HTTPS — Test them both yourself](https://www.httpvshttps.com/)

- [ ] **Page weight < 1500 KB (ideally < 500 KB):** ![high] Reduce the size of your page + resources as much as you can.

    *¿Por qué?:*
    > Ideally you should try to target < 500 KB but the state of web shows that the median of Kilobytes is around 1500 KB (even on mobile). Depending on your target users, network connection, devices, it's important to reduce as much as possible your total Kilobytes to have the best user experience possible.

    *¿Cómo?:*
    > ⁃ All the rules inside the Front-End Performance Checklist will help you to reduce as much as possible your resources and your code.

    * 📖 [Page Weight](https://httparchive.org/reports/page-weight#bytesTotal)
    * 🛠 [What Does My Site Cost?](https://whatdoesmysitecost.com/)
    * 🛠 [web - Measure full page size in Chrome DevTools - Stack Overflow](https://stackoverflow.com/questions/38239980/measure-full-page-size-in-chrome-devtools)

- [ ] **Page load times < 3 seconds:** ![high] Reduce as much as possible your page load times to quickly deliver your content to your users.

    *¿Por qué?:*
    > Faster your website or app is, less you have probability of bounce increases, in other terms you have less chances to lose your user or future client. Enough researches on the subject prove that point.

    *¿Cómo?:*
    > Use online tools like [Page Speed Insight](https://developers.google.com/speed/pagespeed/insights/) or [WebPageTest](https://www.webpagetest.org/) to analyze what could be slowing you down and use the Front-End Performance Checklist to improve your load times.

    * 🛠 [Compare your mobile site speed](https://www.thinkwithgoogle.com/feature/mobile/)
    * 🛠 [Test Your Mobile Website Speed and Performance - Think With Google](https://testmysite.thinkwithgoogle.com/intl/en-us)
    * 📖 [Average Page Load Times for 2018 - How does yours compare? - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/average-page-load-times-websites-2018/)

- [ ] **Time To First Byte < 1.3 seconds:** ![high] Reduce as much as you can the time your browser waits before receiving data.

    * 📖 [What is Waiting (TTFB) in DevTools, and what to do about it](https://scaleyourcode.com/blog/article/27)
    * 📖 [Monitoring your servers with free tools is easy](https://scaleyourcode.com/blog/article/7)
    * 📖 [Time to First Byte (TTFB)](https://varvy.com/pagespeed/ttfb.html)
    * 🛠 [Global latency testing tool](https://latency.apex.sh)

* [ ] **Cookie size:** ![medium] If you are using cookies be sure each cookie doesn't exceed 4096 bytes and your domain name doesn't have more than 20 cookies.

    *¿Por qué?:*
    > cookies are exchanged in the HTTP headers between web servers and browsers. It's important to keep the size of cookies as low as possible to minimize the impact on the user's response time.

    *¿Cómo?:*
    > Eliminate unnecessary cookies

    * 📖 [Cookie specification: RFC 6265](https://tools.ietf.org/html/rfc6265)
    * 📖 [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
    * 🛠 [Browser Cookie Limits](http://browsercookielimits.squawky.net/)
    * 📖 [Website Performance: Cookies Don't Taste So Good - Monitis Blog](http://www.monitis.com/blog/website-performance-cookies-dont-taste-so-good/)
    * 📖 [Google's Web Performance Best Practices #3: Minimize Request Overhead - GlobalDots Blog](https://www.globaldots.com/googles-web-performance-best-practices-3-minimize-request-overhead/)

- [ ] **Minimizing HTTP requests:** ![high] Always ensure that every file requested are essential for your website or application.
 * 📖 [Combine external CSS](https://varvy.com/pagespeed/combine-external-css.html)
 * 📖 [Combine external JavaScript](https://varvy.com/pagespeed/combine-external-javascript.html)

- [ ] **Use a CDN to deliver your assets:** ![medium] Use a CDN to deliver faster your content over the world.

 * 📖 [10 Tips to Optimize CDN Performance - CDN Planet](https://www.cdnplanet.com/blog/10-tips-optimize-cdn-performance/)
 * 📖 [HTTP Caching  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

- [ ] **Serve files from the same protocol:** ![high] Avoid having your website serving files coming from source using HTTP on your website which is using HTTPS for example. If your website is using HTTPS, external files should come from the same protocol.

- [ ] **Serve reachable files:** ![high] Avoid requesting unreachable files (404).
 * 📖 [How to avoid bad requests](https://varvy.com/pagespeed/avoid-bad-requests.html)

- [ ] **Set HTTP cache headers properly:** ![high] Set HTTP headers to avoid expensive number of roundtrips between your browser and the server.
 * 📖 [Using cache-control for browser caching](https://varvy.com/pagespeed/cache-control.html)

- [ ] **GZIP / Brotli compression is enabled:** ![high] Use a compression method such as Gzip or Brotli to reduce the size of your JavaScript files. With a smaller sizes file, users will be able to download the asset faster, resulting in improved performance.

 * 🛠 [Check GZIP compression](https://checkgzipcompression.com/)
 * 🛠 [Check Brotli Compression](https://tools.keycdn.com/brotli-test)
 * 📖 [Can I use... Brotli](https://caniuse.com/#feat=brotli)

**[⬆ volver arriba](#tabla-de-contenidos)**

---
## Performances and JS Frameworks

### Angular
 * 📖 [Angular Performance Checklist](https://github.com/mgechev/angular-performance-checklist)

### React

 * 📖 [Optimizing Performance - React](https://reactjs.org/docs/optimizing-performance.html)
 * 📖 [React image manipulation | Cloudinary](https://cloudinary.com/documentation/react_image_manipulation)
 * 📖 [Debugging React performance with React 16 and Chrome Devtools.](https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad)

### Vue

## Rendimiento y CMS

### WordPress

* 🛠 [Test Your Website Speed | WordPress Hosting by @WPEngine](https://wpengine.com/speed-tool/)

#### Artículos

 * 📖 [19 Tips to Speed Up WordPress Performance (Updated)](https://www.wpbeginner.com/wordpress-performance-speed/)
 * 📖 [Speed Up Your WordPress - How to Save Images Optimized for Web](https://www.wpbeginner.com/beginners-guide/speed-wordpress-save-images-optimized-web/)

#### Plugins recomendados

* 🛠 [Caching Plugin for WordPress - Speed up your website with WP Rocket](https://wp-rocket.me/)
* 🛠 [WP-Sweep | WordPress.org](https://wordpress.org/plugins/wp-sweep/)
* 🛠 [Imagify Image Optimizer | WordPress.org](https://wordpress.org/plugins/imagify/)

---

## Traducciones

¡Lista de requerimientos para el rendimiento front-end quiere estar disponible en otros idiomas! ¡No dudes en enviar su contribución!

* 🇵🇹 Portuguese: [fernandofawkes/Front-End-Performance-Checklist](https://github.com/fernandofawkes/Front-End-Performance-Checklist)
* 🇨🇳 Chinese: [JohnsenZhou/Front-End-Performance-Checklist](https://github.com/JohnsenZhou/Front-End-Performance-Checklist)
* 🇷🇺 Russian: [lex111/Front-End-Performance-Checklist](https://github.com/lex111/Front-End-Performance-Checklist)
* 🇫🇷 French: [WilliamDASILVA/Front-End-Performance-Checklist](https://github.com/WilliamDASILVA/Front-End-Performance-Checklist)
* 🇰🇷 Korean: [ParkSB/Front-End-Performance-Checklist](https://github.com/ParkSB/Front-End-Performance-Checklist)

## Contribuir

**Abre un issue o un pull request para sugerir cambios o adiciones.**

## Apoyo

Si tiene alguna pregunta o sugerencia, no dude en usar Gitter o Twitter:

* [Chat en Discord](https://discord.gg/btHQRkm)
* [Facebook](https://www.facebook.com/frontendchecklist/)
* [Twitter](https://twitter.com/thedaviddias)

## Autor

**Hecho con ❤️ por [David Dias](https://github.com/thedaviddias) en [@influitive](https://influitive.com/) 🇨🇦**

## Colaboradores

Este proyecto existe gracias a todas las personas que contribuyen. [[Contribuir]](.github/CONTRIBUTING.md).
<a href="https://github.com/thedaviddias/Front-End-Performance-Checklist/graphs/contributors">
    <img src="https://opencollective.com/front-end-checklist/contributors.svg?width=890" />
</a>


## Backers

¡Gracias a todos nuestros backers! 🙏 [[Conviertete en un backer](https://opencollective.com/front-end-checklist#backer)]

<a href="https://opencollective.com/front-end-checklist#backers" target="_blank"><img src="https://opencollective.com/front-end-checklist/backers.svg?width=890"></a>


## Patrocinadores

Apoya este proyecto convirtiéndote en un patrocinador. Tu logo aparecerá aquí con un enlace a tu sitio web. [[Conviértete en patrocinador] (https://opencollective.com/front-end-checklist#sponsor)]

<a href="https://opencollective.com/front-end-checklist/sponsor/0/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/1/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/2/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/3/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/4/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/5/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/6/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/7/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/8/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/9/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/9/avatar.svg"></a>

## Licencia

[MIT](LICENSE)

Todos los iconos son provistos por [Icons8](https://icons8.com/)

**[⬆ volver arriba](#tabla-de-contenidos)**

[logo]: images/logo-front-end-performance-checklist.jpg
[html]: images/html.png
[css]: images/css.png
[fonts]: images/fonts.png
[images]: images/images.png
[javascript]: images/javascript.png
[server-side]: images/server-side.png

[low]: https://front-end-checklist.now.sh/low.svg
[medium]: https://front-end-checklist.now.sh/medium.svg
[high]: https://front-end-checklist.now.sh/high.svg
