# Generador de Presupuestos versión 3.0

## v3.0 – 12/10/2026
- Nueva exportación a Excel (.xlsx) con aspecto profesional: título, datos del presupuesto, encabezados oscuros, filas alternadas, filtros y encabezado inmovilizado.
- Columnas auto-ajustadas y formato moneda con 2 decimales (con la moneda de cada importe); descuentos y margen en %, negativos en rojo.
- Costo Neto y Precio Venta destacados en negrita y verde suave; fila TOTAL con suma automática.
- Listo para imprimir (A4 horizontal, 1 página de ancho) y re-importable en la app. El CSV sigue disponible.

## Versiones anteriores
El detalle completo está en [`CHANGELOG.txt`](CHANGELOG.txt).

- **v2.9:** Nro. Cliente y Cliente / Empresa obligatorios, validados contra `clientes.csv`, con sugerencias de tipeo; PDF/CSV se bloquean si faltan datos.
- **v2.8:** autocompletado de Cliente / Empresa desde el Nro. Cliente (`clientes.csv`); se vacía al borrar el código.
- **v2.7:** Desc 4 y Desc 5 admiten descuentos negativos (hasta -100 %), mostrados en rojo.
- **v2.6:** la importación completa Detalle y Marca desde el catálogo; PDF con columna Observaciones y encabezado "Propuesta económica"; CSV con importes en formato moneda de 2 decimales.
