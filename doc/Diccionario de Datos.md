DICCIONARIO DE DATOS



Cliente: idCliente + Documento + NombreCompleto + Correo + Telefono + Estado + FechaRegistro

Proveedor: idProveedor + Documento + RazonSocial + Correo + Telefono + Estado + FechaRegistro

Usuario: idUsuario + Documento + NombreCompleto + Correo + Clave + idRol + Estado + FechaRegistro

Categoria: idCategoria + Descripcion + Estado + FechaRegistro

Producto: idProducto + Codigo + Nombre + Descripcion + idCategoria + Stock + PrecioCompra + PrecioVenta + Estado + FechaRegistro

CompraProveedor: idCompra + idUsuario + idProveedor + TipoDocumento + NumeroDocumento + MontoTotal + FechaRegistro

Detalle compra: idDetalle + idCompra + idProducto + PrecioCompra + PrecioVenta + Cantidad + MontoTotal + FechaRegistro

Venta: idVenta + idUsuario + TipoDocumento + NumeroDocumento + DocumentoCliente + NombreCliente + MontoPago + MontoCambio + MontoTotal + FechaRegistro

Detalle venta: idDetalleVenta + idVenta + idProducto + PrecioVenta + Cantidad + SubTotal + FechaRegistro
