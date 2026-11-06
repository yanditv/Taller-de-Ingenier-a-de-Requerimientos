# Taller colaborativo: Ingeniería de Requerimientos de Software

**Modalidad:** Trabajo en grupos — simulación cliente y equipo desarrollador  
**Alcance de esta entrega:** Fases 1 y 2  
**Propósito:** Comprender las necesidades de un negocio y practicar técnicas de levantamiento de requerimientos mediante la interacción con otro grupo.

## Organización del taller

Cada grupo seleccionará o propondrá un negocio que necesita un sistema de software. Un grupo distinto asumirá el rol de **equipo desarrollador** de ese proyecto.

Todos los grupos tendrán dos responsabilidades simultáneas:

- **Grupo cliente:** representar al dueño o responsables del negocio, explicar sus problemas y necesidades, y proporcionar información al equipo desarrollador.
- **Grupo desarrollador:** investigar el negocio asignado, preparar y realizar entrevistas, registrar hallazgos y documentar necesidades sin inventar respuestas.

### Asignación cruzada sugerida

| Grupo | Es cliente del proyecto | Desarrolla el proyecto de |
|---|---|---|
| 1 | Proyecto 1 | Grupo 5 |
| 2 | Proyecto 2 | Grupo 1 |
| 3 | Proyecto 3 | Grupo 2 |
| 4 | Proyecto 4 | Grupo 3 |
| 5 | Proyecto 5 | Grupo 4 |

### Casos de negocio sugeridos

1. Clínica veterinaria que necesita mejorar la gestión de sus actividades y atención.
2. Negocio comercial con dificultades para administrar ventas e inventario.
3. Institución educativa que requiere organizar el uso de laboratorios y recursos.
4. Restaurante que necesita mejorar la coordinación de pedidos y atención.
5. Centro médico con problemas en la organización de reservas y turnos.

Los grupos pueden proponer otro caso con aprobación del docente. Los casos son **puntos de partida**, no listas de funcionalidades ya definidas.

---

## Fase 1. Definición de la necesidad del negocio

**Responsable:** Grupo propietario del negocio (cliente).

### Objetivo

Describir el negocio, sus problemas y lo que espera conseguir con un sistema informático, desde la perspectiva del cliente.

### Actividades

1. Seleccionar el caso o proponer un negocio propio.
2. Definir el nombre, la actividad y una breve descripción del negocio.
3. Explicar cómo se realizan actualmente sus principales actividades.
4. Identificar los problemas, dificultades o limitaciones que enfrenta.
5. Justificar por qué necesita un sistema de software.
6. Explicar los resultados que espera obtener con el sistema.
7. Identificar a las personas involucradas y a los futuros usuarios.
8. Establecer las prioridades y restricciones conocidas del negocio.

### Entregable 1. Documento de necesidades del negocio

El documento debe incluir:

| Sección | Contenido requerido |
|---|---|
| Identificación | Nombre del negocio, actividad y grupo propietario |
| Contexto | Descripción general y funcionamiento actual |
| Problema | Principales dificultades que motivan el proyecto |
| Justificación | Razones por las que se necesita el software |
| Objetivo del negocio | Qué se espera mejorar o conseguir |
| Personas involucradas | Propietarios, trabajadores, clientes y posibles usuarios |
| Necesidades iniciales | Lo que el negocio desea que el sistema permita realizar, expresado en lenguaje del cliente |
| Restricciones | Condiciones o limitaciones conocidas, si existen |

### Evidencias obligatorias de la fase 1

- **E1.** Documento de necesidades del negocio en formato Markdown o PDF.
- **E2.** Identificación de los integrantes y sus roles como representantes del negocio.
- **E3.** Relación de al menos tres problemas del negocio con sus consecuencias.
- **E4.** Listado de necesidades iniciales, priorizadas por el grupo cliente.

> **Regla:** En esta fase no se debe diseñar la base de datos, seleccionar tecnologías ni redactar una especificación técnica. El cliente explica el problema y sus expectativas; no sustituye el trabajo de análisis del desarrollador.

---

## Fase 2. Reunión entre el cliente y el equipo desarrollador

**Responsables:** Grupo desarrollador y grupo cliente asignado.

### Objetivo

Obtener información directamente del cliente mediante una entrevista estructurada y registrar las necesidades, procesos, reglas y dudas que servirán para el análisis de requerimientos.

### Actividades del grupo desarrollador

1. Revisar el documento de necesidades entregado por el cliente.
2. Preparar un cuestionario con **al menos diez preguntas abiertas**.
3. Organizar y realizar una reunión con el grupo cliente.
4. Preguntar cómo funcionan los procesos actuales y qué dificultades presentan.
5. Identificar usuarios, responsabilidades y necesidades de información.
6. Indagar sobre funcionalidades esperadas, reglas de negocio y restricciones.
7. Preguntar por situaciones excepcionales y prioridades.
8. Registrar las respuestas sin cambiar su significado.
9. Identificar contradicciones, dudas y aspectos pendientes de aclaración.
10. Redactar un acta y compartirla con el cliente para su revisión.

### Actividades del grupo cliente

1. Presentar el negocio y sus problemas reales o simulados.
2. Responder de manera coherente y detallada las preguntas.
3. Explicar ejemplos concretos de sus procesos cotidianos.
4. Aclarar qué es prioritario y qué podría quedar para una etapa posterior.
5. Revisar el acta y confirmar o corregir la información registrada.

### Preguntas orientadoras para la entrevista

Estas preguntas son ejemplos; cada equipo debe adaptarlas a su proyecto.

1. ¿Cuál es la actividad principal del negocio?
2. ¿Cómo se realiza actualmente el proceso que desean mejorar?
3. ¿Qué problemas ocurren con mayor frecuencia?
4. ¿Quiénes participan en ese proceso y qué hace cada uno?
5. ¿Qué información se registra, consulta o modifica?
6. ¿Qué tareas esperan realizar con el sistema?
7. ¿Qué situaciones especiales o errores deben contemplarse?
8. ¿Qué reglas del negocio deben cumplirse obligatoriamente?
9. ¿Qué información debe ser confidencial o estar restringida?
10. ¿Cuáles son las necesidades más importantes y por qué?
11. ¿Qué herramientas o sistemas utilizan actualmente?
12. ¿Cómo sabrán que el nuevo sistema resuelve el problema?

### Entregable 2. Informe de levantamiento inicial de requerimientos

| Sección | Contenido requerido |
|---|---|
| Identificación | Proyecto, grupo cliente, grupo desarrollador y participantes |
| Preparación | Objetivo de la reunión y cuestionario utilizado |
| Entrevista | Preguntas y respuestas registradas |
| Procesos actuales | Descripción de las actividades explicadas por el cliente |
| Actores | Personas o perfiles que interactuarían con el sistema |
| Necesidades identificadas | Lista preliminar de necesidades expresadas por el cliente |
| Reglas y restricciones | Condiciones señaladas por el cliente |
| Prioridades | Necesidades más importantes según el cliente |
| Pendientes | Preguntas sin resolver, contradicciones y acuerdos de seguimiento |
| Validación | Observaciones y conformidad del grupo cliente sobre el acta |

### Evidencias obligatorias de la fase 2

- **E5.** Cuestionario de entrevista preparado por el grupo desarrollador.
- **E6.** Registro completo de preguntas y respuestas.
- **E7.** Evidencia de la reunión: fotografía, captura de pantalla o registro de asistencia, con consentimiento de los participantes.
- **E8.** Acta de reunión con fecha, participantes, temas tratados, acuerdos y pendientes.
- **E9.** Listado preliminar de necesidades y actores identificados.
- **E10.** Confirmación del grupo cliente de que el acta refleja lo conversado; puede constar mediante firma, comentario escrito o aprobación digital.

> **Regla:** El equipo desarrollador no debe inventar funcionalidades ni dar por aprobadas necesidades que el cliente no haya confirmado. Las dudas deben quedar registradas para una siguiente reunión.

---

## Formato de acta de reunión

**Proyecto:**  
**Grupo cliente:**  
**Grupo desarrollador:**  
**Fecha:**  
**Participantes:**  
**Objetivo de la reunión:**  

### Temas tratados

| N.º | Tema | Información proporcionada por el cliente |
|---|---|---|
| 1 | | |
| 2 | | |
| 3 | | |

### Acuerdos y pendientes

| N.º | Acuerdo o pendiente | Responsable | Estado |
|---|---|---|---|
| 1 | | | |
| 2 | | | |

**Observaciones del cliente:**  
**Confirmación del cliente:**  

---

## Lista de verificación antes de entregar

- [ ] El grupo cliente describió el negocio y sus problemas.
- [ ] Se documentaron las necesidades y prioridades iniciales.
- [ ] El equipo desarrollador preparó al menos diez preguntas abiertas.
- [ ] Se realizó la entrevista con el grupo cliente asignado.
- [ ] Se registraron preguntas, respuestas y ejemplos relevantes.
- [ ] Se identificaron actores, procesos y necesidades preliminares.
- [ ] Se elaboró el acta con acuerdos y pendientes.
- [ ] El grupo cliente revisó el acta.
- [ ] Se adjuntaron las evidencias E1 a E10.

## Forma de entrega

Cada grupo presentará **dos carpetas separadas**, una por cada rol que desempeña:

```text
Grupo_N/
├── Fase_1_Como_Cliente/
│   ├── necesidades_negocio.md
│   └── evidencias/
└── Fase_2_Como_Desarrollador/
    ├── cuestionario.md
    ├── entrevista_preguntas_respuestas.md
    ├── informe_levantamiento.md
    ├── acta_reunion.md
    └── evidencias/
```

**Resultado esperado:** al finalizar las dos fases, cada grupo habrá definido las necesidades de su propio negocio y habrá levantado información de otro proyecto. Esta información será la base de la **Fase 3: Análisis y especificación de requerimientos funcionales y no funcionales**.
