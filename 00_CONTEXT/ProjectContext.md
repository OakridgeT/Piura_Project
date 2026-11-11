
# PROJECT CONTEXT
## Software de Gestión de Mantenimiento de Ascensores

Document ID: PROJECT_CONTEXT
Version: 0.1.0
Status: Draft
Last Updated: 2026-11-04

---

# 1. Project Overview

## 1.1 Project Purpose
Develop a software system to manage the daily operations of a company that provides elevator maintenance for corporate buildings, using a single centralized platform that integrates a desktop application and a mobile app to maintain communication channels between office staff and field technical personnel.

## 1.2 Business Objective
The primary business objective is to improve the operational efficiency, traceability, and service quality of the elevator maintenance company through a centralized digital platform.

The system aims to:

- Centralize customer, building, elevator, and contract information.
- Improve preventive maintenance scheduling and compliance.
- Reduce administrative workload associated with work orders.
- Improve technician assignment and field service coordination.
- Provide real-time visibility into service execution status.
- Maintain a complete service history for each elevator.
- Improve communication between field technicians,
  supervisors, and administrative personnel.
- Reduce information loss caused by paper-based processes
  and disconnected communication channels.

The platform should support business growth without requiring a proportional increase in administrative personnel.

## 1.3 Project Vision
The system must be capable of meeting the requirements of the operational, commercial, and customer service areas.
The system must integrate:
- Customer information
- Maintenance plans and monitoring of work performed on elevators and equipment
- Activity-based costing system
- Customer service channels
- Quotations for unscheduled work

## 1.4 Expected Benefits
- Optimization of operations.
- Maintenance traceability.
- Reduction of administrative time.
- Oversight of technicians and work orders.
- Improvement of customer service.

---

# 2. Company Profile

## 2.1 Company Description
The company provides maintenance services for elevators and related equipment, as well as services that are either associated with or can be integrated into this offering. It employs both administrative staff and field maintenance personnel.

## 2.2 Business Model
How it generates revenue:
- Maintenance contracts.
- Corrective services.
- Repairs.
- Installations or modernizations.
- Extraordinary services.

## 2.3 Customer Profile
Client characteristics:
- Corporate entities.
- Building managers.
- Property owners or managers.

## 2.4 Operational Environment
Elevator maintenance operations are carried out in clients' buildings. Elevators are taken out of service during maintenance work, which must be kept brief so as not to inconvenience users.
Technicians receive work orders and travel to the buildings according to the maintenance schedule.

## 2.5 Organizational Structure
The following areas exist:
- Commercial area: dedicated to entering into contracts with clients and expanding the client base.
- Services area: dedicated to managing maintenance services for clients, handled by technical staff, and scheduling maintenance tasks.
- Accounting area: dedicated to recording operational expenses and payments.

---

# 3. Business Operations

## 3.1 Service Lifecycle
The company provides elevator maintenance services through preventive maintenance contracts, corrective maintenance requests, emergency services, and technical inspections.

The general service lifecycle consists of:

1. Service requirement identification.
2. Service classification.
3. Work order creation.
4. Technician assignment.
5. Service scheduling and client communication.
6. Field execution.
7. Activity and findings recording include client validation / reception.
8. Service completion or follow-up scheduling.
9. Technical report submission.
10. Supervisor review when applicable.
11. Work order closure.
12. Customer notification and service history update.

A service may remain open when:
- The maintenance activity is incomplete.
- Spare parts are required.
- Additional technical work is identified.
- Supervisor approval is pending.

The service lifecycle must preserve traceability from service initiation to final closure and client validation / reception.

## 3.2 Maintenance Operations
- Preventive maintenance.
- Corrective maintenance.
- Emergency response.
- Technical inspections.
- Repairs.

## 3.3 Contract Management
Contract management, coverage, term, and conditions.

## 3.4 Work Order Management
An annual maintenance plan has been established for each elevator.
These annual maintenance plans are subdivided into monthly activities.
Monthly technician visits to the buildings are scheduled, during which the planned monthly activities are carried out.
The maintenance scheduler assigns maintenance work orders to the technicians using the OfficeTrack system/application.

> [!NOTE]
> OfficeTrack is a mobile workforce management platform developed by OfficeCore that optimizes field operations through a combination of a web application and mobile apps. Its primary function is to automate, manage, and oversee employees who travel as part of their workday, enabling a digital flow of information between the operations center and field personnel.
> Key services and features:
> Geolocation and Routing: Real-time monitoring of employees and vehicles via GPS, combined with route optimization to improve operational efficiency.
> Task Management: Assignment and tracking of work orders, custom digital forms, and attendance or time-tracking.
> Visibility and Reporting: Real-time reporting, inventory management, and the collection of evidence (photos, signatures, barcodes) for audits and certifications.
> Integration: Operates as a cloud-based SaaS, compatible with internal systems such as ERP, CRM, or TMS, and functions both online and offline in areas without connectivity.

## 3.5 Field Operations
Receipt of a work order via the OfficeTrack application.
The technician reports to the building manager and obtains authorization to begin work, which involves halting the elevator's operation.
The technician carries out a Job Safety Analysis (JSA) by completing the form provided within the OfficeTrack application.
The work order is executed, with photographic evidence and comments recorded in the OfficeTrack application.
The technician informs the building manager that the work is complete; the elevator is returned to service, and the building manager provides confirmation that the work is satisfactory.
The technician closes the work order in the system, adding any necessary comments or observations.


## 3.6 Inventory and Spare Parts
A stock of spare parts has not yet been defined; this aspect remains to be developed.

## 3.7 Customer Communication
- Communication between the company and technicians: This currently takes place via mobile phones. Technicians receive maintenance orders on their phones through the OfficeTrack application, which allows them to review the details of work orders and also document completed tasks by uploading photographic evidence.
- Communication between the company and clients: Clients use mobile phones and email to report emergencies or make inquiries. The company, in turn, notifies clients in advance—via telephone—about any scheduled maintenance.

---

# 4. Current Business Challenges

## 4.1 Existing Problems
Process management relies more on people than on work systems; specifically, the calculation of performance indicators, task tracking, assignment of maintenance work orders, and the control of expenses and price quotes are all handled manually.
Information is managed using Excel spreadsheets and OfficeTrack; there is no unified model in place to centralize this information.

## 4.2 Operational Limitations
While using software such as OfficeTrack automates part of the operation, this software lacks the capacity to manage all the aspects of information required for efficient resource management.

## 4.3 Information Management
Information is managed via Excel spreadsheets, reports generated and stored by OfficeTrack, and emails.

## 4.4 Bottlenecks
- Operational bottleneck: Technicians do not correctly complete reports on work performed; extra time is required to correct them and obtain validated information.
- Administrative bottleneck: Processes for control, task scheduling, and the calculation of performance indicators are cumbersome and time-consuming to carry out.

## 4.5 Risks
- Operational risks: Making errors during maintenance due to a lack of control over quality and the execution of the work.
- Commercial risks: Loss of clients due to service-related complaints.
- Technological risks: Not yet identified.
---

# 5. Stakeholders and Users

## 5.1 Stakeholders
Individuals or entities with an interest in the system.

## 5.2 User Roles
- Administrator.
- Operations manager.
- Technical supervisor.
- Maintenance technician.
- Administrative staff.
- Clients.

## 5.3 Permissions and Responsibilities
Responsibilities and limits of each role.

---

# 6. Project Scope

## 6.1 In Scope
- Clients and contracts: client profiles, building information, maintenance contracts, and renewals.
- Asset management (elevators): technical specifications for each unit, service history, current status, and operational parameters (capacity, number of stops, speed).
- Preventive maintenance: recurring maintenance schedules, a calendar with automated alerts, and the automatic generation of work orders.
- Corrective maintenance / emergencies: incident logging, repair quotes, client approval, and 24/7 tracking.
- Work orders (WOs): technician assignment, status tracking, priority levels, task checklists, photo documentation, and digital signatures via a mobile app.
- Inventory and spare parts: tracking of parts from the warehouse to the specific elevator, including stock control and usage monitoring.
- Billing and finance: automated invoicing based on contracts or individual service interventions, payment tracking, and basic accounting.
- Certifications and compliance: annual elevator certifications with expiration alerts.
- Reports and KPIs: system availability, MTBF (Mean Time Between Failures), response times, and maintenance plan compliance.

## 6.2 Out of Scope
Human resources management.
Client portal for self-assessment.

## 6.3 Future Scope
- Incorporate a chatbot for customer service.
- Incorporate an artificial intelligence model for data analysis.
- Integration with predictive IoT systems.

## 6.4 Project Constraints
- It is assumed that the applicable local regulations (e.g., inspection intervals) are available for configuring the plans.
- Fixed budget and timeline; scope changes are managed through a change control process.
- The mobile app must function in offline mode for areas without network coverage.
---

# 7. Functional Requirements

## 7.1 Core Modules
The software platform is organized into functional modules
representing the main business areas.

### 7.1.1 Customer and Building Management
Manage customer accounts, corporate buildings,
contacts, service locations, and customer relationships.

### 7.1.2 Equipment Management
Maintain elevator records, technical specifications,
equipment identification, components, and service history.

### 7.1.3 Contract Management
Manage maintenance contracts, contract validity,
service coverage, obligations, and customer agreements.

### 7.1.4 Work Order Management
Create, assign, execute, track, and close work orders
for preventive, corrective, and emergency maintenance.

### 7.1.5 Maintenance Planning
Schedule preventive maintenance activities,
manage recurring tasks, and monitor compliance.

### 7.1.6 Technician Management
Manage technicians, qualifications, availability,
assignments, and workload.

### 7.1.7 Inventory Management
Track spare parts, materials, consumption,
and inventory movements.

### 7.1.8 Reports and Documentation
Generate technical reports, maintenance records,
photographic evidence, and service documentation.

### 7.1.9 Dashboard and Analytics
Provide operational indicators and management reports.

### 7.1.10 User and Access Management
Manage user accounts, authentication,
roles, permissions, and access restrictions.

## 7.2 Business Requirements
- R5: Create preventive maintenance plans.
- R6: Create an equipment register (elevators, platforms, etc.) containing technical details, structured with a focus on maintenance (systems, subsystems, components, etc.).
- R7: Create and maintain a maintenance history.
- R8: Record emergencies reported by clients and the actions taken to address them.
- R9: Record the receipt and formal acceptance of work by clients.

## 7.3 User Requirements
- R1: Send maintenance orders to company maintenance technicians remotely via a mobile device.
- R2: Collect evidence of the work performed by technicians on equipment (elevators, platforms, etc.).
- R3: Streamline the preparation of maintenance work reports based on the evidence provided by the maintenance technicians.
- R4: Monitor the timing and duration of maintenance order execution.

## 7.4 General Workflows

### 7.4.1 Preventive Maintenance Workflow

1. The system identifies maintenance activities
   due according to the maintenance schedule.
2. A preventive work order is generated.
3. The supervisor reviews the work order.
4. A technician is assigned.
5. The technician receives the work order.
6. The technician performs the maintenance.
7. The technician completes the maintenance checklist.
8. Findings, activities, and photographs are recorded.
9. The technician submits the technical report.
10. The work order is reviewed and closed.

### 7.4.2 Corrective Maintenance Workflow

1. A customer reports an elevator failure.
2. The service request is registered.
3. The request is classified according to urgency.
4. A corrective work order is created.
5. A technician is assigned.
6. The technician performs fault diagnosis.
7. The technician records findings and repair activities.
8. If the repair cannot be completed, a follow-up
   activity is scheduled.
9. When the repair is completed, functional
   verification is performed.
10. The technical report is submitted.
11. The work order is closed.

### 7.4.3 Workflow Rules

- Work orders must have a unique identifier.
- Work orders must reference a building and elevator.
- Work orders must record their assigned technician.
- Work orders must preserve execution history.
- Work orders requiring follow-up must remain traceable.
- Closure must require the applicable technical records.

## 7.5 Reporting and Analytics
- R10: Assign a cost to each maintenance order.
- R11: Develop KPIs related to the operations area.
- R12: Develop KPIs related to the customer service area.

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
Hybrid infrastructure combining an on-premises server with data stored on a cloud server.

## 9.2 Infrastructure Constraints
No infrastructure restrictions have been defined yet.

## 9.3 Devices
Field technicians currently use mobile phones to receive maintenance orders and to collect evidence and observations regarding maintenance work.
Administrative staff have access to laptops.

## 9.4 Connectivity
LAN, VPN, Internet, and field connectivity.

## 9.5 Existing Systems
The following software is currently in use:
- Microsoft Office for creating documents and spreadsheets.
- OfficeTrack for managing maintenance work orders and sending information to field technicians.

---

# 10. Data and Information

## 10.1 Business Entities
- Clients
- Buildings
- Elevators
- Contracts
- Technicians
- Work orders
- Spare parts

## 10.2 Data Ownership
There is no person who centralizes and manages the information; each user keeps their documents on their own hard drives.

## 10.3 Data Lifecycle
An information life cycle has not been defined within the company.

## 10.4 Documents and Attachments
- Photographs
- Reports
- Digital Signatures
- Documents
- 
## 10.5 Data Migration
Currently, the only active database belongs to the OfficeTrack software; it is hosted in the cloud and contains information on completed jobs as well as reports for clients.

---

# 11. Regulatory and Safety Considerations

## 11.1 Applicable Regulations
Regulations applicable to the business.
- UNE 58720 "Mantenimiento preventivo de ascensores" "This document was developed in Spain. 

## 11.2 Safety Requirements
Personnel safety and technical procedures.

## 11.3 Auditability
Traceability of operations and changes.

## 11.4 Data Privacy
Protection of customer and user information.

---

# 12. Success Criteria

## 12.1 Business KPIs
## 12.2 Operational KPIs
## 12.3 Software Acceptance Criteria
## 12.4 Expected Outcomes

---

# 13. Assumptions and Open Questions

## 13.1 Confirmed Facts
Validated information (under development).

## 13.2 Assumptions
Assumptions awaiting confirmation (under development).

## 13.3 Open Questions
Questions requiring investigation or a decision (under development).

---


## 14. Project Decisions

### 14.1 Business Decisions

| ID | Decision | Status | Date |
|---|---|---|---|
| BD-001 | The system will initially target elevator maintenance companies. | Approved | 2026-11-06 |
| BD-002 | The initial customer segment will be corporate buildings. | Approved | 2026-11-06 |

### 14.2 Technical Decisions

| ID | Decision | Status | Date |
|---|---|---|---|
| TD-001 | Backend will use Go. | Approved | 2026-11-06|
| TD-002 | Database will use PostgreSQL. | Approved | 2026-11-06 |
| TD-003 | Mobile application will target Android. | Approved | 2026-11-06 |
| TD-003 | Mobile application will be functional with and with out internet connection and preserve timestamp of activities  | Approved | 2026-11-06 |
| TD-004 | Deployment will support customer-owned infrastructure. | Approved | 2026-11-06 |
| TD-005 | Software will use Api Rest . | Approved | 2026-11-06 |

### 14.3 Decision Log

#### TD-001: Backend Technology

- Status: Approved
- Date: 2026-11-06
- Decision: Go will be used for backend development.
- Context: The project requires a maintainable backend  suitable for self-hosted deployment.
- Rationale: Go provides efficient execution, straightforward deployment, and strong support for API development.
- Consequences:
  - Backend code will use Go.
  - API services will follow Go conventions.
  - Developers must maintain consistent coding standards.

#### TD-002: Database Technology

- Status: Approved
- Date: 2026-11-06
- Decision: PostgreSQL will be used as the primary database.
- Context: The system requires relational data management  for customers, buildings, elevators, contracts,   technicians, and work orders.
- Rationale: PostgreSQL provides relational integrity, transactional consistency, and extensibility.
- Consequences:
  - Database design will use PostgreSQL.
  - SQL migrations will be maintained.
  - Database-specific features must be documented.

---

# 15. Glossary

Terminology specific to the elevator business (under development).

---

# 16. References

Documentos, normativas, diagramas y fuentes
utilizadas para definir el contexto.
