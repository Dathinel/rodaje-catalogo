# rodaje-catalogo

Catálogo de complementos de [Rodaje](https://github.com/Dathinel/rodaje). No tiene código: solo releases con `indice.json` (qué paquetes, módulos y modelos se pueden descargar, con su URL, SHA-256 y tamaño) e `indice.json.sig` (firma ECDSA P-256 de Dathinel).

Rodaje lee la última release (`releases/latest/download/indice.json`), comprueba la firma con la clave pública que lleva dentro y solo entonces baja cada archivo, que también se verifica por hash. Un índice sin firma válida o más viejo que el último visto se rechaza.

Licencia CC0 1.0.