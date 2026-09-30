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

Se identificaron ocho interesados relacionados con el desarrollo, la utilización y el seguimiento del sistema web de Moya's Pizza. El poder y el interés se valoran de **1 (muy bajo) a 5 (muy alto)**. La actitud y las puntuaciones representan una valoración inicial del equipo; los segmentos de clientes y los usuarios de prueba son grupos propuestos para el análisis del proyecto.

| Interesado | Necesidad | Poder (1–5) | Interés (1–5) | Actitud | Estrategia | Responsable del seguimiento |
|---|---|:---:|:---:|---|---|---|
| Dueño de Moya's Pizza | Gestionar el catálogo, recibir pedidos sin interrumpir la preparación y consultar las ventas. | 5 | 5 | Favorable | Gestionar de cerca mediante revisiones y validación de entregables. | Equipo de desarrollo |
| Equipo de desarrollo | Disponer de requerimientos claros y cumplir el alcance y las restricciones del proyecto. | 4 | 5 | Favorable | Coordinar tareas, revisar avances y resolver dificultades continuamente. | Equipo de desarrollo |
| Profesor del curso | Verificar el cumplimiento de los objetivos y entregables académicos. | 4 | 4 | Favorable | Presentar avances y atender la retroalimentación académica. | Equipo de desarrollo |
| Clientes habituales | Consultar precios y promociones y realizar pedidos de forma sencilla y confiable. | 3 | 5 | Favorable | Mantener informados y solicitar comentarios sobre la experiencia de compra. | Equipo de desarrollo |
| Clientes nuevos | Conocer el negocio, el catálogo y el proceso para realizar su primer pedido. | 2 | 4 | Neutral | Facilitar información clara y recopilar dudas de uso. | Equipo de desarrollo |
| Proveedores tecnológicos | Que el uso de los servicios contratados respete sus condiciones y límites. | 4 | 3 | Neutral | Mantener satisfechos mediante el seguimiento de límites y condiciones de los planes gratuitos. | Equipo de desarrollo |
| Usuarios encargados de probar el sistema | Contar con un sistema comprensible y poder reportar problemas antes de su lanzamiento. | 2 | 4 | Favorable | Involucrar en pruebas de usabilidad y recoger observaciones. | Equipo de desarrollo |
| Visitantes ocasionales del sitio web | Consultar el menú o la información del negocio sin necesidad de realizar un pedido. | 1 | 2 | Neutral | Monitorear comentarios y patrones generales de uso, cuando estén disponibles. | Equipo de desarrollo |

### 2.2 Justificación de las valoraciones

- **Dueño (5, 5):** tiene la autoridad para aprobar las decisiones comerciales y el máximo interés porque el sistema busca solucionar problemas de su operación diaria.
- **Equipo de desarrollo (4, 5):** toma las decisiones técnicas y ejecuta el proyecto, aunque el dueño conserva la aprobación de las decisiones del negocio.
- **Profesor (4, 4):** tiene influencia sobre los entregables y la evaluación académica, pero no sobre la operación comercial de Moya's Pizza.
- **Clientes habituales (3, 5):** son usuarios directamente afectados por la experiencia de pedido. Sus opiniones pueden orientar mejoras, aunque no aprueban formalmente el proyecto.
- **Clientes nuevos (2, 4):** necesitan comprender el catálogo y el proceso de compra; su influencia individual sobre las decisiones del proyecto es limitada.
- **Proveedores tecnológicos (4, 3):** los límites y condiciones de los servicios gratuitos pueden afectar el funcionamiento o la implementación. No participan directamente en las decisiones del negocio, por lo que se les asigna un interés moderado.
- **Usuarios de prueba (2, 4):** sus observaciones pueden revelar errores o problemas de usabilidad, pero no tienen autoridad para definir el alcance final.
- **Visitantes ocasionales (1, 2):** pueden consultar el catálogo sin comprar ni participar en el desarrollo; su poder e interés iniciales se consideran bajos.

### 2.3 Mapa Poder-Interés

Se consideran **altos los valores 4 y 5**, y **bajos los valores del 1 al 3**.

| | **Interés bajo (1–3)** | **Interés alto (4–5)** |
|---|---|---|
| **Poder alto (4–5)** | **Mantener satisfechos**<br>Proveedores tecnológicos (4, 3) | **Gestionar de cerca**<br>Dueño de Moya's Pizza (5, 5)<br>Equipo de desarrollo (4, 5)<br>Profesor del curso (4, 4) |
| **Poder bajo (1–3)** | **Monitorear**<br>Visitantes ocasionales (1, 2) | **Mantener informados**<br>Clientes habituales (3, 5)<br>Clientes nuevos (2, 4)<br>Usuarios de prueba (2, 4) |

**Aplicación de las estrategias:** los interesados con poder e interés altos participarán en revisiones y decisiones pertinentes. Los proveedores tecnológicos se atenderán mediante la revisión de condiciones y límites de sus servicios. Los clientes y usuarios de prueba recibirán información y oportunidades para aportar comentarios. Los visitantes ocasionales se monitorearán sin requerir participación continua.

### 2.4 Tres interesados críticos

Se seleccionaron tres interesados por su relación directa con la aprobación, el desarrollo y la aceptación del sistema.

**1. Dueño de Moya's Pizza.** Es el principal interesado porque conoce las necesidades del negocio y autoriza las decisiones comerciales. Se le involucrará mediante reuniones periódicas, revisión de prototipos, demostraciones funcionales y validación del catálogo, el flujo de pedidos y el panel administrativo. El equipo de desarrollo será responsable de mantener la comunicación.

**2. Equipo de desarrollo.** Es responsable de convertir los requerimientos en un sistema funcional, respetando las restricciones de costo y alcance. Sus integrantes participarán en la planificación de entregas, la distribución de tareas, las revisiones de avance y las pruebas de cada componente. Se mantendrá una comunicación continua para identificar bloqueos y coordinar cambios.

**3. Clientes habituales.** Su uso del catálogo y del proceso de pedidos permitirá comprobar si la solución resulta clara y práctica. Se les involucrará mediante consultas breves y pruebas de usabilidad, enfocadas en encontrar productos, comprender precios y promociones y completar pedidos. Sus comentarios se revisarán antes de la implementación final.

### 2.5 Enfoque de gestión del proyecto

**Enfoque seleccionado: híbrido (predictivo y adaptativo).**

El componente **predictivo** se utilizará para establecer el alcance general, los entregables, los recursos y las restricciones conocidas desde el inicio. Entre ellas están el uso de servicios en sus planes gratuitos, el dominio como único costo recurrente previsto y la decisión de no procesar pagos en línea.

El componente **adaptativo** se utilizará para desarrollar y validar progresivamente el catálogo, el proceso de pedidos y el panel administrativo. Las revisiones con el dueño y las pruebas con usuarios permitirán ajustar la navegación, la presentación de la información y los flujos de trabajo conforme se identifiquen necesidades.

El enfoque híbrido permite conservar una planificación inicial y controlar las restricciones del proyecto, sin impedir ajustes basados en la retroalimentación de los interesados durante el desarrollo.

---

## Próximas semanas

Las siguientes entregas se incorporarán a este mismo README, con una sección independiente por semana y sus respectivos enlaces en la tabla de contenido.
