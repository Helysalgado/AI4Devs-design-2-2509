# 🧭 PLAN DE TRABAJO COMPLETO --- Proyecto LTI (ATS con IA)

**Propósito:**. 
Desarrollar paso a paso el sistema **LTI (Applicant Tracking System)** aplicando metodologías ágiles, documentación reproducible, y usoresponsable de la inteligencia artificial como apoyo en el diseño,
priorización y desarrollo.

------------------------------------------------------------------------

## 🌐 Marco metodológico general

Este plan sigue el enfoque propuesto en el material
*documentacion-historias-clase.md*, aplicando:

-   **Metodología ágil (Scrum)** adaptada a proyectos con IA.
-   **Documentación estructurada en Markdown** compatible con GitHub.
-   **Plantillas estandarizadas** para cada artefacto (PRD, HU, backlog, tickets, sprint plan, reflexión).
-   **Uso documentado de IA** (role + prompt + evidencias de salida).
-   **Trazabilidad completa** entre Requisitos (RF), Casos de Uso (UC), Historias de Usuario (HU) y Tickets.
-   **Priorización basada en valor, esfuerzo y riesgo.**
-   **Criterios observables de calidad (Definition of Done).**
-   **Formato Gherkin (Dado/Cuando/Entonces)** en criterios de aceptación.
-   **Validación fase a fase:** no se avanza sin aprobación.
-   **Reflexión final sobre el uso ético y productivo de la IA.**

------------------------------------------------------------------------

## 🧩 FASES, PLANTILLAS, ROLES IA Y RECOMENDACIONES

| Fase | Objetivo | Role de la IA | Prompt base sugerido | Plantilla / Recomendaciones clave | Artefacto |
|------|-----------|---------------|----------------------|-----------------------------------|------------|
| **1️⃣ Análisis y Contexto (PRD)** | Comprender el problema, el mercado y las métricas del MVP. | 🧠 *Experto en producto digital y análisis de requerimientos* | “Eres un experto en producto digital. Ayúdame a construir el PRD del sistema LTI (ATS con IA). Define los objetivos, usuarios, métricas y funcionalidades iniciales.” | **Plantilla PRD:** 1) Propósito 2) Descripción general 3) Usuarios y stakeholders 4) Funcionalidades principales 5) Métricas del MVP 6) Riesgos / limitaciones 7) Role y prompt IA. **Recomendaciones:** incluir métricas observables del MVP, conectar con Lean Canvas, mencionar stakeholders clave (reclutadores, candidatos, managers), definir KPIs principales. | `PRD_LTI.md` |
| **2️⃣ Historias de Usuario (HU)** | Traducir funcionalidades a lenguaje centrado en el usuario. | ✍️ *Product Owner y UX Writer* | “Actúa como un Product Owner. Genera historias de usuario para el sistema LTI usando el formato ‘Como [rol], quiero [acción], para [beneficio]’. Incluye criterios Gherkin y trazabilidad.” | **Plantilla HU:** 1) ID/Título 2) Descripción (Como/Quiero/Para) 3) Criterios Gherkin 4) Notas 5) Trazabilidad 6) DoD 7) Role y prompt IA. **Recomendaciones:** incluir criterios medibles, agregar HU positivas y negativas, validar consistencia entre HU y PRD, usar lenguaje empático y claro. | `HistoriasUsuario_LTI.md` |
| **3️⃣ Backlog del Producto** | Priorizar las HU según valor, esfuerzo y riesgo. | 📊 *Scrum Master y Analista de Producto* | “Eres un Scrum Master. Evalúa el valor, esfuerzo y riesgo de cada historia de usuario del LTI. Construye el backlog priorizado y justifica el orden.” | **Plantilla Backlog:** ID HU, Valor de negocio, Esfuerzo, Riesgo, Prioridad, Justificación, Dependencias, Role y prompt IA. **Recomendaciones:** usar matriz Valor–Esfuerzo o técnica RICE, documentar cómo la IA ayudó en la estimación, mantener backlog vivo y actualizado. | `Backlog_LTI.md` |
| **4️⃣ Tickets de Trabajo (Sprint Backlog)** | Descomponer HU seleccionadas en tareas técnicas. | 🧾 *Tech Lead / Arquitecto de Software* | “Eres un Tech Lead. Descompón las historias seleccionadas del backlog en tickets técnicos con estimación y Definition of Done.” | **Plantilla Tickets:** ID Ticket, Relación HU, Descripción técnica, Estimación, DoD, Asignado a, Estado, Role y prompt IA. **Recomendaciones:** evitar tickets vagos (1–2 días máximo), registrar dependencias, incluir criterios técnicos, mantener consistencia con pipeline del proyecto. | `Tickets_Sprint1_LTI.md` |
| **5️⃣ Planeación del Sprint** | Preparar la ejecución del Sprint 1. | 🕒 *Scrum Master* | “Eres un Scrum Master. Ayúdame a planificar el Sprint 1 del LTI: selecciona HU, define objetivo, capacidad y métricas.” | **Plantilla Sprint:** Sprint objetivo, HU seleccionadas, Capacidad del equipo, Métricas, Riesgos, Role y prompt IA. **Recomendaciones:** seleccionar HU de alto valor, documentar criterios de selección, registrar cómo la IA apoyó la priorización. | `PlanSprint1_LTI.md` |
| **6️⃣ Evaluación y Reflexión** | Evaluar el aporte y límites de la IA. | 💬 *Mentor en ingeniería de software e IA aplicada* | “Eres un mentor de desarrollo ágil. Analiza cómo la IA apoyó el desarrollo del sistema LTI: beneficios, limitaciones, aprendizajes y próximos pasos.” | **Plantilla Reflexión:** Beneficios, Limitaciones, Aprendizajes, Mejoras, Role y prompt IA. **Recomendaciones:** evaluar calidad del proceso, incluir ejemplos de prompts usados, reflexionar sobre ética y sesgos IA, comparar productividad con y sin IA. | `Reflexion_IA_LTI.md` |

  


## ⚙️ Modo de trabajo (iterativo y reflexivo)

1.  Avanzaremos **fase por fase**, usando las plantillas y prompts correspondientes.
2.  Al inicio de cada documento se incluirá el **role IA + prompt base + versión de salida**.
3.  Cada artefacto tendrá trazabilidad con los anteriores.
4.  No se avanza a la siguiente fase hasta aprobación explícita.
5.  Al final, tendrás un **paquete reproducible y evaluable** con criterios claros de calidad, coherencia y aplicación de IA.


---


# ✍️ Historias de Usuario — Sistema LTI (Fase 2)

> **Rol IA:** Product Owner y UX Writer  
> **Prompt:** “Actúa como un Product Owner. Genera historias de usuario para el sistema LTI usando el formato ‘Como [rol], quiero [acción], para [beneficio]’. Incluye criterios Gherkin y trazabilidad.”  
> **Propósito:** Documentar las Historias de Usuario del **MVP (Must)** según el PRD_LTI.md, manteniendo trazabilidad con requisitos funcionales (RF) y casos de uso (UC).

---

## 🧩 Módulo 1. Gestión de Vacantes

### HU-001 / Crear vacante
- **Como** reclutador, **quiero** crear una vacante con título, descripción y requisitos, **para** iniciar el proceso de reclutamiento.  
- **Criterios de aceptación (Gherkin):**
  ```gherkin
  Given que soy un reclutador autenticado
  When ingreso al módulo de vacantes y selecciono "Crear nueva vacante"
  Then el sistema debe permitirme ingresar campos requeridos y guardar la vacante con estado "Borrador"
  ```
- **Notas o reglas de negocio:** Cada vacante debe tener un ID único, estado inicial “Borrador”, y al menos un responsable asignado.  
- **Trazabilidad:** RF1, UC1  
- **Definition of Done (DoD):** La vacante se crea, valida y persiste correctamente en BD; visible en lista principal.  
- **Role IA / Prompt / Evidencia IA:** Generada por IA según PRD v1.0 (ChatGPT‑5).

### HU-002 / Publicar vacante
- **Como** reclutador, **quiero** publicar una vacante en el portal público, **para** recibir postulaciones de candidatos.  
- **Criterios de aceptación (Gherkin):**
  ```gherkin
  Given una vacante con estado "Borrador"
  When selecciono "Publicar vacante"
  Then el sistema cambia su estado a "Publicada" y genera una URL pública accesible
  ```
- **Notas o reglas de negocio:** Solo usuarios con rol “Reclutador” o “Admin” pueden publicar.  
- **Trazabilidad:** RF1, UC1  
- **DoD:** Estado actualizado, visible en listado público, notificación enviada.  
- **Role IA / Prompt / Evidencia IA:** PRD → HU‑002 derivada del caso CU1.

---

## 📄 Módulo 2. Ingesta y Parsing de CV

### HU-003 / Subir CV
- **Como** candidato, **quiero** subir mi CV en formato PDF o DOCX, **para** aplicar a una vacante.  
- **Criterios de aceptación (Gherkin):**
  ```gherkin
  Given que estoy en la página de una vacante publicada
  When adjunto mi CV y presiono "Enviar postulación"
  Then el sistema almacena el archivo y confirma la recepción
  ```
- **Notas o reglas de negocio:** Validar tamaño máximo (10MB) y formatos permitidos (PDF, DOCX).  
- **Trazabilidad:** RF2, UC2  
- **DoD:** CV cargado, asociado a candidato, con hash único y registro en BD.  
- **Role IA / Prompt / Evidencia IA:** Generado automáticamente del RF2.

### HU-004 / Parsear CV
- **Como** sistema, **quiero** extraer información estructurada del CV, **para** facilitar el análisis y el ranking de candidatos.  
- **Criterios de aceptación (Gherkin):**
  ```gherkin
  Given un CV subido correctamente
  When el sistema ejecuta el parser
  Then debe extraer campos como nombre, email, habilidades, educación y experiencia
  ```
- **Notas o reglas de negocio:** Parser basado en modelo NLP estándar (sin fine‑tuning en MVP).  
- **Trazabilidad:** RF2, UC2  
- **DoD:** Información persistida y vinculada al candidato.  
- **Role IA / Prompt / Evidencia IA:** Basado en análisis IA PRD secciones RF2.

---

## 🧠 Módulo 3. Ranking IA y Matching

### HU-005 / Generar ranking de candidatos
- **Como** reclutador, **quiero** ver un ranking de candidatos por relevancia IA, **para** priorizar entrevistas.  
- **Criterios de aceptación (Gherkin):**
  ```gherkin
  Given una vacante con postulaciones válidas
  When ejecuto el motor de ranking
  Then el sistema muestra una lista ordenada según score de similitud IA
  ```
- **Notas o reglas de negocio:** El score IA debe ser explicable (mostrar criterios principales).  
- **Trazabilidad:** RF3, UC3  
- **DoD:** Ranking visible, actualizado en <2 s, persistido en BD.  
- **Role IA / Prompt / Evidencia IA:** PRD → RF3 → HU‑005.

---

## 🧭 Módulo 4. Pipeline de Postulaciones

### HU-006 / Mover candidato de etapa
- **Como** reclutador, **quiero** mover candidatos entre etapas del pipeline, **para** gestionar su progreso.  
- **Criterios de aceptación (Gherkin):**
  ```gherkin
  Given un pipeline con etapas configuradas
  When arrastro un candidato de una etapa a otra
  Then el sistema actualiza su estado y registra el cambio
  ```
- **Notas o reglas de negocio:** Debe mantenerse historial de movimientos y usuario responsable.  
- **Trazabilidad:** RF4, UC4  
- **DoD:** Actualización persistente + evento registrado.  
- **Role IA / Prompt / Evidencia IA:** Derivada automáticamente de RF4.

---

## 🗓️ Módulo 5. Agenda y Entrevistas

### HU-007 / Agendar entrevista
- **Como** reclutador, **quiero** agendar una entrevista con el candidato, **para** coordinar fechas y horarios con el equipo.  
- **Criterios de aceptación (Gherkin):**
  ```gherkin
  Given que el candidato está en etapa "Entrevista"
  When selecciono "Agendar" y elijo fecha/hora
  Then el sistema crea un evento en el calendario y envía confirmaciones
  ```
- **Notas o reglas de negocio:** Integración con Google Calendar / iCal.  
- **Trazabilidad:** RF5, UC5  
- **DoD:** Evento confirmado + email enviado a partes involucradas.  
- **Role IA / Prompt / Evidencia IA:** PRD RF5.

---

## 💬 Módulo 6. Comunicación por Email

### HU-008 / Enviar correo con plantilla
- **Como** reclutador, **quiero** enviar correos automáticos usando plantillas, **para** mantener comunicación profesional con candidatos.  
- **Criterios de aceptación (Gherkin):**
  ```gherkin
  Given que selecciono un candidato
  When elijo una plantilla de correo
  Then el sistema envía el mensaje con los placeholders completados
  ```
- **Notas o reglas de negocio:** Uso de variables como {{nombre}}, {{vacante}}.  
- **Trazabilidad:** RF7, UC6  
- **DoD:** Correo enviado y registrado en historial.  
- **Role IA / Prompt / Evidencia IA:** Generado con IA, referencia PRD RF7.

---

## 📊 Módulo 7. Reportes y Métricas

### HU-009 / Consultar métricas del funnel
- **Como** admin o reclutador, **quiero** ver reportes de desempeño (funnel, time‑to‑hire), **para** evaluar eficiencia del proceso.  
- **Criterios de aceptación (Gherkin):**
  ```gherkin
  Given que accedo al módulo de reportes
  When selecciono rango de fechas
  Then el sistema muestra métricas clave del proceso de reclutamiento
  ```
- **Notas o reglas de negocio:** Cálculos basados en postulaciones cerradas.  
- **Trazabilidad:** RF8, UC7  
- **DoD:** Dashboard funcional con KPIs básicos.  
- **Role IA / Prompt / Evidencia IA:** PRD RF8.

---

## 👥 Módulo 8. Usuarios y Roles

### HU-010 / Administrar usuarios y permisos
- **Como** administrador, **quiero** gestionar usuarios y roles, **para** controlar accesos y permisos.  
- **Criterios de aceptación (Gherkin):**
  ```gherkin
  Given que soy un administrador autenticado
  When accedo a la sección de usuarios
  Then puedo crear, editar o desactivar cuentas y asignar roles
  ```
- **Notas o reglas de negocio:** Roles disponibles: reclutador, manager, admin.  
- **Trazabilidad:** RF9, UC8  
- **DoD:** CRUD completo de usuarios + permisos validados.  
- **Role IA / Prompt / Evidencia IA:** PRD RF9.

---

## ✅ Estado de la Fase 2
- **Estatus:** *Completado (versión inicial de MVP Must)*  
- **Entradas:** `PRD_LTI.md`  
- **Salidas:** `HistoriasUsuario_LTI.md`  
- **Pendientes:** HUs de tipo Should/Could (próxima iteración).



---

# 📊 Backlog del Producto — Sistema LTI (Fase 3)

> **Rol IA:** Scrum Master y Analista de Producto  
> **Prompt:** “Eres un Scrum Master. Evalúa el valor, esfuerzo y riesgo de cada historia de usuario del LTI. Construye el backlog priorizado y justifica el orden.”  
> **Propósito:** Priorizar las Historias de Usuario del MVP del sistema LTI según valor para el usuario, esfuerzo técnico y riesgo, con enfoque en entregas tempranas de alto impacto.

---

## 🔢 Criterios de clasificación
- **Valor:** impacto para usuario o negocio → *Alto / Medio / Bajo*  
- **Esfuerzo:** complejidad técnica y recursos → *Alto / Medio / Bajo*  
- **Riesgo:** incertidumbre, dependencias, factores externos → *Alto / Medio / Bajo*  
- **Prioridad:** derivada de la relación entre valor, esfuerzo y riesgo.

---

## 🧩 Backlog Priorizado del MVP

| ID | Título | Valor | Esfuerzo | Riesgo | Prioridad | Justificación |
|----|---------|--------|-----------|----------|------------|----------------|
| HU-001 | Crear vacante | Alto | Medio | Bajo | 🟩 Alta | Punto de partida del flujo, esencial para activar todo el proceso. |
| HU-002 | Publicar vacante | Alto | Bajo | Bajo | 🟩 Alta | Dependiente de HU‑001, entrega valor directo (primer input de candidatos). |
| HU-003 | Subir CV | Alto | Medio | Medio | 🟩 Alta | Acción clave de los candidatos; desbloquea matching y pipeline. |
| HU-004 | Parsear CV | Alto | Alto | Medio | 🟧 Media | Requiere modelo NLP; puede implementarse tras HU‑003. |
| HU-005 | Generar ranking IA | Alto | Alto | Alto | 🟥 Baja | Feature diferencial pero compleja; dependerá del modelo IA estable. |
| HU-006 | Mover candidato de etapa | Medio | Bajo | Bajo | 🟩 Alta | Alta frecuencia de uso; bajo riesgo; interfaz drag‑and‑drop. |
| HU-007 | Agendar entrevista | Medio | Medio | Medio | 🟧 Media | Requiere integración calendario; valor importante pero no crítico al inicio. |
| HU-008 | Enviar correo con plantilla | Medio | Bajo | Bajo | 🟩 Alta | Comunicación esencial; rápida implementación. |
| HU-009 | Consultar métricas del funnel | Alto | Medio | Alto | 🟧 Media | Requiere consolidación de datos; se habilita tras HU‑006 y HU‑007. |
| HU-010 | Administrar usuarios y permisos | Alto | Medio | Medio | 🟩 Alta | Seguridad básica; prerequisito para todos los demás módulos. |

---

## ⚙️ Observaciones y dependencias
- **HU‑002** depende de **HU‑001** (una vacante debe existir para publicarse).  
- **HU‑004** depende de **HU‑003** (no se puede parsear sin CV).  
- **HU‑005** depende de **HU‑004** (requiere datos estructurados).  
- **HU‑009** depende de **HU‑006** y **HU‑007** (datos operativos previos).  
- **HU‑010** se considera *infraestructura transversal* (debe existir antes de cualquier operación).  

---

## 🧭 Conclusiones de priorización
1. **Sprint 1 (Core funcional):** HU‑001, HU‑002, HU‑010, HU‑006, HU‑008.  
2. **Sprint 2 (IA y mejoras operativas):** HU‑003, HU‑004, HU‑007.  
3. **Sprint 3 (Optimización y analítica):** HU‑005, HU‑009.  

La estrategia busca entregar valor temprano asegurando estabilidad del flujo base (crear‑publicar‑postular‑mover‑comunicar), antes de abordar las capas IA y analítica.

---

## ✅ Estado de la Fase 3
- **Estatus:** *Completado (versión inicial del backlog priorizado)*  
- **Entradas:** `HistoriasUsuario_LTI.md`  
- **Salidas:** `Backlog_LTI.md`  
- **Pendientes:** Validar con equipo técnico estimaciones detalladas (story points).


---

# 🧾 Tickets de Trabajo — Sprint 1 (Sistema LTI)

> **Rol IA:** Tech Lead / Arquitecto de Software  
> **Prompt:** “Eres un Tech Lead. Descompón las historias seleccionadas del backlog en tickets técnicos con estimación y Definition of Done.”  
> **Propósito:** Detallar las tareas técnicas derivadas de las Historias de Usuario priorizadas en el Sprint 1, usando **Story Points (1–13)** para reflejar complejidad.

---

## 🧩 HU‑001 — Crear vacante

### 🎯 Ticket T‑001‑1 / Endpoint API de creación de vacantes
- **Descripción técnica:** Diseñar y desarrollar el endpoint `POST /vacantes` para registrar vacantes con campos obligatorios (título, descripción, responsable).  
- **Story Points:** 5  
- **DoD:** Endpoint funcional, validaciones completadas, pruebas unitarias >80%.  
- **Dependencias:** BD (tabla `vacantes` creada).  
- **Role IA / Evidencia IA:** Desglosado de HU‑001 vía ChatGPT‑5.

### 🎯 Ticket T‑001‑2 / Formulario de creación en UI
- **Descripción técnica:** Implementar formulario en frontend con validación y feedback visual.  
- **Story Points:** 3  
- **DoD:** Formulario operable, validaciones dinámicas y persistencia exitosa.  
- **Dependencias:** API T‑001‑1.  

### 🎯 Ticket T‑001‑3 / Persistencia en base de datos
- **Descripción técnica:** Crear modelo `Vacante` con migraciones y persistencia ORM.  
- **Story Points:** 2  
- **DoD:** Modelo probado, campos auditables (created_at, updated_at).  

---

## 🧩 HU‑002 — Publicar vacante

### 🎯 Ticket T‑002‑1 / Endpoint de publicación de vacante
- **Descripción técnica:** Crear endpoint `PATCH /vacantes/{id}/publicar` que cambie estado a “Publicada”.  
- **Story Points:** 2  
- **DoD:** Endpoint funcional, logs generados, pruebas unitarias.  
- **Dependencias:** HU‑001 (vacante existente).  

### 🎯 Ticket T‑002‑2 / Generación de URL pública
- **Descripción técnica:** Implementar lógica para generar enlace público único (`/jobs/{uuid}`).  
- **Story Points:** 3  
- **DoD:** URL funcional, persistida, probada manualmente.  

### 🎯 Ticket T‑002‑3 / Notificación al reclutador
- **Descripción técnica:** Enviar correo al reclutador confirmando publicación.  
- **Story Points:** 2  
- **DoD:** Correo entregado y registrado en historial.  

---

## 🧩 HU‑006 — Mover candidato de etapa

### 🎯 Ticket T‑006‑1 / Endpoint para actualizar etapa del candidato
- **Descripción técnica:** Crear endpoint `PATCH /postulaciones/{id}/etapa` con validaciones.  
- **Story Points:** 3  
- **DoD:** Endpoint probado, logs y auditoría activos.  

### 🎯 Ticket T‑006‑2 / UI Drag‑and‑Drop del pipeline
- **Descripción técnica:** Implementar funcionalidad drag‑and‑drop para mover tarjetas entre etapas.  
- **Story Points:** 8  
- **DoD:** Movimiento fluido, actualización inmediata y confirmación visual.  

### 🎯 Ticket T‑006‑3 / Registro histórico de movimientos
- **Descripción técnica:** Guardar histórico (fecha, usuario, etapa origen/destino).  
- **Story Points:** 5  
- **DoD:** Auditoría persistente, consulta verificable en panel admin.  

---

## 🧩 HU‑008 — Enviar correo con plantilla

### 🎯 Ticket T‑008‑1 / Endpoint de envío de correos
- **Descripción técnica:** Crear endpoint `POST /correos` que use plantilla + placeholders.  
- **Story Points:** 3  
- **DoD:** Endpoint probado, logs y colas activas (async si aplica).  

### 🎯 Ticket T‑008‑2 / Módulo de plantillas de correo
- **Descripción técnica:** Diseñar CRUD para gestionar plantillas (`asunto`, `cuerpo`, variables).  
- **Story Points:** 5  
- **DoD:** CRUD operativo, vinculado con endpoint de envío.  

### 🎯 Ticket T‑008‑3 / Pruebas de integración de correo
- **Descripción técnica:** Validar envío end‑to‑end con proveedor SMTP de prueba.  
- **Story Points:** 3  
- **DoD:** Email recibido, logs sin errores.  

---

## 🧩 HU‑010 — Administrar usuarios y permisos

### 🎯 Ticket T‑010‑1 / Modelo y migraciones de usuarios
- **Descripción técnica:** Crear tabla `usuarios` con roles (admin, reclutador, manager).  
- **Story Points:** 5  
- **DoD:** Modelo validado, migraciones correctas, prueba de autenticación básica.  

### 🎯 Ticket T‑010‑2 / Endpoint CRUD usuarios
- **Descripción técnica:** Implementar endpoints `GET/POST/PATCH/DELETE /usuarios`.  
- **Story Points:** 8  
- **DoD:** CRUD funcional con validaciones y paginación.  

### 🎯 Ticket T‑010‑3 / Middleware de permisos
- **Descripción técnica:** Desarrollar middleware para validar rol antes de cada acción.  
- **Story Points:** 5  
- **DoD:** Restricciones activas, pruebas unitarias completas.  

---

## 🧭 Resumen del Sprint 1 (Estimaciones)

| Historia | Tickets | Total Story Points |
|-----------|----------|-------------------|
| HU‑001 | 3 | 10 |
| HU‑002 | 3 | 7 |
| HU‑006 | 3 | 16 |
| HU‑008 | 3 | 11 |
| HU‑010 | 3 | 18 |
| **Total Sprint 1** | **15 tickets** | **62 Story Points** |

---

## ✅ Estado de la Fase 4
- **Estatus:** *Completado (versión inicial del Sprint Backlog)*  
- **Entradas:** `Backlog_LTI.md`  
- **Salidas:** `Tickets_Sprint1_LTI.md`  
- **Pendientes:** Ajuste de estimaciones tras validación del equipo técnico y definición del Sprint Goal.


---

# 🕒 Planificación del Sprint 1 — Sistema LTI

> **Rol IA:** Scrum Master  
> **Prompt:** “Eres un Scrum Master. Ayúdame a planificar el Sprint 1 del LTI: selecciona HU, define objetivo, capacidad y métricas.”  
> **Propósito:** Definir el alcance, objetivo, métricas y plan operativo del **Sprint 1**, aplicando prácticas ágiles de Scrum basadas en los artefactos generados en fases previas.

---

## 🎯 Objetivo del Sprint (Sprint Goal)
**Entregar la base funcional del flujo principal de reclutamiento del sistema LTI**, incluyendo creación y publicación de vacantes, gestión inicial de postulaciones y comunicación con candidatos, con control de usuarios y permisos.

> 🧩 “Al finalizar el Sprint 1, el usuario podrá crear y publicar vacantes, recibir postulaciones, mover candidatos en el pipeline y enviar correos automáticos usando plantillas.”

---

## 📅 Duración y Capacidad

| Parámetro | Valor |
|------------|--------|
| **Duración del Sprint** | 2 semanas (10 días hábiles) |
| **Equipo de desarrollo** | 5 personas |
| **Capacidad estimada** | ~60 Story Points |
| **Velocidad de referencia** | 60 SP promedio / sprint |
| **Dedicación por persona** | 6 h/día promedio (sin overhead) |

---

## 🧩 Historias y Tickets Seleccionados (Sprint 1)

| HU | Descripción | Total SP | Tickets Asociados |
|----|--------------|-----------|------------------|
| HU‑001 | Crear vacante | 10 | T‑001‑1, T‑001‑2, T‑001‑3 |
| HU‑002 | Publicar vacante | 7 | T‑002‑1, T‑002‑2, T‑002‑3 |
| HU‑006 | Mover candidato de etapa | 16 | T‑006‑1, T‑006‑2, T‑006‑3 |
| HU‑008 | Enviar correo con plantilla | 11 | T‑008‑1, T‑008‑2, T‑008‑3 |
| HU‑010 | Administrar usuarios y permisos | 18 | T‑010‑1, T‑010‑2, T‑010‑3 |
| **Total estimado** | — | **62 Story Points** | **15 tickets** |

> Nota: se asume una ligera sobreasignación (62 vs 60 SP) aceptable para el Sprint 1 dada la naturaleza fundacional del trabajo.

---

## ⚙️ Criterios de Aceptación Globales del Sprint

- Todas las APIs CRUD básicas (vacantes, usuarios, correos) operan con persistencia real.  
- Pipeline de candidatos con interfaz drag‑and‑drop funcional.  
- Flujo de publicación y postulación completo (E2E).  
- Autenticación y permisos activos.  
- Pruebas unitarias ≥80% cobertura.  
- Documentación mínima de endpoints generada (`README_LTI.md`).

---

## 📈 Métricas de Éxito del Sprint

| Categoría | Métrica | Meta |
|------------|----------|------|
| **Entrega** | Historias completadas | ≥ 90% del compromiso |
| **Calidad** | Cobertura de pruebas | ≥ 80% |
| **Velocidad** | SP entregados | 60 ± 10% |
| **Satisfacción** | Feedback del Product Owner | ≥ 8/10 |
| **Defectos post‑entrega** | Bugs críticos abiertos | ≤ 2 |

---

## 🚧 Riesgos y Mitigaciones

| Riesgo | Impacto | Probabilidad | Mitigación |
|---------|----------|---------------|-------------|
| Integración API/UI no sincronizada | Alto | Medio | Revisión diaria y pruebas tempranas de endpoints. |
| Dudas en modelo de permisos | Medio | Medio | Sesión técnica con arquitecto y validación de roles. |
| Exceso de SP en Sprint 1 | Medio | Alto | Priorización diaria y recorte si se excede capacidad. |
| Problemas con SMTP o plantillas | Bajo | Medio | Entorno de prueba aislado (sandbox). |

---

## 🧭 Ceremonias Planificadas

| Ceremonia | Frecuencia | Objetivo |
|------------|-------------|-----------|
| **Daily Scrum** | Diario (15 min) | Sincronizar avances y bloqueos. |
| **Sprint Planning** | Día 1 (2 h) | Revisar backlog, asignar tickets y objetivos. |
| **Sprint Review** | Día 10 (1.5 h) | Mostrar incremento al Product Owner. |
| **Sprint Retrospective** | Día 10 (1 h) | Analizar aprendizajes y mejoras. |

---

## ✅ Estado de la Fase 5
- **Estatus:** *Completado (planificación inicial del Sprint 1)*  
- **Entradas:** `Tickets_Sprint1_LTI.md`  
- **Salidas:** `PlanSprint1_LTI.md`  
- **Pendientes:** Revisión del Sprint Goal y capacidad real tras retroalimentación del equipo.


---

