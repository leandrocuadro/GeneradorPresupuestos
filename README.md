# Generador de Presupuestos versión 2.9

## v2.9 – 10/10/2026
- Nro. Cliente y Cliente / Empresa ahora son obligatorios y se validan contra la base maestra de clientes (`clientes.csv`).
- Nuevas sugerencias de tipeo en Cliente / Empresa (ej.: "Ter" → TERNIUM ARGENTINA S.A.); al elegir una se completan nombre y Nro. Cliente.
- Exportar PDF/CSV se bloquea si faltan o no coinciden los datos del cliente. El respaldo JSON no se bloquea.

## Versiones anteriores
El detalle completo está en [`CHANGELOG.txt`](CHANGELOG.txt).

- **v2.8:** autocompletado de Cliente / Empresa desde el Nro. Cliente (`clientes.csv`); se vacía al borrar el código.
- **v2.7:** Desc 4 y Desc 5 admiten descuentos negativos (hasta -100 %), mostrados en rojo.
- **v2.6:** la importación completa Detalle y Marca desde el catálogo; PDF con columna Observaciones y encabezado "Propuesta económica"; CSV con importes en formato moneda de 2 decimales.
