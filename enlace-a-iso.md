# Auditoría de Seguridad y Cumplimiento: Framework ISO 27001/2 & GDPR

**Objetivo:** Evaluar y fortalecer la postura de seguridad de la infraestructura perimetral e interna de la organización, asegurando el cumplimiento de normativas internacionales de protección de datos.

### 1. Inventario y Control de Accesos (ISO A.5, A.8 y A.9)
* **Relevamiento de Activos:** Ejecución de un mapeo completo de hardware, software y servidores, logrando una visibilidad total de la red.
* **Identity & Access Management (IAM):** Implementación de un esquema de roles bajo el Principio de Mínimo Privilegio. Se auditaron y revocaron accesos de ex-empleados y se evaluó la integración de Autenticación Multifactor (MFA).

### 2. Privacidad y Datos Sensibles (GDPR)
* Diseño e implementación de un checklist de auditoría para Información de Identificación Personal (PII).
* Análisis de métodos de cifrado, políticas de backup y aseguramiento de los flujos de envío de información confidencial para mitigar riesgos legales.

### 3. Hardening y Seguridad de Red (ISO A.11 y A.13)
* **Segmentación:** Auditoría de controles de acceso físico al servidor (UPS, cámaras) y segmentación lógica de la red mediante VLANs y redes de invitados.
* **Defensa Perimetral:** Ejecución de tareas de hardening en gateways (FiberHome). Se deshabilitaron protocolos inseguros (Telnet, FTP, HTTP) forzando la migración a HTTPS, y se configuraron Firewalls con inspección profunda de paquetes (SPI) en modo sigilo.

### 4. Resiliencia y Continuidad del Negocio (ISO A.17)
* Desarrollo de la documentación base para la respuesta ante crisis corporativas.
* Redacción de borradores para un **Plan de Respuesta ante Incidentes (IRP)** y un **Plan de Continuidad de Negocio (BCP)** enfocados en casos de pérdida total (ej. incendios o robo de equipamiento crítico).

**Herramientas y Estándares:** `ISO/IEC 27001` | `ISO/IEC 27002` | `GDPR` | `Nmap` | `Hardening de Sistemas`
