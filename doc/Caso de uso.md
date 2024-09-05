Caso de uso: Sistema de ventas para librería.

  

Actores: Usuario. (primario).

  

Camino básico:

  

1.  El usuario ingresa el artículo del producto del que quiere realizar la venta.
    
2.  El sistema muestra el precio del producto y muestra las opciones con las que se puede pagar.
    
3.  El usuario elige una opción y en caso de elegir pagar con tarjeta deberá de ingresar los datos.
    
4.  El sistema registra la venta y almacena los datos del cliente en la base de datos.
    

  

Camino alternativo:

  

1.  a. El producto ingresado no existe.
    

1.a.1. El sistema muestra el mensaje “Artículo inexistente”. Vuelve a realizar el paso.

3. a. Los datos ingresados son incorrectos.

3.a.1. El sistema muestra el mensaje “Los datos ingresados son incorrectos" .Regresa al paso 2

  

Escenario de éxito: El sistema realiza el pago y registra la venta.

Escenario de fracaso: El sistema no pudo realizar el pago porque los datos ingresados son incorrectos.
