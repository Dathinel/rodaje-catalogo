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
  <img src="https://img.shields.io/badge/firma-ECDSA_P--256-E8833A?style=flat-square&labelColor=1D1D1D" alt="Firma ECDSA P-256">
  <a href="https://github.com/Dathinel/rodaje"><img src="https://img.shields.io/badge/para-Rodaje-E8833A?style=flat-square&labelColor=1D1D1D" alt="Para Rodaje"></a>
</p>

No tiene código: solo [releases](https://github.com/Dathinel/rodaje-catalogo/releases) con `indice.json` e `indice.json.sig` (firma ECDSA P-256 de Dathinel).

Rodaje lee la última release (`releases/latest/download/indice.json`), comprueba la firma con la clave pública que lleva dentro y solo entonces baja cada archivo, que también se verifica por hash. Un índice sin firma válida o más viejo que el último visto se rechaza.

| Complemento | Repositorio |
|---|---|
| Transiciones | [rodaje-transiciones](https://github.com/Dathinel/rodaje-transiciones) |
| Filtros y LUT | [rodaje-filtros](https://github.com/Dathinel/rodaje-filtros) |

## Licencia

CC0 1.0 (dominio público), ver `LICENSE`. El logotipo de Rodaje es marca de su autor y no forma parte de este contenido ([TRADEMARK.md](https://github.com/Dathinel/rodaje/blob/main/TRADEMARK.md)).
