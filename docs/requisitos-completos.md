# Requisitos Detallados — Sistema Inventario Ferretería

## Requisitos funcionales (completos)

### RF-01: Gestión de productos
El sistema permitirá al administrador registrar productos con los siguientes campos:
- Código único (autogenerado)
- Nombre del producto
- Descripción breve
- Categoría (seleccionable de lista)
- Precio unitario
- Stock inicial

### RF-02: Control de existencias
Al registrar una venta, el sistema descontará automáticamente la cantidad vendida del stock. Al registrar una compra, sumará la cantidad ingresada.

### RF-03: Consulta de inventario
El sistema permitirá buscar productos por nombre, código o categoría, mostrando: código, nombre, stock actual, precio y categoría.

## Requisitos no funcionales (completos)

### RNF-01: Rendimiento
Las consultas de inventario deben responder en menos de 3 segundos para hasta 10,000 productos.

### RNF-02: Seguridad
Solo usuarios autenticados pueden modificar datos. Las contraseñas se almacenarán con hash bcrypt.

### RNF-03: Disponibilidad
El sistema debe estar disponible el 99.5% del tiempo en horario comercial (lunes a sábado, 8:00-18:00).
