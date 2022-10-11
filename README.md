# Formato de imágenes WebP
[![Licencia: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Una manera de utilizar imágenes con formato (.webp) en una página web adaptandose a diferentes tamaños de pantalla y mejorando el rendimiento de la velocidad de carga frente a recursos (.jpg, .png..). 

## Ejemplo de uso
```XML
<picture>
   <!--[if IE 9]><video style="display: none;"><![endif]-->
   <source type="image/webp" srcset="img/example-01.webp 1200w, img/example-01-tablet.webp 700w, img/example-01-mobile.webp 340w" sizes="(min-width: 1200px) 740px, (min-width: 768px) 700px, calc(100vw - 36px)" />
   <source type="image/jpg" srcset="img/example-01.jpg 1200w, img/example-01-tablet.jpg 700w, img/example-01-mobile.jpg 340w" sizes="(min-width: 1200px) 740px, (min-width: 768px) 700px, calc(100vw - 36px)" />
   <!--[if IE 9]></video><![endif]-->
   <img src="img/example01.jpg" alt="Texto alternativo." title="Título." />
</picture>
```

Puede consultar el ejemplo en [jaracoder.com/examples/webp-images](https://jaracoder.com/examples/webp-images/index.html).

## Licencia

Este proyecto está bajo la licencia de [GNU General Public License v3.0](https://github.com/jaracoder/webp-images/blob/master/LICENSE.MD).

---
<sub>
  &copy; Copyright 2020. Escrito con ❤️ por <a href="https://jaracoder.com">JARACODER</a>.
</sub>
