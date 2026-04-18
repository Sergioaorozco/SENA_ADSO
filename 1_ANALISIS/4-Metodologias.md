## Metodologías
Proponen un conjunto de procesos y actividades que deben ser ejecutadas por el equipo de desarrollo de software.
Para -> Que el trabajo sea organizado y sea fácil de hacerle seguimiento con el propósito de hacer planes de mejora
Para -> Una mejor calidad en los productos y servicios que se desarrollan.

**Qués es una metodología?** Maida y Pacienzia(2015)
Hace referencia a un conjunto de procedimientos genéricos y lógicos que se usan para alcanzar un objetivo particular, utilizando una serie de conocimientos y habilidades.

**Metodologías Ágiles**
Nacen cuando son proyectos complejos, y no es posible definir completamente los requrimientos y sus estimaciones en la fase inicial; o cuando se requiere adaptabilidad a lo largo del desarollo de software.

Prioridad a los productos > Documentación Exhaustiva
Cliente en todo el proceso de desarrollo.

_4 Principios del manifiesto ágil:_
1. Individuos e interacciones > Procesos y herramientas.
2. Software Funcional > Documentación Exhaustiva.
3. Colaboración Cliente > Negociación Contractual.
4. Respuesta al Cambio > Ceñirse a un Plan

### XP (Xtreme Programming)
Su foco es entregar software de calidad en entornos muy volubles. se emplea en contextos que presentan riesgos de plazos fijos,
implementación de tecnologías emergentes, y equipos de trabajo reducidos.

_Valores:_
- Transferencia del conocimiento.
- Discusiones cara a cara con herramientas visuales.
- Solo lo estrictamente necesario.
- Retroalimentación.
- Enfrentarse a situaciones desafiantes.
- Respetuo mutuo = Comunicación efectiva.

_Roles:_


### RAD (Rapid Applications Development)
Su foco son las aplicaciones (funcionales), iteraciones frecuentes y retroalimentación constante.

_Beneficios:_

- Se fomenta la reutilización de código.
- Reducción de tiempo de desarrollo = Ritmo de entrega acelerado.
- Mayor flexibilidad a cualquier ajuste.
- Mejor gestión del riesgo

_Roles:_
- Facilitador
- Escriba
- Equipo SWAT
- Administrador del modelo
- Administrador de bases de datos
- Equipo de planificación del taller
- Equipo de diseño de usuario
- Equipo de soporte de construcción
- Equipo de transición

### Scrum
Es un marco de trabajo de muy amplio uso en la industria del software.
Se fundamenta en los principios y valores del manifiesto ágil publicado en 2001.

_3 Pilares Fundamentales:_

- Transparencia: Cualquier proceso puede ser conocido por cualquiera. (Reuniones de revisión, Pila de producto, Instrumentos de seguimiento).
- Inspección: Cualquiera puede estar enterado de las actividades del otro.
- Adaptación: Fijar actividades de mejora que puedan cambiar cualquier tipo de proceso en pro de la calidad.

_Roles:_
- Product Owner (Dueño del producto) Determina cuando aprobar o no una entrega. representa al cliente y tiene amplio conocimiento de sus necesidades.
- Equipo (Desarrollo) Responsables de transformar los requerimientos en código ejecutable por el Cliente. (Autorganizado, y Autogestionado, Planea las iteraciones).
- Scrum Master: Facilita los procesos al interior del equipo removiendo cualquier impedimento. 

_Ceremonias:_
- Sprint: iteración acotada entre 2 a 4 semanas donde se realiza un ciclo completo.
- Planeación del Sprint: Reunión realizada antes del inicio del sprint.se define el sprint backlog.
- Daily Meeting: Reunión corta al inicio de cada día donde el equipo informa acerca del progreso de las tareas asignadas.
- Revisión del Sprint: Reunión donde el equipo muestra los resultados del sprint.
- Reunión de Retrospectiva: Reunión de autoevaluación del desempeño del sprint con el propósito de documentar y mejorar.

_Artefactos:_
- Product Backlog: Lista priorizada de requerimientos representadas en historias de usuario.
- Sprint Backlog: Lista de requerimientos seleccionados desde el product backlog para ser desarrollados dentro de un sprint particular.
- Burndown Chart: Gráfico visual de dos ejes que muestra a los equipos la cantidad de trabajo pendiente de realizar (Eje Y) VS el tiempo disponible para hacerlo.

### Crystal
Es considerada una familia de metodologías, debido a que se subdivide en varios tipos según su función de la cantidad de personas involucradas en el proyecto.
Fue creada por el antropólogo _Alistar Cockburn_, al analizar diferentes experiencias en el desarrollo de proyectos de software.

Crystal Clear es la encarnación más ágil de la serie. la misma se define con mucho énfasis en la comunicación y liviana en los entregables.
- Dispone de feedback constante del usuario/cliente.
- Propone un usuario real al menos part time probando la aplicación
- Dispone de un gráfico que califica la complejidad y criticidad de la metodología con un código de color.
- Clear es para equipos de 8 personas o menos.
- Amarillo entre 10 y 20 personas por equipo; Naranja 30 - 50 personas por equipo ; Rojo > 50 personas por equipo.
- La frecuencia de entrega puede variar puede ser (diara, semanal o mensual).
- Comunicación Osmótica: Todos en el mismo cuarto.

### LEAN DEVELOPMENT (LD) Y LEAN SOFTWARE DEVELOPMENT (LSD) 
Es una adaptación a los entornos de desarrollo de software del método de producción que desarolló _Toyotá_.
Se fundamenta principalmente en la integración de un equipo fuerte, motivado y altamente calificado para llevar a cabo cualquier tarea en poco tiempo.
Se considera que cuanto más hayan aprendido los miembros de un equipo y más unidos se sientan, será menor el costo (tiempo - dinero) de desarrollo.

_Principios Lean:_
- Eliminar el desperdicio.
- Ampliar el aprendizaje.
- Decidir lo más tarde posible.
- Reaccionar tan rápido como sea posible.
- Potenciar al equipo.
- Crear la integridad.
- Véase todo el conjunto


### SAFe

Sí, SAFe (Scaled Agile Framework) se considera a menudo un enfoque híbrido porque combina principios Ágiles (Scrum, Kanban, XP) con estructuras de gobernanza, planificación a largo plazo y gestión de carteras tradicionales,

_Roles:_
- Nivel Equipo (Agile Team):
  - Scrum Master / Team Coach: Facilita el equipo, elimina impedimentos y fomenta la agilidad.
  - Product Owner (PO): Representa al cliente, gestiona y prioriza el backlog del equipo.
  - Miembros del Equipo: Desarrollan, prueban y entregan el valor (desarrolladores, testers).
- Nivel Programa (Agile Release Train - ART):
  - Release Train Engineer (RTE): Actúa como un "Scrum Master de trenes", facilitando el ART y la planificación PI.
  - Product Manager (PM): Define y prioriza las funcionalidades (features) del programa.
  - Arquitecto de Sistema/Ingeniero: Define la arquitectura técnica y visión del sistema.
  - Business Owners: Partes interesadas clave responsables del retorno de inversión (ROI).
- Nivel Solución (Solution Train):
  - Solution Train Engineer (STE): Facilita el trabajo de múltiples trenes.
  - Solution Manager: Gestiona el backlog de la solución y las capacidades.
  - Solution Architect/Engineer: Define la arquitectura técnica de la solución.


### Foro

Esta combinación te permite dar seguridad a los organismos públicos (que suelen pedir fechas y presupuestos fijos) mientras mantienes la flexibilidad para ajustar la aplicación según el feedback de los ciudadanos.

Requerimientos Legales y de Privacidad: El manejo de datos ciudadanos y la validación OTP que mencionaste requieren un marco legal claro desde el día uno.

Arquitectura de Datos: Definir cómo se guardarán los puntos georreferenciados para que sean compatibles con los sistemas de las autoridades ambientales.

Una vez definida la base, pasa a un ciclo ágil de 2 semanas:

Scrum para el Desarrollo: Usa Sprints para entregar funcionalidades concretas (ej. Sprint 1: Autenticación OTP; Sprint 2: Mapa interactivo y marcador de puntos).

Kanban para Soporte y Mejora: Ideal para gestionar los reportes de errores una vez que la plataforma esté en manos de los ciudadanos de zonas periféricas.