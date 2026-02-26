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


# 1.¿Qué problema soluciona?

El proyecto FCJ_ironFit soluciona problemas de desorganización en la gestión de usuarios, control manual de inscripciones, pagos, asistencia y planes de entrenamiento.
También reduce errores en registros y pérdida de información.

# 2. ¿A qué nivel de decisión impacta?
El sistema impacta en tres niveles de decision:

## Nivel operativo:
Mejora el registro diario de clientes, pagos e inventario

## Nivel tactico: 
Permite analizar ingresos mensulaes, clientes activos y clientes deudores

## Nivel estrategico:
Facilita la toma de decisiones a largo plazo, como expansion de negocio, creacion de nuevos planes o inversion en nuevos equipos 

# ¿Qué decisiones permitirá tomar?
* Controlar qué usuarios están activos o morosos.

* Definir horarios y clases con mayor demanda.

* Evaluar ingresos mensuales.

* Mejorar la atención y organización del gimnasio.

 # ¿Qué pasaría si no existiera ese sistema?

Si no existiera el sistema, el gimnasio tendría:

* Desorden en la información de clientes.

* Mayor probabilidad de errores en pagos y registros.

* Pérdida de tiempo en procesos manuales.

* Dificultad para tomar decisiones y mejorar el servicio.

# Objectivo general
Desarrollar e implementar un sistema de informacion web que permita gestionar de manera automatizada los clientes, pagos e inventario del gimnasio, con el fin de mejorar la organizacion
reducir errores y optimizar la toma de decisiones administrativas


# Dos objetivos específicos
1. Registrar y controlar la información de clientes y pagos en una base de datos organizada y actualizada en tiempo real.
2. Generar reportes automáticos de ingresos, clientes activos y estado del inventario para facilitar el análisis financiero y administrativo

# Nivel de decisión principal que impacta
El sistema impacta principalmente el nivel táctico, ya que permite a la administración analizar información, identificar clientes dudosos y evaluar el rendimiento del negocio para mejorar su gestión

# Características críticas que debe cumplir
Preicion: La información financiera y de clientes debe ser precisa.

Seguridad: Protección de datos personales y financieros.

# ¿Qué decisión permitirá tomar?
* Determinar si el gimnasio está generando ganancias o pérdidas.
* Decidir cuándo reabastecer inventario.
* Ajustar precios o crear nuevos planes.
* Planear posibles expansiones del negocio.









