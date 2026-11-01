# Plan de indicadores y control

Los umbrales provienen de la Entrega 2 cuando se aclara expresamente; los demás son estándares propuestos en la Entrega 4, no mediciones ya obtenidas.

| Indicador | Definición / fórmula | Estándar | Fuente y frecuencia | Responsable |
|---|---|---|---|---|
| Discrepancia física-lógica | Total de unidades de diferencia absoluta entre conteo físico y stock registrado; comparar contra línea base inicial. | Reducir un 90 % respecto de la línea base (Entrega 2). | Inventario físico y registro; al inicio y en cortes semanales. | Depósito y QA. |
| Ventas sin existencia | Ventas confirmadas cuyo stock previo era inferior a la cantidad solicitada. | Cero desde la semana 11 (Entrega 2). | Pruebas de validación y movimientos; por operación y en cierre semanal. | QA y Ventas. |
| Tiempo de preparación | Promedio de minutos desde solicitud válida hasta pedido o repuesto preparado. | Disminuir 30 % a los 60 días de salida en producción (Entrega 2). | Registro temporal; semanal y a 60 días. | Operaciones. |
| Capacitación | Personal operativo capacitado / total operativo x100. | 100 % antes del lanzamiento (Entrega 2). | Asistencia y verificación práctica; al cierre de capacitación. | Analista funcional. |
| Trazabilidad | Movimientos con usuario, fecha/hora, origen y referencia / movimientos totales x100. | 100 % (nuevo control propuesto). | Auditoría de movimientos; semanal. | Sistemas. |
| Alertas correctas | Casos con stock_actual <= stock_minimo que emiten alerta / total de casos probados x100. | 100 % de escenarios definidos (nuevo control propuesto). | Pruebas automáticas/manuales; por versión. | QA. |
| Recepciones no conformes | Recepciones rechazadas que no generan ingreso conforme / total rechazadas x100. | 100 % (nuevo control propuesto). | Muestreo de incidentes; semanal. | Depósito. |
| Calidad de integración | PR a `main` revisados por el otro integrante / PR integrados x100. | 100 % del trabajo publicado (nuevo control propuesto). | Historial de GitHub; por integración. | Forte y Ruiz. |

**Regla:** umbrales no son resultados; deben existir datos de ejecución y una línea de base válida antes de informar logros.
