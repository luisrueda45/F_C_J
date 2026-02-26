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

 # A QUE NIVEL DE DESICION IMPACTA?

 Principalmente en el nivel operativo y tactico.

 * operativo: control diario de usuarios, asistencia y pagos.

 * Tactico: planificacion de promiciones, horarios y servicios segun la demanda.

   # QUE DECISIONES PERMITIRA TOMAR?

   * Controlar que usuarios estan activos o morosos.
     
   * Definir horarios y clases con mayor demanda.
  
   * Evaluar ingresos mensuales.
  
   * Mejorar la atencion y organizacion del gimnacio.
  
     # QUE PASARIA SI NO EXIXTIERA ESE SISTEMA?

     * Desorden en la informacion de clientes.
    
     * Mayor probabilidad de errores en pagos y registros.
    
     * Perdida de tiempo en procesos manuales.
    
     * Dificultad para tomar decisiones y mejorar el servicio.
    
# OBJETIVO GENERAL

* Desarrollar e implementar un sistema de informacion web que permita gestionar de manera automatizada los clientes. pagos e inventario de gimnasio FCJ_IronFit, con el fin de mejorar la organizacion, reducir errores y optimizar la toma de desiciones administrativos.

# OBJETIVOS ESPECIFICOS

* Registrar y controlar la información de clientes y pagos en una base de datos organizada y actualizada en tiempo real.

* Generar reportes automáticos de ingresos, clientes activos y estado del inventario para facilitar el análisis financiero y administrativo.

# NIVEL DE DECISION PRINCIPAL QUE IMPACTA

El sistema impacta principalmente el nivel táctico, ya que permite a la administración analizar información mensual, controlar ingresos, identificar clientes morosos y evaluar el rendimiento del negocio para mejorar su gestión.

# CARACTERISTICAS CRITICAS QUE DEBE CUMPLIR

* Precision: la informacion financiera y de clientes debe ser precisa.

* Seguridad: proteccion de datos personales y financieros.

# QUE DECISION PERMITIRA TOMAR?

* Determinar si el gimnasio está generando ganancias o pérdidas.

* Identificar clientes activos y morosos.

* Decidir cuándo reabastecer inventario.

* Ajustar precios o crear nuevos planes.

* Planear posibles expansiones del negocio.






     
