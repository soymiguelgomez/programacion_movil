**Creacion de apllicacion inventario**

Hecho : Miguel Gomez
        Ivan Perdomo
**Objetivo**

- Una aplicación de inventario , seguimiento y optimización del inventario de una empresa o negocio. Su función fundamental consiste en facilitar un control preciso y eficiente de los bienes o productos disponibles, asegurando la disponibilidad adecuada para satisfacer la demanda, sin incurrir en excesos que puedan generar costos adicionales.

**Identificar proyectos similares**


Holded
Odoo Inventory


**Plantear una justificación**

Para llevar un control,interno desde un negocio pequeño a un negocio grande

**Defina un alcance**

Realizacion de inventario y hacerle salida con la colocacion del usuario que lo hace y generar un informe dependiendo como lo requiera el usuario
- Solo ingresos
- Solo salidas
- Inventario actual 



**Que funcion cumple una aplicacion de inventario**

1. Gestión de Productos:

- Descripción:Permite llevar un registro y organización de todos los productos gestionados por la empresa, incluyendo detalles como el nombre, código, categoría, proveedor, precio y cualquier otra información pertinente.

- Qué hace:Facilita la creación, modificación y eliminación de registros de productos, contribuyendo así al mantenimiento de una base de datos actualizada que contiene información fundamental sobre cada artículo.


2. Control de Stock:

- Descripción:Supervisa en tiempo real las cantidades de cada producto en el inventario.

- Qué hace:Actualiza de manera automática las cantidades de inventario al recibir o vender productos. Genera alertas cuando las existencias de un producto alcanzan niveles mínimos o críticos, lo que permite a la empresa realizar los pedidos de reposición de manera oportuna.


3. Gestión de Proveedores:

- Descripción:Administra la información y relación con los proveedores.

- Qué hace:Permite el registro y la gestión de la información de contacto de los proveedores, la asignación de productos a proveedores específicos y la facilitación del proceso de reabastecimiento.


4. Generación de Reportes:

- Descripción:Ofrece informes detallados sobre el estado del inventario y el rendimiento de los productos.

- Qué hace:Elabora informes que incluyan inventarios actuales, movimientos de stock, productos más vendidos y análisis de rotación de productos. Estos informes pueden ser exportados en formatos como PDF, Excel o CSV para su análisis externo.



**objetivo principal**
- El objetivo fundamental de una aplicación de inventario radica en optimizar la eficiencia operativa y minimizar los costos vinculados a la gestión del inventario. Al contar con un control preciso y automatizado de las existencias, las empresas pueden prevenir situaciones como el desabastecimiento, el exceso de stock y las pérdidas derivadas de la caducidad o deterioro de los productos. Asimismo, esta herramienta ofrece una visión clara y actualizada del estado del inventario, facilitando así la toma de decisiones estratégicas.



**Requerimiento Funcionales**


1. Gestión de Productos:

- Registrar productos con detalles como nombre, código, categoría, precio, y proveedor.
- Editar información de los productos existentes.
- Eliminar productos del inventario.

2. Control de Stock:

- Actualizar cantidades de stock automáticamente al recibir o vender productos.
- Notificar al usuario cuando el stock de un producto alcance un nivel mínimo.
- Registrar el historial de movimientos de stock (entradas y salidas).

3. Gestión de Proveedores:

- Registrar y gestionar información de proveedores.
- Asignar productos a proveedores específicos.

4.Generación de Reportes:

- Generar reportes sobre el inventario actual, movimientos de stock, productos más vendidos, etc.
- Exportar reportes en formatos como PDF, Excel, o CSV.


**Requerimiento No Funcionales**

1. Rendimiento:

- La aplicación debe ser capaz de manejar un gran número de transacciones sin degradación en el rendimiento.
- El tiempo de respuesta de las operaciones críticas no debe exceder de 2 segundos.

2. Escalabilidad:

- El sistema debe ser escalable para manejar un número creciente de usuarios y datos.

3. Seguridad:

- Implementar autenticación segura (como autenticación de dos factores).
- Encriptar datos sensibles, como contraseñas y datos de transacciones.
- Auditoría de las acciones de los usuarios en el sistema.

4. Usabilidad:

- Interfaz de usuario intuitiva y fácil de navegar.
- Accesibilidad para personas con discapacidades.