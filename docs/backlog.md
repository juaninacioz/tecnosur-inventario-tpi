# Backlog ágil · TecnoSur S.R.L.

Las tres HU se **formularon para esta entrega** a partir de las funciones documentadas en los TPI 1, 2 y 3; no se encontraron previamente redactadas con el formato formal de historia de usuario.

## HU-01 · Registrar una salida sin exceder existencias

**Como** vendedor/a de TecnoSur, **quiero** consultar el stock disponible y registrar una venta únicamente cuando existan unidades suficientes, **para** no prometer artículos sin disponibilidad y mantener actualizado el inventario.

**Criterios de aceptación:**
1. Se informa el stock actual del producto antes de confirmar la operación.
2. Una solicitud superior al stock disponible se rechaza sin descontar unidades.
3. Una operación válida registra `MovimientoInventario` de tipo salida y actualiza `Producto.stock_actual`.
4. Cada movimiento guarda fecha/hora, origen, referencia e identificador de usuario.

**Prioridad:** Alta. **Estado inicial propuesto:** Por Hacer. **Issue real:** pendiente de enlazar.

## HU-02 · Alertas y recepción de reposiciones

**Como** responsable de Compras, **quiero** recibir alertas cuando un producto alcance o supere hacia abajo el stock mínimo y registrar el ingreso de mercadería, **para** planificar la reposición con información confiable.

**Criterios de aceptación:**
1. Se emite una alerta cuando `stock_actual <= stock_minimo`.
2. El análisis permite documentar si se autoriza o no la compra.
3. Depósito verifica cantidad y condición antes de registrar una recepción conforme.
4. Un ingreso conforme aumenta el stock y genera un movimiento con origen compra, referencia, fecha y responsable.
5. Una recepción con diferencia se registra como incidencia y no se contabiliza automáticamente como ingreso conforme.

**Prioridad:** Alta. **Estado inicial propuesto:** Por Hacer. **Issue real:** pendiente de enlazar.

## HU-03 · Consumo de repuestos en servicio técnico

**Como** técnico/a de TecnoSur, **quiero** asociar el consumo de repuestos a una orden de reparación y descontarlo del inventario, **para** conocer la disponibilidad real y conservar la trazabilidad de los componentes utilizados.

**Criterios de aceptación:**
1. El sistema comprueba disponibilidad antes de aceptar el consumo.
2. La salida identifica origen reparación y referencia a la orden de trabajo.
3. La operación queda asociada al usuario y fecha/hora.
4. La salida no permite stock negativo y activa la alerta de mínimo cuando corresponde.

**Prioridad:** Media. **Estado inicial propuesto:** Por Hacer. **Issue real:** pendiente de enlazar.

## Tablero

Crear un proyecto (tabla o Kanban) con las columnas **Por Hacer**, **En Progreso**, **Listo**, agregar las tres HU como issues, y mover cada issue al iniciar y finalizar el trabajo. Conservar enlaces y capturas reales de al menos una transición; **no usar esta planificación como evidencia de actividad que no ocurrió**.
