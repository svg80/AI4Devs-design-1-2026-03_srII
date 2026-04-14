- [Asistentes](#asistentes)
  - [Prompt 1 - Invstigación](#prompt-1---invstigación)
  - [Prompt 2 - Investigación](#prompt-2---investigación)
  - [Prompt 3  - Investigación](#prompt-3----investigación)
  - [Prompt 4 - Brainstorming diferencial](#prompt-4---brainstorming-diferencial)
  - [Prompt 6 - Priorización y enfoque](#prompt-6---priorización-y-enfoque)
  - [Prompt 7 - Definición del producto](#prompt-7---definición-del-producto)
  - [Prompt 9 - Lean Canvas](#prompt-9---lean-canvas)
  - [Promto 10 - Descripción de casos de uso y diagramas](#promto-10---descripción-de-casos-de-uso-y-diagramas)
  - [Prompt 11 - Modelo de datos](#prompt-11---modelo-de-datos)
  - [Prompt 12 - Diseño del sistema a alto nivel](#prompt-12---diseño-del-sistema-a-alto-nivel)
  - [Prompt 13 - Diagrama en C4 de uno de los componentes](#prompt-13---diagrama-en-c4-de-uno-de-los-componentes)


# Asistentes
* ChatGPT
* ChatDiagram para contstruir Lean Canvas


## Prompt 1 - Invstigación
```
Eres un experto en producto, con experiencia en ATS - Applicant-Tracking-System, incluyo una imagen para ampliar el contexto de lo que es un ATS. ¿Qué funcionalidades básicas tiene un ATS - Applicant-Tracking-System? Descríbelas en un listado, ordenado de mayor a menor prioridad.
```

## Prompt 2 - Investigación
```
¿Qué beneficios obtiene el cliente de un ATS para considerar su uso?
```

## Prompt 3  - Investigación
```
¿Qué alternativas tiene a usar un ATS y cuándo pueden ser relevantes?
```

## Prompt 4 - Brainstorming diferencial
```
Contexto:
Estás diseñando un producto SaaS llamado LTI (plataforma de recruiting / ATS).

Objetivos clave del producto:
- Aumentar la eficiencia operativa de los equipos de HR
- Mejorar la colaboración en tiempo real entre recruiters y hiring managers
- Automatizar tareas repetitivas del proceso de selección
- Incorporar IA como asistente en distintas fases del proceso

Notas:
- Ya se han identificado funcionalidades básicas típicas (pipeline, gestión de candidatos, etc.), NO son el foco
- Debes buscar diferenciación real frente a herramientas como Greenhouse, Lever, Workday
- El resultado debe ser aplicable a un producto real (no ideas genéricas)

Actúa como un Product Manager senior especializado en HR Tech B2B SaaS.

Tarea:
Genera un brainstorming de funcionalidades diferenciales para LTI.

Condiciones:
- Evita funcionalidades básicas de ATS
- Prioriza eficiencia, colaboración e IA
- Piensa en problemas reales no resueltos o mal resueltos en procesos de selección de empresas medianas y grandes
- No propongas solo “features”, sino capacidades de producto con impacto claro

Salida estructurada:
Para cada funcionalidad:
- Nombre
- Problema que resuelve
- Usuario principal (HR / manager / candidato)
- Cómo se resuelve hoy y cuáles son sus limitaciones
- En qué consiste la mejora propuesta
- Impacto esperado (ahorro de tiempo, calidad de contratación, reducción de fricción, etc.)
- Complejidad estimada (baja / media / alta)

Además:
1. Clasifica las funcionalidades en:
   - Quick wins
   - Medium bets
   - Big bets (IA avanzada)
2. Prioriza dentro de cada grupo
3. Señala cuáles podrían convertirse en ventajas competitivas reales frente a Greenhouse, Lever y Workday
```

## Prompt 6 - Priorización y enfoque
```
Contexto:
Estás diseñando un producto SaaS llamado LTI (plataforma de recruiting / ATS).

Objetivos clave del producto:
- Aumentar la eficiencia operativa de los equipos de HR
- Mejorar la colaboración en tiempo real entre recruiters y hiring managers
- Automatizar tareas repetitivas del proceso de selección
- Incorporar IA como asistente en distintas fases del proceso

Notas:
- Ya se han identificado funcionalidades básicas típicas (pipeline, gestión de candidatos, etc.), NO son el foco
- Debes buscar diferenciación real frente a herramientas como Greenhouse, Lever, Workday
- El resultado debe ser aplicable a un producto real (no ideas genéricas)

Resultados del brainstorming:
Aquí tienes el brainstorming estructurado para LTI, orientado a diferenciación real frente a ATS que ya destacan en structured hiring, CRM recruiting y automatización/IA como Greenhouse, Lever y Workday. Greenhouse está muy asociado a structured hiring y scorecards; Lever a ATS + CRM; Workday a IA embebida para priorización y matching. Por tanto, la oportunidad para LTI no está en repetir eso, sino en resolver mejor la fricción operativa entre HR y managers, la ejecución real del proceso y la capa de inteligencia accionable y auditable.

- Quick wins
  1. Orquestador de alineación de vacante
    - Problema que resuelve: mucha ineficiencia nace antes de publicar la vacante: HR y manager no están alineados sobre perfil, prioridades, must-have vs nice-to-have, salario realista, SLAs y criterios de descarte.
    - Usuario principal: HR + hiring manager
    - Cómo se resuelve hoy y limitaciones: kickoff por email, reuniones, documentos sueltos o templates. El conocimiento queda disperso y no se reutiliza. Greenhouse estructura la evaluación, pero no siempre resuelve bien la alineación operativa inicial.
    - Mejora propuesta: un “briefing inteligente” guiado que fuerza acuerdos explícitos antes de abrir la vacante:
      * objetivos del rol
      * skills críticas y ponderación
      * riesgos de mercado
      * entrevistadores y responsabilidades
      * tiempos objetivo por etapa
      * criterios de descarte y señales de calidad
    - Impacto esperado: menos retrabajo, menos candidatos mal filtrados, menos cambios de criterio a mitad del proceso.
    - Complejidad estimada: baja
    - Ventaja competitiva real: media-alta. No es solo un formulario; si se convierte en el punto de verdad compartido para todo el proceso, sí diferencia.

  2. Centro de decisiones y bloqueos del proceso
    - Problema que resuelve: los procesos no se ralentizan por falta de pipeline, sino por cuellos de botella invisibles: feedback pendiente, entrevistas sin cerrar, managers que no responden, decisiones ambiguas.
    - Usuario principal: HR
    - Cómo se resuelve hoy y limitaciones: dashboards genéricos, Slack, recordatorios manuales. Los ATS suelen mostrar estado, pero no siempre explican “qué bloquea la contratación ahora”. Lever automatiza tareas rutinarias, pero el problema de coordinación sigue vivo.
    - Mejora propuesta: vista operativa orientada a acción:
      * “qué contrataciones están bloqueadas”
      * “quién tiene el siguiente paso”
      * “qué feedback falta”
      * “qué vacantes van fuera de SLA”
      * sugerencias automáticas de resolución
    - Impacto esperado: reducción directa de time-to-hire y menor carga de seguimiento manual.
    - Complejidad estimada: baja
    - Ventaja competitiva real: alta si la UX está centrada en resolución, no en reporting.

  3. Feedback guiado y comparativo en tiempo real
    - Problema que resuelve: feedback tardío, pobre, inconsistente o sesgado; difícil comparar candidatos entre entrevistadores.
    - Usuario principal: hiring manager + entrevistadores
    - Cómo se resuelve hoy y limitaciones: scorecards y notas manuales. Greenhouse ya trabaja bien structured hiring y scorecards, así que repetir eso no basta.
    - Mejora propuesta:
      * feedback guiado por competencias
      * obligación de evidencias observables
      * comparación entre evaluaciones
      * detección de incoherencias
      * alertas de feedback vago o no justificable
    - Impacto esperado: mejor calidad de decisión, menor sesgo, menos debriefs improductivos.
    - Complejidad estimada: media
    - Ventaja competitiva real: media. Sube a alta si se combina con IA auditada y coaching de entrevistadores.

  4. Agenda colaborativa de contratación
    - Problema que resuelve: HR persigue a managers para conseguir disponibilidad, feedback y cierre.
    - Usuario principal: HR + manager
    - Cómo se resuelve hoy y limitaciones: calendarios, correo, chat, automatizaciones parciales. Hay herramientas con scheduling, pero el problema no es solo encontrar huecos, sino mantener el compromiso del manager con el proceso. Workday y el ecosistema AI recruiting se están moviendo fuerte en automatización conversacional, así que aquí LTI debe enfocarse en accountability, no solo scheduling.
    - Mejora propuesta:
      * compromiso visible por rol
      * tareas con fecha y ownership
      * recordatorios según criticidad
      * escalado automático si un manager bloquea el proceso
      * resumen semanal por vacante
    - Impacto esperado: menos chasing manual y más disciplina operativa.
    - Complejidad estimada: baja
    - Ventaja competitiva real: media-alta.

- Medium bets

  5. Copiloto de recruiter para priorización diaria
    - Problema que resuelve: el recruiter pierde tiempo decidiendo dónde actuar primero entre decenas de vacantes, candidatos y tareas.
    - Usuario principal: HR
    - Cómo se resuelve hoy y limitaciones: dashboards, filtros, experiencia personal. Workday ya ofrece priorización y grading con IA; por tanto LTI no debe quedarse en “ranking de candidatos”, sino priorizar trabajo operativo completo.
    - Mejora propuesta:
      * lista diaria de acciones recomendadas
      * qué vacante necesita atención hoy
      * qué candidato requiere aceleración
      * qué manager está creando riesgo
      * qué acción genera más probabilidad de cierre
    - Impacto esperado: mejora de productividad recruiter y reducción de contexto mental.
    - Complejidad estimada: media
    - Ventaja competitiva real: alta, si la IA prioriza trabajo y no solo candidatos.

  6. Motor de calibración HR–manager
    - Problema que resuelve: HR y managers tienen estándares distintos; lo que para uno es “fuerte candidato”, para otro no lo es.
    - Usuario principal: HR + manager
    - Cómo se resuelve hoy y limitaciones: reuniones de calibración, debriefs, intuición. Poca trazabilidad y difícil aprendizaje organizativo.
    - Mejora propuesta:
      * detección de divergencias recurrentes entre recruiters e entrevistadores
      * análisis por vacante, equipo, manager y tipo de perfil
      * sugerencias para recalibrar criterios
      * histórico de decisiones y posterior desempeño del contratado
    - Impacto esperado: mejora de consistencia y calidad de contratación.
    - Complejidad estimada: media
    - Ventaja competitiva real: alta. Esto va más allá del ATS tradicional.

  7. Diagnóstico de proceso por vacante
    - Problema que resuelve: cuando una vacante no avanza, nadie sabe con precisión si el problema es sourcing, salario, filtro, entrevistadores o lentitud de decisión.
    - Usuario principal: HR lead / recruiting ops
    - Cómo se resuelve hoy y limitaciones: reporting clásico posterior, muy agregado y poco accionable.
    - Mejora propuesta:
      * diagnóstico por vacante en tiempo real
      * identificación del punto de fuga
      * benchmark interno entre vacantes similares
      * recomendaciones concretas: replantear scorecard, ampliar salario, cambiar panel, reducir etapa, ajustar JD
    - Impacto esperado: menos tiempo perdido en interpretación y mejor optimización continua.
    - Complejidad estimada: media
    - Ventaja competitiva real: alta.

  8. Capa de colaboración contextual recruiter-manager
    - Problema que resuelve: hoy gran parte de la colaboración sucede fuera del ATS, en Slack, email o reuniones, y se pierde el contexto.
    - Usuario principal: HR + manager
    - Cómo se resuelve hoy y limitaciones: comentarios sueltos por candidato o comunicación fuera de plataforma. Lever enfatiza colaboración, pero el contexto sigue fragmentándose con facilidad.
    - Mejora propuesta:
      * decisiones y conversaciones ancladas a vacante, etapa o candidato
      * menciones, resolución de dudas, propuestas de avance
      * resumen automático de decisiones tomadas
      * todo queda trazado y reutilizable
    - Impacto esperado: menos pérdida de contexto, menos reuniones, mayor velocidad de decisión.
    - Complejidad estimada: media
    - Ventaja competitiva real: media-alta si reemplaza coordinación externa de forma natural.

- Big bets (IA avanzada)

  9. Debrief inteligente y auditable
    - Problema que resuelve: los debriefs son lentos, subjetivos y muchas veces repiten información dispersa.
    - Usuario principal: HR + hiring manager
    - Cómo se resuelve hoy y limitaciones: reunión manual + lectura de notas + scorecards. Mucho tiempo y baja consistencia.
    - Mejora propuesta:
      * síntesis automática del feedback por candidato
      * agrupación por competencias
      * conflictos entre entrevistadores
      * huecos de evidencia
      * recomendación de decisión con trazabilidad completa
      * versión auditable y editable por humanos
    - Impacto esperado: menos tiempo en debrief, decisiones más consistentes, mejor gobernanza.
    - Complejidad estimada: alta
    - Ventaja competitiva real: muy alta, especialmente por la parte auditable. La presión regulatoria y litigios sobre IA en empleo hacen crítica la trazabilidad.

  10. Coach de entrevistas para managers
    - Problema que resuelve: muchos managers entrevistan mal, preguntan de forma inconsistente, evalúan sin evidencia y generan mala experiencia al candidato.
    - Usuario principal: hiring manager / entrevistador
    - Cómo se resuelve hoy y limitaciones: templates, formación ocasional, shadowing. Poco escalable y sin seguimiento.
    - Mejora propuesta:
      * preparación automática previa a la entrevista
      * guion adaptado al rol y etapa
      * recordatorio de señales a observar
      * revisión posterior del feedback dado
      * coaching sobre calidad de evaluación y sesgos
    - Impacto esperado: mejora de calidad de entrevista y menor dependencia de recruiters senior.
    - Complejidad estimada: alta
    - Ventaja competitiva real: muy alta. Pocos ATS resuelven de verdad la capacitación operativa del manager dentro del flujo.

  11. Simulador de riesgo de cierre de vacante
    - Problema que resuelve: HR detecta tarde que una vacante va a cerrarse mal o tarde.
    - Usuario principal: HR lead / recruiting ops
    - Cómo se resuelve hoy y limitaciones: intuición, reporting histórico, experiencia del recruiter.
    - Mejora propuesta:
      * predicción de riesgo de no cobertura
      * señales explicables: salario fuera de mercado, baja conversión, lentitud de managers, panel excesivo, feedback inconsistente
      * recomendación de intervención
    - Impacto esperado: actuación temprana y mejor planificación de capacidad.
    - Complejidad estimada: alta
    - Ventaja competitiva real: alta si es explicable y accionable.

  12. Memoria organizativa de contratación
    - Problema que resuelve: cada nueva vacante se trata casi desde cero; la empresa no aprende sistemáticamente de contrataciones pasadas.
    - Usuario principal: HR / recruiting ops / leadership
    - Cómo se resuelve hoy y limitaciones: reporting histórico fragmentado, conocimiento tácito de recruiters senior.
    - Mejora propuesta:
      * base de conocimiento viva sobre qué perfiles funcionaron
      * qué paneles entrevistaron mejor
      * qué criterios predijeron éxito
      * qué managers bloquean procesos
      * qué configuraciones aceleran cierres sin bajar calidad
    - Impacto esperado: aprendizaje compuesto a nivel organización, no solo eficiencia puntual.
    - Complejidad estimada: alta
    - Ventaja competitiva real: muy alta. Esto sí puede convertirse en moat si se alimenta bien.

- Priorización dentro de cada grupo
  - Quick wins
    * Centro de decisiones y bloqueos del proceso
    * Orquestador de alineación de vacante
    * Agenda colaborativa de contratación
    * Feedback guiado y comparativo en tiempo real
  - Medium bets
    * Motor de calibración HR–manager
    * Diagnóstico de proceso por vacante
    * Copiloto de recruiter para priorización diaria
    * Capa de colaboración contextual recruiter-manager
  - Big bets
    * Debrief inteligente y auditable
    * Coach de entrevistas para managers
    * Memoria organizativa de contratación
    * Simulador de riesgo de cierre de vacante

Qué funcionalidades tienen más potencial de ventaja competitiva real

Las que veo con mayor capacidad de diferenciar de verdad a LTI son estas:
 - Centro de decisiones y bloqueos del proceso
   Porque ataca un dolor cotidiano muy real: la fricción de ejecución. Los ATS suelen registrar el proceso; pocos lo “desbloquean” activamente.
  - Motor de calibración HR–manager
    Porque resuelve un problema muy costoso y poco bien cubierto: la desalineación de criterios entre negocio y recruiting.
  - Debrief inteligente y auditable
    Porque une productividad + calidad + trazabilidad, y eso gana relevancia con la presión regulatoria sobre IA en hiring.
  - Coach de entrevistas para managers
    Porque desplaza valor desde “gestionar candidatos” a “mejorar cómo decide la empresa”.
  - Memoria organizativa de contratación
    Porque crea aprendizaje acumulativo y barreras de salida: cuanto más usa el cliente LTI, más valor diferencial obtiene.
Lectura estratégica

Si tuviera que resumir el brainstorming en una tesis de producto:

LTI no debería competir como otro ATS con IA, sino como la plataforma que reduce la fricción de decisión entre HR y managers, convierte el proceso de selección en un sistema operativo colaborativo y añade una capa de inteligencia auditable sobre cómo se decide y se mejora la contratación.

Ejemplo concreto
Una vacante de Engineering Manager:
- hoy: HR abre req, manager define perfil “más o menos”, se publican entrevistas, cada entrevistador da feedback desigual, el debrief tarda, nadie sabe por qué la vacante no cierra.
- con LTI:
  - alineación inicial guiada
  - criterios ponderados y ownership claro
  - seguimiento de bloqueos en tiempo real
  - feedback con evidencia
  - debrief generado automáticamente con conflictos detectados
  - recomendación de acciones si la vacante está en riesgo

Eso sí es más potente que “otro pipeline bonito”.

Regla:
Usa EXCLUSIVAMENTE las funcionalidades listadas. No inventes nuevas.


Actúa como Head of Product.

Tarea:
Prioriza estas funcionalidades para definir un MVP realmente diferencial, maximizando impacto en time-to-hire y calidad de contratación, minimizando dependencia de datos históricos

Salida:
1. Top 5 funcionalidades clave (las que realmente definen el producto)
2. Justificación de cada una:
   - Impacto en negocio
   - Impacto en usuario
   - Diferenciación competitiva
3. Qué NO construir (descartar features menos estratégicas)

Condiciones:
- Sé crítico: menos es más
- Enfócate en MVP con alto valor
```


## Prompt 7 - Definición del producto
```
# Contexto

Estás definiendo el MVP de un producto SaaS llamado **LTI** (plataforma de recruiting / ATS).

## Objetivos clave
- Reducir time-to-hire
- Mejorar calidad de contratación
- Aumentar eficiencia de HR
- Mejorar colaboración recruiter–hiring manager
- Introducir IA de forma útil y explicable

## Restricciones
- No incluir funcionalidades básicas de ATS
- No depender de datos históricos complejos
- Producto orientado a empresas medianas/grandes
- Diferenciación real frente a Greenhouse, Lever, Workday

---

# Scope del MVP (no ampliar)

Funcionalidades a definir (solo estas):

1. Centro de decisiones y bloqueos del proceso
2. Orquestador de alineación de vacante
3. Feedback guiado y comparativo en tiempo real
4. Agenda colaborativa de contratación
5. Debrief inteligente y auditable

## Tesis de producto
LTI reduce la fricción operativa entre HR y hiring managers, mejora la calidad de evaluación y acelera la decisión final con inteligencia auditable.

---

# Reglas
- Usa exclusivamente estas funcionalidades
- No añadas nuevas capacidades
- No generalices (cada afirmación debe ser concreta)
- Evita lenguaje de marketing

---

# Tarea

Define el producto LTI para un documento interno.

## Estructura obligatoria

### 1. Descripción breve del software
(3-4 líneas, qué es y qué hace)

### 2. Propuesta de valor
- Qué problema resuelve
- Para quién
- Por qué es mejor que alternativas

### 3. Ventajas competitivas
- Lista de 4–6 bullets
- Cada bullet debe ser específico y defendible

### 4. Funciones principales (ordenadas por prioridad)

Para cada función:
- Descripción
- Problema que resuelve
- Cómo aporta valor diferencial
- Uso de IA (si aplica, y cómo exactamente)

---

# Criterios de calidad (importante)
- Cada función debe poder entenderse sin contexto adicional
- Evitar duplicidades entre funcionalidades
- Priorizar claridad sobre exhaustividad
- Si algo no aporta diferenciación clara, simplifícalo

Devuélveme el documento final en markdown listo para entregar, con tono profesional y sin redundancias
```

## Prompt 9 - Lean Canvas
```
Genera un diagrama Lean Canvas alineado estrictamente con el MVP definido, sin introducir nuevas funcionalidades ni hipótesis genéricas.
```
La salida de este promp de Chatgpt la inserté en ChatDiagram

```
# Lean Canvas — LTI (MVP)

## 1. Problemas

- Procesos de selección bloqueados por falta de coordinación (feedback pendiente, decisiones retrasadas)
- Desalineación entre HR y hiring managers al definir vacantes
- Evaluaciones inconsistentes y difíciles de comparar entre entrevistadores
- Exceso de tiempo en debriefs manuales y poco estructurados
- Falta de visibilidad operativa sobre el estado real de cada proceso

---

## 2. Segmentos de clientes

### Cliente principal
- Empresas medianas y grandes con procesos de selección estructurados

### Usuarios
- Equipos de HR / Recruiting
- Hiring managers
- Entrevistadores involucrados en el proceso

---

## 3. Propuesta de valor única

Plataforma que reduce bloqueos operativos en procesos de selección, alinea a HR y managers desde el inicio y mejora la calidad de decisión mediante feedback estructurado y debrief asistido.

---

## 4. Solución (MVP)

- Centro de decisiones y bloqueos del proceso  
- Orquestador de alineación de vacante  
- Feedback guiado y comparativo en tiempo real  
- Agenda colaborativa de contratación  
- Debrief inteligente y auditable  

---

## 5. Canales

- Venta directa B2B (equipo comercial)
- Demos de producto orientadas a HR
- Pruebas piloto en procesos de selección activos
- Expansión interna (HR → managers)

---

## 6. Fuentes de ingresos

- Suscripción SaaS por empresa (modelo anual)
- Pricing basado en:
  - número de vacantes activas
  - tamaño del equipo de recruiting
  - número de usuarios (HR + managers)

---

## 7. Estructura de costes

- Desarrollo de producto (backend, frontend, IA)
- Infraestructura cloud
- Coste de modelos de IA (procesamiento de texto / síntesis)
- Equipo de ventas B2B
- Soporte e implementación inicial

---

## 8. Métricas clave

- Time-to-hire (antes vs después)
- Tiempo medio de respuesta de hiring managers
- % de procesos con bloqueos críticos
- Tiempo dedicado a debrief por vacante
- Ratio de feedback completo vs incompleto

---

## 9. Ventaja competitiva (Unfair Advantage)

- Enfoque en ejecución operativa del proceso (no solo gestión de candidatos)
- Visibilidad en tiempo real de bloqueos y responsabilidades
- Integración de IA en puntos críticos de decisión (no en todo el flujo)
- Trazabilidad completa de decisiones (auditable)
- Dependencia baja de datos históricos para generar valor desde el inicio
```

## Promto 10 - Descripción de casos de uso y diagramas
```
Contexto:
Estás definiendo el MVP de un producto SaaS llamado LTI, una plataforma de recruiting / ATS orientada a empresas medianas y grandes.

Tesis de producto:
LTI reduce la fricción operativa entre HR y hiring managers, mejora la calidad de evaluación y acelera la decisión final con inteligencia auditable.

Scope del MVP (no ampliar):
- Centro de decisiones y bloqueos del proceso
- Orquestador de alineación de vacante
- Feedback guiado y comparativo en tiempo real
- Agenda colaborativa de contratación
- Debrief inteligente y auditable

Restricciones:
- No introducir nuevas funcionalidades fuera del MVP
- No usar casos de uso genéricos como “gestionar candidatos”, “crear usuario” o similares
- Los casos de uso deben representar el valor diferencial del producto
- Los casos deben cubrir tres momentos distintos del proceso:
  1. Inicio / alineación
  2. Ejecución / seguimiento y desbloqueo
  3. Decisión final / cierre

Tarea:
Define los 3 casos de uso principales del sistema LTI.

Para cada caso de uso, proporciona exactamente esta estructura:

1. Nombre del caso de uso
2. Descripción breve
3. Actores
4. Disparador (trigger)
5. Precondiciones
6. Flujo principal (paso a paso numerado, máximo 10 pasos)
7. Flujos alternativos o excepciones relevantes
8. Resultado final
9. Funcionalidades del MVP implicadas
10. Justificación de por qué este es uno de los 3 casos de uso principales

Además, para cada caso de uso, genera un diagrama asociado con estas condiciones:
- Debe ser un diagrama UML de casos de uso
- Debe estar en formato PlantUML
- Debe incluir actores y casos de uso claramente nombrados
- Puede usar relaciones <<include>> y <<extend>> cuando tenga sentido
- No generar diagramas de secuencia, activity, flowchart ni otros tipos
- El código PlantUML debe ser sintácticamente válido

Formato de salida:
- Devuelve todo en un único fichero Markdown listo para entregar
- Usa un bloque por cada caso de uso
- En cada caso de uso incluye el diagrama en bloque de código ```plantuml
- No añadas explicaciones fuera del documento final
- Tono profesional, claro y académico
- Sin redundancias

Importante:
Cada diagrama debe representar únicamente el caso de uso descrito en su bloque, sin mezclar otros casos de uso no explicados.
```

Para la visualización de los plantUml  --> https://plantuml.com/


## Prompt 11 - Modelo de datos 

```
Contexto:
Estás definiendo el MVP de un producto SaaS llamado LTI, una plataforma de recruiting / ATS para empresas medianas y grandes.

Tesis de producto:
LTI reduce la fricción operativa entre HR y hiring managers, mejora la calidad de evaluación y acelera la decisión final con inteligencia auditable.

Scope del MVP (no ampliar):
- Centro de decisiones y bloqueos del proceso
- Orquestador de alineación de vacante
- Feedback guiado y comparativo en tiempo real
- Agenda colaborativa de contratación
- Debrief inteligente y auditable

Casos de uso principales:
1. Alinear una vacante antes de iniciar el proceso
2. Gestionar bloqueos operativos de una vacante en ejecución
3. Consolidar evaluación y cerrar decisión final de candidatura

Restricciones:
- No introducir funcionalidades fuera del MVP
- Evitar entidades genéricas sin valor de dominio (ej: “Log”, “GenericEntity”)
- No modelar detalles físicos de base de datos (índices, particionado, etc.)
- Mantener un nivel lógico/conceptual, no técnico de implementación

---

Tarea:
Define el modelo de datos lógico del sistema LTI, asegurando que cubre completamente los casos de uso descritos.

---

Estructura obligatoria de salida:

## 1. Entidades principales

Para cada entidad:
- Nombre
- Descripción breve
- Atributos:
  - nombre
  - tipo (usar tipos genéricos: UUID, string, text, boolean, date, datetime, integer, enum)
  - obligatorio (sí/no)
  - descripción

Condiciones:
- Solo incluir atributos relevantes para el dominio
- Evitar redundancias entre entidades
- Si un atributo es un estado, modelarlo como enum

---

## 2. Relaciones entre entidades

Para cada relación:
- Entidad origen
- Entidad destino
- Cardinalidad (1:1, 1:N, N:M)
- Descripción funcional de la relación

Condiciones:
- Si existe una relación N:M con significado en el dominio, modelarla como entidad intermedia
- Explicar relaciones desde el punto de vista del negocio, no técnico

---

## 3. Decisiones de modelado

Explica de forma breve:

- Por qué existen las entidades clave (no todas, solo las importantes)
- Cómo el modelo soporta:
  - alineación de vacante
  - gestión de bloqueos
  - feedback estructurado
  - debrief auditable

Condiciones:
- Evitar explicaciones genéricas
- Conectar decisiones con casos de uso reales

---

## 4. Diagrama ER del modelo

- Generar un diagrama en Mermaid (ERD) o PlantUML
- Debe incluir:
  - entidades principales
  - relaciones con cardinalidad
- El código debe ser válido y renderizable
- No incluir detalles irrelevantes (claves técnicas, índices, etc.)

---

Criterios de calidad:

- El modelo debe reflejar claramente el dominio de recruiting definido en el MVP
- Debe ser coherente con los casos de uso (no sobredimensionado)
- Debe ser entendible por perfiles de producto y técnicos
- Nombres de entidades y atributos claros y consistentes
- Evitar modelar “futuro”, centrarse en el MVP

---

Formato de salida:

- Un único documento en Markdown listo para entregar
- Secciones bien separadas
- Diagrama incluido en bloque de código
- Sin explicaciones fuera del documento
- Tono profesional, claro y sin redundancias

Limita el modelo a un máximo de 12–15 entidades principales
```

## Prompt 12 - Diseño del sistema a alto nivel
```
Contexto:
Estás definiendo el MVP de un producto SaaS llamado LTI, una plataforma de recruiting / ATS orientada a empresas medianas y grandes.

Tesis de producto:
LTI reduce la fricción operativa entre HR y hiring managers, mejora la calidad de evaluación y acelera la decisión final con inteligencia auditable.

Scope del MVP (no ampliar):
- Centro de decisiones y bloqueos del proceso
- Orquestador de alineación de vacante
- Feedback guiado y comparativo en tiempo real
- Agenda colaborativa de contratación
- Debrief inteligente y auditable

Casos de uso principales:
1. Alinear una vacante antes de iniciar el proceso
2. Gestionar bloqueos operativos de una vacante en ejecución
3. Consolidar evaluación y cerrar decisión final de candidatura

Modelo de datos lógico (entidades principales):
- Organization
- User
- Vacancy
- VacancyAlignment
- EvaluationCriterion
- Candidate
- Application
- Interview
- Feedback
- FeedbackCriterionAssessment
- ProcessBlocker
- ActionItem
- Debrief

Restricciones:
- No introducir funcionalidades nuevas fuera del MVP
- No diseñar a nivel de infraestructura específica (no AWS, no Kubernetes, etc.)
- No devolver una arquitectura genérica tipo “frontend + backend + database”
- El diseño debe reflejar claramente el dominio del producto
- Mantener nivel alto (arquitectura), no bajo (clases, endpoints, etc.)

---

Tarea:
Define la arquitectura de alto nivel del sistema LTI para su MVP.

---

Estructura obligatoria de salida:

## 1. Visión general de la arquitectura
- Describe el enfoque arquitectónico (ej: modular monolith, servicios desacoplados, etc.)
- Explica los bloques principales del sistema
- Justifica por qué esta arquitectura es adecuada para el MVP

---

## 2. Componentes principales del sistema

Para cada componente, incluye:
- Nombre (orientado a dominio, no técnico genérico)
- Responsabilidad principal
- Casos de uso que soporta
- Entidades del modelo que gestiona principalmente
- Interacciones con otros componentes

Condiciones:
- Entre 5 y 8 componentes máximo
- Evitar nombres genéricos como “CoreService” o “Manager”
- Cada componente debe tener sentido funcional claro

---

## 3. Flujos de interacción de alto nivel

Describe cómo colaboran los componentes para soportar:

### 3.1 Alineación de vacante  
### 3.2 Gestión de bloqueos  
### 3.3 Debrief y decisión final  

Condiciones:
- Explicar flujo de información y responsabilidades
- No usar detalles de implementación (HTTP, colas, etc.)
- No repetir el flujo de los casos de uso, sino enfocarlo a arquitectura

---

## 4. Decisiones de diseño

Explica brevemente:

- Por qué se han separado los componentes como están
- Dónde reside la lógica de negocio principal
- Cómo se gestiona la consistencia del proceso (fuente de verdad)
- Cómo se integra la lógica de IA (debrief) sin acoplarla al core
- Qué trade-offs se han asumido (simplicidad vs escalabilidad, etc.)

---

## 5. Diagrama de arquitectura de alto nivel

Genera un diagrama con estas condiciones:

- Formato: Mermaid o PlantUML
- Debe incluir:
  - Actores principales (Recruiter, Hiring Manager, etc.)
  - Componentes del sistema
  - Relaciones entre componentes
- Debe representar:
  - responsabilidades
  - flujo general de interacción
- No usar notación C4 todavía (eso será en el siguiente paso)
- El código debe ser válido y renderizable

---

Criterios de calidad:

- La arquitectura debe estar alineada con el MVP (no futura)
- Debe reflejar claramente el valor diferencial del producto
- Debe ser comprensible tanto para perfiles técnicos como de producto
- Evitar sobreingeniería
- Evitar ambigüedad en responsabilidades de componentes

---

Formato de salida:

- Un único documento en Markdown listo para entregar
- Secciones bien estructuradas
- Diagrama incluido en bloque de código
- Sin explicaciones fuera del documento final
- Tono profesional, claro y sin redundancias

Limita cada flujo de interacción a máximo 8–10 líneas
```

## Prompt 13 - Diagrama en C4 de uno de los componentes
```
Contexto:
Estás definiendo el MVP de un producto SaaS llamado LTI, una plataforma de recruiting / ATS orientada a empresas medianas y grandes.

Tesis de producto:
LTI reduce la fricción operativa entre HR y hiring managers, mejora la calidad de evaluación y acelera la decisión final con inteligencia auditable.

Scope del MVP (no ampliar):
- Centro de decisiones y bloqueos del proceso
- Orquestador de alineación de vacante
- Feedback guiado y comparativo en tiempo real
- Agenda colaborativa de contratación
- Debrief inteligente y auditable

Casos de uso principales:
1. Alinear una vacante antes de iniciar el proceso
2. Gestionar bloqueos operativos de una vacante en ejecución
3. Consolidar evaluación y cerrar decisión final de candidatura

Modelo de datos lógico (entidades principales):
- Organization
- User
- Vacancy
- VacancyAlignment
- EvaluationCriterion
- Candidate
- Application
- Interview
- Feedback
- FeedbackCriterionAssessment
- ProcessBlocker
- ActionItem
- Debrief

Arquitectura de alto nivel ya definida:
- Aplicación Web LTI
- Gestión de Vacantes y Alineación
- Orquestación del Proceso
- Evaluación y Feedback
- Gestión de Debrief y Decisión
- Inteligencia Asistiva
- Almacenamiento del Dominio

Componente elegido para profundizar:
- Orquestación del Proceso

Restricciones:
- No introducir funcionalidades nuevas fuera del MVP
- No inventar integraciones externas
- Mantener coherencia con la arquitectura de alto nivel ya definida
- El nivel 4 debe seguir siendo lógico/arquitectónico, sin bajar a código real ni detalles de framework
- El resultado debe ser útil para una entrega académica/técnica

Tarea:
Construye una vista C4 completa del sistema LTI, llegando hasta el nivel 4 sobre el componente Orquestación del Proceso.

Estructura obligatoria de salida:

1. Justificación breve de la elección del componente

2. Nivel C1 — Contexto del sistema
- actores principales
- relación con LTI

3. Nivel C2 — Contenedores
Para cada contenedor:
- nombre
- responsabilidad
- interacción principal

4. Nivel C3 — Componentes del contenedor/módulo “Orquestación del Proceso”
Para cada componente:
- nombre
- responsabilidad
- entidades principales
- colaboración con otros componentes o módulos

5. Nivel C4 — Descomposición interna lógica del componente más relevante dentro de “Orquestación del Proceso”
Elige el subcomponente más importante y descompónlo en elementos internos de diseño lógico.
Para cada elemento interno:
- nombre
- responsabilidad
- relación con otros elementos

Condiciones para el nivel 4:
- Debe ser coherente con el dominio
- Puede modelar agregados, políticas, repositorios, validadores o coordinadores
- No incluir métodos, clases técnicas de framework ni detalles de implementación

6. Decisiones de diseño
- por qué esta descomposición tiene sentido
- qué responsabilidades se mantienen dentro de Orquestación del Proceso
- cómo se preserva consistencia del estado

7. Diagramas en PlantUML
Genera:
- C1 Context Diagram
- C2 Container Diagram
- C3 Component Diagram de Orquestación del Proceso
- C4 Diagram del subcomponente interno elegido

Condiciones:
- usar PlantUML
- diagramas válidos y consistentes entre sí
- listos para entregar
- tono profesional y claro

Formato de salida:
- un único documento en Markdown
- cada diagrama en bloque ```plantuml
- sin explicaciones fuera del documento final

Limita la explicación textual a lo necesario para acompañar los diagramas. Prioriza precisión sobre exhaustividad.
```