# Arquitectura del sistema: Tienda SC

## Entrada(imputs)
* ¿Que datos recibe el sistema?
   productos, precios y cantidad.
  
* ¿Quien los ingresa?
   Administradores.
  
* ¿Son numeros, texto, archivos?
   Numeros y texto.

## Procesos(Throughput)
* ¿Que hace el sistema con esos datos?
   Controla, organiza y gestiona los productos.
  
* ¿Valida?
   Nombre de los productos, que usen numeros para el precio y la cantidad de stock.
  
* ¿Calcula?
   Calcula la cantidad del producto que queda y las ganancias.
  
* ¿Guarda?
   Datos del Administrador, todos los datos del producto.

## Salida(outputs)
* ¿Que optiene el usuario?
   Control en el inventario del local.
  
* ¿Que genera el sistema?
   Un listado de los datos de los productos.
  
* ¿Permite tomar decisiones?
   Si, porque notaria que productos se venden mas y se abasteceria de los productos necesarios.

## Usuarios y roles
* ¿Quien usa el sistema?
   El dueño del local y un trabajador.
  
* ¿Todos hacen lo mismo?
   Si, accederan a la misma informacion.
  
* ¿Hay permisos?
   Si, un login donde pondran digitar los datos para acceder unicamente ellos y nadie mas.

## Información manejada
* ¿Que datos son críticos?
   Permisos del usuario, los precios correctos de los productos, el nombre del producto para evitar que se duplique y la cantidad en stock para evitar que se marquen ventas inexistentes.
  
* ¿Que no se puede perder?
   las ventas realizadas, los precios y nombres establecidos para los productos.





