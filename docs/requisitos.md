# Requisitos del Sistema — Inventario Ferretería

## Requisitos funcionales

1. **RF-01:** El sistema debe permitir registrar productos con código único, nombre, descripción, categoría, precio unitario y stock inicial.
2. **RF-02:** El sistema debe actualizar el stock automáticamente al registrar una entrada (compra) o salida (venta) de productos.
3. **RF-03:** El sistema debe permitir consultar productos por nombre, código o categoría y mostrar su stock disponible.

## Requisitos no funcionales

1. **RNF-01:** El sistema debe responder las consultas de inventario en menos de 3 segundos para catálogos de hasta 10,000 productos.
2. **RNF-02:** El sistema debe garantizar que solo usuarios autenticados puedan modificar el inventario, mediante autenticación por usuario y contraseña.
