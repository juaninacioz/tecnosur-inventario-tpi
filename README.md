# TecnoSur S.R.L. | Módulo de Gestión de Inventario

**Trabajo Práctico Integrador y Progresivo · Organización Empresarial · UTN**  
**Integrantes:** Ángel Guillermo Forte y Juan Ignacio Ruiz.  
**Carrera:** Tecnicatura Universitaria en Programación a Distancia.

## Descripción del proyecto

TecnoSur S.R.L. es una empresa ficticia de venta minorista de tecnología y servicio técnico. El proyecto propone un módulo centralizado para gestionar productos, repuestos, existencias, ingresos, salidas, ajustes, alertas de stock mínimo y trazabilidad. Se trata de una propuesta documental y de diseño; no se afirma que exista una implementación productiva.

### Objetivo general de la Entrega 2

Desarrollar, probar e implementar el módulo en **16 semanas**, con el propósito de reducir **90 % las discrepancias** entre el stock físico y el registrado y mejorar la reposición. Como metas específicas se fijaron: catálogo activo consolidado durante las cinco primeras semanas; prevención de ventas sin stock para la semana 11; reducción del 30 % de los tiempos de preparación en los primeros 60 días después de la puesta en producción; capacitación del 100 % del personal antes del lanzamiento.

## Documentación del TPI

- [Entrega 1 – Enfoque sistémico](docs/entregas/TPI_Entrega_1_Forte_Ruiz.pdf).
- [Entrega 2 – Planeación administrativa](docs/entregas/TPI_Entrega_2_Forte_Ruiz.pdf).
- [Entrega 3 – Estructura y diccionario de datos](docs/entregas/TPI_Entrega_3_Forte_Ruiz.pdf).
- [Entrega 4 – Procesos, trabajo colaborativo y control](docs/entregas/TPI_Entrega_4_Forte_Ruiz.pdf).
- [Proceso BPMN: salida de inventario](docs/bpmn/salida_inventario.bpmn) · [imagen](docs/bpmn/salida_inventario.png).
- [Proceso BPMN: reposición](docs/bpmn/reposicion_stock.bpmn) · [imagen](docs/bpmn/reposicion_stock.png).
- [Backlog de historias de usuario](docs/backlog.md).
- [Indicadores de control](docs/control/indicadores.md).

Los archivos `.bpmn` permiten abrir y editar los diagramas con un modelador compatible con BPMN 2.0.

## Estructura de la información

El diccionario de datos de la Entrega 3 propone cinco entidades: **Producto**, **Categoría**, **Proveedor**, **MovimientoInventario** y **Usuario**. No se incorporan entidades nuevas como si ya hubieran sido aprobadas; la referencia a la orden de reparación o compra se mantiene como campo descriptivo de un movimiento.

## Trabajo colaborativo

El trabajo se versiona en la rama `main` y en ramas de corta duración. Cada cambio lleva un commit descriptivo y se integra con un Pull Request revisado por el otro integrante.

- **Repositorio público:**
- **Tablero (GitHub Projects o Jira):**
- **Pull Request revisado:**

## Declaración de Uso de IA

Se utilizó **ChatGPT** como apoyo para estructurar un borrador de la Entrega 4, organizar la descripción de procesos, elaborar diagramas preliminares, redactar historias de usuario y contrastar las nuevas secciones con las Entregas 1, 2 y 3 y con la consigna de la cátedra.

La orientación central provino de las instrucciones de los estudiantes: **tomar como referencia los tres trabajos entregados y preparar la nueva entrega y sus archivos**, evitando modificar sin fundamento el caso TecnoSur. Este tipo de instrucción es preferible a pedir una respuesta genérica porque delimita el caso y obliga a recuperar elementos concretos (las cinco entidades, el objetivo de 16 semanas, las áreas y las reglas de stock).

**Límites y evaluación crítica:** los resultados generados por IA no prueban que se haya creado un repositorio, un PR, una revisión de pares ni un tablero activo. Tampoco pueden sustituir la comprobación humana de la semántica BPMN, los criterios de aceptación ni los indicadores.

**Correcciones humanas:** los autores revisan los flujos y los porcentajes frente a los trabajos previos, abren los diagramas `.bpmn` en un modelador y validan las historias y los indicadores antes de presentar el trabajo.
