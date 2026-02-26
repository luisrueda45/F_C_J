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

  ## ¿A que nivel de decicio0n impacta?

* Principalmente en el nivel operativo y tactico

* Operativo: control diario de usuarios asistencia y pagos

* Tactico: planificacion de promociones horarios y sevicios seguin la demanda.

  ## ¿Que decision permite tomar?

* Controlar que los usuarios estan activos o deudosos

* Definir horarios y clases con mayor demanda

* Evaluar ingresos mensuales

  ## ¿Que pasaria si no existiera ese sistema?

* Desorden en la informacion

* mayor probabilidad de errores

* Dificultad para tomar deciciones y mejorar el servicios.

## Objetivo general del sistema

* Desarrollar e implementar un sistema de información web que permita gestionar de manera automatizada los clientes, pagos e inventario del gimnasio FCJ_IronFit, con el fin de mejorar la organización, reducir errores y optimizar la toma de decisiones administrativas.


  ## Dos objetivos especificos

* Registrar y controlar la información de clientes y pagos en una base de datos organizada y actualizada en tiempo real.
  

  ## Nivel de decision que impacta

* El sistema impacta principalmente el nivel táctico, ya que permite a la administración analizar información mensual y controlar ingresos

* Generar reportes automáticos de ingresos, clientes activos y estado del inventario para facilitar el análisis financiero y administrativo.


  ## Caracteristicas criticas que debe cumplir

* Precision: La información financiera y de clientes debe ser precisa.

* Seguridad: Protección de datos personales y financieros.


## ¿Que decision permitira tomar?

*Determinar si el gimnasio está generando ganancias o pérdidas.

Decidir cuándo reabastecer inventario.

Ajustar precios o crear nuevos planes.

Planear posibles expansiones del negocio.



  

  
