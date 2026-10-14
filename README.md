# Generador de Presupuestos versión 3.2

## v3.2 – 14/10/2026
- Nueva "Vista previa PDF" en Exportar: revisá el presupuesto antes de descargarlo.
- Nueva "Descargar plantilla de ejemplo" en Importar: CSV con los encabezados correctos y filas de ejemplo.
- Atajos en la tabla: Enter baja a la misma columna de la fila siguiente; Ctrl+Enter agrega una fila.

## v3.1 – 14/10/2026
- Nuevo botón "Limpiar Encabezado": borra cliente, número, fecha, moneda, IVA y cotizaciones, sin tocar los ítems.
- "Limpiar Todo" pasa a llamarse "Limpiar Ítems" y borra solo la tabla.
- Las cotizaciones (Dólar BNA, Dólar Divisa, Euro) arrancan en 0. Si un presupuesto usa una moneda sin cotización, la app lo avisa.
- Se quitó la leyenda "Edición Local Windows" del encabezado.

## Versiones anteriores
El detalle completo está en [`CHANGELOG.txt`](CHANGELOG.txt).

- **v3.1:** botón "Limpiar Encabezado" (sin tocar ítems); "Limpiar Todo" pasa a "Limpiar Ítems"; cotizaciones arrancan en 0 con aviso si falta una; se quitó "Edición Local Windows".
- **v3.0:** corregido el CSV: en presupuestos en dólares, Costo Neto, Precio Venta y Total son números que Excel suma (la moneda va en el encabezado).
- **v2.9:** Nro. Cliente y Cliente / Empresa obligatorios, validados contra `clientes.csv`, con sugerencias de tipeo; PDF/CSV se bloquean si faltan datos.
- **v2.8:** autocompletado de Cliente / Empresa desde el Nro. Cliente (`clientes.csv`); se vacía al borrar el código.
- **v2.7:** Desc 4 y Desc 5 admiten descuentos negativos (hasta -100 %), mostrados en rojo.
- **v2.6:** la importación completa Detalle y Marca desde el catálogo; PDF con columna Observaciones y encabezado "Propuesta económica"; CSV con importes en formato moneda de 2 decimales.
