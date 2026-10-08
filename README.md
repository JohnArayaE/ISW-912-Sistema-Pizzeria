<div align="center">

# Administración de Proyectos Informáticos

### ISW-912 · Ingeniería del Software

**Universidad Técnica Nacional**  
**Sede Regional de San Carlos**

**Profesor:** Deiver Cubero Molina  
**Estudiantes:** John Alejandro Araya Echeverría y Ryan Eliecer Vega Solano  
**Septiembre de 2026**

---

# Sistema web de catálogo y gestión de pedidos para Moya's Pizza

*Repositorio de entregables semanales del curso*

</div>

## Tabla de contenido

- [Semana 1: Planteamiento del proyecto](#semana-1-planteamiento-del-proyecto)
  - [Tema del proyecto](#11-tema-del-proyecto)
  - [Problema identificado](#12-problema-identificado)
  - [Proyecto propuesto](#13-proyecto-propuesto)
  - [Valor esperado](#14-valor-esperado)
  - [Indicadores de verificación](#15-indicadores-de-verificación)
  - [Objetivos](#16-objetivos)
- [Semana 2: Taller de interesados del proyecto](#semana-2-taller-de-interesados-del-proyecto)
  - [Identificación y registro de interesados](#21-identificación-y-registro-de-interesados)
  - [Justificación de las valoraciones](#22-justificación-de-las-valoraciones)
  - [Mapa Poder-Interés](#23-mapa-poder-interés)
  - [Tres interesados críticos](#24-tres-interesados-críticos)
  - [Enfoque de gestión del proyecto](#25-enfoque-de-gestión-del-proyecto)
- [Semana 3: Formalización y gestión del proyecto](#semana-3-formalización-y-gestión-del-proyecto)
  - [Acta de Inicio (Project Charter)](#31-acta-de-inicio-project-charter)
  - [Definición del Scrum Team](#32-definición-del-scrum-team)
  - [Análisis del entorno (Lean Canvas y EEFs)](#33-análisis-del-entorno-lean-canvas-y-eefs)
- [Próximas semanas](#próximas-semanas)

---

## Semana 1: Planteamiento del proyecto

### 1.1 Tema del proyecto

**Sistema web de catálogo y gestión de pedidos para Moya's Pizza.**

### 1.2 Problema identificado

Moya's Pizza es una pizzería local que recibe pedidos únicamente mediante llamadas telefónicas y mensajes de WhatsApp. El dueño atiende estos canales mientras prepara las pizzas, lo que ocasiona los siguientes problemas:

- **Errores y pérdida de pedidos:** los pedidos se anotan en papel o se recuerdan de memoria, con posibles equivocaciones en tamaños, cantidades y precios.
- **Interrupciones en la cocina:** atender llamadas durante la preparación aumenta los tiempos de entrega y limita la cantidad de pedidos que pueden atenderse simultáneamente.
- **Ausencia de registros de ventas:** no es posible consultar cuánto se vendió en un día, identificar los productos más solicitados ni fundamentar decisiones sobre precios y promociones.
- **Información limitada para los clientes:** deben llamar para conocer el menú, los precios, las promociones y los tiempos de espera.

### 1.3 Proyecto propuesto

Se propone desarrollar e implementar un sitio web propio compuesto por tres elementos:

1. **Catálogo público:** permitirá consultar pizzas, combos, promociones, precios actualizados y descuentos vigentes.
2. **Proceso de pedido guiado:** permitirá crear un carrito, consultar un tiempo estimado de espera según la carga de la cocina, proporcionar datos de contacto y registrar el pedido directamente en la base de datos.
3. **Panel de administración:** ofrecerá al dueño acceso restringido para gestionar el menú, los precios, las promociones y los descuentos; recibir pedidos en tiempo real, actualizar su estado hasta la entrega y consultar el historial de ventas.

El sistema se plantea sobre servicios con planes gratuitos, por lo que el único costo recurrente previsto es la renovación anual del dominio. **No se procesarán pagos en línea:** el cliente indicará su método de pago y cancelará en el local o contra entrega.

### 1.4 Valor esperado

El proyecto busca reducir la carga de trabajo del dueño y proporcionarle información útil para administrar el negocio. Se esperan los siguientes beneficios:

- Reducir errores al permitir que cada cliente seleccione sus productos y que el sistema calcule el total con los precios vigentes.
- Aumentar la capacidad de atención al disminuir las interrupciones para contestar llamadas.
- Consultar las ventas por día o por rango de fechas.
- Dar autonomía al dueño para modificar precios, publicar promociones y cerrar temporalmente el negocio sin intervención técnica.
- Evitar costos operativos recurrentes adicionales y comisiones por pedido.

### 1.5 Indicadores de verificación

Para evaluar los resultados del proyecto se proponen estos indicadores:

| Indicador | Qué permitirá verificar |
| --- | --- |
| Porcentaje de pedidos recibidos por el sitio frente a llamadas | Adopción del canal digital. |
| Cantidad de pedidos con errores antes y después de implementar el sistema | Reducción de errores en la toma de pedidos. |
| Disponibilidad del historial diario de ventas | Acceso a información para la gestión del negocio. |

### 1.6 Objetivos

#### Objetivo general

Desarrollar e implementar un sistema web que permita a Moya's Pizza publicar su catálogo, recibir pedidos en línea y administrar su operación diaria, sin incorporar costos recurrentes al negocio.

#### Objetivos específicos (planteamiento inicial)

1. Analizar el proceso actual de toma de pedidos del negocio e identificar sus principales puntos de falla.
2. Definir los requerimientos funcionales y no funcionales del sistema junto con el cliente.
3. Diseñar la estructura de datos que soporte el catálogo, las promociones y el registro histórico de pedidos.
4. Desarrollar el sitio público y el panel de administración conforme a los requerimientos definidos.

---

## Semana 2: Taller de interesados del proyecto

### 2.1 Identificación y registro de interesados

Se identificaron **nueve interesados** relacionados con el proyecto. El poder y el interés se valoran de **1 (muy bajo) a 5 (muy alto)**. Las actitudes y puntuaciones son valoraciones iniciales para el taller.

| Interesado | Necesidad | Poder | Interés | Actitud | Estrategia |
|---|---|:---:|:---:|---|---|
| Dueño de Moya's Pizza | Administrar pedidos, productos, promociones y ventas. | 5 | 5 | Favorable | Gestionar de cerca. |
| Clientes | Consultar el menú y realizar pedidos fácilmente. | 3 | 5 | Favorable | Mantener informados. |
| Personal de cocina | Recibir pedidos claros y conocer los tiempos de preparación. | 3 | 5 | Favorable | Involucrar en pruebas. |
| Equipo de desarrollo | Contar con requerimientos claros y recursos suficientes. | 4 | 5 | Favorable | Gestionar de cerca. |
| Administrador del sistema | Gestionar el catálogo, los pedidos y las promociones. | 4 | 5 | Favorable | Gestionar de cerca. |
| Proveedores tecnológicos | Garantizar el uso adecuado de sus servicios. | 4 | 3 | Neutral | Mantener satisfechos. |
| Profesor del curso | Verificar el cumplimiento de los objetivos académicos. | 4 | 4 | Favorable | Gestionar de cerca. |
| Proveedores de ingredientes | Mantener la relación comercial con el negocio. | 2 | 2 | Neutral | Monitorear. |
| Personal de entrega | Recibir información correcta de los pedidos. | 2 | 4 | Favorable | Mantener informado. |

### 2.2 Justificación de las valoraciones

- **Dueño (5, 5):** autoriza las decisiones comerciales y tiene interés directo en mejorar la operación diaria.
- **Clientes (3, 5):** necesitan consultar información y hacer pedidos sin dificultades; influyen mediante sus comentarios, aunque no aprueban el proyecto.
- **Personal de cocina (3, 5):** el flujo de recepción de pedidos y los tiempos de preparación afectan directamente su trabajo.
- **Equipo de desarrollo (4, 5):** toma decisiones técnicas y ejecuta el proyecto, dentro del alcance acordado con el dueño.
- **Administrador del sistema (4, 5):** utiliza las funciones de gestión del catálogo, pedidos y promociones, por lo que tiene influencia operativa e interés elevado. Este rol podría ser desempeñado por el propio dueño.
- **Proveedores tecnológicos (4, 3):** las condiciones y límites de los servicios gratuitos pueden afectar la implementación, aunque no participan en las decisiones comerciales.
- **Profesor (4, 4):** supervisa los entregables académicos y evalúa el trabajo, sin dirigir el negocio.
- **Proveedores de ingredientes (2, 2):** mantienen una relación comercial con la pizzería, pero su participación en el desarrollo del sistema es limitada.
- **Personal de entrega (2, 4):** necesita datos correctos para las entregas, aunque tiene poca autoridad sobre el alcance del proyecto.

### 2.3 Mapa Poder-Interés

Se consideran **altos los valores 4 y 5** y **bajos los valores de 1 a 3**. El mapa corresponde a los nueve interesados del registro anterior.

![Mapa Poder-Interés del proyecto Moya's Pizza](assets/mapa-poder-interes.png)

| | **Interés bajo (1–3)** | **Interés alto (4–5)** |
|---|---|---|
| **Poder alto (4–5)** | **Mantener satisfechos:** proveedores tecnológicos (4, 3). | **Gestionar de cerca:** dueño de Moya's Pizza (5, 5); equipo de desarrollo (4, 5); administrador del sistema (4, 5); profesor del curso (4, 4). |
| **Poder bajo (1–3)** | **Monitorear:** proveedores de ingredientes (2, 2). | **Mantener informados:** clientes (3, 5); personal de cocina (3, 5); personal de entrega (2, 4). |

### 2.4 Tres interesados críticos

**1. Dueño de Moya's Pizza.** Tiene autoridad para aprobar las decisiones comerciales y conoce las necesidades del negocio. Se le involucrará mediante reuniones semanales, revisión de prototipos, demostraciones del sistema y validación de los entregables.

**2. Personal de cocina.** El sistema debe presentar pedidos claros y tiempos de preparación realistas. Se le involucrará mediante entrevistas sobre el proceso actual y pruebas del flujo de recepción y actualización de pedidos.

**3. Clientes.** Utilizarán el catálogo y el proceso de pedidos. Se les involucrará mediante encuestas breves y pruebas de usabilidad para evaluar la navegación, la claridad de precios y la facilidad para realizar pedidos.

### 2.5 Enfoque de gestión del proyecto

**Enfoque seleccionado: híbrido (predictivo y adaptativo).**

El componente **predictivo** se utilizará para establecer el alcance general, los entregables, los recursos y las restricciones conocidas desde el inicio. Entre ellas están el uso de servicios en sus planes gratuitos, el dominio como único costo recurrente previsto y la decisión de no procesar pagos en línea.

El componente **adaptativo** se utilizará para desarrollar y validar progresivamente el catálogo, el proceso de pedidos y el panel administrativo. Las revisiones con el dueño y las pruebas con usuarios permitirán ajustar la navegación, la presentación de la información y los flujos de trabajo conforme se identifiquen necesidades.

El enfoque híbrido permite conservar una planificación inicial y controlar las restricciones del proyecto, sin impedir ajustes basados en la retroalimentación de los interesados durante el desarrollo.

---

## Semana 3: Formalización y gestión del proyecto

### 3.1 Acta de Inicio (Project Charter)

El acta formaliza el propósito, el alcance inicial y las condiciones generales del proyecto. Constituye una base de referencia para el equipo y para la validación de las decisiones con el dueño del negocio. **Se presenta como propuesta académica, pendiente de validación formal con el patrocinador.**

| Elemento | Definición |
|---|---|
| Nombre del proyecto | Sistema web de catálogo y gestión de pedidos para Moya's Pizza. |
| Organización beneficiaria | Moya's Pizza. |
| Patrocinador y responsable de validación comercial | Dueño de Moya's Pizza. |
| Equipo ejecutor | John Alejandro Araya Echeverría y Ryan Eliecer Vega Solano. |
| Contexto académico | ISW-912, Universidad Técnica Nacional, período de trabajo de 14 semanas. |
| Enfoque de gestión | Híbrido: planificación general predictiva y desarrollo incremental adaptativo. |
| Estado del acta | Propuesta inicial, sujeta a revisión y aprobación. |

#### 3.1.1 Justificación

Actualmente, el dueño recibe pedidos por llamadas y WhatsApp mientras prepara pizzas. Esto ocasiona interrupciones, errores o pérdida de pedidos y falta de registros de ventas. El proyecto busca organizar la recepción de pedidos y facilitar la consulta del menú, las promociones y la información de ventas, sin incorporar costos operativos recurrentes adicionales a la renovación prevista del dominio.

#### 3.1.2 Objetivos

**Objetivo general:** Desarrollar e implementar un sistema web que permita a Moya's Pizza publicar su catálogo, recibir pedidos en línea y administrar su operación diaria, sin incorporar costos recurrentes al negocio.

**Objetivos específicos:**

1. Analizar el proceso actual de toma de pedidos e identificar sus principales puntos de falla.
2. Definir los requerimientos funcionales y no funcionales junto con el cliente.
3. Diseñar la estructura de datos del catálogo, las promociones y el historial de pedidos.
4. Desarrollar el sitio público y el panel administrativo conforme a los requerimientos definidos.

#### 3.1.3 Alcance general y límites

**Incluye:** catálogo público de pizzas, combos, promociones y precios; carrito y proceso guiado para registrar pedidos con datos de contacto y tiempo estimado de espera; panel de acceso restringido para gestionar productos, precios, descuentos y promociones, visualizar y actualizar pedidos, y consultar el historial de ventas.

**Excluye:** procesamiento de pagos en línea, cobro automático y comisiones por pedidos mediante plataformas externas. El pago se realizará en el local o contra entrega, según el método declarado por el cliente.

**Límite operativo:** la gestión cotidiana del negocio y el abastecimiento de ingredientes no forman parte del desarrollo del sistema. El cálculo de espera deberá validarse con el negocio antes de considerarse una función terminada.

#### 3.1.4 Entregables principales

| Entregable | Resultado esperado |
|---|---|
| Análisis de requerimientos | Necesidades funcionales y no funcionales documentadas y revisadas. |
| Diseño de datos | Estructura para productos, promociones, pedidos e historial de ventas. |
| Catálogo público | Consulta de productos, precios y promociones vigentes. |
| Flujo de pedidos | Carrito, captura de datos y registro de pedidos. |
| Panel administrativo | Gestión del menú y de pedidos, con consulta de ventas. |
| Pruebas y documentación | Evidencia de validación funcional y documentación de entrega. |

#### 3.1.5 Restricciones y supuestos

| Tipo | Descripción |
|---|---|
| Tiempo | El trabajo académico se organiza en un período de 14 semanas. |
| Costo | Se priorizarán servicios en planes gratuitos; el único costo recurrente previsto es el dominio anual. |
| Alcance | No se integrarán pagos en línea. |
| Disponibilidad | La revisión de requisitos y resultados depende del tiempo que pueda dedicar el dueño. |
| Supuesto | El negocio podrá facilitar información del menú y retroalimentación para las validaciones. |
| Supuesto | Los servicios gratuitos elegidos serán suficientes para el alcance inicial; esto debe verificarse. |

#### 3.1.6 Riesgos iniciales

| Riesgo | Posible efecto | Respuesta propuesta |
|---|---|---|
| Límites o cambios en los planes gratuitos | Restricciones técnicas o necesidad de ajustar la solución. | Revisar cuotas y condiciones; evitar dependencias innecesarias. |
| Poca disponibilidad del dueño | Retrasos en decisiones y validaciones. | Acordar revisiones breves y registrar decisiones pendientes. |
| Cambios de requisitos durante el desarrollo | Retrabajo o retrasos. | Priorizar el Product Backlog y evaluar cada cambio frente al alcance. |
| Tiempo académico limitado | Funcionalidades incompletas. | Entregar incrementos funcionales y priorizar lo indispensable. |
| Manejo inadecuado de datos de contacto | Riesgos de privacidad y confianza. | Limitar los datos recopilados y aplicar controles de acceso. |

#### 3.1.7 Criterios de éxito y validación

Se considerará que la solución cumple su propósito inicial cuando se demuestre que: **(a)** el catálogo presenta productos y precios vigentes; **(b)** un cliente puede registrar un pedido con los datos requeridos; **(c)** el dueño puede consultar y actualizar los pedidos desde el panel; **(d)** existe un historial de ventas consultable; y **(e)** se respetan las exclusiones y restricciones acordadas. Estos criterios deberán convertirse en casos de prueba y ser validados con el dueño.

Los indicadores de impacto definidos en la [Semana 1](#15-indicadores-de-verificación) —adopción del canal digital, errores de pedidos e historial de ventas— servirán para evaluar los resultados después de la puesta en uso. No se fijan porcentajes de mejora sin una línea base.

### 3.2 Definición del Scrum Team

El equipo académico está integrado por dos estudiantes. Para cubrir las responsabilidades solicitadas en clase, ambos participarán como **Developers** y cada uno asumirá adicionalmente una responsabilidad de gestión. Esta es una adaptación práctica por el tamaño del equipo, no una estructura de tres personas distintas.

#### 3.2.1 Asignación de roles

| Integrante | Rol asignado | Responsabilidades principales |
|---|---|---|
| **John Alejandro Araya Echeverría** | **Scrum Master y Developer** | Facilitar los eventos de Scrum, dar seguimiento a impedimentos, promover la mejora continua y desarrollar y probar funcionalidades. |
| **Ryan Eliecer Vega Solano** | **Product Owner y Developer** | Organizar y priorizar el Product Backlog, aclarar requisitos con el dueño, orientar las decisiones hacia el valor del producto y desarrollar y probar funcionalidades. |

El **dueño de Moya's Pizza** actuará como referente del negocio para validar necesidades y entregables; no se le asigna formalmente un rol interno del Scrum Team académico.

#### 3.2.2 Responsabilidades compartidas

| Actividad | John | Ryan |
|---|---|---|
| Planificación de Sprint | Participa y facilita | Participa y prioriza |
| Gestión del Product Backlog | Apoya con estimaciones técnicas | Responsable de ordenarlo y aclararlo |
| Seguimiento de impedimentos | Facilita su resolución | Colabora |
| Diseño e implementación | Developer | Developer |
| Pruebas y revisión de calidad | Developer | Developer |
| Documentación y entregables académicos | Compartida | Compartida |
| Revisión con el dueño | Facilita y presenta avances | Recopila retroalimentación y valida prioridades |

### 3.3 Análisis del entorno (Lean Canvas y EEFs)

El análisis identifica condiciones que pueden favorecer o limitar el desarrollo de Moya's Pizza. Se distinguen los **factores ambientales (EEFs)**, que no están bajo control directo del equipo, de las decisiones internas de alcance y organización.

#### 3.3.1 Factores ambientales de la empresa (EEFs)

| Factor | Condición relevante | Impacto y consideración para el proyecto |
|---|---|---|
| Tecnológico | Uso de servicios externos con planes gratuitos. | Las cuotas, políticas y disponibilidad del proveedor pueden limitar la solución; deben revisarse antes de desplegar. |
| Económico | El negocio busca evitar costos recurrentes adicionales. | Condiciona la selección de infraestructura y obliga a vigilar el consumo de recursos. |
| Organizacional y operativo | El dueño atiende pedidos y participa en la preparación. | Su disponibilidad para entrevistas y pruebas puede ser limitada; conviene programar validaciones breves. |
| Legal y privacidad | El sitio recopilará datos de contacto para gestionar pedidos. | Deben considerarse las obligaciones aplicables de protección de datos y el acceso restringido a esa información. |
| Académico | El curso establece un horizonte de trabajo de 14 semanas. | Exige priorizar entregables y coordinar las revisiones académicas. |
| Adopción de usuarios | Los clientes están acostumbrados a llamadas y WhatsApp. | La interfaz debe ser clara y el cambio de canal debe validarse con usuarios. |

#### 3.3.2 Lean Canvas del proyecto

El siguiente Lean Canvas es un **planteamiento inicial** para analizar la solución; sus hipótesis deberán contrastarse con el dueño y los usuarios.

| Bloque | Aplicación en Moya's Pizza |
|---|---|
| **1. Problema** | Errores o pérdida de pedidos, interrupciones en cocina y ausencia de registros de ventas. |
| **2. Segmentos de clientes** | Clientes actuales y potenciales de la pizzería que desean consultar el menú y realizar pedidos. |
| **3. Propuesta única de valor** | Un canal propio que organiza los pedidos y permite al dueño gestionar información comercial sin depender de comisiones por pedido. |
| **4. Solución** | Catálogo público, proceso guiado de pedidos y panel administrativo. |
| **5. Canales** | Sitio web propio; llamadas y WhatsApp como canales actuales de contacto y posible difusión. |
| **6. Fuentes de ingresos** | Ventas de pizzas, combos y otros productos del negocio; el sistema no introduce pagos digitales. |
| **7. Estructura de costos** | Renovación anual del dominio y uso previsto de planes gratuitos; cualquier cambio de consumo deberá evaluarse. |
| **8. Métricas clave** | Porcentaje de pedidos digitales, cantidad de errores reportados y disponibilidad del historial de ventas. |
| **9. Ventaja diferencial** | Adaptación del catálogo y del flujo de pedidos a la operación específica de Moya's Pizza; ventaja propuesta, aún no validada. |

#### 3.3.3 Influencia de los interesados (stakeholders)

Se retoma el registro de **nueve interesados** de la [Semana 2](#21-identificación-y-registro-de-interesados), sin modificar sus puntuaciones ni reemplazar el [mapa Poder-Interés](#23-mapa-poder-interés).

| Interesado o grupo | Influencia principal | Respuesta prevista |
|---|---|---|
| Dueño de Moya's Pizza | Autoriza decisiones comerciales y valida necesidades. | Reuniones y demostraciones periódicas. |
| Clientes | Determinan la facilidad de uso y la aceptación del canal web. | Pruebas de usabilidad y recopilación de comentarios. |
| Personal de cocina | Aporta información sobre la recepción y preparación de pedidos. | Entrevistas y validación del flujo operativo. |
| Equipo de desarrollo | Define e implementa las soluciones técnicas. | Coordinación de Sprints y revisión de calidad. |
| Administrador del sistema | Gestionará el catálogo y los pedidos; puede ser el dueño. | Validar permisos y tareas administrativas. |
| Proveedores tecnológicos | Condicionan la disponibilidad y los límites de infraestructura. | Revisar condiciones y monitorear uso. |
| Profesor del curso | Evalúa los entregables y requisitos académicos. | Presentar avances y atender observaciones. |
| Proveedores de ingredientes | Relación comercial indirecta con el proyecto informático. | Monitorear sin involucramiento intensivo. |
| Personal de entrega | Requiere información correcta para completar entregas. | Consultar necesidades relacionadas con datos de pedido. |

#### 3.3.4 Relación con el enfoque híbrido

El **componente predictivo** permite acordar límites, recursos, criterios de éxito y entregables generales. El **componente adaptativo**, organizado mediante Sprints, permite revisar incrementos, priorizar el Product Backlog y ajustar detalles a partir de las validaciones. Así se mantiene la coherencia con el enfoque seleccionado en la [Semana 2](#25-enfoque-de-gestión-del-proyecto).

---

## Próximas semanas

Las siguientes entregas se incorporarán a este mismo README, con una sección independiente por semana y sus respectivos enlaces en la tabla de contenido.
