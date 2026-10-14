# Generador de Presupuestos versión 3.0

## v3.0 – 14/10/2026
- Corregido el CSV de exportación: en presupuestos en dólares, Costo Neto Unit., Precio Venta Unit. y Total Precio Venta ahora son números que Excel suma (la moneda va en el encabezado).

## Versiones anteriores
El detalle completo está en [`CHANGELOG.txt`](CHANGELOG.txt).

- **v2.9:** Nro. Cliente y Cliente / Empresa obligatorios, validados contra `clientes.csv`, con sugerencias de tipeo; PDF/CSV se bloquean si faltan datos.
- **v2.8:** autocompletado de Cliente / Empresa desde el Nro. Cliente (`clientes.csv`); se vacía al borrar el código.
- **v2.7:** Desc 4 y Desc 5 admiten descuentos negativos (hasta -100 %), mostrados en rojo.
- **v2.6:** la importación completa Detalle y Marca desde el catálogo; PDF con columna Observaciones y encabezado "Propuesta económica"; CSV con importes en formato moneda de 2 decimales.
