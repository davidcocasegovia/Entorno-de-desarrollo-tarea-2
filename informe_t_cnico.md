# Informe Técnico: Análisis de Elementos y Requisitos del Software - StudyPlan

**Autor:** David Coca Segovia  
**Módulo:** Entorno de Desarrollo (UD2)  
**Institución:** MEDAC (Instituto Oficial de Formación Profesional)  

---

## 1. Selección de la Aplicación

### 1.1 Aplicación Elegida: StudyPlan
StudyPlan es una solución digital concebida para estudiantes con el objetivo de centralizar la gestión de tareas, exámenes y sesiones de estudio. Su propósito fundamental es combatir la desorganización y los despistes recurrentes en el ámbito académico mediante herramientas de planificación visual y recordatorios.

La elección de este proyecto se fundamenta en su idoneidad para aplicar **metodologías ágiles**. Al tratarse de un sistema modular, permite la entrega progresiva de valor a través de pequeños incrementos funcionales, alineándose con los conceptos estudiados sobre el modelo en espiral extremo y el marco de trabajo **Scrum**. Asimismo, destaca la necesidad de realizar una fase de toma de requisitos rigurosa para capturar adecuadamente las necesidades reales del usuario final antes de iniciar el diseño y la codificación.

---

## 2. Listado de Características

El sistema contempla un conjunto de prestaciones clasificadas en funcionales y no funcionales:

| $N^{\circ}$ | Característica | Tipo |
| :---: | :--- | :--- |
| 1 | Crear una cuenta de usuario | Funcional |
| 2 | Iniciar y cerrar sesión | Funcional |
| 3 | Crear, modificar y eliminar tareas | Funcional |
| 4 | Registrar exámenes y fechas de entregas | Funcional |
| 5 | Mostrar las tareas y exámenes mediante un calendario | Funcional |
| 6 | Enviar recordatorios de tareas y exámenes próximos | Funcional |
| 7 | Marcar una tarea como completada | Funcional |
| 8 | Responder de forma rápida a las acciones habituales del usuario | No funcional |
| 9 | Proteger los datos personales y las credenciales | No funcional |
| 10 | Disponer de una interfaz sencilla y fácil de utilizar | No funcional |
| 11 | Ser compatible con móvil y navegador web | No funcional |
| 12 | Permitir recuperar los datos en caso de pérdida | No funcional |

---

## 3. Documentación Inicial del Sistema

* **Nombre de la aplicación:** StudyPlan
* **Descripción breve:** Software de organización académica enfocado en tareas, exámenes y planificación de estudio.
* **Objetivos principales:** Resolver la desorganización académica, minimizar el olvido de fechas clave y optimizar el tiempo de estudio.
* **Usuarios principales:** Estudiantes jóvenes, perfil caracterizado por un alto nivel de dinamismo y una menor tendencia natural a la planificación estructurada formal.
* **Plataforma:** Aplicación multiplataforma disponible para dispositivos móviles (Android / iOS) y acceso web.
* **Modelo de desarrollo sugerido:** Metodología Ágil (**Scrum**), implementando iteraciones (*sprints*) de 15 días orientadas a construir un producto mínimo viable e ir enriqueciéndolo progresivamente.

---

## 4. Análisis de Requisitos

La fase de especificación de requisitos resulta crítica para evitar desviaciones y asegurar que el software cumpla con lo esperado antes de abordar la codificación.

### 4.1 Requisitos Funcionales
* **RF1 - Registro de usuario:** Habilita el alta de nuevos perfiles de estudiantes.
* **RF2 - Gestión de tareas:** Permite el CRUD (Crear, Leer, Actualizar, Borrar) de tareas.
* **RF3 - Gestión de fechas:** Permite agendar exámenes y fechas límite de entregas.
* **RF4 - Calendario:** Interfaz visual para consultar eventos y tareas organizados cronológicamente.
* **RF5 - Recordatorios:** Sistema de alertas para notificar entregas y exámenes inminentes.
* **RF6 - Estado de tareas:** Indicadores de control para alternar entre tareas pendientes y completadas.

### 4.2 Requisitos No Funcionales
* **RNF1 (Rendimiento):** Respuesta ágil del sistema para garantizar una experiencia de usuario fluida.
* **RNF2 (Seguridad):** Cifrado y salvaguarda de credenciales e información personal del usuario.
* **RNF3 (Usabilidad):** Diseño intuitivo adaptado a usuarios con perfiles y experiencias tecnológicas heterogéneas.
* **RNF4 (Compatibilidad):** Multidispositivo (navegadores web y apps nativas/híbridas móviles).
* **RNF5 (Disponibilidad y Recuperación):** Mecanismos de persistencia y respaldo ante contingencias de pérdida de datos.

---

## 5. Comunicación y Colaboración

El desarrollo del proyecto está concebido para un equipo de 2 a 3 integrantes, distribuyendo responsabilidades conforme a roles profesionales estándar del sector (analista de sistemas, diseñador de software y analista programador).

* **Integrantes y reparto de tareas:**
  * **David Coca Segovia:** Selección de la aplicación, establecimiento de objetivos, definición de usuarios y requisitos funcionales. Elaboración del listado de características, requisitos no funcionales, análisis de plataforma, metodología de desarrollo, reflexión final y revisión integral de los entregables y presentaciones.

---

## 6. Reflexión Final

A modo de conclusión sobre el ciclo de desarrollo analizado, se extraen las siguientes valoraciones:

1. **Dificultad en los Requisitos:** Es una de las etapas más complejas y propensas a cambios por parte de los clientes/usuarios, lo que subraya la importancia de documentar exhaustivamente y mantener una comunicación constante.
2. **Relevancia de la Fase de Pruebas:** Las pruebas posteriores a la implementación son indispensables para contrastar que el software responde fielmente a los requisitos previamente especificados y corregir posibles defectos a tiempo.
3. **Idoneidad de Scrum:** Las metodologías ágiles aportan gran flexibilidad frente a los modelos predictivos tradicionales, permitiendo adaptar el producto gradualmente mediante sprints.
4. **Coherencia del Ciclo de Vida:** Las fases del desarrollo se encuentran intrínsecamente conectadas; omitir o descuidar los cimientos analíticos y de diseño suele derivar en fallos estructurales graves durante la implementación final.