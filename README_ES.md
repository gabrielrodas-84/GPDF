# Governed Process Design Framework (GPDF) v1.0

**Un Enfoque Estructurado para la Gobernanza de Procesos Basados en Solicitudes**

---

## 👤 Autor

**Gabriel Rodas**
Senior OTC Process Owner | Governance & Automation | Lean Six Sigma Green Belt
📍 Buenos Aires, Argentina
🔗 https://linkedin.com/in/gabrielrodas84/
📧 gabriel.rodas@comunidad.ub.edu.ar

---

## 📖 ¿Qué es GPDF?

GPDF es un **design pattern y modelo operativo** para construir procesos de negocio
gobernados, basados en solicitudes, utilizando datos estructurados, orquestación
modular y decisiones basadas en reglas.

Está diseñado para equipos y organizaciones donde los procesos de negocio se
gestionan actualmente mediante correos electrónicos, hojas de cálculo o aprobaciones
informales — y donde se requiere **trazabilidad, auditabilidad y toma de decisiones
consistente**.

GPDF no reemplaza sistemas transaccionales empresariales (ERP, ITSM). Opera como una
**capa de decisión gobernada** para procesos que quedan fuera de esas plataformas.

---

## 🏗️ Arquitectura

GPDF organiza cada proceso gobernado en **seis capas independientes**:

| Capa | Responsabilidad |
|------|----------------|
| **User** | Define quién interactúa con el proceso y en qué rol (Requester, Reviewer, Approver, Executor, Process Owner) |
| **Data** | Almacén único y autoritativo para todas las solicitudes, decisiones, cambios de estado y evidencia |
| **Orchestration** | Workflows automatizados que ejecutan la lógica del proceso, transiciones, validaciones y handoffs |
| **Governance** | Reglas de negocio, matrices de aprobación y criterios de decisión gestionados como datos de configuración estructurados |
| **Intelligence** | Análisis asistido por IA, recomendaciones y soporte contextual (opcional) |
| **Output** | Notificaciones, reportes, dashboards y registros de auditoría |

Cada proceso sigue un ciclo de vida estándar: **Intake → Decision → Execution → Closure**.

---

## 🎯 Resultados Clave

- ✅ Reemplazo de aprobaciones por correo electrónico con flujos de decisión estructurados y auditables
- ✅ Trazabilidad completa desde la captura de la solicitud hasta el cierre
- ✅ Ejecución consistente mediante stage ownership y handoffs controlados
- ✅ Diseño de procesos escalable a través de configuración, no de reingeniería

---

## 🧱 Principios Fundamentales

- **Single Source of Truth** — Cada proceso se ancla a un único almacén de datos autoritativo
- **Stage Ownership** — Cada fase del ciclo de vida tiene un responsable definido con responsabilidades claras
- **Rule-Driven Decisions** — Las reglas de gobernanza se gestionan como datos, nunca hardcodeadas
- **Platform-Agnostic** — Funciona en Microsoft 365, ServiceNow, Google Workspace, SQL/Custom, o cualquier stack que cumpla los requisitos

---

## 📂 Ecosistema de Documentos

GPDF se estructura como un ecosistema de tres documentos:

| Documento | Qué Contiene | Audiencia | Incluido Aquí |
|-----------|-------------|-----------|:-------------:|
| **Public Overview** | Qué es GPDF, por qué existe, principios, arquitectura, casos de uso comprobados | Decisores, stakeholders, evaluadores del framework | ✅ |
| **Full Framework** | Arquitectura completa, componentes estandarizados, modelo de ciclo de vida, roles, métricas, anti-patterns, glosario | Process owners, líderes de gobernanza, analistas | 🔒 |
| **Implementation Guide** | Instrucciones paso a paso, modelo de datos (88+ campos), 101 escenarios de prueba, 17 KPIs, mapeos de plataforma | Implementadores, QA leads, administradores de plataforma | 🔒 |

> 🔒 El Full Framework y la Implementation Guide están disponibles bajo solicitud.
> Contactá al autor para acceso.

---

## ✅ Casos de Uso Comprobados

- **Financial Approval Process** — Gobernanza de notas de crédito
- **Credit Risk Evaluation** — Seguimiento de revisiones de límite de crédito
- **Initiative Intake & Evaluation** — Gobernanza de innovación

---

## 📜 Propiedad Intelectual y Registro

Esta obra está **registrada en la Dirección Nacional del Derecho de Autor (DNDA)**,
el organismo nacional de derechos de autor de la República Argentina. Este registro
proporciona prueba legal de autoría, fecha de creación e integridad del contenido
bajo la legislación argentina de derechos de autor (Ley 11.723).

**Qué significa el registro en la DNDA:**
- 🔐 Registro oficial del gobierno argentino que certifica autoría y fecha de creación
- 📄 Evidencia legal en caso de disputas de derechos de autor
- 🌍 Protegido bajo tratados internacionales de propiedad intelectual (Convenio de Berna, OMPI/WIPO)
- ✅ Verificación independiente de la existencia y contenido de la obra a la fecha de registro

---

## 📄 Licencia

© 2026 Gabriel Rodas. Todos los derechos reservados.

Esta obra está licenciada bajo la [Licencia Creative Commons
Atribución-NoComercial-SinDerivadas 4.0 Internacional (CC BY-NC-ND 4.0)]
(https://creativecommons.org/licenses/by-nc-nd/4.0/).

**Sos libre de:**
- **Compartir** — Copiar y redistribuir el material en cualquier medio o formato

**Bajo los siguientes términos:**
- **Atribución** — Debés dar crédito apropiado al autor (Gabriel Rodas), proporcionar
  un enlace a la licencia e indicar si se realizaron cambios
- **NoComercial** — No podés utilizar este material con fines comerciales
- **SinDerivadas** — Si remezclás, transformás o construís sobre este material, no
  podés distribuir el material modificado

Para permisos más allá del alcance de esta licencia, contactá al autor.

---

## 🤝 Contribuciones

Esta es una publicación de solo lectura. Las contribuciones, forks y obras derivadas
**no están permitidas** bajo la licencia CC BY-NC-ND 4.0. Si tenés feedback o
consultas, contactá directamente al autor.

---

## ⭐ Apoyo

Si encontrás valor en este framework, considerá:
- ⭐ Darle una estrella a este repositorio
- 🔗 Compartirlo con colegas que gestionen procesos de negocio
- 💬 Conectar en [LinkedIn](https://linkedin.com/in/gabrielrodas84/)
