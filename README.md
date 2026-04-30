# nombre del equipo: LOS F_C_J
Integrantes:

Jose Alejandro Martinez

Cristian Diaz

Luis Felipe Rueda Saldarriaga

enlace:
https://github.com/luisrueda45/F_C_J.git

Nombre empresa: FCJ_IronFit

sector economico: terciario

Descripcion:

El gimnacio maneja la informacion de clientes y pagos de forma manual, lo que genera desorden y errores.
No cuenta con reportes claros para conocer ingresos ni clientes activos.
Por ellos necesita un sistema de informacion que automatice los procesos y mejoren la organizacion y la toma decisiones 

Solucion: 

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

# Procesos:

## ¿Que hace el sistema con esos datos?

* Registrar clientes 

* Controlar pagos 

* Organizar inventario

* Genera reportes automaticos

## ¿Valida?

Si

* Verifica que los campos esten completos.

* Controla que los pagos correspondan al cliente.

* Puede validar fechar de vencimiento.

## ¿Calcula?

Si

* Total de ingresos.

* Clientes activos.

* Pagos pendientes.

## ¿Guarda?

* Si, Almacena toda la informacion en una base de datos para consultar futuramente.

  
# ¿Son números, texto, archivos?

Texto: nombres, direcciones, correos, tipo de plan.

Números: montos de pago, cantidades de inventario, número de clientes.

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

# USUARIOS

## ¿Quién usa el sistema?

* Administrador del gimnasio.

* Recepcionista o personal administrativo.

## ¿Todos hacen lo mismo?

No, solo el administrador puede ver y configurar el sistema y el recepcionista puede regristar clientes y pagos

## ¿Hay permisos?

* Si, hay diferentes niveles de acceso segun el rol que se tenga (Administador o empleado)

    # INFORMACION

## ¿Qué datos son críticos?

* Datos personales de los clientes.

* Información de pagos e ingresos.

* Estado de clientes activos.

## ¿Qué no se puede perder?

* Historial de pagos.

* Base de datos de clientes.

* Información financiera del gimnasio.

  # Diagrama de flujo login 1

  <img width="399" height="538" alt="image" src="https://github.com/user-attachments/assets/b7c32927-231e-4786-9eeb-2f4891eebf8f" />

  # Diagrama de flujo login 1

  <img width="492" height="649" alt="image" src="https://github.com/user-attachments/assets/5639b948-1ca4-4eaa-90d7-584d33a633a6" />

  # Diagrama de flujo proceso principal

  <img width="381" height="619" alt="image" src="https://github.com/user-attachments/assets/cfdef518-3bdc-409c-bff5-60cb841118a8" />

  # Diagrama de flujo otro proceso del sistema

  <img width="439" height="573" alt="image" src="https://github.com/user-attachments/assets/d1269d8b-80fd-4893-a481-9c457f2403c6" />

  # Diagrama Registro de usuario
<img width="566" height="885" alt="image" src="https://github.com/user-attachments/assets/c433f4ae-1fe7-43d3-b62a-cee6f8021438" />


# Diagrama Inicio Sesion
<img width="518" height="808" alt="image" src="https://github.com/user-attachments/assets/01f22c45-a2d0-4fb2-b64f-059713333b8a" />

# Diagrama Registro de membresia
<img width="245" height="284" alt="image" src="https://github.com/user-attachments/assets/1c0afca7-3f98-4c91-9141-24ad45457923" />










 
