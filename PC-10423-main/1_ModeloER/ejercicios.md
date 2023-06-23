
## EJERCICIO 1: 
A partir del siguiente enunciado se desea realizar el modelo entidad-relación. 
Una empresa vende productos a varios clientes.
* Se necesita conocer los datos personales de los clientes (nombre, apellidos, RFC, dirección y fecha de nacimiento).
* Cada producto tiene un nombre y un código, así como un precio unitario. 
* Un cliente puede comprar varios productos a la empresa, y un mismo producto puede ser comprado por varios clientes.
* Los productos son suministrados por diferentes proveedores.
* Se debe tener en cuenta que un producto sólo puede ser suministrado por un proveedor, y que un proveedor puede suministrar diferentes productos.
* De cada proveedor se desea conocer el RFC, nombre y dirección.

[Solución](diagramas/Ejercicio1.pdf)

## EJERCICIO 2: 
Se desea diseñar una base de datos para almacenar y gestionar la información empleada por una empresa dedicada a la venta de automóviles, teniendo en cuenta los siguientes aspectos: 
* La empresa dispone de una serie de coches para su venta. Se necesita conocer la matrícula, marca y modelo, el color y el precio de venta de cada coche. 
* Los datos que interesa conocer de cada cliente son el RFC, nombre, dirección, ciudad y número de teléfono: además, los clientes se diferencian por un código interno de la empresa que se incrementa automáticamente cuando un cliente se da de alta en ella.
* Un cliente puede comprar tantos coches como desee a la empresa. 
* Un coche determinado solo puede ser comprado por un único cliente.
* El concesionario también se encarga de llevar a cabo las revisiones que se realizan a cada coche. 
* Cada revisión tiene asociado un código que se incrementa automáticamente por cada revisión que se haga.
* De cada revisión se desea saber si se ha hecho cambio de filtro, si se ha hecho cambio de aceite, si se ha hecho cambio de frenos u otros. 
* Los coches pueden pasar varias revisiones en el concesionario.

[Solución](diagramas/Ejercicio2.pdf)

## EJERCICIO 3: 
Un micromercado desea diseñar una Base de Datos para llevar el control de ventas. Para esto se tiene que los productos se registran con un código, una descripción, una unidad de venta y un precio unitario. Los clientes se registran con cédula, apellido, nombre, correo electrónico. Las ventas se registran en una factura que se identifica con un número de factura y la fecha; se anota también la forma de pago. Se debe anotar el número de unidades de cada producto que se asocia a la factura.  Se sabe que un cliente puede tener muchas facturas de sus compras y que una factura debe tener un cliente asociado.

[Solución](diagramas/Ejercicio3.pdf)