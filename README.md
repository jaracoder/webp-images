# Imágenes WebP en HTML5
[![Licencia: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

Optimiza la carga de imágenes en tu página web utilizando el formato `.webp`. Aprovecha su capacidad para adaptarse a diferentes tamaños de pantalla y mejorar la velocidad de carga en comparación con otros formatos como `.jpg`, `.png`, etc.

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

Puede ver este ejemplo en [jaracoder.com/examples/webp-images](https://jaracoder.com/examples/webp-images/index.html).

## Licencia

Este proyecto se distribuye bajo la licencia de [GNU General Public License v3.0](https://github.com/jaracoder/webp-images/blob/master/LICENSE.MD).

---
<sub>
  &copy; Copyright 2023. Escrito con ❤️ por <a href="https://jaracoder.com">JARACODER</a>.
</sub>
