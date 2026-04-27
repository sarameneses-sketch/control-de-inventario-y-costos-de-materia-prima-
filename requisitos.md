## Introducción
Este documento detalla los requerimientos necesarios para el desarrollo de la plataforma de servicios de marketing.

Requisitos Funcionales (RF)
Estos requisitos definen las funciones específicas que el software debe ejecutar para satisfacer las necesidades de cada área de la empresa.

1. Gestión de Catálogo de Servicios: El sistema debe permitir crear, editar y eliminar los diferentes servicios de publicidad (desarrollo informativo, tarjetas, etc.), asignándoles un costo de producción y un precio de venta.

2. Control de Stock de Materiales: El sistema debe registrar la entrada y salida de insumos (papel, tintas, materiales informáticos) y emitir una alerta automática cuando el inventario llegue a un nivel mínimo crítico.

3. Cálculo de Rentabilidad Mensual: El sistema debe generar reportes financieros que resten los egresos (sueldos, materiales, servicios) de los ingresos por ventas para mostrar la utilidad neta por mes.

4. Registro de Jornada Laboral: El sistema debe permitir que los empleados registren su hora de entrada y salida para el control de asistencia y el cálculo de horas laboradas.

5. Módulo de Gestión de Nómina: El sistema debe calcular automáticamente los pagos mensuales de cada trabajador basándose en su salario base, horas trabajadas y posibles bonificaciones.

6. Gestión de Promociones y Ofertas: El sistema debe permitir aplicar descuentos temporales o "packs" de servicios (ej. Tarjetas + Redes Sociales) que se reflejen automáticamente en el precio final de la factura.

7. Seguimiento de Orden de Producción: El sistema debe permitir visualizar el estado de cada pedido (En diseño, En impresión, Entregado) para que el área de operaciones gestione los tiempos de entrega.

8. Base de Datos de Clientes: El sistema debe almacenar el historial de compras y preferencias de cada cliente para facilitar estrategias de marketing relacional.

9.Presupuesto Automatizado: El sistema debe generar un presupuesto de compra de materiales basado en las órdenes de servicio pendientes y el stock actual en bodega.

10. Tablero de Análisis Estratégico (Dashboard): El sistema debe mostrar gráficos comparativos entre las ventas actuales y las metas de expansión establecidas por la dirección.

 Requisitos No Funcionales (RNF)
Estos requisitos aseguran la calidad, seguridad y eficiencia de la plataforma.

1. Seguridad (Acceso por Roles): El sistema debe implementar un control de acceso basado en roles (RBAC), donde el personal de Recursos Humanos no pueda ver los costos de producción y el de Operaciones no pueda ver la nómina de pagos.

2. Disponibilidad: El sistema debe garantizar una disponibilidad del 99.5% durante el horario laboral, asegurando que las áreas de producción y ventas no se detengan.

3. Usabilidad: La interfaz del sistema debe ser intuitiva, permitiendo que un nuevo empleado pueda realizar un registro de venta o de asistencia con una capacitación previa menor a 2 horas.

4.Rendimiento: El sistema debe procesar y generar los reportes de rentabilidad financiera en un tiempo no mayor a 2 segundos, incluso cuando la base de datos crezca con el paso de los meses.

5. Integridad de Datos: El sistema debe contar con respaldos (backups) automáticos diarios para evitar la pérdida de información financiera o de clientes en caso de fallos en el servidor.


