2. ### Ingeniería de Requisitos (IR)
Es la disciplina para generar una especificación completa, consistente y no ambigua. La cuál servirá como base para acuerdos comunes entre todas las partes involucradas.

De esta forma la IR proporciona el mecanismo apropiado para:

- Entender lo que el cliente quiere.
- Analizar las necesidades.
- Evaluar la factibilidad.
- Negociar una solución razonable.
- Especificar la solución sin ambigüedades.
- Validar la especificación.
- Administrar los requisitos conforme éstos se transforman en un sistema operacional.

Etapas de la Ingeniería de Requisitos: Elicitación, Análisis, Especificación y Validación

#### Elicitación
Actividad involucrada en el descubrimiento de los requisitos del sistema.
Analistas y Clientes trabajan de la mano para identificar los problemas que el sistema debe resolver.

#### Análisis
Descubrir problemas identificados con los requisitos del sistema identificados.
- Detectar ambigüedades o contradicciones en los requisitos.
- Profundizar en el conocimiento del dominio del problema.
- Refinamiento del entendimiento del problema. (Retroalimentación).

#### Especificación
- Se documentan los requisitos acordados con el cliente aplicando técnicas de notación.
- Pasar en limpio el análisis realizado previamente.

#### Validación
- Evaluación de los requisitos respecto a las necesidades de clientes y usuarios.
- Pueden aparecer requisitos nuevos, producto del ejercicio con el cliente.


### 2.1 Ciclo de vida del software (SDLC)
SDLC => System Development Lifer Cycle.

Es el proceso que se sigue para construir y evolucionar un software a través de una serie de fases.

**Fases:** Es un conjunto de actividades relacionadas con un objetivo en el desarrollo del proyecto.
**Entregables:** Es el producto material o inmaterial que genera una fase, que permite evaluar y comprobar el progreso y la asertividad del proceso.


#### Fases del Ciclo de Software
son: planificación, análisis, diseño, implementación, pruebas y mantenimiento.

**Planificación:** Planteamiento del problema, se definen alcances y objetivos.
**Análisis:** Se definen requisitos alcanzables del desarrollo de software.
**Diseño:** Se estudian posibles opciones de implementación.
**Implementación:** Es un conjunto de actividades relacionadas con un objetivo en el desarrollo del proyecto.
**Pruebas:** Detectar fallos en las fases anteriores.
**Mantenimiento:** Asegura la coherencia entre el uso del proyecto y los requerimientos.

Existen 3 tipos de mantenimiento:
- Mantenimiento correctivo.
- Mantenimiento adaptativo.
- Mantenimiento perfectivo.

#### Paradigmas de los modelos de ciclo de vida del software
Es una vista de las actividades que ocurren durante el desarrollo de software e intenta determinar:
1. El orden de las fases.
2. Los criterios de transición adecuadas.

#### Paradigma Tradicional
Se identifican fundamentalmente por ser lineales, tratando de completar cada proceso de inicio a fin hasta avanzar a la siguiente fase del ciclo del software.

Modelos más comunes del paradigma tradicional son:
- **Modelo en cascada:** W. Royce en 1970, una actividad debe terminanr antes de comenzar la siguiente.
- **Modelo espiral:** Boehm en 1988, es una serie de ciclos repetitivos hasta satisfacer los requerimientos.
- **Modelo iterativo/por prototipos:**  Mc.Cracken y Jackson 1982. es un procedimiento que permite al equipo diseñar y analizar una aplicación que represente el sistema que será implementado. (Prototipado)

#### Paradigma Desarrollo orientado a objetos
Se confomra principalmente por la creación de clases, análisis de requisitos y diseño.
Pretende que el código fuente sea reutilizable.

#### Paradigma Desarrollo Agil
El objetivo de este paradigma es el desarrollo de proyectos en poco tiempo.
Para ello el cliente está involucrado en el proceso de retroalimentación

##### Modelo Scrum
Metodología Japonesa que se fundamenta en el desarrollo incremental, en cada iteración, se hace más robusto el producto.

Los procesos que utiliza son:
1. Product Backlog.
2. Sprint Backlog.
3. Sprint Planning Meeting.
4. Daily Scrum.
5. Sprint Review
6. Sprint Retrospective

**Ventajas**
- Gestión Regular de las expectativas del usuario dada su participación en el proceso.
- Resultados anticipados.
- Flexibilidad. (Usuarios antes que sistemas - Manifiesto agil).
- Gestión sistemática de Riesgos: Los riesgos se atienden con prioridad tan pronto son descubiertos.

##### Modelo Kanban
David J. Anderson, lider de pensamiento de la adopción del Lean/Kanban.
Formuló el método Kanban, como una aproximación al proceso evolutivo e incremental, es uno de los modelos más visuales.
Es básicamente, un tablero con etiquetas, describiendo cada una de las fases del proyecto.


##### Modelo XP/Programación Extrema
Kent Beck, Esta metodología es adaptable según las necesidades y requerimientos a implementar.

### 2.2 Fase de definición de Requisitos
Esta es la primera fase del ciclo del software, también llamada fase de análisis, se recopila, se examina y se formulan los requisitos del cliente.

- La inestabilidad de los requerimientos es inevitable.

### 2.3 Requisitos
Un requisito es una condición o capacidad que necesita un usuario para resolver un problema.
Los requisitos comunican las expectativas de los consumidores de productos de software.
Establecen el alcance del trabajo subsecuente.

**Características**
- Necesario: ¿Qué sería lo peor de no incluirlo?
- Completo: Si no requiere más ampliación en su redacción.
- Consistente: Si no es contradictorio con otro requisito.
- Correcto: acuerdo entre 2 partes. engloba una sola idea.
- Factible: posible y encaja dentro del presupuesto.
- Modificable: Los cambios en los requisitos deben hacerse de manera sistemática, evaluando su impacto en otros requisitos.
- Priorizado: Categorizar el requisito para conocer su grado de necesidad: esencial, deseado, opcional, verificable.
- Verificable: Debe poderse comprobar sea por inspección, análisis de prueba o demostración.
- Rastreable: Cada función del sistema debe poderse rastrear hasta sus requerimientos.
- Claro: Fácil de leer y entender.

**Clasificación**

Según el nivel de descripción:

- Requerimientos del Usuario: Son declaraciones en lenguaje natural y en diagramas, de los servicios que se espera que el sistema proporcione y de sus restricciones.
- Requerimientos del Sistema: Detallan las funcionas y restricciones operativas del sistema.

Según su descripción:
- Requerimientos funcionales: Son declaraciones de los servicios que debe o no debe proporcionar el sistema.
- Requerimientos no funcionales: Son restricciones de los servicios o funciones, por ejemplo en relación al tiempo de respuesta, o a la capacidad de almacenamiento.


### 3. Fuentes de Requisitos
#### 3.1 Identificar las fuentes de Requisitos.
Es todo aquello que abastece de información, acerca del problema y las necesidades del usuario.

**Clasificación**
- Fuentes primarias: Protagonistas de los hechos, aportan información original y que no ha sido filtrada o interpretada.
- Fuentes secundarias: Toman, organizan y reproducen la fuente primaria, partiendo de datos preelaborados.
- Fuentes terciarias: Son guías físicas o virtuales que contienen información de fuentes secundarias.
- Orales
- Escritas


#### 3.2 Identificar interesados del producto
Identificar todas las personas involucradas activamente en el desarrollo de un producto (stakeholders), tienen influencia directa o indirecta o se ven impactados por su desarrollo.


#### 3.4 Roles involucrados
- Clientes: Representa a la persona u organización que solicita la creación de un sistema. Es con quien se negocia el tiempo, costo y alcance de un proyecto. Puede ser o no un usuario de sistema
- Usuario: Son quienes interactúan con el sistema.
- Líder de proyecto: Es el representante ante el cliente.
- Analista: Su función se concentra en la ingeniería de requisitos. los identifica, analiza, modela y doocumenta.
- Programador: Realiza la codificación cumpliento en los requisitos proporcionados.
- Asegurador de calidad: Garantiza el cumplimiento del proceso y de los estándares del producto.
- Arquitecto: Es el responsable del diseño de alto nivel

#### 3.5 Técnicas de Análisis
- Entrevistas con expertos.
- Focus Groups.
- Lista de chequeo.

### Requeimientos funcionales y no funcionales
Funcionales - Todos los requerimientos que interactúan con el usuario.
No Funcionales - Todo lo que necesita para servir apropiadamente.