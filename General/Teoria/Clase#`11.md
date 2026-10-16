# CONSTRUYENDO SISTEMAS DE INFORMACIÓN

## 1. Una decisión antes de comprar tecnología

* Una empresa registra pedidos en **tres archivos** y promete al cliente **productos agotados**.
* Pregunta de reflexión: ¿qué cambiarían primero: la **herramienta**, el **procedimiento** o las **responsabilidades**?
* La idea central es que comprar tecnología no resuelve por sí solo un problema organizacional: antes hay que decidir qué cambia en el trabajo, en las reglas y en quién responde.

---

## 2. Objetivos de la clase

| N.º | Objetivo |
|---|---|
| **01** | Distinguir **cuatro niveles de cambio organizacional** |
| **02** | Relacionar las **etapas del desarrollo** con decisiones administrativas |
| **03** | Justificar una **alternativa de adquisición** y un **plan de transición** |

### Contenido del tema

* Sistemas de información y cambio organizacional.
* Automatización y racionalización de procedimientos.
* Rediseño del proceso y cambio de paradigma.
* Análisis y diseño de sistemas.
* Construcción, pruebas y aceptación del sistema.
* Conversión, mantenimiento y evaluación de resultados.
* Enfoques de desarrollo, modelado y herramientas CASE.
* Alternativas para crear o adquirir sistemas: una decisión final.

---

## 3. Sistemas de información y cambio organizacional

* Un sistema de información **también transforma el trabajo**: cuando cambia el sistema, cambia la organización.

| Dimensión | Qué cambia |
|---|---|
| **Personas** | Nuevas habilidades, capacitación y participación |
| **Procesos** | Reglas, secuencia de actividades y tratamiento de excepciones |
| **Organización** | Responsables, coordinación y decisiones |
| **Tecnología y datos** | Aplicaciones, infraestructura e información confiable |

### Cuatro niveles de cambio

| Nivel | Descripción |
|---|---|
| **1. Automatización** | Ejecutar una **tarea existente** con tecnología |
| **2. Racionalización** | **Eliminar pasos innecesarios** y estandarizar procedimientos |
| **3. Rediseño** | **Reorganizar integralmente** un proceso de negocio |
| **4. Cambio de paradigma** | **Transformar el modelo de negocio** o la misión operativa |

### Alcance, beneficios y riesgos

* Las formas más comunes de cambio organizacional son la **automatización** y la **racionalización**: se mueven con relativa lentitud, ofrecen **rendimientos modestos** pero **riesgo bajo**.
* El cambio más rápido y extenso (**rediseño** y **cambio de paradigma**) conlleva **mayores recompensas**, pero con un **riesgo considerable de fracaso**.
* En la gráfica riesgo-rendimiento, los niveles se ubican de menor a mayor: automatización, racionalización, rediseño y cambios de paradigma.
* Un cambio más amplio suele exigir **mayor coordinación y aprendizaje**.
* La tecnología puede facilitar el cambio, pero los **beneficios dependen de su implementación**.
* La gerencia debe evaluar el impacto en **clientes, personal, costos y continuidad**.
* Pregunta de reflexión: ¿siempre conviene elegir el cambio más radical? ¿Por qué?

---

## 4. Automatización y racionalización de procedimientos

### 4.1 Automatización

* El sistema ejecuta **tareas repetitivas** siguiendo reglas definidas.
* El procedimiento básico puede mantenerse.
* Ejemplos: calcular la nómina, registrar ventas y emitir alertas de inventario.
* **Responsabilidad administrativa:** validar las reglas y atender las excepciones.

### Ejemplo: alerta de inventario

* Caso hipotético: el sistema alerta cuando quedan **menos de 50 cartuchos**; Compras revisa la demanda y autoriza el pedido.
* Una alerta automática agiliza la tarea. Un **pedido automático** también exige **límites y reglas de autorización**.
* Pregunta de reflexión: ¿quién responde si el dato de inventario es incorrecto?

### 4.2 Racionalización de procedimientos

* La organización **revisa cómo trabaja** y elimina duplicidades.
* Define **criterios uniformes** y responsabilidades claras.
* Ejemplo: usar un **solo catálogo de productos** y una **única captura del pedido**.
* El sistema aplica el procedimiento que la organización ha acordado.

### Gestión de la calidad total (TQM) aplicada a la racionalización de procesos

| Principio | Descripción |
|---|---|
| **Enfoque en el cliente** | Satisfacer las necesidades del cliente es la prioridad; los procesos se ajustan para mejorar la calidad del producto o servicio final |
| **Mejora continua** | Impulsa la revisión y optimización constante de los procesos para reducir errores y aumentar la eficiencia |
| **Participación de todos** | Involucra a todos los niveles de la organización en la mejora de procesos, promoviendo una cultura de calidad |
| **Decisiones basadas en datos** | Utiliza datos y análisis para identificar oportunidades de mejora y optimizar procesos de manera objetiva |
| **Gestión por procesos** | Evalúa y mejora cada etapa del proceso para eliminar tareas innecesarias, reducir desperdicios y aumentar la productividad |

* La calidad involucra a **toda la organización** y parte de las necesidades del cliente.
* La mejora continua utiliza **evidencia y participación del personal**.
* Aplicación al caso: revisar reclamos, acordar un procedimiento y comprobar su cumplimiento.
* Pregunta de reflexión: ¿qué dato permitiría comprobar que el cliente recibe un mejor servicio?

### Six Sigma y el ciclo DMAIC

| Fase | Descripción |
|---|---|
| **Definir** | Precisar el problema y el resultado esperado |
| **Medir** | Conocer el desempeño inicial |
| **Analizar** | Identificar causas con evidencia |
| **Mejorar** | Aplicar y probar cambios |
| **Controlar** | Verificar que la mejora se mantiene |

### Ejemplo: racionalizar un pedido

| Antes | Después |
|---|---|
| Ventas y Bodega registran el mismo pedido en archivos distintos | Una sola captura, códigos uniformes y validación de disponibilidad |
| Responsabilidades poco claras | Ventas registra, Bodega confirma y Compras atiende faltantes |

* La mejora elimina duplicidades y aclara responsabilidades, además de usar tecnología.

---

## 5. Rediseño del proceso y cambio de paradigma

### 5.1 Rediseño del proceso de negocio

* La organización **reconsidera el proceso completo** para mejorar su desempeño.
* Puede cambiar la secuencia de trabajo, las funciones y la coordinación entre áreas.
* La gerencia **define el objetivo y evalúa riesgos** antes de implementar.
* Ejemplo: integrar **pedido, reserva, despacho y seguimiento** en un solo flujo.

### Ejemplo: FashionNow

* **Contexto:** FashionNow, tienda de ropa, gestionaba inventario y ventas manualmente, causando errores y demoras.

| Situación inicial | Propuesta |
|---|---|
| Ventas, Bodega y Entregas trabajan por separado | Reservar inventario al confirmar el pedido y coordinar el despacho con un **responsable del proceso** |
| Gestión manual de inventario y ventas | Sistema de gestión de inventarios automatizado, sistema de ventas digital (**POS**) y análisis de datos con **BI** |

* **Beneficios esperados:** menos reprocesos y entregas más oportunas. Deben **medirse tras la implementación**.

### 5.2 Cambio de paradigma

* La racionalización y el rediseño contemplan solamente **partes parciales** de las organizaciones.
* La incorporación de S.I. puede afectar el diseño de **toda la organización**.
* El cambio de paradigma es la **forma más radical** de cambio organizacional.
* La organización **redefine cómo crea y entrega valor**: puede cambiar su modelo de ingresos, sus canales y la relación con el cliente.
* Su alcance supera la mejora de una tarea o un proceso aislado.
* **Digitalizar documentos**, por sí solo, no demuestra este nivel de cambio.

### Ejemplo: un nuevo modelo de servicio

| Situación inicial | Propuesta |
|---|---|
| Una clínica ofrece únicamente consultas presenciales individuales | Servicio de **seguimiento remoto por suscripción**, con atención coordinada y monitoreo continuo |

* Cambian la oferta, los ingresos y la relación con el paciente.
* La viabilidad requiere evaluar **calidad de atención, acceso, privacidad y regulación aplicable**.

---

## 6. Actividad 1: decisiones de cambio

* Un mismo problema puede admitir cambios de **distinto alcance**.

### Caso Innovatec

* Caso hipotético: una distribuidora recibe pedidos por correo y teléfono.

| Aspecto | Situación |
|---|---|
| **Coordinación entre áreas** | Ventas promete existencias sin confirmación de Bodega; Compras recibe solicitudes duplicadas |
| **Personas y responsabilidades** | El personal teme perder funciones y nadie ha definido quién valida los datos |

* La gerencia propone **comprar un sistema** para resolver el problema.

### Propuesta del equipo

* **Duración:** 20 minutos. **Formato:** equipos de 4. **Entregable:** una hoja.
* **Roles:** coordinación, análisis, registro y vocería.

| Paso | Tarea |
|---|---|
| **01** | Identificar dos problemas y sus causas probables |
| **02** | Proponer un cambio y clasificarlo con una justificación |
| **03** | Asignar un responsable y una acción de capacitación |
| **04** | Definir un indicador y cómo se obtendrán sus datos |

---

## 7. Etapas del desarrollo de sistemas

| N.º | Etapa | Decisión o evidencia |
|---|---|---|
| **01** | **Análisis** | Problema y requisitos |
| **02** | **Diseño** | Solución propuesta |
| **03** | **Construcción o configuración** | Solución operativa |
| **04** | **Pruebas** | Evidencia de funcionamiento |
| **05** | **Conversión** | Transición al nuevo sistema |
| **06** | **Mantenimiento** | Continuidad y mejora |

* Las etapas **pueden repetirse**. La **seguridad** y la **participación de usuarios** atraviesan todo el ciclo.

### 7.1 Análisis de sistemas

* Identifica el **problema, sus causas y las necesidades** de los usuarios.
* Examina procesos actuales, datos y restricciones.
* Evalúa **viabilidad económica, técnica y organizacional**.
* **Resultado:** requisitos priorizados y alcance acordado por las áreas involucradas.

### Un requisito que se puede comprobar

| Elemento | Ejemplo |
|---|---|
| **Necesidad** | Evitar promesas de entrega sin inventario |
| **Requisito** | Al confirmar un pedido, el sistema debe verificar existencias y registrar la reserva |
| **Criterio de aceptación** | Con inventario insuficiente, impide confirmar y muestra el faltante |

* Práctica en parejas (3 minutos): redactar otro requisito para Innovatec.

### 7.2 Diseño de sistemas

* Define **cómo la solución responderá a los requisitos**.
* Incluye procesos, datos, interfaces, accesos e integración.
* La gerencia y los usuarios validan responsabilidades y reglas de negocio.
* **Resultado:** una propuesta que permite construir o configurar la solución.

### Diseño: responsabilidades y permisos

| Área | Responsabilidad |
|---|---|
| **Ventas** | Registra pedidos y consulta disponibilidad |
| **Bodega** | Confirma reservas y despachos |
| **Compras** | Gestiona solicitudes de abastecimiento |
| **Gerencia** | Aprueba excepciones según límites acordados |

* Pregunta de reflexión: ¿qué riesgo aparece si cualquier persona puede modificar existencias?

### 7.3 Construcción y configuración

* El equipo técnico **programa componentes** o **configura una solución adquirida**.
* La organización valida reglas y participa en demostraciones.
* Una **configuración incorrecta** puede producir errores aunque el software funcione.
* **Resultado:** una versión disponible para pruebas.

### El papel del área administrativa

* El equipo presenta una regla que permite **pedidos sin existencias**: Ventas la considera útil, Bodega advierte que generará incumplimientos.
* La **gerencia debe decidir** cómo tratar pedidos pendientes y comunicar la regla.
* Pregunta de reflexión: ¿qué evidencia necesita para resolver el desacuerdo?

### 7.4 Pruebas

| Tipo de prueba | Descripción |
|---|---|
| **Unitarias** | Verifican componentes individuales |
| **Integración** | Verifican la interacción entre componentes |
| **Sistema** | Verifican la solución completa |
| **Aceptación** | Los usuarios comprueban los requisitos acordados |

* La organización decide si la evidencia permite **iniciar la operación**.

### Una prueba de aceptación

| Elemento | Ejemplo |
|---|---|
| **Escenario** | 8 unidades disponibles y 10 solicitadas |
| **Acción** | Intentar confirmar el pedido |
| **Resultado esperado** | El sistema bloquea la confirmación y muestra un faltante de 2 |
| **Evidencia** | Registro del resultado, fecha y persona que validó |

* Pregunta de reflexión: ¿qué caso adicional probarían antes de aprobar el sistema?

### 7.5 Conversión: estrategias de transición

| Estrategia | Descripción |
|---|---|
| **Directa** | Sustituir el sistema anterior en una fecha |
| **Paralela** | Operar ambos sistemas durante un período |
| **Piloto** | Comenzar en una unidad o grupo |
| **Por fases** | Incorporar funciones o áreas progresivamente |

* La elección depende de **riesgos, recursos y continuidad del servicio**.

### Una transición justificada

* Innovatec tiene **tres sucursales** y no puede detener despachos.
* **Opción:** iniciar un **piloto en una sucursal** y evaluar resultados antes de ampliar.
* **Plan:** validar datos, capacitar usuarios y definir soporte y recuperación.
* El equipo debe establecer **criterios para continuar, corregir o detener** la expansión.

### 7.6 Mantenimiento

| Tipo | Descripción |
|---|---|
| **Correctivo** | Resolver fallos |
| **Adaptativo** | Responder a cambios del entorno |
| **Perfectivo** | Mejorar utilidad o desempeño |
| **Preventivo** | Reducir problemas futuros |

* La organización prioriza solicitudes y verifica que los cambios **no afecten la operación**.

### Resultados después de implementar

* **Indicador:** porcentaje de pedidos completos = pedidos completos / pedidos despachados × 100.
* **Fuente:** registro de pedidos y despachos. **Responsable:** jefatura de Bodega.
* **Comparación:** desempeño inicial y resultados posteriores en **períodos equivalentes**.
* Una mejora observada requiere **analizar causas y condiciones** antes de atribuirla al sistema.

---

## 8. Enfoques y herramientas de desarrollo

* El ciclo de vida, el modelado y las herramientas cumplen **funciones distintas**.

### 8.1 Modelado estructurado

* Representa **procesos, entradas, salidas y flujos de datos**.
* Ayuda a comprender dónde se genera y utiliza la información.
* El equipo administrativo valida que el modelo **refleje el trabajo real**.
* Este enfoque no obliga a utilizar exclusivamente una secuencia en cascada.

### 8.2 SDLC: ciclo de vida del sistema

* Organiza el **desarrollo, la operación y la evolución** del sistema.
* Existen modelos **secuenciales, iterativos e incrementales**.
* La **cascada** es una forma de organizar las etapas, no un sinónimo de SDLC.
* Cada proyecto requiere evidencias, responsables y criterios de aprobación adecuados.

### Secuencial o iterativo

| Enfoque | Descripción |
|---|---|
| **Secuencial** | Planifica etapas sucesivas y requiere gestionar cambios al alcance |
| **Iterativo** | Revisa la solución mediante ciclos de aprendizaje |
| **Incremental** | Entrega funcionalidades en partes |

* La elección depende de **incertidumbre, riesgos y participación disponible**.
* Pregunta de reflexión: ¿qué enfoque conviene si los usuarios aún no conocen sus necesidades?

### 8.3 Desarrollo orientado a objetos

* Modela entidades mediante **objetos con estado y comportamiento**.
* Ejemplos: Cliente, Pedido y Producto.
* Puede facilitar la **reutilización** y la organización del software.
* Los cambios en un objeto pueden afectar a otros; el equipo debe evaluar sus **dependencias**.

### Del negocio al modelo

| Elemento | Ejemplo (objeto Pedido) |
|---|---|
| **Atributos** | Número, fecha y estado |
| **Acciones** | Confirmar, cancelar y registrar despacho |
| **Regla administrativa** | Un pedido despachado requiere un procedimiento de devolución |

* Pregunta de reflexión: ¿qué área valida esta regla y qué información necesita?

### 8.4 Herramientas CASE

* Apoyan actividades de **ingeniería de software**.
* Pueden facilitar modelado, documentación y consistencia entre artefactos.
* Algunas permiten **generar código** o revisar modelos.
* La organización debe evaluar utilidad, capacitación y compatibilidad. **La herramienta no sustituye la validación del negocio.**

### Una representación para acordar el proceso

* El equipo técnico modela la gestión de pedidos; Ventas y Bodega revisan responsables, decisiones y excepciones.
* Una diferencia entre el modelo y la práctica señala un **punto que debe resolverse**.
* Pregunta de reflexión: ¿qué puede ocurrir si la organización aprueba un modelo que nadie entiende?

---

## 9. Alternativas para crear o adquirir sistemas

* La organización compara opciones según **necesidades, riesgos y capacidad**.

### 9.1 Prototipado

* Construye una **representación preliminar** para explorar requisitos.
* Puede ser desechable o evolucionar hacia una solución.
* Los usuarios prueban tareas y comunican dificultades.
* La gerencia define el objetivo, el alcance y el criterio para terminar la revisión.

### Práctica: prototipo en papel

* **Duración:** 5 minutos. **Formato:** en parejas.

| Paso | Tarea |
|---|---|
| **01** | Dibujar una pantalla para registrar un pedido con hasta 5 campos |
| **02** | Otra pareja intenta registrar un pedido y señala una dificultad |
| **03** | Anotar un cambio y el requisito que lo justifica |

* Un prototipo visual **no demuestra** seguridad, capacidad ni funcionamiento completo.

### 9.2 Desarrollo por usuarios finales

* Usuarios del negocio crean soluciones con **herramientas accesibles**.
* Puede resolver necesidades pequeñas con rapidez.
* Requiere **responsables, permisos, documentación y soporte**.
* El área de TI debe participar cuando existen **datos sensibles, integraciones o dependencia operativa**.

### Una solución con gobierno

* Caso hipotético: Ventas crea una aplicación para registrar oportunidades comerciales.
* Antes de usarla, acuerda quién **administra accesos y respalda la información**; también define soporte, documentación y continuidad si cambia su creador.
* Pregunta de reflexión: ¿cuándo una solución local debería convertirse en un proyecto institucional?

### 9.3 Outsourcing y paquetes de software

| Alternativa | Descripción |
|---|---|
| **Paquete de software** | Adquirir software existente y configurarlo |
| **Outsourcing** | Encargar servicios de desarrollo, implementación o soporte |

* Estas opciones pueden **combinarse**.
* La organización **conserva la responsabilidad** de definir requisitos y supervisar resultados.

### Criterios para elegir una alternativa

| N.º | Criterio |
|---|---|
| **01** | **Ajuste** a requisitos y procesos de la organización |
| **02** | **Costo total:** adquisición, implementación, capacitación y operación |
| **03** | **Seguridad, integración** y posibilidad de recuperar los datos |
| **04** | **Soporte, continuidad** y dependencia del proveedor |

* Ninguna opción garantiza por sí sola menor costo o implementación más rápida.

### 9.4 Desarrollo rápido de aplicaciones (RAD)

* Busca **ciclos rápidos** con prototipos y participación frecuente de usuarios.
* Requiere disponibilidad para validar y un **alcance manejable**.
* La rapidez depende de recursos, integración y complejidad.
* La organización debe conservar **pruebas, seguridad y documentación** necesarias.

---

## 10. Actividad 2: comité de decisión

* **Duración:** 25 minutos. **Formato:** equipos de 4. **Caso:** Innovatec. **Entregable:** una hoja (recomendación, responsable, riesgo principal e indicador).
* **Exposición:** 2 minutos por equipo si el tiempo lo permite.

| Paso | Tarea |
|---|---|
| **01** | Comparar **desarrollar**, **adquirir un paquete** y **contratar servicios externos** |
| **02** | Elegir una opción usando **tres criterios** y declarar los supuestos |
| **03** | Proponer **transición, capacitación y dos pruebas de aceptación** |

---

## 11. Cierre: una decisión con evidencia

* **Respuesta individual:** ¿qué cambiaría en el proceso, quién lo lideraría y cómo comprobaría el resultado?
* **Intercambio:** las personas intercambian respuestas y revisan si la justificación relaciona **organización y sistema**.

| Criterios de revisión |
|---|
| Diagnóstico |
| Coherencia de la decisión |
| Responsabilidades |
| Evidencia |

---
