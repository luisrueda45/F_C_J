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

## Arquitectura del Sistema: LOS F_C_J 

# ENTRADAS:

## ¿Qué datos recibe el sistema?

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

# Procesos:

## ¿Que hace el sistema con esos datos?

* Registrar clientes 

* Controlar pagos 

* Organizar inventario

* Genera reportes automáticos

## ¿Valida?

Si

* Verifica que los campos estén completos.

* Controla que los pagos correspondan al cliente.

* Puede validar fechar de vencimiento.

## ¿Calcula?

Si

* Total de ingresos.

* Clientes activos.

* Pagos pendientes.

## ¿Guarda?

* Si, Almacena toda la información en una base de datos para consultar futuramente.

  # SALIDAS

## ¿Que obtiene el usuario?

* listado de clientes.

* estado de pagos.

* reportes del gimnasio.


## ¿que genera el sistema?

* reporte de ingresos.

* clientes activos e inactivos

* alertas de vencimiento.

## ¿permite tomar decisiones?

* saber ingresos mensuales.

* identificar clientes morosos.

* controlar inventario.

# USUARIOS

## ¿Quién usa el sistema?

* Administrador del gimnasio.

* Recepcionista o personal administrativo.

## ¿Todos hacen lo mismo?

No, solo el administrador puede ver y configurar el sistema y el recepcionista puede registrar clientes y pagos

## ¿Hay permisos?

* Si, hay diferentes niveles de acceso según el rol que se tenga (Administrador o empleado)

# INFORMACION

## ¿Qué datos son críticos?

* Datos personales de los clientes.

* Información de pagos e ingresos.

* Estado de clientes activos.

## ¿Qué no se puede perder?

* Historial de pagos.

* Base de datos de clientes.

* Información financiera del gimnasio.

#Diagrama-de-flujo-login-1

*<img width="398" height="545" alt="image" src="https://github.com/user-attachments/assets/bcd6126d-5bcb-4aec-a0fe-7b38c1767fde" />

#Diagrama-de-flujo-login-2

<img width="475" height="624" alt="image" src="https://github.com/user-attachments/assets/1e996740-bf45-41e6-89ce-f83fec1d84a8" />

#proceso-principal

<img width="350" height="621" alt="image" src="https://github.com/user-attachments/assets/afa26ca6-75a7-4bfb-bd07-c83aa2ef6731" />

#Proceso-del-sistema

<img width="410" height="570" alt="image" src="https://github.com/user-attachments/assets/77b1159b-cd48-4e7b-8e12-7d6f9c79fbf4" />

# diagrama registro de usuario

<img width="454" height="788" alt="image" src="https://github.com/user-attachments/assets/d6d17bde-400d-4a82-a407-4a9d8c56ad10" />

















