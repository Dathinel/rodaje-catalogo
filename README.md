<p align="center">
  <a href="https://github.com/Dathinel/rodaje"><img src="https://raw.githubusercontent.com/Dathinel/rodaje/main/assets/marca/rodaje.svg" alt="Logotipo de Rodaje" width="104"></a>
</p>

<h1 align="center">rodaje-catalogo</h1>

<p align="center">
  Catálogo de complementos de <a href="https://github.com/Dathinel/rodaje">Rodaje</a>: un índice firmado con qué paquetes, módulos y modelos se pueden descargar, con su URL, SHA-256 y tamaño.
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/licencia-CC0_1.0-E8833A?style=flat-square&labelColor=1D1D1D" alt="Licencia CC0 1.0"></a>
  <a href="https://github.com/Dathinel/rodaje-catalogo/releases/latest"><img src="https://img.shields.io/github/v/release/Dathinel/rodaje-catalogo?style=flat-square&labelColor=1D1D1D&color=E8833A&label=%C3%ADndice" alt="Última release del índice"></a>
  <img src="https://img.shields.io/badge/entradas-80-E8833A?style=flat-square&labelColor=1D1D1D" alt="80 entradas">
  <img src="https://img.shields.io/badge/firma-ECDSA_P--256-E8833A?style=flat-square&labelColor=1D1D1D" alt="Firma ECDSA P-256">
  <a href="https://github.com/Dathinel/rodaje"><img src="https://img.shields.io/badge/para-Rodaje-E8833A?style=flat-square&labelColor=1D1D1D" alt="Para Rodaje"></a>
</p>

No tiene código: solo [releases](https://github.com/Dathinel/rodaje-catalogo/releases) con `indice.json` e `indice.json.sig` (firma ECDSA P-256 de Dathinel).

Rodaje lee la última release (`releases/latest/download/indice.json`), comprueba la firma con la clave pública que lleva dentro y solo entonces baja cada archivo, que también se verifica por hash. Un índice sin firma válida o más viejo que el último visto se rechaza.

## Índice actual: v7

[v7](https://github.com/Dathinel/rodaje-catalogo/releases/tag/v7) tiene **80 entradas**, una por versión de cada paquete y modelo: 16 complementos (9 de contenido y 7 módulos) y 51 modelos distintos. Las versiones anteriores siguen en el índice.

| Complemento | Tipo | Última versión | Repositorio |
|---|---|---|---|
| Transiciones | Contenido | 1.2.0 | [rodaje-transiciones](https://github.com/Dathinel/rodaje-transiciones) |
| Filtros y looks | Contenido | 1.1.0 | [rodaje-filtros](https://github.com/Dathinel/rodaje-filtros) |
| Fuentes | Contenido | 1.0.0 | [rodaje-fuentes](https://github.com/Dathinel/rodaje-fuentes) |
| Estilos de texto | Contenido | 1.0.0 | [rodaje-titulos](https://github.com/Dathinel/rodaje-titulos) |
| Zonas de encuadre | Contenido | 1.0.0 | [rodaje-zonas](https://github.com/Dathinel/rodaje-zonas) |
| LUT de cámara | Contenido | 1.0.0 | [rodaje-camaras](https://github.com/Dathinel/rodaje-camaras) |
| Efectos de sonido | Contenido | 1.0.0 | [rodaje-sonidos](https://github.com/Dathinel/rodaje-sonidos) |
| Preajustes pro | Contenido | 1.0.0 | [rodaje-preajustes-pro](https://github.com/Dathinel/rodaje-preajustes-pro) |
| Video 360 | Contenido | 1.0.0 | [rodaje-360](https://github.com/Dathinel/rodaje-360) |
| Codificadores GPL (x264, x265) | Módulo | 0.2.0 | [rodaje-codificadores-gpl](https://github.com/Dathinel/rodaje-codificadores-gpl) |
| Subtítulos automáticos | Módulo de IA | 1.1.0 | [modulo-subtitulos](https://github.com/Dathinel/modulo-subtitulos) |
| Traducir subtítulos | Módulo de IA | 1.0.1 | [modulo-traducir](https://github.com/Dathinel/modulo-traducir) |
| Texto a voz | Módulo de IA | 1.0.0 | [modulo-voz](https://github.com/Dathinel/modulo-voz) |
| Ruido y detección de voz | Módulo de IA | 1.0.0 | [modulo-audio-ia](https://github.com/Dathinel/modulo-audio-ia) |
| Visión (fondo, rostros, reencuadre) | Módulo de IA | 1.1.0 | [modulo-vision](https://github.com/Dathinel/modulo-vision) |
| RAW (CinemaDNG) | Módulo | 1.0.0 | [modulo-raw](https://github.com/Dathinel/modulo-raw) |

Cómo se instalan desde la app: [guía de complementos](https://github.com/Dathinel/rodaje/blob/main/docs/guia/complementos.md).

## Licencia

CC0 1.0 (dominio público), ver `LICENSE`. El logotipo de Rodaje es marca de su autor y no forma parte de este contenido ([TRADEMARK.md](https://github.com/Dathinel/rodaje/blob/main/TRADEMARK.md)).
