
# PROJECT CONTEXT
## Software de Gestión de Mantenimiento de Ascensores

Document ID: PROJECT_CONTEXT
Version: 0.1.0
Status: Draft
Last Updated: 2026-11-04

---

# 1. Project Overview

## 1.1 Project Purpose
Crear un sistema de software integral diseñado para gestionar y automatizar las operaciones diarias de una empresa de mantenimiento de ascensores de edificios coorporativos  en una única plataforma centralizada.

## 1.2 Business Objective
Expandir su cartera de clientes en base al concepto de mantenimiento preventivo y predictivo evitando paradas  y evitando reparaciones correctivas costosas para los clientes.

## 1.3 Project Vision
Es sistema debe ser capaz de atender los requerimientos del area operativa, comercial y de servicio al cliente.
El sistema debe integrar:
- Información de los clientes
- Planes de mantenimiento y control de ejecución de trabajos realizado en los ascensores y equipos
- Sistema de costeo de actividades
- Canales de atención al cliente.
- Cotizacion de trabajos no programados.

## 1.4 Expected Benefits
- Optimización de operaciones.
- Trazabilidad del mantenimiento.
- Reducción de tiempos administrativos.
- Control de técnicos y órdenes de trabajo.
- Mejora del servicio al cliente.

---

# 2. Company Profile

## 2.1 Company Description
La empresa ofrece el servicio de mantenimiento de ascensores y equipos anexos, así como los servicios relacionados o que se puedan integrar a este servicio. Cuenta con personal administrativo y personal de mantenimiento de campo.

## 2.2 Business Model
Cómo genera ingresos:
- Contratos de mantenimiento.
- Servicios correctivos.
- Reparaciones.
- Instalaciones o modernizaciones.
- Servicios extraordinarios.

## 2.3 Customer Profile
Características de los clientes:
- Empresas corporativas.
- Administradores de edificios.
- Propietarios o gestores de inmuebles.

## 2.4 Operational Environment
Las operaciones de mantenimiento de los ascensores se realizan en los edificios de los clientes. Los ascensores son detenidos durante los trabajos de mantenimiento, los cuales deben ser breves para no afectar a los ususarios.
Los tecnicos reciben las ordenes de trabajo y acuden a los edificios de acuerdo a la programacion de los trabajos.

## 2.5 Organizational Structure
Existen las siguientes areas:
- Area comercial: dedicada a realizar los contratos con los clientes y ampliar la cartera de clientes.
- Area de servicios: dedicada a gestionar el servicio de mantenimiento a los clientes a cargo del personal tecnico y la programación de los mantenimiento.
- Area contable: dedicada a registrar los gastos y los pagos de la operación.

---

# 3. Business Operations

## 3.1 Service Lifecycle
Descripción del ciclo de prestación del servicio.

## 3.2 Maintenance Operations
- Mantenimiento preventivo.
- Mantenimiento correctivo.
- Atención de emergencias.
- Inspecciones técnicas.
- Reparaciones.

## 3.3 Contract Management
Gestión de contratos, cobertura, vigencia y condiciones.

## 3.4 Work Order Management
Se tiene creado un plan de mantenimiento anual para cada ascensor.
Los planes de mantenimiento anuales de sub dividen en actividades mensuales.
Se programan visitas mensuales de los tecnicos a los edificios en las cuales se ejecutan las actividades programadas mensualmente.
El programador de mantenimiento asigna las ordenes de mantenimiento a los tecnicos usando el sistema / aplicativo OficceTrack 

> [!NOTE]
> OfficeTrack es una plataforma de gestión de fuerza de trabajo móvil desarrollada por OfficeCore que optimiza las operaciones de personal en campo mediante una combinación de aplicación web y apps móviles.  Su función principal es automatizar, gestionar y controlar a los empleados que se desplazan durante su jornada laboral, permitiendo el flujo de información digital entre la base de operaciones y los operarios. 
> Servicios clave y funcionalidades:
> Geolocalización y Ruteo: Monitoreo en tiempo real de empleados y vehículos mediante GPS, junto con la optimización de rutas para mejorar la eficiencia operativa.
> Gestión de Tareas: Asignación y seguimiento de órdenes de trabajo, formularios digitales personalizados y control de asistencia o presentismo.
> Visibilidad y Reportes: Obtención de informes en tiempo real, gestión de inventarios y registro de evidencias (fotos, firmas, códigos de barras) para auditorías y certificaciones.
> Integración: Funciona como SaaS en la nube, compatible con sistemas internos como ERP, CRM o TMS, y opera tanto en línea como offline en zonas sin conexión.

## 3.5 Field Operations
Recepción de Orden de trabajo a travez del aplicativo OfficeTrack.
El técnico se presenta ante el encargado del edificio y obtiene su autorizacion coordinada para iniciar los trabajos deteniendo la operacion del ascensor.
El técnico realiza su procedimiento de Analisis de trabajo seguro (ATS) que consiste en el llenado del formulario registrado en el aplicativo OficceTrack.
Ejecución de Orden de trabajo y toma de evidencia fotografica y comentario registrado en el aplicativo OfficeTrack.
El tecnico se presenta ante el encargado del edificio y le comunica el fin de los trabajos, se restituye la operacion del ascensor y se obtiene la conformidad del encargado del edificio.
El tecnico cierra la orden de trabajo en el sistema revisando agregando comentarios y observaciones segun requiera.


## 3.6 Inventory and Spare Parts
Aun no se cuenta con un stock de repuestos definidos, esta aspecto  está pendiente de ser desarrollado

## 3.7 Customer Communication
- Comunicación empresa - técnicos: actualmente se realiza por medio de telefonos celulares, los tecnicos reciben las Ordenes de mantenimiento en sus celulares a travez de la aplicacion OficceTrack , en la cual, ademas de revisar el detalle de las ordenes de trabajo, realizan tambien el registro de la evidencia fotografica de las tareas
- Comunicación empresa - clientes: los clientes se comunican por medio telefonos celulares y correos electrónicos para comunicar alguna emergencia o consulta, la empresa comunica a los clientes via telefónica con anticipación los mantenimientos programados

---

# 4. Current Business Challenges

## 4.1 Existing Problems
La gestión de los procesos se apoya mas en la personas que en los sistemas de trabajo, es decir, el calculo de indicadores, seguimiento de trabajos, asignacion de ordenes de manteniminto, control de gastos y cotizaciones se realiza de manera manual.
La información se maneja usndo de hojas de excell y del OfficeTrack, no se cuenta con un modelo que centralize la información.

## 4.2 Operational Limitations
Si bien el Uso de un software como el OfficeTrack automatiza prte de la operación, este software no tiene la capacidad de gestionr todos los aspectos de informacion que necesitan para una gestion eficiente de recursos.

## 4.3 Information Management
La informacion se administra en hojas excell, reportes generados y almacenados por el OfficeTrack y correos electronicos.

## 4.4 Bottlenecks
- Cuello de botella operativo: Los tecnicos no llenan correctamente los informes de trabajos ejecutados, se requiere tiempo extra para corregirlos y obtener informacion validada.
- Cuello de botella  administrativo: los procesos de control, programación de tareas y calculo de indicadores son engorrosos y toman mucho tiempo en realizarse.

## 4.5 Risks
- Riesgos operativos: Cometer errores durante el mantenimiento por falta de control en la calidad y ejecucion de los trabajos.
- Riesgos comerciales: Pérdida de clientes por reclamos en el servicio.
- Riesgos tecnológicos: aun no identificado.
---

# 5. Stakeholders and Users

## 5.1 Stakeholders
Personas o entidades interesadas en el sistema.

## 5.2 User Roles
- Administrador.
- Gerente de operaciones.
- Supervisor técnico.
- Técnico de mantenimiento.
- Personal administrativo.
- Clientes.

## 5.3 Permissions and Responsibilities
Responsabilidades y límites de cada rol.

---

# 6. Project Scope

## 6.1 In Scope
- Clientes y contratos: fichas de clientes, edificios, contratos de mantenimiento y renovaciones.
- Gestión de activos (ascensores): ficha técnica por unidad, historial de intervenciones, estado y parámetros (capacidad, paradas, velocidad).
- Mantenimiento preventivo: planes por periodicidad, calendario con avisos y generación automática de órdenes.
- Mantenimiento correctivo / emergencias: registro de incidencias, cotización de reparaciones, aprobación por el cliente y seguimiento 24/7.
- Órdenes de trabajo (OT): asignación a técnicos, estados, prioridades, checklist de tareas, fotos y firma digital en app móvil.
- Inventario y repuestos: trazabilidad de piezas desde almacén hasta el ascensor, control de stock y consumo.
- Facturación y finanzas: generación automática de facturas por contrato y por intervención, cartera de pagos y contabilidad básica.
- Certificaciones y cumplimiento: certificados anuales por ascensor con avisos de vencimiento.
- Reportes e indicadores: disponibilidad, MTBF, tiempo de respuesta, cumplimiento del plan. 

## 6.2 Out of Scope
Gestión de recursos humanos.
Portal de clientes para autodiagnóstico.

## 6.3 Future Scope
- Incorporar un chatbot para atencion al cliente.
- Incorporar un modelo de inteligencia artificial para el analisis de datos.
- Integración con sistemas IoT predictivos 

## 6.4 Project Constraints
- Se asume disponibilidad de la normativa local aplicable (p. ej. intervalos de revisión) para configurar los planes.
- Presupuesto y plazo fijos; los cambios de alcance se gestionan por control de cambios.
- La app móvil debe funcionar en modo offline para zonas sin cobertura.

---

# 7. Functional Requirements

## 7.1 Core Modules
Módulos principales del software.

## 7.2 Business Requirements
- R5: Crear planes de mantenimiento preventivo.
- R6: Crear un registro de equipos (ascensores, plataformas, etc) con detalle tecnico con una estructura enfocada en su mantenimiento ( sitemas, sub sistemas, componentes, etc).
- R7: Crear y mantener un historial de mantenimiento.
- R8: Registrar las emergencias reportadas por los clientes y su atencion.
- R9: Registar la recepcion y conformidad de los trabajos por parte de los clientes.

## 7.3 User Requirements
- R1: Enviar ordenes de mantenimiento a los tecnicos de mantenimiento de la empresa de manera remota atravez de un dispositivo movil.
- R2: Recoger evidencia de la ejecución de los trabajos realizados de los tecnicos en los equipos (ascensores, plataformas, etc).
- R3: Simplificar la elaboracion de informes de trabajos de mantenimiento basado en la evidencia de los tecnicos de mantenimiento.
- R4: Controlar el momento de ejecucion y la duracion de las ordenes de mantenimiento.

## 7.4 General Workflows
Flujos operativos generales.

## 7.5 Reporting and Analytics
- R10: Asignar un costo a cada orden de mantenimiento
- R11: Desarrollar KPIs relacionados al area de operaciones.
- R12: Desarrollar KPIs relacionados al area de servicio al cliente.

---

# 8. Non-Functional Requirements

## 8.1 Performance
## 8.2 Availability
## 8.3 Security
## 8.4 Scalability
## 8.5 Maintainability
## 8.6 Usability
## 8.7 Data Integrity
## 8.8 Offline Operation

---

# 9. Technical Environment

## 9.1 Deployment Model
Infraestructura híbrida combinando servidor propio y dtos en servidor en la nube.

## 9.2 Infrastructure Constraints
No hay restricciones de infraestructura.

## 9.3 Devices
Actualmente se usan telefonos celulares por parte de los tecnicos en campo para la recepcion de las ordenes de mantenimiento y recoger la evidencia y observaciones de los trabajos de mantenimientos.
El personal administrativo tiene acceso a computadoras portatiles

## 9.4 Connectivity
LAN, VPN, Internet y conectividad de campo.

## 9.5 Existing Systems
Actualmente se usan siguientes softwares:
Office de Microsoft 
OfficeTrack para la gestión de las ordenes de mantenimiento y el envío de información a los técnicos en campo

---

# 10. Data and Information

## 10.1 Business Entities
Clientes, edificios, ascensores, contratos,técnicos, órdenes de trabajo, repuestos.

## 10.2 Data Ownership
Quién administra y controla la información.

## 10.3 Data Lifecycle
Creación, actualización, conservación y eliminación.

## 10.4 Documents and Attachments
Fotografías, informes, firmas y documentos.

## 10.5 Data Migration
Información existente que debe migrarse.

---

# 11. Regulatory and Safety Considerations

## 11.1 Applicable Regulations
Regulaciones aplicables al negocio.

## 11.2 Safety Requirements
Seguridad del personal y procedimientos técnicos.

## 11.3 Auditability
Trazabilidad de operaciones y cambios.

## 11.4 Data Privacy
Protección de información de clientes y usuarios.

---

# 12. Success Criteria

## 12.1 Business KPIs
## 12.2 Operational KPIs
## 12.3 Software Acceptance Criteria
## 12.4 Expected Outcomes

---

# 13. Assumptions and Open Questions

## 13.1 Confirmed Facts
Información validada.

## 13.2 Assumptions
Suposiciones pendientes de confirmación.

## 13.3 Open Questions
Preguntas que requieren investigación o decisión.

---

# 14. Project Decisions

## 14.1 Business Decisions
## 14.2 Technical Decisions
## 14.3 Decision Log

---

# 15. Glossary

Terminología específica del negocio de ascensores.

---

# 16. References

Documentos, normativas, diagramas y fuentes
utilizadas para definir el contexto.
