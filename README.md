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

# Diagrama de flujo login 1
  <img width="398" height="544" alt="image" src="https://github.com/user-attachments/assets/d6056f62-7d1d-4885-b252-c7ba68fcdfac" />

# Diagrama de flujo login 2
<img width="493" height="646" alt="Captura de pantalla 2026-04-09 175337" src="https://github.com/user-attachments/assets/f143da4b-ff84-4bae-943e-dfce621c45c5" />

# Proceso Principal
<img width="381" height="617" alt="Captura de pantalla 2026-04-09 175227" src="https://github.com/user-attachments/assets/34caf8bd-90fc-4817-a3b4-a71f568aeb21" />

# Diagra de flujo otros procesos del sistema
<img width="435" height="577" alt="image" src="https://github.com/user-attachments/assets/cc0bca02-b353-4cdc-a730-8f150cfa0e60" />

# Diagrama Registro de usuario
<img width="454" height="788" alt="image" src="https://github.com/user-attachments/assets/d6d17bde-400d-4a82-a407-4a9d8c56ad10" />

# Diagrama Inicio Sesion
<img width="518" height="808" alt="image" src="https://github.com/user-attachments/assets/01f22c45-a2d0-4fb2-b64f-059713333b8a" />

# Diagrama Registro de membresia
<img width="245" height="284" alt="image" src="https://github.com/user-attachments/assets/1c0afca7-3f98-4c91-9141-24ad45457923" />
