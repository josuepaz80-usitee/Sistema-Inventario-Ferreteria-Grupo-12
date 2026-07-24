# Diagrama de Clases — Sistema Inventario Ferretería

## Clases principales

### Producto
- codigo (PK): String
- nombre: String
- descripcion: Text
- categoria: String
- precio_unitario: Decimal
- stock_actual: Integer
- proveedor_id (FK): String

### Proveedor
- id (PK): String
- nombre: String
- telefono: String
- email: String
- direccion: Text

### MovimientoStock
- id (PK): Integer
- producto_id (FK): String
- tipo: Enum(ENTRADA, SALIDA)
- cantidad: Integer
- fecha: DateTime
- usuario_id (FK): String

### Usuario
- id (PK): String
- nombre: String
- email: String
- rol: Enum(ADMIN, VENDEDOR)

## Relaciones
- Producto N:1 Proveedor (un proveedor puede suministrar varios productos)
- Producto 1:N MovimientoStock (un producto tiene muchos movimientos)
- Usuario 1:N MovimientoStock (un usuario registra muchos movimientos)
