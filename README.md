# Generador de Presupuestos versión 3.1

## v3.1 – 14/10/2026
- Nuevo botón "Limpiar Encabezado": borra cliente, número, fecha, moneda, IVA y cotizaciones, sin tocar los ítems.
- "Limpiar Todo" pasa a llamarse "Limpiar Ítems" y borra solo la tabla.
- Las cotizaciones (Dólar BNA, Dólar Divisa, Euro) arrancan en 0. Si un presupuesto usa una moneda sin cotización, la app lo avisa.
- Se quitó la leyenda "Edición Local Windows" del encabezado.

## Versiones anteriores
El detalle completo está en [`CHANGELOG.txt`](CHANGELOG.txt).

- **v3.0:** corregido el CSV: en presupuestos en dólares, Costo Neto, Precio Venta y Total son números que Excel suma (la moneda va en el encabezado).
- **v2.9:** Nro. Cliente y Cliente / Empresa obligatorios, validados contra `clientes.csv`, con sugerencias de tipeo; PDF/CSV se bloquean si faltan datos.
- **v2.8:** autocompletado de Cliente / Empresa desde el Nro. Cliente (`clientes.csv`); se vacía al borrar el código.
- **v2.7:** Desc 4 y Desc 5 admiten descuentos negativos (hasta -100 %), mostrados en rojo.
- **v2.6:** la importación completa Detalle y Marca desde el catálogo; PDF con columna Observaciones y encabezado "Propuesta económica"; CSV con importes en formato moneda de 2 decimales.
