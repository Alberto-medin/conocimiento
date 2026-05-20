# Ingeniería del Conocimiento (TIC-1015)
## Investigación Individual

### Título de la investigación
**Modelo organizacional CommonKADS: estructura y utilidad**

---

### Estudiante
**Nombre completo:**  
Jimenez Salazar Alan Antonio

### Docente
Rene Solis Reyes 
### Asignatura
Ingeniería del Conocimiento (TIC-1015)

### Institución
Tecnológico Nacional de México

---

## 1. Introducción
El desarrollo de sistemas basados en conocimiento requiere metodologías formales que permitan analizar, modelar y representar de manera estructurada el conocimiento organizacional. En este contexto surge CommonKADS , una metodología ampliamente reconocida dentro de la Ingeniería del Conocimiento , cuyo propósito es apoyar el análisis y diseño de sistemas de conocimiento considerando tanto los aspectos técnicos como organizacionales. Constituye uno de los pilares fundamentales de esta metodología, ya que permite comprender el entorno en el que opera una organización, sus objetivos, procesos, actores y problemas, antes de proponer soluciones basadas en sistemas inteligentes. Su importancia radica en que asegura que los sistemas desarrollados estén alineados con las necesidades reales de la organización y no solo con requerimientos técnicos.

---

## 2. Objetivo
### Objetivo general
Analizar el modelo organizacional de la metodología CommonKADS, describiendo su estructura, componentes y utilidad, con el fin de comprender su aplicación en el análisis organizacional y el desarrollo de sistemas basados en conocimiento.

---

## 3. Marco teórico
### 3.1 Ingeniería del Conocimiento

La Ingeniería del Conocimiento es una disciplina que se enfoca en la adquisición, modelado, representación y mantenimiento del conocimiento para el desarrollo de sistemas inteligentes, tales como sistemas expertos, sistemas de apoyo a la decisión y aplicaciones basadas en inteligencia artificial.

### 3.2 Metodología CommonKADS

CommonKADS (Common Knowledge Acquisition and Design System) es una metodología estructurada para el desarrollo de sistemas basados en conocimiento. Proporciona modelos conceptuales que facilitan el análisis del conocimiento desde diferentes perspectivas: organizacional, de tareas, de agentes y de implementación.

### 3.3 Modelo organizacional

El modelo organizacional en CommonKADS se enfoca en analizar la organización como un todo, identificando su contexto, objetivos, procesos clave, actores involucrados y problemas existentes. Este modelo sirve como base para determinar la viabilidad y relevancia de un sistema basado en conocimiento.

### 3.4 Componentes del modelo organizacional

El modelo organizacional se compone principalmente de:

-   **Modelo de contexto (OM-1)**: describe el entorno organizacional y sus objetivos.
  <!--  Ejemplo y texto agregado para OM-1 -->
    *Ejemplo operativo:* Define el alcance global de la organización. Si se analiza un hospital, este modelo delimita las regulaciones de salud externas, las políticas internas y la misión de mejorar la atención al paciente. --!>
    
-   **Modelo de procesos (OM-2)**: identifica y analiza los procesos principales del negocio.
  <!--  Ejemplo y texto agregado para OM-2 -->
    *Ejemplo operativo:* Mapea la cadena de valor. En una empresa manufacturera, desglosa el flujo desde la llegada de la materia prima, pasando por el ensamblaje, hasta la distribución final, localizando dónde se genera valor.--!>
    
-   **Modelo de tareas (OM-3)**: detalla las tareas que se realizan dentro de los procesos.
<!--  Ejemplo y texto agregado para OM-3 -->
    *Ejemplo operativo:* Analiza los cuellos de botella cognitivos. No se limita a listar acciones, sino que evalúa la complejidad de una tarea específica, como la "evaluación de riesgos de crédito" en un banco, determinando si requiere experiencia avanzada.--!>
    
-   **Modelo de agentes (OM-4)**: identifica a los actores humanos y sistemas involucrados.
<!--  Ejemplo y texto agregado para OM-4 -->
    *Ejemplo operativo:* Determina la ejecución y competencia. Establece quién realiza cada tarea (por ejemplo, un operador senior o un software CRM heredado) y evalúa si las habilidades del agente son suficientes o si el conocimiento está centralizado en una sola persona.--!>
    
-   **Modelo de problemas y oportunidades (OM-5)**: detecta áreas de mejora donde el conocimiento puede aportar valor.
  <!--  Ejemplo y texto agregado para OM-5 -->
    *Ejemplo operativo:* Justifica la solución tecnológica. Identifica pérdidas financieras por malas decisiones operativas o fugas de conocimiento por jubilación de personal, proponiendo formalmente cómo un Sistema Basado en Conocimiento solventará dicha vulnerabilidad.--!>
---

## 4. Desarrollo

### 4.1 Estructura del modelo organizacional CommonKADS

El modelo organizacional de CommonKADS se estructura mediante un conjunto de plantillas que permiten recopilar información de manera sistemática. Estas plantillas facilitan el análisis de la organización desde un enfoque estratégico y operativo.

El **OM-1** establece los objetivos estratégicos de la organización y su contexto interno y externo. El **OM-2** analiza los procesos del negocio, permitiendo identificar cuellos de botella o procesos críticos. El **OM-3** descompone dichos procesos en tareas específicas, mientras que el **OM-4** asigna estas tareas a agentes responsables. Finalmente, el **OM-5** integra el análisis para detectar problemas, riesgos y oportunidades de mejora.

``` mermaid

graph TD
    A["🏢 CommonKADS\nModelo Organizacional"] --> B["OM-1\nModelo de Contexto"]
    A --> C["OM-2\nModelo de Procesos"]
    A --> D["OM-3\nModelo de Tareas"]
    A --> E["OM-4\nModelo de Agentes"]
    A --> F["OM-5\nProblemas y Oportunidades"]

    B --> B1["Objetivos estratégicos\nde la organización"]
    B --> B2["Contexto interno\ny externo"]

    C --> C1["Procesos clave\ndel negocio"]
    C --> C2["Identificación de\ncuellos de botella"]

    D --> D1["Descomposición de\nprocesos en tareas"]
    D --> D2["Tareas intensivas\nen conocimiento"]

    E --> E1["Actores humanos\ninvolucrados"]
    E --> E2["Sistemas y\nherramientas"]

    F --> F1["Detección de\nproblemas y riesgos"]
    F --> F2["Oportunidades de\nautomatización"]

    F --> G["💡 Sistema Basado\nen Conocimiento"]

    style A fill:#2E75B6,color:#fff,font-weight:bold
    style G fill:#70AD47,color:#fff,font-weight:bold
    style B fill:#4472C4,color:#fff
    style C fill:#4472C4,color:#fff
    style D fill:#4472C4,color:#fff
    style E fill:#4472C4,color:#fff
    style F fill:#4472C4,color:#fff

```

``` mermaid

flowchart LR
    OM1["📋 OM-1\nContexto\nOrganizacional"] --> OM2["⚙️ OM-2\nProcesos\ndel Negocio"]
    OM2 --> OM3["📌 OM-3\nTareas\nEspecíficas"]
    OM3 --> OM4["👥 OM-4\nAgentes\nResponsables"]
    OM4 --> OM5["🔍 OM-5\nProblemas y\nOportunidades"]
    OM5 --> SKS["🤖 Sistema Basado\nen Conocimiento"]

    style OM1 fill:#1F4E79,color:#fff
    style OM2 fill:#2E75B6,color:#fff
    style OM3 fill:#2980B9,color:#fff
    style OM4 fill:#5BA3D0,color:#fff
    style OM5 fill:#7CB9E8,color:#000
    style SKS fill:#1E8449,color:#fff,font-weight:bold

```

### 4.2 Utilidad del modelo organizacional

La principal utilidad del modelo organizacional es asegurar que los sistemas basados en conocimiento respondan a necesidades reales. Permite:

-   Alinear la tecnología con los objetivos organizacionales.
    
-   Identificar tareas intensivas en conocimiento.
    
-   Evaluar la viabilidad de soluciones basadas en conocimiento.
    
-   Reducir riesgos en el desarrollo de sistemas inteligentes.
  Para comprender a fondo cómo interactúan estos componentes, es fundamental mapear de manera detallada los artefactos resultantes y las preguntas clave que cada plantilla busca resolver dentro de la metodología CommonKADS.

| Plantilla / Componente | Enfoque Principal | Artefactos / Entregables | Pregunta Clave de Análisis |
| :--- | :--- | :--- | :--- |
| **OM-1: Contexto** | Estrategia de la empresa y entorno global. | Diagrama del entorno de negocio, lista de factores críticos de éxito. | ¿Cuál es la misión de la organización y qué factores externos impactan su operación? |
| **OM-2: Procesos** | Cadena de valor y flujo de actividades. | Mapa de procesos, diagramas de flujo de trabajo (Workflow). | ¿Cómo fluyen el valor y la información a través de los departamentos clave? |
| **OM-3: Tareas** | Descomposición operativa de procesos. | Catálogo de tareas, matriz de criticidad de conocimiento. | ¿Qué acciones específicas requieren experiencia humana avanzada o cuellos de botella cognitivos? |
| **OM-4: Agentes** | Actores humanos y sistemas de software. | Perfiles de competencias, inventario de sistemas de información. | ¿Quién (o qué sistema de cómputo) ejecuta cada tarea y qué conocimiento posee? |
| **OM-5: Problemas y Oportunidades**| Diagnóstico, viabilidad y justificación técnica. | Matriz de riesgos, propuesta formal de proyecto de Sistema Basado en Conocimiento (SBC). | ¿Dónde falla la transferencia de conocimiento y cómo puede la IA/SBC solucionar el problema? |

Adicionalmente, el modelo sirve como un puente de comunicación interdisciplinario. Frecuentemente, los ingenieros de software carecen de una comprensión profunda de los procesos de negocio complejos, mientras que los expertos del dominio (los administradores o especialistas) desconocen el alcance de la Inteligencia Artificial. Al configurar la empresa bajo estas cinco plantillas, se establece un lenguaje común que previene la construcción de herramientas técnicamente impecables pero operativamente inútiles.
    

### 4.3 Ejemplo aplicado

En una empresa de logística, el modelo organizacional puede utilizarse para analizar el proceso de planificación de rutas. A través del OM-2 se identifican los procesos clave, el OM-3 detalla las tareas de asignación de rutas, el OM-4 identifica a los planificadores y sistemas involucrados, y el OM-5 detecta problemas como decisiones basadas en experiencia individual. Esto justifica el desarrollo de un sistema experto para optimizar rutas.

---

## 5. Análisis y discusión
El modelo organizacional CommonKADS ofrece una visión integral de la organización, lo cual constituye una ventaja significativa frente a enfoques puramente técnicos. Su estructura formal facilita la comunicación entre ingenieros del conocimiento y expertos del dominio.
Entre sus ventajas se encuentran la reducción de ambigüedad en los requerimientos y la identificación temprana de oportunidades de automatización. Sin embargo, una de sus limitaciones es el tiempo y esfuerzo requerido para recopilar información organizacional detallada, así como la necesidad de colaboración activa por parte de los actores involucrados.
En aplicaciones reales, este modelo ha demostrado un impacto positivo en la toma de decisiones, especialmente en sistemas de apoyo a la decisión y sistemas expertos, al garantizar que el conocimiento capturado sea relevante y contextualizado.

---

## 6. Conclusiones
El modelo organizacional de CommonKADS es una herramienta fundamental dentro de la Ingeniería del Conocimiento, ya que permite comprender de manera estructurada el contexto en el que se aplicará un sistema basado en conocimiento. Su enfoque integral facilita la alineación entre objetivos organizacionales y soluciones tecnológicas, incrementando la probabilidad de éxito de los proyectos.
A pesar de requerir un análisis detallado y tiempo considerable, los beneficios obtenidos en términos de claridad, reducción de riesgos y calidad del sistema final justifican su aplicación en entornos organizacionales complejos.

---

## 7. Aporte al repositorio

Esta investigación aporta una explicación estructurada y clara del modelo organizacional CommonKADS, que puede ser utilizada como material de consulta para estudiantes de Ingeniería en Sistemas, Informática o áreas afines. Además, puede servir como base para trabajos futuros relacionados con metodologías de Ingeniería del Conocimiento y desarrollo de sistemas inteligentes.

---

## 8. Referencias
-   Schreiber, G., Akkermans, H., Anjewierden, A., de Hoog, R., Shadbolt, N., Van de Velde, W., & Wielinga, B. (2000). _Knowledge Engineering and Management: The CommonKADS Methodology_. MIT Press.
    
-   Studer, R., Benjamins, V. R., & Fensel, D. (1998). Knowledge engineering: Principles and methods. _Data & Knowledge Engineering_, 25(1–2), 161–197.
    
-   Documentación académica sobre CommonKADS y metodologías de Ingeniería del Conocimiento.
-   Gómez-Pérez, A., Fernández-López, M., & Corcho, O. (2004). _Ontological engineering_. Springer.
    
-   Studer, R., Benjamins, V. R., & Fensel, D. (2003). Ingeniería del conocimiento: Principios y métodos. _Revista Iberoamericana de Inteligencia Artificial_, 7(19), 5–16.
    
-   Universidad Politécnica de Madrid. (s. f.). _Introducción a CommonKADS y modelos de conocimiento_. Material docente del Departamento de Inteligencia Artificial.
---

## 9. Declaración de originalidad
Declaro que esta investigación es de autoría propia y que las fuentes utilizadas han sido debidamente citadas.

**Firma:**  
Jimenez Salazar Alan Antonio

**Fecha:**  
09/2/2026
