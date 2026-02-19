# nombre del equipo: LOS F_C_J
# Integrantes:

Jose Alejandro Martinez

Cristian Diaz

Luis Felipe Rueda Saldarriaga

# enlace:
https://github.com/luisrueda45/F_C_J.git

Nombre empresa: FCJ_IronFit

sector economico: terciario

# Descripcion:

El gimnacio maneja la informacion de clientes y pagos de forma manual, lo que genera desorden y errores.
No cuenta con reportes claros para conocer ingresos ni clientes activos.
Por ellos necesita un sistema de informacion que automatice los procesos y mejoren la organizacion y la toma decisiones 

# Solucion: 

Implementar un sistemas (pagina web) que permita registrar clientes, controlar pagos, generar reportes automaticamente y organizar el inventario.
esto mejorara la eficiencia, reducira errores y facilitara la toma de decisiones en el gym

# Arquitectura del Sistema: LOS F_C_J 

## ENTRADAS:

# ¿Qué datos recibe el sistema?

Datos de clientes (nombre, identificación, contacto, plan adquirido).

Información de pagos (monto, fecha, método de pago, estado).

Datos de inventario (productos, cantidad, precios).

# ¿Quién los ingresa?

* Personal administrativo del gimnasio.

* Recepcionista.

* Posiblemente el administrador o dueño.
  
# ¿Son números, texto, archivos?

Texto: nombres, direcciones, correos, tipo de plan.

Números: montos de pago, cantidades de inventario, número de clientes.


## Procesos:

# ¿Que hace el sistema con esos datos?

* Registrar clientes 

* Controlar pagos 

* Organizar inventario

* Genera reportes automaticos

# ¿Valida?

Si

* Verifica que los campos esten completos.

* Controla que los pagos correspondan al cliente.

* Puede validar fechar de vencimiento.

# ¿Calcula?

Si

* Total de ingresos.

* Clientes activos.

* Pagos pendientes.

# ¿Guarda?

* Si, Almacena toda la informacion en una base de datos para consultar futuramente.



## SALIDAS

# ¿Que obtiene el usuario?

*listado de clientes.

esta

## USUARIOS Y ROLES

# ¿Quién usa el sistema?

* Administrador del gimnasio.

* Recepcionista o personal administrativo.

# ¿Todos hacen lo mismo?

No, solo el administrador puede ver y configurar el sistema y el recepcionista puede regristar clientes y pagos

# ¿Hay permisos?

Si, hay diferentes niveles de acceso segun el rol que se tenga (Administador o empleado)

## SALIDAS
# ¿Que obtiene el usuario?

*listado de clientes.

*eestado de pagos.

*reportes del gimnasio.


¿que genera el sistema?

*reporte de ingresos.

*clientes activos e inactivos

*alertas de vencimiento.

¿permite tomar decisiones?

*saber ingresos mensuales.

*identificar clientes morosos.

*controlar inventario.
