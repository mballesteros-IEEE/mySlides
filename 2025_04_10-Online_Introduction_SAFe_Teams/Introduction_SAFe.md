# SAFe for Teams 6.0 – Apuntes por Manuel Ballesteros

## 1. Introducción a SAFe

### 1.1 Scaled Agile Framework (SAFe)
SAFe (Scaled Agile Framework) es un marco para escalar la Agilidad a nivel empresarial. Proporciona patrones y prácticas que permiten a múltiples equipos ágiles **alinearse y colaborar** en la entrega de valor, manteniendo los principios Lean y Agile ([ Valores y principios de Scaled Agile Framework (SAFe) | Atlassian ](https://www.atlassian.com/es/agile/agile-at-scale/what-is-safe#:~:text=A%20medida%20que%20las%20empresas,Portfolio%20SAFe%20y%20Full%20SAFe)). SAFe combina ideas de Lean (minimizar desperdicios, enfoque en valor), desarrollo ágil de software y pensamiento sistémico, para ayudar a organizaciones a **responder rápidamente al cambio** y ser más competitivas en la era digital. ([SAFe Glossary - Scaled Agile Framework](https://framework.scaledagile.com/glossary?lang=es#:~:text=%2A%20,medida%20de%20predictibilidad%20del%20ART))

SAFe se representa mediante el “**Big Picture**”, un diagrama que muestra todos los niveles, roles, eventos y flujos de trabajo del marco. Existen configuraciones de SAFe para distintos contextos: Essential (el núcleo para la mayoría de implementaciones), Large Solution, Portfolio y Full SAFe. Todas comparten un nivel esencial donde operan los **Equipos Ágiles** y los **Trenes de Liberación Ágil (ART)**, que son los elementos clave para entregar valor continuamente.

**Equipos Ágiles:** En SAFe, un Equipo Ágil es un grupo multifuncional de ~10 personas o menos, con todas las habilidades necesarias para definir, construir, probar y entregar valor al cliente. Son similares a un equipo Scrum estándar (desarrolladores, testers, etc., con un Product Owner y un Scrum Master), capaces de entregar un incremento de producto terminado en cada iteración.

**Agile Release Train (ART):** El Tren de Liberación Ágil (ART) es un “equipo de equipos” – un conjunto de equipos ágiles (5 a 12 equipos, ~50-125 personas) que trabajan juntos en la **misma cadencia** para entregar una o más **Soluciones** (productos o servicios) de forma incremental  . Un ART opera como una unidad alineada a una **misión y visión comunes**, con un backlog común de programa. Todos los equipos de un ART sincronizan sus iteraciones y realizan planificación en conjunto (PI Planning) para coordinar entregas. El ART es la  de entrega en SAFe, asegurando **alineación** entre equipos y **entregas integradas** de mayor valor que la suma de las partes.

SAFe promueve cuatro **Valores Fundamentales** que definen su cultura: **Orientación (Alignment)**, **Calidad Incorporada (Built-In Quality)**, **Transparencia (Transparency)** y **Ejecución del Programa (Program Execution)**. Estos valores apoyan la colaboración eficaz; por ejemplo, *Calidad incorporada* enfatiza que no se debe sacrificar calidad por velocidad, y *Transparencia* implica visibilidad de progresos e impedimentos para generar confianza. *Orientación* (alineación) asegura que todos trabajen hacia objetivos comunes, y *Ejecución del programa* destaca la importancia de cumplir con la entrega de valor planificada.

### 1.2 Las siete competencias fundamentales de la Agilidad Empresarial
SAFe define siete **Competencias de Agilidad Empresarial** que las organizaciones deben desarrollar para lograr **Business Agility** (agilidad en el negocio). ([¿CÓMO FUNCIONA UN PI EN SAFE? - Blog Adaptworks](https://blog.adapt.works/como-funciona-un-pi-en-safe/#:~:text=Esto%20se%20hace%20como%20parte,confiabilidad%20de%20la%20pr%C3%B3xima%20IP)) Estas agrupan prácticas y mentalidades clave necesarias para prosperar en entornos complejos. Las siete competencias son:

- **Liderazgo Lean-Agile:** Líderes que adoptan mentalidad Lean-Agile, promueven los valores y principios y son ejemplos a seguir en la transformación.
- **Agilidad de Equipo y Técnica:** Equipos ágiles altamente efectivos con prácticas técnicas de calidad (por ejemplo, integración continua, test-driven development) y habilidades para entregar valor continuamente.
- **Entrega Ágil de Producto:** Enfoque en entregar soluciones valiosas de forma continua al cliente, incluyendo la orientación al cliente, *DevOps* y la gestión de productos con enfoques ágiles.
- **Entrega de Soluciones Empresariales:** Habilidad para construir soluciones de gran escala (a nivel de programa y solución) de forma ágil, coordinando múltiples ARTs y proveedores si es necesario.
- **Gestión Lean de Portafolio:** Aplicación de principios Lean para alinear la ejecución con la estrategia empresarial, mediante la gestión de inversiones (épicas, presupuestos) de forma ágil y con gobierno ligero.
- **Agilidad Organizacional:** Capacidad de la organización para adaptarse rápidamente, optimizando procesos de negocio end-to-end y respondiendo al cambio más allá del desarrollo de TI (incluye áreas de negocio).
- **Cultura de Aprendizaje Continuo:** Fomentar un entorno de **mejora constante**, innovación y aprendizaje, donde se experimenta, se aprende de los errores y se comparte el conocimiento abiertamente.

Estas competencias sirven de guía para *medir y crecer* en la transformación Lean-Agile. Por ejemplo, **Agilidad de Equipo y Técnica** se ve directamente reflejada en los equipos SAFe: su habilidad para entregar incrementos de valor con calidad cada iteración. La **Entrega Ágil de Producto** enfatiza estar *centrados en el cliente* y habilitar una entrega continua (por medio de pipeline de entrega continua y DevOps). Cada competencia tiene prácticas específicas y evaluaciones (assessment) que permiten a la organización identificar áreas de mejora, reforzando la idea de mejora continua.

### 1.3 La Mentalidad Lean-Agile y los Valores Fundamentales de SAFe
En el corazón de SAFe está la **Mentalidad Lean-Agile**, una combinación de principios Lean y valores ágiles que guían la forma de pensar y comportarse. Esta mentalidad se suele ilustrar con la “**Casa Lean**” y los valores del Manifiesto Ágil:

- **Casa Lean:** Es una metáfora de SAFe que representa  **“Valor”** para el cliente como objetivo final. Sus pilares son **Respeto por las personas y cultura**, **Flujo (Flow)**, **Innovación** y **Mejora Implacable (Relentless Improvement)**, sostenidos todos por el liderazgo Lean-Agile. La idea es que, para lograr entregas ágiles a gran escala, la organización debe *construir calidad* en cada paso, fomentar la inno  rar los procesos y el produc esto Ágil:** Aunque originalmente concebido para equipos de desarrollo, sus valores (individuales e interacciones sobre procesos, software funcionando sobre documentación extensiva, colaboración con el cliente sobre negociación contractual, respuesta al cambio sobre seguir un plan) también se aplican a gran escala. SAFe extiende estos valores a nivel de programa y portafolio.

Adoptar la mentalidad Lean-Agile implica **aceptar el cambio**, enfocarse en entregar valor rápidamente y eliminar desperdicios. Por ejemplo, un principio Lean es limitar el trabajo en curso (WIP) para mantener el flujo de valor; un valor ágil es la colaboración con el cliente. En SAFe, esto se traduce a prácticas concretas como **reuniones de sincronización periódicas**, ciclos cortos de entrega e involucrar regularmente a los stakeholders para feedback.

Los **Valores Fundamentales de SAFe** (alineación, calidad incorporada, transparencia y ejecución del programa) ya mencionados complementan esta mentalidad. Estos valores crean la cultura necesaria para que las prácticas funcionen. Por ejemplo, la **Calidad Incorporada** significa que la calidad no es negociable: todos los equipos definen claramente “qué significa terminado” (Definition of Done) para cada actividad o elemento, e incorporan prácticas de calidad en todo el proceso . SAFe identifica cinco dimensiones clave de calidad incorporada: *Flujo, Calidad de Arquitectura y Diseño, Calidad del Código, Calidad del Sistema y Calidad de la Publicación* . Esto se traduce en hacer pruebas desde el inicio, automatizar entregas, refactorizar cuando sea necesario, y asegurar que cada incremento cumple criterios de calidad antes de considerarse “done”.

En resumen, la mentalidad Lean-Agile y los valores de SAFe crean un **marco cultural** donde los equipos pueden innovar, aprender y entregar valor de forma sostenible. Un practicante de SAFe debe internalizar esta mentalidad para aplicar efectivamente las técnicas y prácticas en el día a día.

### 1.4 Los principios de SAFe
SAFe está sustentado por **10 Principios Lean-Agile** que orientan la toma de decisiones y las prácticas a todos los niveles. Estos principios son universales en SAFe 6.0 y derivan de Lean, Agile, sistemas de desarrollo de producto y gestión del flujo. A continuación se listan de forma resumida:

1. **Tomar una perspectiva económica:** Las decisiones de desarrollo (priorizar, secuenciar trabajo) deben considerar el impacto económico: entregar pronto para evitar costes de retraso, operar con presupuestos Lean, etc.
2. **Aplicar pensamiento sistémico:** Optimizar el sistema completo en lugar de subóptimos locales. Ver la solución, el flujo de valor y la organización como un todo interconectado.
3. **Asumir variabilidad; preservar opciones:** Dado que al inicio hay incertidumbre, mantener múltiples opciones de diseño y requerimientos el mayor tiempo posible, y converger basándose en evidencia (no “apostarlo todo” a una sola idea temprana).
4. **Construir de forma incremental con ciclos de aprendizaje rápidos e integrados:** Entregar valor en incrementos cortos, recibiendo feedback frecuente (integración y pruebas frecuentes) para ajustar. Esto minimiza riesgo y permite aprender a medida que se avanza.
5. **Basear hitos en evaluación objetiva de sistemas funcionando:** Los hitos (milestones) deben basarse en tener algo funcional que evaluar, no solo documentos o planes. Ejemplo: **PI Milestones** se basan en demostrar un sistema integrado en el *System Demo* de PI, donde se evalúa objetivamente el progreso .
6. **Visualizar y limitar el WIP, reducir el tamaño de lote, y gestionar la longitud de cola:** Tres principios Lean de *flujo*: Limitar el trabajo en curso para evitar sobrecarga, entregar en lotes pequeños para acelerar feedback y reducir riesgos, y gestionar las colas (backlogs) para evitar tiempos de espera largos. Esto mejora la **fluidez** con que las unidades de valor atraviesan el sistema.
7. **Aplicar cadencia, sincronizar con planificación inter-dominio:** Usar una **cadencia** fija (ritmo de tiempo, e.g. iteraciones de 2 semanas, PIs de 10 semanas) para convertir eventos impredecibles en previstos, y sincronizar múltiples equipos con ciclos comunes (por ejemplo, todos los equipos comienzan y terminan iteraciones al mismo tiempo) . La planificación periódica conjunta (PI Planning) actúa como un latido que sincroniza a todos con la misma misión.
8. **Desbloquear la motivación intrínseca de los trabajadores del conocimiento:** En vez de control rígido, dar autonomía a los equipos, propósito claro y ambiente para maestría. Equipos autoorganizados motivados producirán mejores resultados. Por ejemplo, incluirlos en la toma de decisiones de estimación, planificación y mejora incrementa compromiso.
9. **Descentralizar la toma de decisiones:** Decisiones frecuentes y de bajo impacto deben ser tomadas localmente por equipos (para velocidad y contexto), mientras que decisiones estratégicas o de alto impacto se centralizan prudentemente. Esto reduce colas de aprobación y empodera a los equipos para actuar rápido.
10. **Organizarse alrededor de valor:** Estructurar la organización (equipos, ARTs) en torno a los **Flujos de Valor** que entregan a los clientes, en vez de en silos funcionales. Así, los equipos multidisciplinarios pueden entregar valor de principio a fin sin depender de pasos externos. Un ART corresponde típicamente a un flujo de valor de desarrollo, asegurando que todas las habilidades necesarias para entregar valor en ese flujo están dentro del tren.

Estos principios no son meras teorías, sino guías prácticas. Por ejemplo, el principio 6 (limitar WIP, etc.) se refleja en que los equipos SAFe utilizan tableros Kanban o Scrum para limitar trabajo y prefieren historias pequeñas; el principio 7 (cadencia) se observa en que **todas las iteraciones duran lo mismo en un ART** y se sincronizan eventos como la *Scrum of Scrums* semanal. Un equipo SAFe efectivo entiende y aplica estos principios en su trabajo diario, lo que conduce a una mejor toma de decisiones incluso ante situaciones no cubiertas explícitamente por las prácticas.

## 2. Formar Equipos Ágiles como un Tren de Liberación Ágil

### 2.1 Formación de Equipos Ágiles multifuncionales
En SAFe, la base de la pirámide son los **Equipos Ágiles**. Cada equipo ágil es *multifuncional* (cross-functional) y autoorganizado, capaz de entregar incrementos de valor por sí mismo. Idealmente cuentan con todos los roles necesarios: desarrolladores, testers, especialistas si aplica (UX, DevOps, etc.), trabajando juntos en todas las fases desde la definición hasta la entrega de una historia de usuario. Un equipo típico tiene entre 5 y 11 miembros. Según SAFe, hasta 10 es un buen número para mantener eficiencia de comunicación .

Los equipos se organizan en torno a **productos o componentes** específicos de la solución. Pueden seguir marcos Agile como *Scrum* o *Kanban* (o una combinación) según qué encaje mejor a su trabajo, pero todos comparten el mismo ritmo de iteraciones para poder sincronizarse. Un equipo Agile en SAFe tiene dos roles clave adicionales a los miembros desarrolladores: el **Product Owner (PO)** y el **Scrum Master/Team Coach**.

La **formación de equipos** pone énfasis en que cada equipo tenga una identidad clara (nombre, objetivo común, área del producto sobre la que trabaja) y en asignar las personas con las habilidades complementarias adecuadas. Por ejemplo, un equipo que desarrolla una aplicación móvil debería incluir desarrolladores de frontend, un diseñador UI/UX, y testers con conocimiento móvil, asegurando que pueden entregar una funcionalidad completa sin depender de otro equipo para completar su trabajo. Durante una implementación SAFe, a menudo se realizan talleres de Team Building para establecer estos equipos estables y sus formas de trabajo.

Es importante resaltar que en SAFe los equipos son **responsables de la calidad** de lo que entregan. Adoptan prácticas técnicas de calidad (QA incorporado en el equipo) como parte de la filosofía de *“Calidad incorporada”*. Cada equipo define su **Definition of Done** para historias e iteraciones, garantizando que no se pase trabajo “a medio terminar” al siguiente ciclo. Los equipos multifuncionales facilitan esto, pues al tener testers y devs juntos, las pruebas se realizan concurrentemente con el desarrollo dentro de la iteración.


#### 🧩 Matriz de roles clave en SAFe

| Rol                      | Nivel        | Responsabilidades clave                                                                 |
|--------------------------|--------------|------------------------------------------------------------------------------------------|
| Product Owner (PO)       | Equipo       | Gestionar backlog de equipo, representar la voz del cliente, priorizar trabajo          |
| Scrum Master / Team Coach| Equipo       | Facilitar eventos ágiles, remover impedimentos, promover mejora continua               |
| Product Manager          | Programa     | Definir visión, priorizar Features, gestionar backlog de programa                       |
| Release Train Engineer   | Programa     | Facilitar PI Planning, coordinar equipos, remover impedimentos entre equipos            |
| System Architect         | Programa     | Definir arquitectura técnica, guiar decisiones técnicas y coordinar habilitadores       |
| Business Owner           | Programa     | Asegurar ROI, validar prioridades de negocio, participar en PI Planning y demos         |


### 2.2 Roles de Scrum Master / Team Coach y Product Owner
Cada Equipo Ágil en SAFe tiene un **Product Owner (PO)** y un **Scrum Master** (a veces denominado **Team Coach** en SAFe 6.0 para equipos Kanban u otros enfoques). Estos roles son fundamentales para que el equipo funcione bien y se alinee con el Tren Ágil.

- **Product Owner (PO):** Es el responsable de **maximizar el valor** que produce el equipo. Gestiona el **Backlog del Equipo**: prioriza las historias de usuario y otros ítems (déuda técnica, historias de habilitador, etc.) aseguran ajo más importante se realiza primero. Para más detalle, ver sección 2.2 sobre equipos ágiles.. En ejecución, aprueba que las features cumplen los criterios una vez integradas.
  - **System Architect/Engineering:** Provee guía técnica y de arquitectura para el ART. Define la arquitectura global de la solución, normas técnicas, interfaces entre componentes/equipos, y trabaja con equipos para asegurar que el diseño técnico es consistente y sostenible. Puede crear *Enabler Epics/Features* para abordar riesgos técnicos o asegurar infraestructura. Participa en PI Planning explicando aspectos técnicos y en el desarrollo ayudando a resolver problemas de diseño.
  - **Business Owners:** Ya mencionados, son los ejecutivos o stakeholders de negocio clave que están “sponsoreando” el ART. Aseguran que el trabajo del ART está alineado con las necesidades del negocio, participan en PI Planning aprobando objetiv  ocio*, y en la validación de que lo entregado genera el impacto esperado.

- **Eventos del ART:** Aparte de PI Planning (trimestral, por así decir), el ART realiza eventos como:
  - **ART Sync:** combinando Scrum of Scrums y PO Sync como vimos, para coordinar entre iteraciones.
  - **System Demo (Demostración del Sistema):** al final de cada iteración, se integra el trabajo de *todos los equipos* y se presenta un demo del sistema completo al ART y stakeholders. Esto brinda feedback objetivo sobre el progreso integrado . (Lo detallaremos en la lección 6).
  - **Inspect and Adapt (I&A):** al final de cada PI, el ART en conjunto realiza un evento de inspección y adaptación, que incluye la Demo del PI (sistema integrado final), revisión de métricas (ej. cumplimiento de objetivos de PI) y un **Taller de resolución de problemas** donde se analizan las principales problemáticas (ej. a través de un análisis de causa raíz) y se identifican acciones de mejora para el próximo PI . Este es el mecanismo formal de mejora continua a nivel del tren.

- **Governanza ligera pero presente:** El ART equilibra autonomía con alineación. Los equipos son autónomos en cómo cumplir sus Objetivos de PI, pero deben colaborar en las dependencias (reflejadas en un **Program Board** tras PI Planning, que visualiza qué equipo entrega qué feature en qué iteración y qué dependencias existen ). Los Business Owners revisan periódicamente el progreso (por ejemplo, mid-PI check, o asistiendo a System Demos) para garantizar que el tren se mantiene en rumbo hacia la *visión*.

Como ejemplo, imagine un ART desarrollando un nuevo producto de banca móvil. Tendrá varios equipos (uno de frontend app, otro de backend servicios, otro de seguridad, etc.). Cada equipo trabaja su parte, pero todos deben entregar juntos una experiencia funcional. En PI Planning acuerdan cómo las próximas funciones (features) – por ejemplo “Depositar cheque vía foto” – serán divididas: el equipo app hace la interfaz para fotografiar, el equipo backend crea el servicio de validar cheque, etc. Definen dependencias (backend entrega API antes de que frontend la integre, quizás en Iteración 2). Durante la ejecución, en las Scrum of Scrums monitorean que esa secuencia va en camino. Al final de la iteración donde integran la funcionalidad, hacen un System Demo para mostrar “Depositar cheque” completo funcionando en la app, recibiendo feedback de Business Owners o incluso usuarios piloto. Al final del PI, evalúan cómo fue el desarrollo de esa y otras features, miden si cumplieron con los objetivos, y deciden mejoras (tal vez descubrieron que la comunicación inter-equipos falló en algo, y acuerdan un nuevo método para próximos PIs). **Eso es operar como un Tren Ágil**: *misma dirección, mismo ritmo, aprendizaje conjunto*.

En resumen, “convertirse en un ART” implica que los equipos dejan de actuar aisladamente y *funcionan sincronizados como una unidad mayor*, con roles y eventos que respaldan la colaboración. El resultado buscado es un incremento sustancial en la **capacidad de entrega de valor** de la organización, ya que se evita la desalineación entre equipos, se reducen tiempos de integración y se logra responder más rápido a las necesidades complejas del cliente.

## 3. Conectarse con el Cliente

### 3.1 Aplicar el Foco en el Cliente y Design Thinking
Una de las piedras angulares de SAFe es la **Centralidad en el Cliente (Customer Centricity)**. Esto significa que todos en el ART – desde los líderes hasta cada miembro de equipo – deben tener empatía con el cliente y un entendimiento claro de sus necesidades. *Conectarse con el Cliente* es adoptar una mentalidad donde las decisiones se toman evaluando cómo impactan al usuario final ([Scaling Agile Practices| Customer Centricity and Design Thinking](https://agilemania.com/customer-centricity-and-design-thinking#:~:text=Scaling%20Agile%20Practices,products%20and%20services%20the)). 

**Foco en el Cliente:** Implica ver al producto a través de los ojos del cliente. SAFe alienta a crear **personas** (perfiles ficticios pero basados en investigación de usuarios) que representen a los usuarios objetivo. Por ejemplo, un ART que desarrolla software de contabilidad puede definir a “Ana, Directora Financiera” como persona y constantemente preguntarse: *¿Esta funcionalidad agrega valor para Ana?*. Se busca comprender las **motivaciones, problemas y deseos** del cliente. Técnicas como entrevistas de usuario, encuestas de satisfacción (NPS), análisis de soporte o feedback continuo ayudan a mantener ese foco. El objetivo es construir *lo que realmente se necesita*, no lo que asumimos en abstracto. 

**Design Thinking:** SAFe incorpora principios de Design Thinking para impulsar la innovación centrada en el usuario. *Design Thinking* es un proceso iterativo de cinco etapas: **Empatizar, Definir, Idear, Prototipar y Testear**. En contexto de SAFe:
- *Empatizar:* Entender profundamente al cliente (como se dijo, usando personas, entrevistas, mapa de empatía).
- *Definir:* Enmarcar claramente el problema o necesidad del cliente que se va a resolver. Ej: “Clientes rurales necesitan hacer depósitos sin sucursal bancaria”.
- *Idear:* Generar múltiples soluciones posibles (lluvia de ideas, workshops), sin limitarse de entrada.
- *Prototipar:* Construir soluciones mínimas (prototipos, maquetas) para explorar esas ideas.
- *Testear:* Validar con clientes reales esos prototipos, recolectando feedback temprano.

En SAFe, Product Management y los Equipos utilizan Design Thinking especialmente en la fase de **Continuous Exploration** del **Pipeline de Entrega Continua**, donde se está explorando qué construir. Por ejemplo, antes de comprometerse a desarrollar una gran Feature, podrían prototipar partes clave y llevarlas a usuarios piloto para ver si resuelven el problema.

El **Customer Journey** (viaje del cliente) es otra herramienta: mapear todos los pasos que un usuario sigue para lograr su objetivo con nuestro producto, identificando “puntos de dolor” donde hay oportunidad de mejora. Esto guía la priorización de nuevas funcionalidades.

La mentalidad centrada en cliente también se refleja en prácticas cotidianas:
- Los **Product Owners** actúan como *“la voz del cliente”* en el equipo, recordando el *porqué* detrás de cada historia. 
- Criterios de aceptación de historias que incluyan *escenarios de uso reales*.
- Incorporar feedback directo del cliente en cada Iteration Review o System Demo (cuando es posible incluir usuarios reales o representantes de negocio que conocen bien al cliente).
- Métricas centradas en cliente: no solo medir throughput de equipos, sino métricas de valor como satisfacción del usuario, adopción de funcionalidades, tasa de éxito en tareas de usuario, etc.

Adoptar Customer Centricity puede requerir un cambio cultural: los equipos de desarrollo aprenden a salir de su enfoque solo técnico y conectarse con el impacto. Se promueve que miembros del equipo participen en sesiones con clientes o vean estudios de usabilidad, para vivenciar los problemas que se están resolviendo.

En resumen, “Aplicar Foco en el Cliente” significa que *el cliente es el centro del universo SAFe*: la definición de qué construir parte de entender al cliente (no de suposiciones internas), y el éxito se mide en términos de valor y satisfacción del cliente. Combinado con *Design Thinking*, SAFe busca garantizar que el ART **construya el producto correcto** – aquel que verdaderamente es deseable por el cliente, factible técnicamente y viable para el negocio.

### 3.2 Reconocer la Visión del producto y los Roadmaps
Para alinear a todos en el ART hacia un objetivo común, SAFe enfatiza la importancia de comunicar una **Visión** clara del producto y apoyarse en **Roadmaps** realistas. Aquí hablamos de conectar al equipo con “el porqué y el hacia dónde” del trabajo que realizan.

**Visión del Producto:** Es una descripción aspiracional del futuro del producto o solución. Suele ser creada por Product Management en colaboración con Business Owners y stakeholders. La visión articula qué problema se pretende resolver, para quién, y cómo será la solución a grandes rasgos. Debe inspirar y dar dirección. Por ejemplo, la visión podría ser *“Proveer la plataforma financiera más confiable y fácil de usar para que pequeños negocios gestionen sus finanzas en cualquier momento y lugar”*. Esta visión guía a todos los equipos en las decisiones grandes y pequeñas – se puede preguntar: *¿esta historia contribuye a la visión?*.

En SAFe, la Visión se comunica en cada **PI Planning** (y se actualiza si es necesario). Suele presentarse a través de un **briefing de visión** que puede incluir:
- Las metas a mediano plazo del producto.
- Principales funcionalidades previstas.
- Diferenciadores competitivos.
- Enfoque en qué valor entregará al cliente.

La Visión se complementa con artefactos como el **Roadmap**.

**Roadmaps:** Un Roadmap es una vista temporal (cronograma a alto nivel) de cómo la solución evolucionará para cumplir la visión. SAFe distingue:
- **Roadmap de PI**: muestra los próximos PIs (a corto plazo, 2-3 PIs típicamente) con las Features o Epics planificadas tentativamente para cada uno. Es un compromiso a corto plazo con algo de detalle.
- **Roadmap a Largo Plazo**: una perspectiva a más largo plazo (6-12 meses o más), con hitos mayormente estratégicos, posiblemente Epics en el horizonte, pero con menor detalle y más sujeta a cambio.

El Roadmap sirve para **alinear expectativas** tanto internamente (equipos) como con stakeholders (ej. otras áreas de la empresa, clientes clave). Por ejemplo, un roadmap puede indicar que en el PI Q3 se planea lanzar la Feature “Deposito mediante foto de cheque”, y en Q4 “Pagos internacionales”, etc. Así los equipos saben el orden de prioridad de las grandes funcionalidades por venir.

Es importante que el roadmap sea **vivo** y se actualice según el feedback y los cambios de mercado – no es un plan fijo inmutable. Aquí entra el concepto Lean de ser adaptable: aunque hay un plan, se revisa en cada PI Planning según los progresos y cambios.

**Relación con Epics:** En SAFe, las iniciativas más grandes (Epics) suelen transcender varios PIs. Una Epic aprobada tendrá una **Hipótesis y un MVP** (Producto Mínimo Viable) definido. El roadmap reflejará cuándo se piensa completar ese MVP e incluso subsecuentes MVPs si la Epic continúa. Por ejemplo, la Epic “Expansión internacional” puede implicar varias Features distribuidas en tres PIs en el roadmap.

**Comunicación al Equipo:** ¿Cómo conecta esto con los equipos? En PI Planning, tras la presentación de visión y roadmap, los equipos tienen contexto para tomar decisiones informadas. Saben no solo lo que toca este PI, sino hacia dónde va el siguiente, lo que les ayuda a pensar en arquitectura, en no hacer soluciones cortoplacistas que bloqueen lo previsto. También les da sentido de propósito: entienden la cadena completa de valor. Un desarrollador podría sentirse más motivado sabiendo que la pequeña parte que hace encaja en un plan mayor de ofrecer una experiencia innovadora al cliente en el próximo año.

Los **Business Owners** y Product Management deben reforzar la visión continuamente. Un buen patrón es iniciar cada Iteration Review o System Demo recordando brevemente la visión o cómo lo mostrado se relaciona a ella (“Esto nos acerca a nuestro objetivo de ser la app más fácil, miren cómo ahora el usuario puede…”) para mantener a todos conectados con el cliente y el negocio.

En síntesis, la Visión y el Roadmap son herramientas para **conectar a los equipos con el “big picture”**: del cliente y el negocio. Aterrizan el enfoque en cliente en un plan tangible. Al reconocer y entender estos artefactos, los equipos trabajan con mayor coherencia estratégica, sabiendo que no solo están cerrando historias en un backlog, sino construyendo paso a paso la visión deseada para los usuarios.

### 3.3 Definir el trabajo para favorecer al Cliente
Traducir la visión y las necesidades del cliente en trabajo realizable requiere definir claramente **qué se va a construir**. En SAFe esto se hace a través de una jerarquía de artefactos: Épicas, Features y Historias, complementados por criterios de aceptación, hipótesis de beneficio, etc. *Definir el trabajo en apoyo al cliente* implica que cada ítem en el backlog esté formulado de manera que preserve la intención de valor para el cliente y sea comprensible para el equipo.

**Épicas (Epics):** Son grandes iniciativas de negocio o tecnología, a menudo a nivel de portafolio, que pueden requerir varios PIs para completarse . Por ejemplo, “Expandir plataforma a Latinoamérica” o “Implementar motor de recomendaciones con IA”. Típicamente se necesita un análisis ligero de estas épicas (Lean Business Case) y aprobación (Go/No Go) por el Portfolio Kanban antes de iniciar. Para SAFe for Teams, no profundizamos en Epics, pero es útil saber que representan el trabajo de muy alto nivel que puede dar lugar a múltiples features. Las épicas tienen un **Epic Owner** que las conduce, y se definen con una **Hipótesis de Epic** (qué valor se espera, criterios de éxito, MVP inicial) . Una vez aprobadas, se descomponen en features que alimentan a los ARTs pertinentes.

**Features:** Una Feature representa una **funcionalidad de la solución que brinda valor de negocio y satisface una necesidad de un stakeholder**, de tamaño lo suficientemente acotado para ser entregada por un ART dentro de un PI . En otras palabras, es un **chunk funcional grande** pero no enorme. Ejemplo: “Depósito de cheque vía foto” en la app bancaria es una Feature. Cada Feature tiene:
- **Beneficio esperado (Benefit Hypothesis):** una breve declaración del beneficio que aportará, para justificar su inversión. Ej: “Esta feature reducirá en 20% las visitas a sucursal, mejorando satisfacción de usuarios remotos”.
- **Criterios de aceptación de la Feature:** condiciones que la feature debe cumplir para ser considerada completa a nivel de solución (puede incluir criterios funcionales y **NFRs** – Non Functional Requirements, como performance, usabilidad, seguridad). Ej: “Debe soportar al menos 10,000 depósitos por hora sin degradación” (NFR de rendimiento).
- Un **tamaño estimado** (en SAFe se suele estimar en puntos de historia agregados o en # de jornadas).
- Posiblemente asociación a una Epic o Capabilidad (si es parte de algo mayor).

Las Features residen en el **Program Backlog**. Durante PI Planning, las features priorizadas para el PI se entregan a los equipos para que las analicen y fragmenten en historias. **Definir bien las Features** es crucial: deben estar centradas en el cliente (“qué hace la solución por el usuario”), no en componentes técnicos. Una manera de expresar features es mediante frases *“Como [persona/rol] quiero [tal funcionalidad] para [tal beneficio]”*, similar a historias de usuario pero a nivel más amplio. Otra es enfocarse en la **habilidad que la solución tendrá** (por ejemplo: “El sistema permite al usuario depositar cheques con la cámara del móvil”). 

**User Stories):** Son la unidad de trabajo a nivel de equipo. Una historia describe una pequeña **pieza de valor** que el equipo puede completar en una iteración o menos, típicamente escrita en formato usuario – objetivo – razón: *“Como [tipo de usuario], quiero [tal capacidad] para [tal fin]”*. Las historias derivan de las features: cada feature se descompone en varias historias que, una vez implementadas, suman la funcionalidad completa de la feature. Por ejemplo, la feature “Depósito de cheque vía foto” puede implicar historias como: “Como usuario, quiero tomar una foto del cheque con la app para iniciar un depósito”, “Como usuario, quiero ingresar el monto del cheque después de fotografiarlo para confirmarlo”, “Como sistema, verificar la legibilidad de la imagen del cheque”, etc. 

Cada historia tiene **Criterios de Aceptación** concretos (condiciones que la historia debe cumplir funcionalmente). Esto asegura que se entienda el *Definition of Done* específico de la historia. Por ejemplo, criterio: “Si la foto del cheque es borrosa, el sistema debe avisar al usuario y permitir tomar otra foto”. Los criterios de aceptación guían las pruebas de la historia y clarifican el alcance.

Se aplican atributos de buena calidad de historias como **INVEST**: Independiente, Negociable, Valiosa, Estimable, Pequeña (Small), Testeable. Historias demasiado grandes se deben **dividir** (split) en más pequeñas sin perder valor.

Además de historias “de negocio” (funcionales), existen **Historias de Enabler (Habilitador)**. Estas son tareas técnicas que habilitan la entrega de futuras valor (ej.: “Refactorizar módulo de autenticación para soportar escalabilidad”, o “Investigar tecnología OCR para cheques” – esta última podría ser un Spike, un tipo especial de historia de exploración). Los Enablers se tratan en backlog junto con las demás, pudiendo tener sus propios criterios de aceptación, pero su valor es indirecto (sirven a la arquitectura, reducir riesgos, mejorar pipeline, etc.). SAFe enfatiza la necesidad de equilibrar trabajo funcional con habilitadores mediante **Capacity Allocation** – dedicar cierta capacidad (porcentaje de esfuerzo) a enablers para no descuidar la “deuda” técnica y la infraestructura.

**Trazabilidad y Prioridades:** Cada nivel se traza con el superior: historias -> feature -> quizá epic. Esto ayuda a mantener **alineamiento con el cliente**. Si un equipo no entiende cómo una historia aporta a la feature, es señal para el PO de clarificar o replantear. La priorización principal ocurre en features (por Product Management usando WSJF). A nivel de equipo, la priorización de historias la maneja el PO, pero normalmente sigue la prioridad de la feature de la que vienen (a menos que internamente requieran secuencia diferente). 

**Refinamiento del Backlog:** Para “definir el trabajo” bien, SAFe prescribe actividades de **Backlog Refinement** periódicas. Cada equipo (incluyendo PO y SM) dedica típicamente un rato cada iteración a refinar historias futuras: discutir los detalles, asegurar que estén entendidas y estimarlas (en puntos de historia). También pueden identificar dependencias o necesidad de enablers con anticipación. Un buen refinamiento incrementa la preparación de las historias (“estar listas” – Definition of Ready) para la siguiente Iteración o PI Planning. Esto eleva la probabilidad de implementar correctamente a la primera lo que el cliente necesita, pues se aclararon dudas de antemano.

**Estimación en equipo:** Los equipos SAFe suelen usar **Estimación relativa** en *puntos de historia* para evaluar el tamaño de historias. Se utiliza Planning Poker u otro método para que todo el equipo participe y llegue a un consenso. SAFe sugiere una guía de calibración: una historia de 1 punto ~ un día de trabajo de una persona (sin interrupciones) como base de referencia, pero lo importante es la comparación entre historias. Estimar ayuda a los equipos a comprender el esfuerzo y a hacer **predictivo** el planning (saben cuántos puntos suelen completar en una iteración – su *velocidad* – y así planifican de acuerdo a esa capacidad).

**Ejemplo concreto:** Supongamos la Feature “Pago de servicios (agua, luz) desde la app”. Product Management la define con beneficio: “facilitar al usuario centralizar pagos – incrementará uso de la app, potencial ingresos por comisiones”. En PI Planning, los equipos la dividen: Equipo Frontend historias sobre UI para ingresar número de cliente de agua, UI para confirmar pago; Equipo Backend historias sobre integrar API del proveedor de agua, procesar respuesta, etc. Cada historia escrita con enfoque usuario o sistema claro y aceptada por el PO. Al implementarse, se valida que cumplen criterios (p. ej. transacción exitosa, error manejado si datos inválidos). Tras varios sprints, la feature se completa y se integra para demo. Los criterios de la feature son probados end-to-end en la System Demo para ver si realmente el usuario pudo pagar su recibo de agua fácilmente.

En conclusión, definir el trabajo para favorecer al cliente significa mantener una **línea de visión clara** desde los requerimientos de alto nivel hasta las tareas diarias del equipo. Usando Épicas, Features y Historias con técnicas ágiles, SAFe asegura que lo que se implementa en cada iteración está directamente ligado a entregar valor que el cliente perciba. Cada desarrollador debe poder entender qué valor al cliente tiene la historia en que trabaja. Si esa conexión se pierde, el riesgo es construir “por construir” y no resolver el problema correcto. Por eso, se insiste tanto en buenas definiciones, ejemplos de aceptación y en la conversación continua PO-equipo sobre el *porqué* de cada ítem.

## 4. Planificar el trabajo

### 4.1 Creación del backlog
El backlog es la lista ordenada de todo el trabajo pendiente por realizar. **Crear y mantener un buen backlog** (tanto de programa como de equipo) es esencial para planificar eficientemente. Un backlog efectivo refleja las necesidades del cliente priorizadas y descompuestas en trozos realizables por los equipos.

A nivel **Programa (ART)**, el **Program Backlog** contiene las **Features** aprobadas y priorizadas que el ART debe implementar para acercarse a la Visión. Product Management es quien gestiona este backlog, priorizando típicamente con técnicas como WSJF (Weighted Shortest Job First: pondera valor, urgencia, tamaño para elegir qué va primero). Antes de cada PI Planning, el Program Backlog se afina para identificar las Features candidatas al próximo PI (normalmente se destaca un *Top 10* de Features). La creación de backlog a este nivel implica:
- Recoger inputs de múltiples fuentes: estrategia de negocio (épicas aprobadas), retroalimentación de clientes (nuevas ideas o mejoras), resultados de I&A (historias de mejora propuestas), *enablers* técnicos necesarios.
- Escribir descripciones claras de Features con hipótesis de beneficio y criterios de aceptación.
- Estimar un tamaño (en puntos o t-shirt sizes) para entender capacidad requerida.
- Priorizar: ordenarlas por WSJF u otra técnica. WSJF, en resumen, calcula un “peso” = (Valor de negocio + Urgencia por oportunidad + Reducción de riesgo o habilitación) / Tamaño (duración). Así, se prefieren trabajos de alto valor y corto plazo sobre grandes y de poco valor.

A nivel **Equipo**, cada equipo tiene su **Team Backlog**, gestionado por el Product Owner. Este backlog incluye:
- **Historias de usuario** derivadas de las Features del Program Backlog (tras PI Planning, el equipo ya incorporó esas historias).
- **Enablers** locales del equipo (ej. deuda técnica que el equipo decide abordar, mejoras internas).
- **Historias de mantenimiento o bugs** si también manejan esas tareas.
- **Historias de mejora** provenientes de retros o I&A (por ejemplo, “automatizar pruebas de X para reducir tiempo en testing” podría ser una historia de mejora técnica).
- **Spikes** (investigaciones) necesarios.

La creación del backlog de equipo sucede en parte durante PI Planning (cuando cada equipo anota qué historias harán de cada Feature) y de forma continua a través del **Refinamiento**. 

**Backlog Refinement:** Los equipos dedican tiempo cada iteración (o antes de PI Planning) a preparar futuros ítems:
- Dividen Features en historias.
- Agregan criterios de aceptación a las historias.
- Estiman las historias en puntos.
- Descubren dependencias entre historias de distintos equipos (ej., “para hacer esta historia necesitamos que el equipo Backend provea un API – crear dependencia explícita”).
- Identifican si alguna historia es muy grande y hay que dividirla antes de comprometerla.
- Priorizan las historias locales según el valor de la Feature madre y las dependencias.

Esto hace que al momento de planificar, las historias ya estén “listas”: bien entendidas, pequeñas y con valor.

**Priorización en el Team Backlog:** El PO normalmente ordena las historias de la siguiente iteración basándose en:
- Prioridad de la Feature (dada por Program Management).
- Dependencias: quizás una historia no es de la Feature más prioritaria, pero hay que hacerla antes porque otro equipo la necesita.
- Tiempo crítico: si cierto enabler debe adelantarse para evitar retrasos luego.
- Capacidad asignada: SAFe recomienda manejar la *Asignación de Capacidad*, es decir, reservar un porcentaje de cada iteración para distintos tipos de trabajo (por ejemplo, 80% funcionalidades nuevas, 20% enablers/defectos). Si eso se aplica, el PO equilibra en el backlog elementos de ambos tipos según ese porcentaje, para no postergar siempre lo técnico ni abrumar de nueva función sin robustez.

**Definición de Ready/Done:** Para asegurar calidad en backlog y en entregas, los equipos y el ART suelen acordar criterios de “Definition of Ready” (DoR) para que una historia o feature pueda ser tomada en una iteración o PI. Ejemplos de DoR: “La historia tiene una descripción clara, criterios de aceptación definidos, está estimada y sin dependencias ocultas”. Esto mejora la planificación porque reduce incertidumbre durante la iteración. La “Definition of Done” (DoD) garantiza que al terminar la historia cumple con calidad (código revisado, pruebas pasadas, documentado si aplica, integrado en build, etc.). Aplicar DoR y DoD consistentemente es parte de *Built-In Quality*.

**Herramientas y Visualización:** Los backlogs se suelen gestionar en herramientas ágiles. Se visualizan con tableros Kanban en diferentes niveles. Por ejemplo, el Program Backlog muchas veces se gestiona con un **Program Kanban** con columnas: Funnel (idea), Análisis, Aprobado, Implementando (en proceso en PI actual), Validando (in progress nearing completion), Done. Cada Feature se mueve por ese flujo. Similarmente, un Team Kanban puede tener el backlog To Do, en progreso, etc. Esta visualización permite ver dónde hay cuellos de botella. Si por ejemplo hay muchas features en análisis pero pocas aprobadas, quizás el equipo de análisis (Product Management) es el cuello de botella.

**Ejemplo:** Supongamos se detecta una necesidad de “Mejorar rendimiento de la aplicación”. Product Management crea una Feature “Reducción del tiempo de carga inicial en 50%”. Identifican valor (mejor retención de usuarios) y estiman esfuerzo mediano. La priorizan para el próximo PI. En backlog de equipo, esta feature se parte en historias: “Optimizar llamadas al servidor en login”, “Implementar caché local de datos frecuentes”, etc., más quizás un spike “Investigar herramienta X de profiling de rendimiento”. El equipo añade esas historias a su backlog, el PO las prioriza junto con otras. Durante la iteración de refinamiento antes del PI, el equipo estima esas historias, ve que para “caché local” necesitarán input del equipo de arquitectura (dependencia), lo anotan. Llegado el PI Planning, ya tienen clarísimo qué historias con qué dependencias propondrán para esa Feature, facilitando la elaboración del plan.

En resumen, la creación del backlog es un proceso continuo de **traducción de necesidades en tareas ordenadas**. Un backlog bien curado refleja *la voz del cliente priorizada por valor*, descompuesta en trozos que los equipos pueden asimilar. Esto sienta las bases para la planificación exitosa: cuando llega la planificación, no se empieza de cero, sino que se basa en un backlog preparado.

### 4.2 Planificación del PI (PI Planning)
La **Planificación de PI** es el evento emblemático de SAFe. Es una reunión de todos los miembros de un ART (equipos + stakeholders clave) que ocurre al inicio de cada Program Increment, con el propósito de **definir un plan conjunto** para las próximas iteraciones (normalmente 4 a 6 iteraciones) del PI. Este evento dura normalmente **dos días** (en persona o virtual), y sigue una agenda estructurada. Según SAFe, PI Planning es un evento cadenciado que involucra a todo el ART y alinea a los equipos y partes interesadas con una misión y visión comunes .

**Objetivos principales de PI Planning:**
- Compartir a todo el ART la **Contexto y Visión**: Entender “hacia dónde vamos” este PI, cuáles son los objetivos del negocio y del producto.
- Que cada equipo planifique qué **Historias** realizará iteración por iteración para cumplir las **Features** (objetivos) asignadas.
- Identificar y resolver las **dependencias** entre equipos durante la planificación, no durante la ejecución.
- Establecer los **Objetivos de PI** de cada equipo (y en conjunto, del ART) y los compromisos para el PI.
- Identificar los **riesgos** y afrontar cómo se manejarán (por ejemplo, con la matriz ROAM).
- Generar alineamiento y compromiso colectivo: todos salen del PI Planning sabiendo qué se espera de ellos y confiando en el plan.

**Antes del PI Planning (preparación):** 
- Product Management prepara el **backlog del programa**: features priorizadas, con valor, con estimaciones aproximadas, etc.
- Se actualiza la **Visión** y se crean **objetivos del PI draft a nivel ART** (temas clave que debe lograr el tren).
- Los **Business Owners** y Stakeholders relevantes se alinean sobre mensajes claves (contexto de negocio actual, hitos).
- Los equipos y POs hacen pre-refinamiento de features si es posible, para llegar con algo de entendimiento previo.
- Logística: reservar lugar físico/virtual, herramientas (ej. mural digital para program board), etc.

**Durante el PI Planning:**
1. **Presentaciones Iniciales:** 
   - *Contexto de negocio:* Un Business Owner o alta dirección presenta la foto grande: cómo está la empresa, mercado, competencia, o cualquier información estratégica que los equipos deban saber (ej: “Nuestro competidor sacó tal función, queremos rebasarlos en X”, o “Tenemos meta de 1 millón de usuarios este año”).
   - *Visión y Top 10 Features:* Product Management presenta la visión del producto/solución y las principales features previstas para el PI, explicando el *qué* y *por qué* de cada una ([](https://www.knowmadmood.com/dam/jcr:f76a6ed3-2bd4-4ced-8dbe-ffd98149d285/SAFe6%20for%20Teams%20(SP).pdf#:~:text=3,y%20liberar%20de%20forma%20continua)). Si aplica, System Architect complementa con cualquier tema de *arquitectura* importante (ej: necesidad de migrar a nube, etc.), y UX puede mostrar *insights de cliente* o prototipos relevantes (Design Thinking contributions).
   - *Planificación de iteración común:* El RTE repasa la agenda del PI Planning, los tiempos, y los objetivos a lograr. También menciona si hay *suposiciones* (ej: “El equipo A estará al 50% por vacaciones, ténganlo en cuenta”).

2. **Breakout por Equipos – Iteración 1:** Tras la apertura, los equipos se separan en mesas (físicas o breakout rooms virtuales). En este primer bloque, cada equipo:
   - Revisa las **Features** que le han sido asignadas o que involucran al equipo.
   - Descompone cada Feature en **Historias** de su backlog (si no lo había hecho).
   - Estima esas historias (si no están estimadas).
   - Decide en qué **Iteración** colocar cada historia. Aquí la premisa es que las primeras iteraciones del PI se llenen con las historias más prioritarias y las dependencias se planifiquen en orden lógico. A menudo empiezan planificando Iteración 1 en detalle.
   - Detecta **dependencias**: “Necesitamos que el equipo X haga Y antes de nuestra historia Z”. Estas se anotan en hojas/cartulinas (en persona) o en sticky notes virtuales, para luego colocarlas en el **Program Board**.
   - Algunos equipos usan una planilla de capacidad: calculan cuántos puntos pueden hacer por iteración (basado en su velocidad histórica, ajustada por cambios de personal o días libres) y verifican que no excedan esa capacidad con las historias seleccionadas.
   - Formulan sus **Objetivos de PI preliminares**: un resumen en lenguaje natural de las metas del equipo este PI. Por ejemplo: “Objetivos equipo A: Implementar módulo de pagos internacionales (Feature X) y mejorar rendimiento en inicio de sesión (Feature Y)”. Se marcan algunos como “estirados” (stretch) si no hay seguridad total de lograrlos.
   - Los **Riesgos y Problemas** identificados se anotan (en un roster de riesgos por equipo).

3. **Revisión de Draft (Plan provisional):** Tras unas horas de breakout, viene una revisión intermedia. Equipos pegan sus **Objetivos de PI provisionales** en la pared y rotan o presentan brevemente al resto:
   - Cada equipo comenta: “Planeamos entregar X, Y, Z; estas son nuestras dependencias; estos riesgos vemos”. 
   - Otras equipos y stakeholders ofrecen feedback. Por ejemplo, si dos equipos tienen una dependencia conflictiva (ambos esperan que el otro haga algo primero), sale a la luz para replanificar.
   - Los Business Owners miran si los objetivos de equipo alinean con la visión global o si falta algo crítico (ej: quizás ninguna equipo mencionó cierta Feature importante -> error de asignación, se discute).
   - Esta sesión destapa incoherencias o suposiciones incorrectas, que luego en el segundo breakout se corrigen.

4. **Breakout por Equipos – Iteración 2+ y ajustes:** Equipos vuelven a planificar con las retroalimentaciones:
   - Ajustan sus planes de iteración: mover historias de una iteración a otra para resolver conflictos de capacidad o dependencias. Completar planificación para todas las iteraciones del PI (excepto IP normalmente, que queda para innovación o buffer).
   - Finalizan sus **Objetivos de PI**, marcando claramente cuáles son **Comprometidos** y cuáles son **Estirados (Stretch)**. Los objetivos estirados son aquellos que el equipo planeará intentar pero no se compromete al 100% (por incertidumbre o dependencia fuerte). Esto gestiona expectativas: solo los comprometidos contarán para evaluar desempeño (predictability) al final.
   - Mitigación de **Riesgos:** Cada riesgo identificado se aborda. SAFe propone usar la matriz **ROAM** para categorizarlos:
     - *Resolved (Resuelto):* el riesgo ya se resolvió, deja de ser preocupación.
     - *Owned (Asumido por Propiedad):* alguien del ART se asigna responsable para darle seguimiento durante el PI ([GESTIÓN DE RIESGOS CON ROAM - Blog Adaptworks](https://blog.adapt.works/es/gestion-de-riesgos-con-roam/#:~:text=,minimizar%20el%20impacto%20del%20riesgo)).
     - *Accepted (Aceptado):* se acepta que no se puede hacer nada al respecto; se asumen las consecuencias si ocurre.
     - *Mitigated (Mitigado):* se ha definido un plan de mitigación o contingencia para reducir impacto/probabilidad .
   - Los riesgos categorizados se suelen pegar en un **ROAM board** visible para todos. Por ejemplo, “Riesgo: retraso en certificación de seguridad” podría ser Owned asignado al Arquitecto para gestionarlo, o “Riesgo: clima podría retrasar envíos – Accepted, nada que hacer”.
   - Completar el **Program Board:** Equipos y RTE plasman en un tablero grande (físico o digital) las Features con sus dependencias en un calendario de iteraciones. Cada iteración (columna) se listan las features entregadas. Flechas o notas indican dependencias entre equipos. Hitos (como fechas límite externas) también se marcan. El Program Board da una vista global que permite ver si el plan es razonable: p.ej. si muchas features caen en la última iteración, es señal de riesgo (carga desequilibrada), o si una dependencia aparece después de la entrega dependiente (orden incorrecto), etc.

5. **Revisiones Finales y Aprobación:** 
   - Cada equipo, uno por uno, presenta su **Plan final** al ART: enumeran sus Objetivos de PI (comprometidos/estirados), destacan las dependencias que tienen y mencionan cualquier cambio de último momento. Exhiben su confianza en el plan.
   - Los Business Owners entonces asignan un **Valor de Negocio (Business Value)** a cada Objetivo de PI de cada equipo, típicamente en una escala de 1 a 10 (donde 10 es extremadamente importante para el negocio). Esto refleja la importancia relativa de ese objetivo para la empresa. Por ejemplo, un objetivo puede ser “Implementar Feature X” y los Business Owners le dan BV=10 si es crítico, u 8 si es importante pero no vital. Este valor no es compromiso de entrega sino una indicación de importancia; servirá al final del PI para evaluar resultados (predictability).
   - Tras escuchar todos los planes, viene la **Votación de confianza (Confidence Vote)**: Cada miembro del ART (todos los que planificaron) vota del 1 al 5 su confianza en que se cumplirán los objetivos del PI (usando “fist of five” por ejemplo). Si la gran mayoría vota 4 o 5, el plan se acepta; si hay muchos 3 o menos, se abre un espacio de discusión de las preocupaciones y eventualmente se ajusta el plan. Se puede volver a votar. Un nivel de confianza por debajo de 3 promedio implica replantear seriamente partes del plan. Idealmente se busca un consenso donde todos tengan suficiente confianza (no necesariamente 5 perfecto, se suele aceptar con mayoría de 4 y 5 y quizá algún 3). Este paso es importante para generar **compromiso real**: todos se sinceran si ven algo inviable ahora, en vez de descubrirlo a mitad del PI.
   - Cuando el plan es aceptado, el RTE lo declara “commit” y suele cerrar el PI Planning con una nota positiva: un resumen, próximos pasos (por ejemplo: “Iteración 1 comienza el lunes, primer Scrum of Scrums el miércoles”), quizás un “PI Planning Retrospective” breve para mejorar el siguiente, y a veces algún tipo de “celebración” breve dado que es un evento intensivo.

**Salidas del PI Planning:**
- **Objetivos de PI aprobados** de cada equipo, con su valor de negocio asignado . Esto se consolida también en un conjunto de **Objetivos del ART** (en esencia la suma de todos los de equipo, a veces resumido).
- **Program Board** mostrando las entregas por iteración y dependencias/marcos temporales clave.
- **ROAMed Risks:** lista de riesgos categorizados, especialmente cualquier Owned tiene un responsable nombrado que lo gestionará.
- **Commitment del ART:** un entendimiento compartido de qué se ha comprometido (los objetivos marcados como comprometidos) y cuáles son aspiracionales (stretch).
- Equipo motivado y socializado: un efecto colateral positivo es que todos escucharon a los demás, conocen qué harán los otros equipos, identificaron caras si necesitan algo luego (rompe silos). Si fue en persona, suele haber dinámicas que refuerzan camaradería.

**Importancia de PI Planning:** 
SAFe considera PI Planning la “piedra angular” de la alineación en escala. Es costoso (múltiples equipos parando 2 días), pero la alternativa –falta de alineación– suele costar más en caos y retrabajo. En el examen SAFe Practitioner suelen enfatizar: *PI Planning es indispensable para asegurar alineamiento y compromiso; realizarlo en cadencia regular genera un ritmo de sincronización entre negocio y desarrollo*.

Un punto a recordar: incluso en entornos distribuidos, se debe hacer PI Planning (adaptado virtualmente con herramientas de videoconferencia, boards online, etc., y posiblemente extendiendo a 3 días con sesiones más cortas para acomodar zonas horarias). La esencia permanece: interacción cara a cara en lo posible, conversaciones ricas que un documento no lograría.

**ROAM en PI Planning:** Vale la pena recalcar cómo se maneja ROAM aquí. Imaginemos durante las presentaciones finales un riesgo: “Integración con el sistema legado puede tomar más tiempo de lo previsto”. El grupo discute y decide: *no podemos resolverlo ahora (no se sabe hasta avanzar), no hay mitigación clara posible porque es impredecible, lo **aceptamos** (Accepted) y estaremos listos para reaccionar si se demora.* Otro riesgo: “El experto en seguridad está de vacaciones todo el PI” -> se **Owned** asignando al Arquitecto de Solución contactar un reemplazo o plan alterno; así al menos alguien lo gestiona. Al final, los riesgos ROAM quedan visibles para seguimiento continuo en las sincronizaciones (el RTE velará por ello ). 

Con PI Planning completo, el ART arranca ejecución del PI con un **plan confiable**. Claro, no es un plan rígido: puede ajustarse, especialmente a partir del feedback de las Iteration Reviews. Pero provee una base estable, como un contrato social interno del tren. Cada equipo sabe lo que debe lograr y cómo encaja con los demás. Esto reduce dramáticamente sorpresas durante el PI.

### 4.3 Planificación del equipo (Iteración)
Después del PI Planning, la siguiente escala de planificación ocurre a nivel de cada iteración, en cada equipo: la **Planificación de la Iteración** (Iteration Planning), que sucede normalmente el primer día de la iteración (y de forma repetitiva al inicio de cada iteración dentro del PI). En esta reunión, el **equipo ágil** se enfoca en el corto plazo: ¿qué vamos a completar en las próximas dos semanas? Se toman los items del Team Backlog (historias) priorizados para esa iteración y se elabora el plan concreto.

**Participantes y Preparación:** Asisten el equipo completo y su PO (facilitado por el Scrum Master). El PO, habiendo salido del PI Planning, ya tiene una idea de qué historias están designadas para la Iteración 1, Iteración 2, etc. Sin embargo, antes de cada iteración se puede ajustar un poco según lo ocurrido en la anterior (por ejemplo si alguna historia quedó pendiente, se reubica). El backlog debería estar refinado: historias comprendidas y estimadas. La capacidad de la iteración se calcula: cuántos puntos (o días-hombre) tiene el equipo disponibles (teniendo en cuenta si alguien toma vacaciones esta iteración, etc.).

**Proceso de Iteration Planning:**
1. **Reafirmar Objetivos del PI relevantes:** Es buena práctica que el PO recuerde al equipo cuál es el objetivo mayor al que contribuyen en esta iteración. Ej: “Esta iteración finalizaremos la Feature X, que es parte de nuestro objetivo de PI ‘Mejorar rendimiento’”. Esto alinea mentalmente al equipo.
2. **Seleccionar Historias:** El PO propone las historias de mayor prioridad para la iteración (según lo planeado). El equipo discute cada historia:
   - Si alguna historia no está clara, la refinan rápidamente (o pueden decidir posponerla si falta información, substituyéndola por otra preparada).
   - Se aseguran que las historias caben en la iteración. A menudo, toman historias en orden hasta sumar aproximadamente su capacidad (velocidad). Ej: si su velocidad es ~20 puntos, seleccionan historias que sumen alrededor de 20. 
   - Si la suma excede capacidad, negocian descartar o mover a stretch alguna. Si es muy inferior, pueden añadir más alcance (o decidir tomar un enabler extra).
   - Consideran **dependencias**: si una historia depende de otra equipo y ésta no se completó aún, tal vez no pueden hacerla ahora y la dejan para más adelante, o coordinan.
3. **Definir Tareas (opcional):** Muchos equipos Scrum descomponen cada historia en tareas técnicas concretas (en horas) para entender mejor el trabajo. Ej: Historia “Implementar pantalla de login” -> tareas: *Diseñar UI (4h)*, *Desarrollar formulario (12h)*, *Pruebas unitarias (4h)*, *Integración con backend (8h)*... Suman horas y verifican que no exceda la disponibilidad real de horas de los miembros. Esto puede revelar que se sobrecargó a un miembro específico, etc., y permite reequilibrar. Aunque SAFe no obliga a tasking, es útil para el equipo autoorganizarse durante la iteración (cada uno sabe qué tareas tomar). Algunos equipos Kanban no hacen esto, sino que trabajan directamente por historia.
4. **Establecer **Metas de Iteración***: Basado en las historias seleccionadas, el equipo formula de 1 a 3 objetivos de negocio/técnicos en lenguaje común que se lograrán en la iteración. Por ejemplo: “Completar la Feature X” puede ser meta, o si es una iteración inicial quizás “Integrar componente básico de autenticación”. Las metas de iteración sirven para comunicar a stakeholders (y a sí mismos) el propósito de la iteración más allá de la lista de historias. También ayudan en la *Scrum of Scrums* o PO Sync a nivel ART: cada equipo comunica su meta, así otros saben en resumen en qué estará enfocada cada equipo en esas 2 semanas.
5. **Compromiso:** El equipo, al terminar la planificación, se **compromete** con el plan de la iteración. Esto significa que cree razonablemente que puede completar todas las historias seleccionadas cumpliendo DoD. Si hay alguna de riesgo que podría no terminar, a veces la marcan como “stretch” de iteración (similar a PI). Pero en general, a nivel iteración el compromiso se toma en serio: si ven que no cabe, ajustan antes de comprometer. El PO acepta el plan.

**Salida de Iteration Planning:** Un **Backlog de Iteración** confirmado, con X historias asignadas a esa iteración, cada miembro sabiendo en qué trabajará primero, y **Metas de Iteración** definidas. El PO es consciente de qué se espera entregar y lo comunica si hace falta a interesados (ej: actualiza el radiador de información o manda una nota a Business Owner si es algo sensible).

**Ejemplo de Iteration Planning:** Equipo Bravo tiene 10 puntos de capacidad. En su backlog próximo hay 3 historias: A(5pts), B(3pts), C(5pts). Suman 13 puntos, demasiado. Deciden que la historia C es menos prioritaria (o quizás es una parte complementaria), y la marcan como stretch o la pasan a la siguiente iteración. Seleccionan A y B (8pts total). Desglosan A en tareas, ven que implicará trabajo de 3 miembros pero bien. B en tareas pequeñas. Todo encaja en horas. Metas: “Entregar funcionalidad A completada y comenzar integración B”. Se comprometen a A y B. Durante la iteración, si terminan antes podrían tomar C (stretch). Si por mitad de iteración ven que A se complica, pueden negociar re-definir alcance de B o avisar al PO que C se descarta del todo.

**Coordinación con ART:** Tras la iteration planning de cada equipo, muchos RTEs hacen una mini reunión Scrum of Scrums inicial para compartir las metas de iteración entre todos los SMs, asegurándose que si había alguna dependencia crítica en esa iteración, todos quedaron al tanto. Es parte de “syncs alinean la entrega” (lo veremos en 5.2). 

**Ajustes en marcha:** Aunque PI Planning traza un plan para ~5 iteraciones, en cada iteración los equipos pueden **ajustar detalles**. Por ejemplo, si en Iteración 1 no lograron terminar una historia, esa historia pasa a Iteración 2’s planning como prioridad (afecta el plan original pero se adapta). El PI plan no es una camisa de fuerza: es una guía, pero los POs y RTEs ajustan si emergen nuevas info o riesgos. Lo importante es comunicar cambios. SAFe por eso define la PI como un *timebox* fijo donde el **alcance es variable** dentro de ciertos límites (al contrario de proyectos tradicionales). Se espera que durante el PI, haya cambios menores en scope, pero no un pivot completo – si hubiera un gran cambio estratégico se abordaría en un re-planning o en el próximo PI.

**Backlog de Iteración vs Team Backlog:** Vale aclarar esta terminología: el *Team Backlog* es la lista global de trabajo del equipo (no comprometido todo de una vez). El *Iteration Backlog* es el subconjunto que el equipo se compromete a hacer en esa iteración. Tras planificar, se configura ese backlog de iteración. Al acabar la iteración, las historias completadas se marcan Done; las no terminadas vuelven al Team Backlog (o a la siguiente iteration backlog, reevaluadas con el PO).

**Continuous Planning:** En SAFe, más allá de estos eventos discretos, se fomenta la planificación continua. Los equipos hacen *refinamiento* cada semana, los POs reordenan backlog cuando reciben nuevo feedback, etc. Pero los hitos formales de compromiso son PI Planning y Iteration Planning.

Así, la Planificación de Iteración cierra el círculo de la planeación multinivel en SAFe: de la estrategia (épicas) a la táctica de 2 semanas. Es breve (generalmente timeboxed a 2 horas por semana de iteración, así ~2h para iteraciones de 2 semanas) pero crítica. Un equipo que planifica bien sus iteraciones opera de forma mucho más predecible y efectiva, cumpliendo sus objetivos y aportando al tren sin sorpresas. 

**Relación con PI Objectives:** Al final de cada iteración, el equipo evalúa su progreso hacia los Objetivos de PI. La iteration planning permite ver cuánto del objetivo global se ha cubierto y qué queda, facilitando decidir si en próximas iteraciones se requiere re-priorizar algo para alcanzar los objetivos comprometidos. En la práctica, los PO y RTE monitorean en la mitad del PI si los equipos van encaminados a cumplir los PI objectives, y ajustan con micro-planeaciones si necesario.

Con un buen backlog y eventos de planificación rigurosos, los equipos SAFe establecen una **cultura de previsión y compromiso** que da confianza a la organización de que las promesas (objetivos) se cumplirán, al mismo tiempo que mantienen la agilidad para adaptar el plan cuando la realidad y el feedback lo requieran.

## 5. Entregar valor

### 5.1 Integrar, desplegar y liberar de forma continua
Entregar valor no se logra solo planificando; hay que ejecutar el trabajo construyendo la solución. SAFe promueve un **Pipeline de Entrega Continua (Continuous Delivery Pipeline, CDP)** que permite a los equipos integrar código, desplegar en entornos y liberar a producción de manera rápida y automatizada . El objetivo es que el ART pueda *release on demand* – liberar al mercado cuando el negocio lo necesite – en vez de estar limitado por ciclos técnicos largos. 

El pipeline de entrega continua consta de cuatro aspectos:
- **Exploración continua (CE – Continuous Exploration):** Donde se explora qué se debe construir (vínculo con lo visto en “Conectar con el cliente”: analizar mercado, definir ideas, convertir en backlog listo).
- **Integración continua (CI – Continuous Integration):** Donde los equipos implementan las historias, integran continuamente su trabajo con el del resto y aseguran que la solución está siempre en un estado potencialmente desplegable .
- **Despliegue continuo (CD – Continuous Deployment):** Automatizar el despliegue de la solución a los entornos necesarios (principalmente producción o staging), de forma que llevar una funcionalidad al usuario sea trivial y seguro .
- **Liberación bajo demanda (Release on Demand):** La capacidad de liberar la solución a los usuarios en el momento apropiado para el negocio .

En el día a día de un equipo, “Integrar, Desplegar y Liberar de forma continua” se traduce en prácticas DevOps concretas:
- **Control de versiones colaborativo:** Todos los desarrolladores integran su código frecuentemente (al menos una vez al día) en un repositorio común. Esto previene grandes divergencias y conflictos de integración tardía. Al integrar, disparan un build del sistema.
- **Integración Continua (CI):** Un servidor de CI (como Jenkins, Azure Pipelines, GitLab CI, etc.) automáticamente compila el código, ejecuta pruebas unitarias y quizás pruebas de integración cada vez que hay cambios. Si algo falla, se notifica de inmediato al equipo (rompieron el build). La regla es mantener el build verde. Esto asegura que siempre se tenga un **sistema parcialmente probado e integrado** hasta ese punto.
- **Ambientes consistentes:** Usar contenedores o scripts de infraestructura como código para replicar entornos locales, de prueba y producción. Así “funciona en mi máquina” es igual a “funciona en staging”.
- **Deployment Pipeline Automatizado:** Tras CI exitoso, el siguiente paso es **Deploy** – llevar el paquete generado a un entorno. En Continuous Deployment, esto se hace sin intervención humana: desplegar a un entorno de prueba automáticamente, y (quizá tras tests adicionales) incluso a producción de forma automatizada. Muchas orgs implementan pipelines donde tras pasar QA, se despliega a producción de inmediato pero *dark* (sin habilitar a usuarios aún).
- **Feature Toggles y DevOps mindset:** Para liberar bajo demanda, a veces se decouple deployment de release. Por ejemplo, una feature puede estar desplegada en producción pero oculta tras una *feature toggle* (bandera de característica), habilitable para usuarios cuando negocio decida (p.ej., se activa la mañana de un lanzamiento oficial). Esto permite desplegar código continuamente sin esperar un gran evento de release, y luego *encender* las features en lote.
- **Pruebas automatizadas en todos los niveles:** Unitarias, funcionales, de regresión, seguridad, performance – cuanto más se pueda automatizar, más confianza para desplegar rápido. La meta es que tras cada cambio, un amplio suite de pruebas garantice que nada crítico se rompió. Esto es parte vital de Built-In Quality.
- **Monitorización y Telemetría:** Entrega continua también implica monitorear la solución en producción. DevOps enfatiza cerrar el ciclo: equipos reciben datos de uso real, logs, métricas de desempeño, y pueden reaccionar (por ejemplo, rollbacks automatizados si detectan un problema grave después de un deploy).

**Cultura DevOps (CALMR):** SAFe incorpora DevOps con el enfoque **CALMR**: *Culture, Automation, Lean Flow, Measurement, Recovery* :
- *Culture:* Cultura de colaboración entre Dev (desarrollo) y Ops (operaciones), que solían ser silos. En SAFe, todos son responsables de entrega hasta producción. “You build it, you run it” idealmente. Esto crea responsabilidad compartida y elimina el finger-pointing (culpar a otro).
- *Automation:* Automatizar todo lo repetitivo y propenso a error: compilación, pruebas, infraestructura, despliegues. Reduce tiempos y errores humanos.
- *Lean Flow:* Aplicar conceptos lean al pipeline: pequeñas tandas de cambio (commits pequeños frecuentes), limitar WIP (no tener 20 features a medio hacer, mejor terminar una y pasar a la siguiente), identificar cuellos de botella en el flujo de entrega (p.ej. si pruebas manuales demoran demasiado, ahí hay que actuar).
- *Measurement:* Medir continuamente tanto la performance del pipeline (tiempo de commit a deploy, frecuencia de deployment, tasa de fallos, MTTR – tiempo medio de recuperación, etc.) como la de la aplicación (métrica de negocio, de calidad). Los datos permiten mejoras informadas.
- *Recovery:* Tener la capacidad de recuperarse rápido ante problemas. Ej: si un despliegue causa fallo, poder hacer rollback o feature toggle off en minutos. Practicar *Chaos engineering* para estar listos ante fallos. Backups, monitoreo para detectar incidentes pronto, etc.

**Rol del Equipo en Entrega Continua:** En SAFe for Teams, se espera que cada equipo participe en la cadena DevOps. Puede haber un CoE de DevOps central, pero los equipos deben integrar a sus miembros con responsabilidades de pipeline. Por ejemplo, algunos miembros pueden encargarse de mantener las configuraciones de CI/CD, crear scripts de test, etc. Todos aportan a la cultura de “entregamos nuestro código hasta producción con calidad”.

**Liberación Cadenciada vs on Demand:** Notar que no necesariamente se liberará al cliente cada iteración. Algunas empresas sí (cadencia regular de releases, ej. cada 2 semanas). Otras más reguladas o con usuarios globales optan por liberar a demanda en momentos adecuados (quizá agrupando varias iteraciones). SAFe decouple la cadencia de desarrollo (iteraciones) de la cadencia de release. El ART provee un flujo continuo de valor *potencialmente liberable* , y el negocio decide la liberación. Pero gracias al pipeline, *pueden liberar cualquier día*, no tienen un ciclo pesado de meses para sacar a producción.

**Ejemplo:** Un ART completó 5 iteraciones. En la IP iteration, deciden liberar a producción todas las features completadas. Gracias a la integración continua, ya a fin de la Iteración 5 el sistema estaba integrado y probado en un entorno staging cercano a producción. Hacen algunos tests adicionales manuales en IP (UAT, etc.), todo bien. Con un click despliegan a producción. Los usuarios ven nuevas funcionalidades inmediatamente. Si descubren un bug crítico, el pipeline permite arreglarlo y desplegar un hotfix en horas (contrario a tiempos pre-DevOps de días/semana). Este ritmo genera confianza en el negocio para lanzar más seguido. 

Otro ejemplo: Un equipo tiene trunk-based development, cada commit va a main branch con CI. Deciden implementar *feature toggles* para una función “beta”. Así, integran el código de la feature inacabada escondida tras toggle. Siguen liberando a producción cada 2 semanas sin activar esa feature. Cuando esté completa y validada internamente, negocio planea un lanzamiento de marketing, y en esa fecha simplemente activan el toggle y la feature aparece para usuarios (release on demand). Esto demuestra flexibilidad: desarrollo no tuvo que esperar al evento de marketing, ya estaba todo desplegado listo.

En síntesis, integrar, desplegar y liberar continuamente se trata de **acortar el ciclo entre desarrollo y uso real en producción**, con alta automatización y prácticas sólidas, para entregar valor de forma rápida y confiable. Para un practicante SAFe, entender DevOps es crucial: el examen puede incluir preguntas sobre qué elementos conforman CALMR, o cuál es objetivo de pipeline, o distinguir despliegue continuo vs liberación continua. La clave: *DevOps no es solo herramientas, es cultura y proceso que permiten que la value delivery sea fluida.* Un ART verdaderamente ágil es aquel que no solo desarrolla rápido, sino que pone esas mejoras en manos del cliente rápidamente con calidad.

### 5.2 Las sincronizaciones (Syncs) alinean la entrega
Durante la ejecución de un PI, con varios equipos trabajando en paralelo, es vital **sincronizar** periódicamente para alinear progreso, resolver impedimentos y ajustar planes. SAFe establece eventos de sincronización a nivel ART conocidos como **ART Sync**, que típicamente se componen de:
- **Scrum of Scrums (SoS)** – ahora a veces llamado **Coach Sync** – enfocado en la coordinación entre Scrum Masters/Team Coaches sobre el avance de los equipos y obstáculos.
- **PO Sync** – sincronización entre Product Owners/Product Management sobre la evolución de las Features y si se requieren re-priorizaciones.

El objetivo de estos “syncs” es garantizar que la *entrega* de los equipos se mantenga alineada con el plan del PI y entre sí. En otras palabras, que el tren siga avanzando junto y no descarrilen vagones por falta de comunicación.

**Scrum of Scrums (Coach Sync):** 
Este es análogo a un Daily Scrum pero a escala de múltiples equipos. Por ejemplo, 2 veces por semana, los Scrum Masters (o Team Coaches) de cada equipo se reúnen en presencia del RTE (facilitador) y a veces System Architect, para responder:
- ¿Qué ha hecho mi equipo desde el último SoS que ayude al tren a lograr sus PI Objectives?
- ¿Qué hará hasta el próximo SoS?
- ¿Enfrentamos algún impedimento que requiera ayuda de otro equipo o RTE?
- ¿Tenemos alguna nueva dependencia o vemos riesgo en cumplir con algo comprometido?

En la práctica, el SoS da visibilidad transversal. Si el Equipo A dice “no podremos completar la historia X esta iteración”, y Equipo B la necesitaba, sale en SoS y pueden coordinar un plan (quizá B asiste o replanifica). El RTE toma nota de impedimentos escalados que los SM no puedan resolver localmente y busca soluciones (facilita un espacio con quienes deban involucrarse).

En SAFe 6.0, al generalizar a *Coach Sync*, se enfatiza que no todos son “Scrum” puramente; puede incluir SMs de equipos Kanban (Team Coaches). Pero la función es la misma: un foro de **colaboración interequipos** enfocado en la entrega.

**PO Sync:** 
En paralelo, los Product Owners se reúnen con el Product Manager (y a veces Business Owners o RTE) – puede ser semanal o a mitad de la iteración – para revisar:
- El avance de cada Feature del PI: ¿Están en camino? ¿Alguna se va a retrasar o necesita ayuda?
- Ajustes de alcance: Si algún equipo terminó sus historias antes, ¿podemos tirar alguna historia nueva? O viceversa, si hay más trabajo del previsto, ¿descartar algo de menor valor?
- Priorización táctica: Puede que surjan nuevos trabajos (un mini-feature solicitado urgente). El PO Sync discute si meterlo en este PI, qué impacto tiene (¿qué se saca?), y coordina con los POs involucrados.
- Dependencias producto: Por ejemplo, la Feature X de equipo A depende de que el criterio de aceptación Y de Feature Z (equipo B) se cumpla; si ven que equipo B cambió ese criterio, revisan impacto para producto global.
- Preparar próximas iteraciones: Confirman qué features deberían terminar en la próxima iteración y cuáles vendrán después, así los POs van preparando sus equipos.

Esta reunión asegura que los POs de todos los equipos cuentan con la **misma información actualizada** de prioridades y cambios. Evita que un equipo siga trabajando en algo que ya no es tan relevante o que se queden descoordinados en entregar una Feature conjunta. También es un espacio para sincronizar con calidad: Pueden comentar “La aceptación de la Feature ABC falló en System Demo – debemos planear un fix”. Todos los POs se enteran y pueden colaborar si necesario (p.ej., reasignar un recurso, etc.).

**ART Sync combinado:** 
Algunas organizaciones, para reducir reuniones, unen SoS y PO Sync en una única reunión ART Sync con RTE, SMs y POs presentes . En esa reunión integral, se toca tanto estado técnico como de producto. Esto puede funcionar si el ART es pequeño o si los roles se solapan (por ejemplo, algún PO es también developer y asiste a todo). En otros casos, mantenerlas separadas es más eficiente para centrar temas (técnicos vs negocio). Sea separado o junto, lo importante es el **flujo de información**.

**Cadencia de sincronización:** Depende del contexto, pero ejemplos:
- SoS: 2 veces por semana (ej. martes y jueves 15 min). Si ART es muy crítico, incluso diario de 15 min, pero no común.
- PO Sync: 1 vez por semana 30 min, a mitad de iteración. O incluso inmediatamente después de cada SoS, para que RTE pase de un foro a otro con info fresca.
- ART Sync (combinado): 1 vez por semana 30-60 min.

**Impedimentos e interdependencias:** Son las estrellas de estos syncs. SAFe anima a visualizar dependencias en un **Radiador** visible (como el Program Board en la sala o en Jira links). En cada sync se repasa qué dependencias para la próxima entrega están en peligro. Ejemplo: “Equipo A: ¿entregarás la API para fin de iteración 3? Equipo B la necesita en iteración 4.” Si A dice “quizá se retrase a iteración 4”, entonces B no podrá cumplir su parte en iteración 4. Aquí se discuten opciones: que B haga un stub temporal, que A priorice diferente, etc. Estas micro-negociaciones evitan sorpresas más adelante.

**Transparency (Transparencia):** Al tener syncs regulares, se genera transparencia total, uno de los core values. Problemas no se ocultan hasta final de PI; se abordan iterativamente. 

**Colaboración espontánea:** Más allá de reuniones formales, los equipos en un ART se comunican ad-hoc. Un desarrollador de Equipo A puede daily escribirle a uno de B sobre una integración. Esta cultura es fomentada por el PI Planning inicial (donde se conocieron) y por la actitud de los SM de animar a su equipo a hablar con otros cuando necesiten. Los eventos de sincronización son el **mínimo**, pero la colaboración puede ser continua.

**Program Kanban / Boards**: En los syncs también se pueden revisar tableros a nivel ART, como el Program Kanban, para ver estado de features (por ejemplo, 3 en progreso, 2 en code review). O métricas de flujo (¿algún atasco?). Todo con fin de *mantener entrega en ritmo*.

**Ejemplo del valor de Syncs:** Supongamos sin syncs, el Equipo X espera que Y entregue algo. Y se atrasa pero no lo comunica hasta la System Demo. Resultado: X no pudo integrar su parte – fiasco. Con syncs, Y hubiera dicho en la semana 1 “Nos retrasaremos, necesitamos ayuda o replan”, X se entera, y juntos con RTE replanifican: quizá intercambiaron alguna historia o pidieron a un especialista que acelere. Evitaron el fallo. 

**Lean-Agile Principle en acción:** “Aplicar cadencia, sincronizar…” (Principio 7) se ve justo aquí. Los syncs son sincronización en miniatura durante el PI, complementando la gran sincronización que fue PI Planning. Mantienen la variabilidad bajo control con chequeos frecuentes.

En resumen, los eventos de sincronización del ART (SoS/Coach Sync y PO Sync) son el **sistema nervioso** del tren durante la ejecución: transmiten información entre los equipos y la gestión, coordinan movimientos y aseguran que la entrega de valor se mantiene en curso. Sin estos syncs, un ART corre riesgo de fragmentarse en silos e incurrir en integraciones dolorosas al final. Con ellos, se genera un *pulso constante de alineación* que facilita entregar valor de forma continua y predecible.

### 5.3 Incorporación de la calidad (Built-In Quality)
Entregar valor solo es realmente valioso si ese valor tiene **calidad**. SAFe establece como principio que la **Calidad Incorporada** es imprescindible: “No puede haber agilidad sin calidad”. *Built-In Quality* significa que la calidad no se “agrega al final” mediante inspecciones o testing masivo, sino que se construye dentro del proceso desde el inicio. Cada integrante del ART es responsable de la calidad en todo momento . 

SAFe identifica cinco dimensiones de calidad incorporada :
1. **Flujo:** Calidad en flujo significa trabajar en lotes pequeños, con WIP limitado, de modo que problemas emergen pronto cuando el contexto aún es fresco. Un flujo fluido evita acumulación de errores.
2. **Calidad de Arquitectura y Diseño:** Tener intencionalidad en la arquitectura (ej. pautas definidas por System Architect) pero permitir diseño emergente. Se busca un diseño robusto que soporte cambios (evitando *deuda técnica* excesiva). Requiere refactorización continua para mantener el diseño limpio.
3. **Calidad del Código:** Aplicar prácticas técnicas ejemplares: *pair programming* (más ojos, más calidad), *code review* sistemático, *guilds* de desarrollo que acuerdan estándares de codificación, análisis estático de código para detectar vulnerabilidades o malos olores, etc. Código limpio y mantenible es base de menos bugs.
4. **Calidad del Sistema:** Pruebas integrales del sistema, incluyendo pruebas funcionales de las features, pruebas de rendimiento, seguridad, usabilidad. Involucrar a usuarios/clienes en validar prototipos o incrementos. Además, simular entornos productivos para validar integraciones (ej: staging environment). 
5. **Calidad de la Publicación (Release Quality):** Asegurar que la liberación al cliente es fluida y el producto en producción se comporta estable. Incluye procedimientos de despliegue robustos, monitoreo post-release, y rollback plan por si algo falla.

Incorporar calidad se logra con muchas prácticas concatenadas. Algunas claves en SAFe:
- **Definition of Done (DoD) estricta:** Como mencionado, se define qué criterios de calidad debe cumplir un elemento para considerarlo “Done”. Para historias: ejemplos, *100% tests unitarios pasados*, *código revisado por compañero*, *documentación actualizada*, *integrado en build principal sin romperlo*. Para iteraciones: *todas historias completadas aceptadas por PO*, *ningún bug crítico abierto*, *demo preparada*. Para PI: *no debt intencional sin abordar, objetivos de PI cumplidos*. Estos checklists aseguran que no se arrastren defectos ocultos a fases posteriores.
- **Test-First / ATDD / BDD:** Prácticas donde los equipos escriben las pruebas antes o junto con el código. *Acceptance Test-Driven Development (ATDD)* involucra a POs, testers y devs definiendo juntos los tests de aceptación (criterios) antes de implementar la historia . Esto alinea entendimiento y guía a codificar solo lo necesario para pasar los tests. *Behavior-Driven Development (BDD)* es similar, usando lenguaje dado/cuando/entonces para ejemplos. Esto incrementa la calidad funcional y reduce retrabajo.
- **Automatización de pruebas y CI:** Como ya se detalló en 5.1, la automatización es un gran habilitador de calidad incorporada. Si cada commit pasa por 1000 pruebas automatizadas, los bugs se detectan minutos después de introducirse, no meses. 
- **Integración frecuente con System Demos:** Al hacer integraciones y demos del sistema cada iteración, se fuerza a abordar problemas de integración tempranamente. La calidad global del sistema se evalúa iterativamente, no al final. *“Integration points control product development”*, por eso cada integración es un control de calidad de sistema .
- **Refactorización continua:** Los equipos deben sentirse con libertad (y tiempo asignado) para refactorizar código o mejorar diseños sobre la marcha. Esto evita la degradación de la base de código y previene que la velocidad futura caiga por “deuda técnica”. Built-In Quality implica no dejar la deuda crecer sin pagarla periódicamente.
- **Parejas y rotación de trabajo:** Programación en pareja o revisión cruzada de historias (un dev de otro equipo revise) puede hallar defectos lógicos o mejorar soluciones. Además, rotar responsabilidades (hoy X hace code review a Y, mañana al revés) distribuye conocimiento y sube nivel colectivo.
- **Políticas de calidad en pipeline:** Ej: no se puede mergear código a main si fallan tests (gate automático), o no se despliega a staging sin aprobar ciertos criterios. Estas políticas en la herramienta CI/CD reafirman la disciplina.
- **NFRs explícitos:** No funcionales, como performance, seguridad, compatibilidad, son *trabajo de todos*. SAFe aconseja capturarlos en el backlog (como Enabler stories o criterios) para no olvidarlos. Ej: “Como sistema, necesito responder en <200ms a la consulta X (NFR)” es algo que el equipo implementará/testeará. Esto eleva calidad global.
- **Environment synchronization:** Asegurar que dev, test, prod estén alineados reduce “calidad variable” (que pase en dev pero falla en prod). Uso de contenedores, etc., ya dicho.
- **Exploratory Testing y UAT:** Además de pruebas automatizadas, los testers y POs realizan pruebas exploratorias a cada iteración: intentando flujos inusuales, busqueda de edge cases. Involucrar usuarios reales en *User Acceptance Testing* para feedback real. Esto captura problemas que las pruebas automatizadas no cubren (usabilidad, confusión del usuario, etc.).
- **Mejora continua de procesos de calidad:** Cada retrospectiva de iteración o PI puede sacar acciones para mejorar calidad. Ej: “Tuvimos muchos bugs de integración – acción: haremos mini hackathon entre equipos en iteración IP para mejorar test de contrato entre servicios”. O “Pruebas manuales nos tardan 3 días – acción: invertir en automación de UI test”.

**Cultura de calidad:** Built-In Quality no es solo herramientas, es actitud. Los equipos se sienten dueños de la calidad, no delegan “QA al final”. Si un test falla, lo atienden de inmediato. Si un defect emerge en producción, en lugar de culpar, hacen *blameless post-mortem* para aprender y mejorar proceso. La alta dirección apoya esto destinando tiempo en PI para refactors o mejoras, entendiendo que *“calidad es velocidad a largo plazo”*. De hecho, SAFe dice: calidad incorporada reduce significativamente los tiempos de entrega, porque evita re-trabajos y retrasa menos por errores tardíos ([La Gestión de Calidad Integrada de la Mejora Continua](https://businessmap.io/es/gestion-lean/mejora-continua/calidad-incorporada-de-la-mejora-continua#:~:text=La%20Gesti%C3%B3n%20de%20Calidad%20Integrada,Lean%20en%20toda%20la%20empresa)).

**Ejemplo concreto de Built-In Quality:** En un equipo, al terminar una historia de desarrollar una API, el DoD requiere: pruebas unitarias al 90% de cobertura, pruebas de integración con base de datos ejecutadas, código revisado por al menos otra persona, documentación de API actualizada. No se marca done hasta cumplirlo. Descubren un bug en pruebas integradas – lo arreglan antes de decir “terminado”. El PO no aceptará la historia hasta ver criterios y DoD cumplidos. Este rigor en cada pequeña historia lleva a que al final de la iteración, el incremento global esté realmente listo, no con “sorpresas”. Multiplicado por todas las iteraciones, resulta en PIs sin caos al final y releases estables.

Otro ejemplo: Para Calidad de Publicación, el equipo de DevOps simula un failover en staging cada PI (apaga servidores random) para asegurar que la aplicación tolera fallos (práctica de *Chaos Engineering*). Esto construye resiliencia de calidad en la solución final.

**Relación con Core Values:** Built-In Quality es uno de los valores centrales, al igual que transparencia. Uno alimenta al otro: al tener calidad en cada paso, se puede ser transparente con el progreso real (no se ocultan “% completado” que en realidad falta probar). Y la calidad genera confianza: Business Owners confían en que al final del PI no recibirán un “engaño” de software incompleto.

Para el SAFe Practitioner exam, recordar que Built-In Quality abarca calidad técnica y de proceso a todos niveles. Puede haber preguntas como “¿Cuál de los siguientes NO es un pilar de calidad incorporada?” o “¿Por qué es importante built-in quality?”. La respuesta general: *porque asegura que cada incremento es de alta calidad, permitiendo acelerar sin generar cascadas de defectos; soporta la entrega continua y la satisfacción del cliente* ([Valores y principios de Scaled Agile Framework (SAFe) - Atlassian](https://www.atlassian.com/es/agile/agile-at-scale/what-is-safe#:~:text=Atlassian%20www,sistema%20y%20calidad%20de)).

En síntesis, **Incorporar la calidad** significa hacer de la excelencia técnica y la verificación continua parte del ADN del trabajo diario. No dejar la calidad al final, sino integrarla en el flujo de desarrollo. Los equipos que lo logran encuentran que pueden entregar valor más rápido (ya que no pierden tiempo corrigiendo fallos más tarde) y los clientes reciben soluciones más fiables. La mejora continua (Kaizen) y la calidad van de la mano en SAFe, como veremos en “Mejorar de manera implacable”.

## 6. Obtener feedback

### 6.1 Obtener feedback del Cliente
Un principio ágil fundamental es **retroalimentación rápida y continua**. En SAFe, “Obtener feedback” se refiere a establecer ciclos para recoger las opiniones, reacciones y datos del cliente o usuario sobre lo que se está construyendo, y utilizar esa información para ajustar el rumbo. Esto ocurre a múltiples niveles: por iteración, por PI, y en general durante la vida del producto.

**Por qué es crucial el feedback:** Sin feedback real, los equipos podrían desviarse de las necesidades del cliente o malinterpretar requerimientos. Al acortar el ciclo feedback, se reducen desperdicios (Lean) al detectar pronto si algo no aporta valor o necesita mejora. Además, involucra al cliente en co-crear la solución, aumentando la probabilidad de aceptación.

**Fuentes de feedback del cliente:**
- **Revisiones de Iteración (Iteration Review):** al final de cada iteración, cada equipo muestra lo que ha producido a los stakeholders (incluido potencialmente usuarios o representantes de negocio que conocen la perspectiva del cliente). El Product Owner, junto con Business Owners o usuarios clave invitados, evalúa si las historias cumplen lo esperado. Se recaba cualquier comentario: “¿Esto soluciona tu problema? ¿Cómo podría mejorarse?”. También se puede medir satisfacción en pequeño (un user demo – “¿te gusta esta interfaz?”).
- **Demostración del Sistema (System Demo):** (Ver 6.3) A nivel integrado, al final de la iteración, donde se obtiene feedback de stakeholders del sistema completo. Aquí se simula la experiencia cliente integrando componentes.
- **Feedback directo de usuarios reales:** Por ejemplo, en desarrollo de software, se podría liberar una versión beta a un grupo de usuarios y recoger su feedback mediante encuestas, analíticas (qué usan o dónde se atascan), sesiones de usabilidad o pruebas A/B. SAFe alienta prácticas de *Continuous Exploration* donde se valida hipótesis con usuarios. 
- **Cliente en PI Planning e I&A:** En PI Planning rara vez hay clientes externos presentes, pero los Business Owners son una proxy del cliente de negocio y dan feedback inmediato en la planificación (“esto no es tan prioritario como pensaban, en cambio aquello sí”). En el evento final de PI (*Inspect & Adapt*), a veces se invita a clientes reales o se usa sus datos para revisar: “Lanzamos X en este PI, obtuvo NPS de 50, que es mejora vs antes, pero pidieron tal feature”.
- **Foros de Cliente:** Algunos ARTs mantienen un *Customer Council* o panel de usuarios que periódicamente ven demos y dan feedback. O integran algún miembro de área de negocio (que representa clientes) en las demos.
- **Métrica de uso en producción:** Una forma de feedback indirecto pero muy valiosa: instrumentar el producto para ver cómo se usa. Ej: Telemetría de clics en una app, tasa de abandono en un flujo, etc. Esto es feedback cuantitativo real del comportamiento del cliente, que puede indicar qué aportar a backlog (si muchos abandonan en paso 3, hay un problema que solucionar).

**Incorporar feedback:** Lo importante es qué se hace con el feedback. SAFe propone ciclos cortos: tras cada iteración y PI, los POs y Product Management analizan el feedback e **incorporan los hallazgos al backlog**. Pueden ajustar la prioridad de features o añadir nuevas historias. Ejemplo: feedback de usuario “me gustaría filtrar los datos en este reporte” puede traducirse en una nueva feature en backlog priorizada pronto si es generalizado el pedido.

**Ejemplo simple:** Un equipo desarrolla una nueva página web. En la Iteration Review la muestran a representantes de usuarios; ellos comentan que el botón de llamada a la acción está poco visible. El equipo toma nota e inmediatamente crea una historia para la siguiente iteración: “Ajustar estilo del botón para resaltarlo”. En la siguiente demo, ese feedback ya se ve implementado, y los usuarios confirman que ahora está mejor. Este micro-ciclo evita lanzar un producto con ese problema y demuestra respuesta ágil a la retroalimentación.

**Feedback y hipótesis:** Muchas features se construyen con una **hipótesis de valor** (“Creemos que implementar X aumentará la retención de clientes un 10%”). El feedback (ya sea cuantitativo – métricas – o cualitativo – opiniones) permite **validar o refutar** esa hipótesis. Si tras implementar X, la retención no cambia, el feedback indica que la hipótesis era incorrecta o insuficiente. Así se puede pivotar: quizás enfocar esfuerzos en otra área más valiosa. Este es un concepto de Lean Startup aplicado: construir-medirs-aprender.

**Cadencia vs on-demand:** Aunque hay eventos formales para feedback (iteration reviews, system demos, I&A), los equipos no deben limitarse a ellos. Si un equipo puede involucrar a un cliente en medio de la iteración para una duda específica, ¡debería hacerlo! Por ejemplo, un diseñador puede hacer un test de usabilidad de un prototipo a mitad de la iteración con 3 usuarios y traer ese feedback al equipo antes de terminar la funcionalidad. Es perfectamente válido y recomendable.

**Cultura de apertura:** Obtener feedback requiere una actitud abierta a la crítica y a la mejora. Los equipos deben ver las observaciones no como ataques sino como *insumos valiosos* para hacer un mejor producto. SAFe Core Value de **Transparencia** juega aquí: al mostrar trabajo frecuentemente, incluso con defectos, se construye confianza con stakeholders, que aprecian la visibilidad y oportunidad de opinar.

**Rol del Product Owner en feedback:** El PO tiene un rol activo: es quien suele recopilar la retroalimentación en la Iteration Review (pregunta a los asistentes qué piensan, toma notas) y después la prioriza. También trabaja con Product Management si el feedback sugiere cambios más allá del equipo (ej. todo un nuevo feature). En un ART, los POs pueden compartir feedback en su PO Sync, para ver si es global o local.

**Ejemplo a nivel ART:** Tras un System Demo del PI, los Business Owners (que representan cliente negocio) dan feedback que la funcionalidad X no cumple ciertos requisitos legales. Ese feedback genera un Enabler feature a incluir de inmediato en el próximo PI. Sin la demo, quizás ese incumplimiento legal se descubría mucho más tarde en auditoría. Así, el feedback evitó un fallo mayor.

**Customer Feedback en desarrollo hardware** (si aplica): SAFe también cubre sistemas ciber-físicos donde iterar puede ser más lento. Aun así, se busca feedback frecuente: simulaciones con clientes, prototipos conceptuales, etc. Por ejemplo, en un ART de automoción, tras un PI pueden tener un prototipo de módulo de coche y hacer que clientes se sienten y den opinión sobre la interfaz, antes de fabricar en masa.

Resumiendo, **Obtener feedback del cliente** es cerrar la loop de comunicación. SAFe no ve la “entrega” como fin, sino entrega + feedback = valor real. Sin feedback, el proceso Lean-Agile queda cojo porque no hay aprendizaje. Con feedback constante, el producto evoluciona verdaderamente orientado al usuario, incrementando su éxito en el mercado.

### 6.2 Demostración de valor con la Revisión de la Iteración
Cada iteración culmina con una **Revisión de Iteración** (Iteration Review), a veces llamada *Sprint Review* en terminología Scrum, que es la ceremonia donde el equipo muestra el trabajo completado durante la iteración a los interesados y obtiene feedback. Esta revisión es fundamental para **demostrar el valor** producido en ese corto ciclo y verificar junto a las partes interesadas si el incremento es adecuado.

**Participantes y Preparación:** En la Iteration Review participan el equipo completo, su Product Owner (que típicamente facilita la sesión), el Scrum Master y se invita a *stakeholders* relevantes. Estos pueden incluir:
- Business Owner(s) asociados al equipo o ART.
- Representantes de negocio (ej: alguien de Marketing para ver la nueva funcionalidad de cara al cliente).
- Otros equipos si hay dependencias cruzadas (para ver cómo encaja su parte).
- Usuarios finales o representantes de usuarios (si es posible).
- Agile Coach/RTE puede asistir para asesorar y también llevar info al nivel programa.

El equipo prepara con anticipación una **demo funcional** de las historias completadas. Frecuentemente se usa un entorno de pruebas donde se ha desplegado lo construido (gracias a CI/CD eso debería estar listo). También se preparan los **criterios de aceptación** de cada historia, de modo que en la review el PO u stakeholder pueda verificar que se cumplen.

**Agenda típica de Iteration Review:**
- **Resumen de la Iteración:** El PO empieza recordando las metas de la iteración y qué historias estaban en el alcance. Ej: “Esta iteración nos propusimos implementar la autenticación con huella digital y corregir el bug de notificaciones”.
- **Demostración de Historias Completadas:** Los miembros del equipo toman turnos para *demostrar* cada funcionalidad terminada. Esto no es una presentación en PowerPoint, sino mostrar el producto real en acción:
  - Si es software, proyectan la aplicación corriendo: “Aquí en la pantalla de login, ahora probaremos la autenticación por huella...” y muestran cómo funciona.
  - Si es un módulo de hardware/firmware, quizás muestran métricas, logs o un video del dispositivo funcionando con la nueva característica.
  - Explican brevemente qué se hizo y cómo cumple el criterio. Por ejemplo, “Criterio: si la huella es incorrecta, se muestra mensaje de error – lo demostramos ahora”.
  - Los stakeholders observan, hacen preguntas o comentarios en el momento.
- **Feedback y Discusión:** Tras cada demo o al final de todas, se abre la conversación. Stakeholders dan su opinión:
  - ¿Cumple la necesidad? (p.ej. Business Owner: “Esto es exactamente lo que necesitábamos para mejorar la UX, buen trabajo” o “Mmm, el mensaje de error quizá debería ser más claro para el usuario medio”).
  - Se anotan solicitudes de cambio o nuevas ideas emergentes. No significa que se implementarán de inmediato, pero alimentan el backlog como nuevas historias o refinamientos.
  - Si algo no cumple criterios o está mal, el PO puede marcar la historia como **no aceptada**. Esa historia vuelve al backlog para completarse en la próxima iteración. (Idealmente, no muchas sorpresas así, porque PO debe estar involucrado continuamente; pero puede pasar si una condición emergente no se detectó).
- **Revisión de Objetivos de Iteración:** El equipo evalúa si alcanzaron las metas definidas. Por ejemplo, si la meta era “Completar funcionalidad X”, confirman “Sí, la completamos y fue aceptada.” Si alguna meta no se logró, se discute brevemente por qué (esta info alimentará la retrospectiva).
- **Estado del PI actual:** A veces, el PO o SM conecta el resultado de esta iteración con el panorama del PI. “Con esto, ya hemos completado 3 de 5 historias de la Feature Y, vamos en buen camino para el PI Objectives.” Esto mantiene informados a Business Owners. Aunque la retrospectiva de mitad de PI se hace en ART Sync, esta mini actualización contextual en la review es útil para el equipo y stakeholders inmediatos.

**Demostrar valor** es clave: no se listan tareas hechas, se muestra incremento funcional *valioso*. La métrica de éxito de una iteración no es “hicimos 50 horas de trabajo”, sino “entregamos X funcionalidad que permite al usuario hacer Y, cumpliendo el criterio Z”. La Review pone el foco en el *outcome* (resultado) más que en el *output* (cantidad de trabajo). 

**Timebox:** Por convención, una Iteration Review dura máx 1 hora por semana de iteración (Scrum Guide sugiere 2 horas para un sprint de 2 semanas). Con práctica, muchos equipos la hacen en 30-60 minutos. Debe ser sustanciosa pero eficiente.

**Relación con System Demo:** La Iteration Review es local de equipo; la System Demo integra todo el ART. A veces, si el ART es pequeño, la Iteration Review y System Demo se combinan en un único evento para todo el tren. Pero en ARTs medianos/grandes, cada equipo hace su review (incluso simultáneas en diferentes salas) y luego se toma el output de los equipos integrados en System Demo (que suele ocurrir no mucho después). 

**Aceptación formal del PO:** La Review es también el momento en que el PO acepta oficialmente las historias terminadas. Si el criterio de aceptación se cumple, el PO dice “Aceptada” – en herramientas de ALM se marca como Done. Esto es importante: solo las historias aceptadas cuentan como completadas en la iteración (para velocity, predictability, etc.). Historias no aceptadas se reactivan.

**Captura de métricas en review:** Algunos equipos revisan su *burn-down chart* o *velocidad* brevemente en la review para transparencia con stakeholders (“planeamos 20 puntos, completamos 18”). Pero esto a veces se deja para la retrospectiva interna. Depende del público; stakeholders de negocio a veces no necesitan o no interpretan los puntos, solo quieren ver la funcionalidad.

**Follow-up:** Tras la review, el PO actualiza el **Team Backlog**: remove las completadas, reordena lo restante, agrega nuevas historias derivadas del feedback. También puede comunicar hacia Product Management si alguna implicación mayor surgió (p.ej., “nuestro stakeholder sugiere añadir un módulo de reportes – quizás esto sea una nueva feature a priorizar”).

**Ejemplo:** Iteración 3 para Equipo Delta, objetivo: “Implementar pago con PayPal”. En la review, demuestran cómo desde la app ahora se puede pagar con PayPal en el checkout. Invitaron a alguien del departamento de ventas online. La persona comenta: “Excelente, esto lo piden mucho nuestros clientes, aunque noté que tras pagar no redirige automáticamente al recibo – deberíamos añadir eso para mayor claridad.” El PO toma nota: nueva historia “redirigir a recibo tras PayPal”. La funcionalidad principal es aceptada (cumple todo lo obligatorio). Todos ven que valor se entregó (nueva opción de pago, muy valorada). El equipo cumplió su meta. Feedback añadido al backlog = iteración exitosa y aprendizaje incorporado.

**Motivación del equipo:** Las demos de iteración también son un momento de reconocimiento. Cuando los stakeholders muestran entusiasmo o gratitud por lo logrado, el equipo siente satisfacción y motivación. Es el momento “mostrar frutos del trabajo”. Esto no es trivial para la moral.

**Comunicación hacia arriba:** A menudo, Business Owners pueden estar demasiado ocupados para cada equipo review, pero al menos el Product Manager o RTE recopilan highlights. En PO Sync post-iteration, POs pueden compartir “nuestro stakeholder amó tal cosa” o “descubrimos en review un caso que requiere más trabajo”. Así la info sube.

**Inspección adaptativa:** La Iteration Review forma parte del ciclo “Inspect and Adapt” a pequeña escala (inspect = review, adapt = ajustar backlog). Es complementaria a la **Retrospectiva de Iteración** (que es más sobre proceso de equipo y mejora interna, no producto). Juntas, review y retrospectiva, completan la inspección de *producto* y *proceso* respectivamente cada iteración.

En resumen, la Revisión de Iteración es donde el equipo **muestra el valor creado** y recoge **feedback inmediato**. Si algo no aporta valor, se sabe de una vez. Si sí aporta, se valida y se celebra. Y siempre se aprende algo para mejorar el producto. Es una práctica esencial para mantener al equipo orientado al cliente y al negocio en ciclos cortos.

### 6.3 Demostración del Sistema (System Demo)
Mientras que las iteration reviews muestran el trabajo de cada equipo por separado, la **Demostración del Sistema** es un evento a nivel **ART** donde se presenta el **incremento integrado** de todos los equipos, ofreciendo una visión de la solución completa. Se lleva a cabo regularmente (idealmente al final de cada iteración) y proporciona feedback de las partes interesadas sobre la eficacia y usabilidad de todos los componentes en conjunto .

**Qué es el System Demo:** 
Es una demo end-to-end del sistema o producto, incluyendo las nuevas features terminadas en la iteración por **todos** los equipos del ART funcionando juntas. En otras palabras, se toma el output de cada equipo (que pudo haber sido visto aisladamente en reviews) y se integra en un entorno lo más cercano posible al real para mostrar cómo la solución se comporta como un todo con esas incrementos agregados . 

Si el ART construye un solo producto, es mostrar la última versión del producto con todo lo nuevo. Si es un Solution Train (varios ARTs), podría haber además una *Solution Demo* integrando ARTs, pero en contexto de Teams se limita al ART.

**Periodicidad:** SAFe recomienda al menos **cada iteración** hacer una System Demo . En algunos contextos, es posible cada 2 iteraciones, pero hacerlo con la mayor frecuencia viable reduce riesgo. “Integrar frecuentemente” es la idea.

**Participantes:** 
- Todo el ART está invitado (equipos, POs, SMs, etc. – aunque ya conocen su parte, ven la global).
- **Business Owners** y otros stakeholders de negocio a nivel programa suelen asistir (más que a cada team review, porque aquí ven panorama total).
- **Product Management** presenta o coordina la demo, a veces junto con RTE. Pueden invitar también a usuarios finales representativos si es factible, o miembros de otras ART conectadas.
- System Architect tal vez participa mostrando aspectos técnicos integrados.

**Preparación:** 
- El entorno integrado (que puede ser un ambiente de staging o laboratorio) debe tener desplegado todo el trabajo completado. Esto implica que los equipos han integrado su código con éxito. Los pipeline CI/CD ayudan mucho a tener una “build del sistema” lista al final de la iteración. 
- Se define un **escenario de demostración**: un guión que recorre las nuevas features principales. Por ejemplo: “En esta iteración, implementamos la funcionalidad de pago con PayPal (equipo A) y la función de historial de transacciones (equipo B). Vamos a demostrar un flujo donde un usuario hace un pago con PayPal y luego verifica que aparece en su historial.” Esto entrelaza las contribuciones de equipos en una narrativa centrada en el usuario.
- Se pueden preparar datos de prueba o configuraciones en el sistema para la demo (ej. una cuenta de usuario con ciertos privilegios para mostrar una feature admin).
- Pueden definir quién narra o maneja la demo. A veces es Product Manager, o a veces delega a POs / miembros de equipos que implementaron la feature (dándoles visibilidad).
  
**Ejecutando la System Demo:**
- **Introducción:** RTE/Product Manager reitera los **Objetivos de PI** y qué incrementos se han logrado hasta esta iteración. Sitúa contexto: “Estamos en iteración 3 de 5 del PI, hasta ahora hemos completado X features. Hoy mostraremos las integraciones nuevas.”
- **Demo en sí:** Se realiza el recorrido de usuario planeado, tocando cada nueva capacidad:
  - Ejemplo: *Demo de App banca:* El presentador hace login, muestra la nueva autenticación (feature equipo 1). Luego navega a pagos, realiza pago PayPal (feature equipo 2) – muestra confirmación. Luego va a historial, ve la transacción (feature equipo 3). Durante todo esto, los stakeholders ven la experiencia cohesiva. Los miembros de equipo responsables están listos en caso de preguntas técnicas específicas (“¿qué pasa si el pago falla? - Implementamos tal manejo de error…”).
  - Se procura que la demo sea lo más cercana a *cómo un usuario real usaría el sistema.* Esto valida no solo que cada pieza funciona, sino que juntas entregan el **flujo de valor** esperado.
- **Feedback de Stakeholders:** Tras o durante la demo, se abren micrófonos:
  - Stakeholders dan su impresión general del sistema. Ej: “Esta versión integrada ya parece muy sólida, la experiencia del usuario de punta a punta para pagar es fluida.” 
  - Preguntan cualquier duda: “¿Qué ocurre si cancela en medio?” – quizá se demuestra también.
  - Notan posibles mejoras: “Sería bueno mostrar el saldo actualizado después del pago en la pantalla final,” anotado para backlog.
  - Pueden también hablar de implicaciones: “Con esto listo, podríamos adelantar el lanzamiento de esta feature a clientes piloto.”
- **Confirmación de Cumplimiento:** Los Business Owners evalúan si las Features presentadas satisfacen los **objetivos de negocio** que esperaban. Esta es su oportunidad de aceptar funcionalmente la entrega a nivel más alto. Pueden referirse a los Objetivos de PI asignados: “El Objetivo ‘Integrar PayPal’ está logrado al 100%, asignaremos 10 de valor de negocio completado.”
- **Metricas:** A veces, en la System Demo (especialmente en I&A final) se presentan métricas del PI: % de objetivo completado, etc. En demos intermedias, quizás solo indicativos (“completamos 3 de 5 features del PI, vamos 60%”).
- **Actualización de Program Board:** System Demo también es momento de revisar si el plan del PI sigue. Si en demo falta algo planificado, se menciona. Ej: “Notarán que la Feature X no la mostramos; está en curso y se integrará para la demo siguiente.” Business Owners pueden recalibrar expectativas.

**Beneficios del System Demo:**
- **Feedback integrado:** Stakeholders ven el *producto integrado real*. Esto puede revelar problemas de integración que en las team reviews no se ven. Ej: la feature de equipo A y B funcionan separadas, pero juntas hay un bug en la interfase – sale a la luz en System Demo, se crea una historia de fix.
- **Validación de hipótesis:** Si se trata de un prototipo temprano del sistema, stakeholders pueden decir “esto cumplirá la necesidad” o “falta ajuste mayor”, sin esperar a final de PI.
- **Cumplimiento de Principio “Objetivamente evaluar sistemas funcionando”:** Este demo provee ese punto objetivo donde en lugar de presentar PPTs, se evalúa un sistema real . Los ajustes se basan en lo observado, no en supuestos.
- **Regulación de Cadencia:** Saber que hay una demo integrada cada iteración motiva a equipos a integrar continuamente (no posponer), fomentando *Continuous Integration*. También crea ritmo para Business Owners, acostumbrados a ver progreso tangible frecuentemente, mejorando confianza.

**System Demo vs PI System Demo:** Cabe distinguir que al final del PI, en el evento I&A, se hace una **PI System Demo** que es básicamente la System Demo de la última iteración pero a menudo mostrando *todas* las features nuevas del PI en conjunto . Es una demostración final de todo el incremento de PI al completo. En PIs con muchos componentes, podría requerir más preparación o un evento un poco más grande con ejecutivos, etc.

**Ejemplo de descubrimiento en System Demo:** Supongamos en la System Demo de iteración 2 se ve que aunque cada parte funciona, la performance de la aplicación con todo activado es lenta. Eso es feedback crítico del sistema. Se decide inmediatamente crear una Spike de performance para iteración 3 y optimizar. Si no hubieran hecho System Demo, quizás ese problema se descubría mucho después, con más dificultad para corregir. 

**Sincronía con SoS/PO Sync:** Los hallazgos de System Demo alimentan la próxima PO Sync o incluso triggers para replanning si algo grave se vio. Por eso suelen programarse System Demos justo antes de una iteración IP o I&A, para consolidar el aprendizaje.

En resumen, la **Demostración del Sistema** es el momento de *“mostrar el valor integrado”* por el ART y **validar que ese valor cumple las expectativas**. Es una instancia de feedback sumamente poderosa a nivel programa. Un tren que consistentemente hace buenas System Demos raramente tendrá sorpresas desagradables al final del PI o en producción, porque está ajustando el rumbo iteración a iteración con ojos externos. Para los equipos, aunque es trabajo extra integrar todo, es gratificante ver la *solución completa* funcionando – les da perspectiva y refuerza la alineación con el objetivo global.

## 7. Mejorar de manera implacable

### 7.1 Mejorar el nivel de competencia
La frase “mejora implacable” (relentless improvement) en SAFe subraya que la organización nunca debe quedarse estática; siempre hay algo que aprender, alguna habilidad que desarrollar. “Mejorar el nivel de competencia” se refiere a elevar constantemente las capacidades (competencias) de los equipos y del ART en su conjunto.

Las **competencias** pueden ser técnicas (ej. aprender una nueva herramienta de automatización), de dominio de negocio (entender mejor la industria cliente), o competencias relacionadas con las 7 Competencias de Agilidad Empresarial (por ejemplo, mejorar en *Entrega Ágil de Producto* o en *Cultura de Aprendizaje Continuo*). 

Formas de mejorar competencias:
- **Formación y Entrenamiento:** Invertir en capacitación formal para el equipo. Por ejemplo, cursos de TDD, certificaciones, talleres de UX para desarrolladores, etc. Un ART maduro dedica parte de las IP (Iteración de Innovación y Planificación) a entrenamiento. Incluso hay IP Iterations donde se organizan *hackathons* o *dojos* de práctica. 
- **Communities of Practice (CoPs):** SAFe alienta la creación de CoPs – grupos voluntarios de personas de distintos equipos que comparten un interés (QA, DevOps, BA, UX, etc.) – que se reúnen periódicamente para compartir conocimiento, estándares, lecciones aprendidas. Esto difunde habilidades. Un tester aprende de otro tester de otro equipo técnicas de test exploratorio y lo lleva a su equipo.
- **Rotación de tareas/responsabilidades:** A veces, para ampliar competencia, se permite que miembros roten roles temporalmente. Ej: un dev hace de Scrum Master adjunto un sprint; un tester se involucra en diseño de historias con el PO; etc. Esto crea entendimiento multifuncional.
- **Mentoring y Coaching:** Agile coaches (internos o externos) observan equipos y les dan feedback sobre cómo mejorar. Senior engineers mentorizan a juniors. Un RTE puede hacer coaching a Scrum Masters para mejorar facilitación. 
- **Evaluación de Competencias (Assessments):** SAFe proporciona *Business Agility Assessments* y específicos por competencia. Un ART podría autoevaluarse (por encuestas) en qué nivel de madurez está en cada Core Competency. Por ejemplo, en *Team and Technical Agility*, preguntan: ¿usamos TDD regularmente? ¿Cumplimos DoD siempre? Califican y detectan áreas débiles. Luego planean acciones para elevar esas puntuaciones. Esto se puede repetir cada PI para ver progreso.
- **Dedicación de tiempo a Innovación y Mejora:** La Iteración IP es un espacio para esto. Los equipos pueden dedicar días a experimentar con nuevas tecnologías (mejorando competencia técnica), o hacer un “inspect & adapt” interno en áreas complicadas. Ej: un equipo decide usar 2 días de IP para que todos hagan un mini-curso de Docker porque notaron deficiencia en despliegues containerizados.
- **Mejorar entendimiento del negocio:** Competencia no es solo técnica; equipos mejoran su competencia de *dominio* pasando tiempo con usuarios o stakeholders. “Ir al Gemba” (sitio de trabajo del cliente) en Lean. Esto les hace más competentes para tomar decisiones orientadas al valor.
- **Herramientas y Procesos:** Aumentar competencia a veces implica adoptar nuevas herramientas o metodologías que amplíen capacidad. Por ejemplo, aprender a usar un framework de carga masiva para ser competente en test de performance (antes no lo hacían).

La mejora de competencia es *implacable* porque nunca se detiene. Cada PI, cada retrospectiva, se busca qué nuevas habilidades adquirir o qué nivel profundizar. Los líderes Lean-Agile fomentan una cultura donde **aprender es parte del trabajo**, no “lujo”.

**Ejemplo:** Un ART de desarrollo de firmware se da cuenta que su cuello de botella es probar en hardware, tardan mucho manualmente. Identifican que les falta competencia en automatización de pruebas de hardware. Deciden enviar a 3 ingenieros a un curso avanzado en laboratorio virtual de pruebas, y al volver esos ingenieros crean un grupo de trabajo que implementa un marco de pruebas automatizadas. En un par de PIs, toda el ART es más competente en testing automatizado, resultando en menos fallos y mayor ritmo.

**Medir la mejora:** Pueden usar indicadores: reducción en defectos, aumento en velocidad de entrega, encuestas de satisfacción del equipo con nuevas habilidades, etc. Por ejemplo, tras un entrenamiento de DevOps, mide si los despliegues son más frecuentes. Si se ve impacto, se refuerza continuar invirtiendo en las personas.

En resumen, un ART no solo entrega software, *se entrega a sí mismo mejora continua*. Un equipo SAFe practitioner en el examen debe reconocer la importancia de la *Cultura de Aprendizaje Continuo*: es uno de los pilares para mantener la agilidad en el tiempo. Sin crecimiento de competencias, se estanca la mejora de resultados.

### 7.2 Mejorar el flujo
“Mejorar el flujo” significa optimizar continuamente cómo el trabajo fluye por el sistema desde la concepción hasta la entrega, eliminando cuellos de botella y desperdicios para entregar valor más rápido y de manera más predecible. En SAFe, flujo se refiere tanto al **flujo de desarrollo** (ideación -> implementación -> release) como al **flujo dentro de cada equipo** (de una historia a través de su proceso). Es la aplicación práctica del pensamiento Lean: visualizar el flujo de valor y mejorar la eficiencia de ese flujo.

¿Cómo se mejora el flujo? Varias prácticas y métricas Lean ayudan:
- **Visualizar el flujo de trabajo:** Todos los niveles deben ver su “pipeline” de trabajo. Equipos usan tableros Kanban con columnas, ART usa Kanban de features/epics. Esta transparencia permite detectar acumulaciones (por ejemplo, muchas tareas “En pruebas” indica testing saturado).
- **Limitar WIP (Work In Process):** Un principio Lean es que demasiado trabajo en proceso a la vez atasca el sistema. Establecer límites explícitos (ej: “máximo 3 items in progress por persona” o en Kanban “máx 5 en testing a la vez”) fuerza a terminar antes de empezar más. Los equipos ajustan WIP limits en retrospectivas según sus observaciones. Menos WIP = ciclos más cortos, mejor calidad (porque enfoque).
- **Reducir tamaños de lote:** Dividir el trabajo en pedazos más pequeños reduce el tiempo de ciclo. Si una Feature tardaría 3 meses, intentar dividirla en sub-features entregables en PIs mensuales. En equipo, historias no más largas de una iteración. Esto hace el flujo más constante en lugar de “grandes entregas esporádicas”. Si se detecta que repetidamente arrastran historias entre iteraciones, eso indica lotes demasiado grandes – hay que partir más.
- **Gestionar la cola/prioridades:** Un backlog saturado y desordenado entorpece flujo. POs y PMs mantienen backlog limpio y priorizado. También evitar tener la cola (backlog) muy larga sin refinamiento, porque trabajo no preparado cuando llega genera esperas (baja flow).
- **Identificar y eliminar desperdicios:** Pueden aplicar los 8 desperdicios Lean (sobreproducción, espera, transporte, exceso de proceso, inventario, movimiento, defectos, talento no aprovechado). Ejemplo: *espera* – un equipo esperando aprobación externa, retarda flujo. Solución: delegar más autoridad (reduce espera). *Exceso de proceso* – formularios innecesarios, quítalos. Equipos en retrospectiva pueden mapear su proceso y marcar cada paso con valor/no valor y eliminar steps innecesarios.
- **Automatización para acelerar flujo:** Quitar labores manuales repetitivas en el flujo (como deployment manual, pruebas manuales repetitivas) e introducir automatización (CI/CD, test automáticos) acelera throughput.
- **Swarming (enjambre) en items importantes:** Si un item crítico atora, todo el equipo puede concentrarse en él para sacarlo adelante y restablecer flujo. Eso es preferible a todos en paralelo con items que luego todos quedan a medias.
- **Cadencia predecible:** Mantener iteraciones de duración fija crea ritmo. Principio 7 de aplicar cadencia reduce variabilidad en flujo. Saber que cada 2 semanas hay entrega obliga a cerrar cosas, evitando arrastrar. 
- **Métricas de flujo:** SAFe sugiere medir:
  - *Tiempo de flujo (Flow Time):* tiempo desde que se inicia un item hasta que se entrega . Reducirlo es objetivo clave.
  - *Velocidad de flujo (Throughput/Flow Velocity):* cantidad de items completados por unidad de tiempo  .
  - *Eficiencia de flujo:* proporción de tiempo activo vs tiempo total en sistema  (ej: historia estuvo 5 días activa, 5 días esperando en cola = 50% eficiencia). Se busca aumentar.
  - *Carga de flujo:* cuántos items en proceso simultáneo  (WIP).
  - *Distribución de flujo:* tipos de trabajo (feature vs tech debt vs maintenance)  – para ver si hay balance saludable.
  
  Revisando estas métricas por iteración/PI, se encuentran mejoras. Ej: un Flow Time promedio de 20 días por historia quizás se quiere bajar a 15 días. Identifican la mayor espera es en code review, entonces se mejora ese proceso (asignar más revisor o tiempo fijo para reviews).
- **Teoría de Colas & Variabilidad:** Lean dice que la alta utilización del 100% produce colas masivas (ej: si todos los devs siempre ocupados, cualquier tarea nueva espera mucho). Por ello a veces contrainutitivo: dejar capacidad para imprevistos (no planificar 100% develociad), que es la famosa “utilización al 80%” idea, mejora flujo global. También, absorber variabilidad con buffers (la IP iteration es un gran buffer).
- **Cadencia de sincronización:** We addressed, but ensuring dependencias se resuelven en sincronizaciones evita esperas prolongadas de “handoffs” mal coordinados.

**Ejemplo de mejora de flujo:** Un equipo nota que sacar una historia completada tarda 3 días en pruebas QA manuales al final de la iteración, creando cola al cierre. Deciden distribuir test durante la iteración en lugar de al final – tester colabora desde el día 1 por cada historia. Resultado: las pruebas se hacen escalonadas, no hay embudo al final. Flow Time de historias bajó. Además, deciden aprender y aplicar test automatizado de regresión, disminuyendo labor manual en siguientes PIs, lo que aceleró más el flujo.

**Otro ejemplo:** A nivel ART, supongamos las features pasan por un proceso: definidas por PM -> elaboradas -> implementadas -> aprobadas. Descubren que en “elaboradas” (definir detalles) se atascan muchas features esperando input legal. Causa: solo 1 persona legal para todo, saturada. Solución: entrenar a un BA en ciertos criterios legales para asumir parte, o involucrar legal más temprano. Este cambio reduce el tiempo en esa etapa, acelerando la entrada de features a implementación – mayor throughput de features por PI.

**Herramientas Lean:** Algunos ARTs hacen eventos de Value Stream Mapping (mapa de cadena de valor) donde dibujan cada paso desde idea hasta release, anotan tiempos de procesamiento vs espera. Identifican el paso más largo (punto crítico) y enfocan mejoras allí (Teoría de restricciones – aliviar el cuello de botella principal, luego el siguiente). 

**Constancia en mejora de flujo:** Cada I&A (Inspect & Adapt) al final del PI suele incluir revisar métricas de flujo del ART (predictability, etc.) y un taller de resolución de problemas. Muchas veces, los problemas detectados son de flujo: “Demoramos mucho en integración porque nos faltó entorno adecuado” – se decide mejorar eso. En retrospectivas locales de equipo, similar: “nuestra velocidad bajó por atender bugs urgentes – planeemos capacidad para bugs la próxima vez”.

La mejora del flujo es “implacable” porque siempre hay algo que optimizar. Incluso equipos altamente eficientes encuentran refinamientos (ej: reducir transición entre Dev y Ops, etc.). Este pensamiento de eliminación de desperdicio continuo es heredado de Lean manufacturing (Kaizen).

Para el exam SP, hay que reconocer prácticas como limitar WIP, batch sizes, addressing bottlenecks y usar métricas de flujo – todo deriva del Principio Lean-Agile #6 y es parte de Relentless Improvement. 

### 7.3 Mejorar los resultados
**Mejorar resultados** significa enfocarse en *mejorar el desempeño del ART en términos de valor de negocio entregado*, no solo en la eficiencia interna. Es llevar la mejora continua al plano de los **outcomes** (resultados concretos) que la empresa y clientes obtienen gracias al ART. En otras palabras, no es solo hacer “más rápido o con menos errores” (flujo y calidad), sino asegurar que se está haciendo lo *correcto* y logrando los objetivos deseados, y cada vez hacerlo mejor.

¿Cómo se mide y mejora resultados?
- **Objetivos de PI cumplidos (Predictability):** SAFe utiliza la *Medida de Predictibilidad del ART*, calculada al final de cada PI como porcentaje de business value achieved vs plan . Un ART previsible y saludable suele estar en 80-100% de logro de PI Objectives. Mejorar resultados podría ser reflejado en mantener ese rango (ni muy bajo, ni 100% exacto siempre porque puede indicar poco reto). Si un ART ve fluctuación (50% un PI, 120% otro), busca causas: compromisos mal hechos, alcance mal entendido – e intentar ser más consistente. Un SP exam question puede citar esta measure.
- **Indicadores de Negocio y Cliente:** Más allá de PI objectives internos, se deben rastrear métricas de valor:
  - *Satisfacción del cliente*: net promoter score (NPS), valoraciones, quejas.
  - *Uso del producto*: usuarios activos, frecuencia de uso de nuevas features.
  - *Resultados de negocio*: incremento de ingresos, reducción de costes, tiempo de respuesta al mercado.
  - *Calidad externa*: defectos en producción, tiempo de indisponibilidad.
  - *Cumplimiento objetivos estratégicos*: si la ART tenía objetivos como “expandir a X mercado” medir progreso real.
  
  Mejorar resultados significa moverse en la dirección correcta en estas métricas. Por ejemplo, si NPS era 30 y tras 2 PIs subió a 50, se mejoró resultado de cliente. O si la entrega continua ahora permite 4 releases/año en vez de 2, se mejoró time-to-market.
- **Hipótesis de Epics/Features validadas:** Cada Feature/Epic debería tener una hipótesis de beneficio. Mejorar resultados implica aumentar la tasa de acierto de esas hipótesis – o sea, que el trabajo entregado efectivamente genere el impacto esperado. Si se aprende de errores (feedback), el equipo de producto puede afinar su backlog para centrarse en items con mayor valor. Un outcome mejor### 7.3 Mejorar los resultados
Más allá de procesos y flujo, SAFe impulsa a mejorar continuamente los **resultados de negocio y de cliente** logrados por el ART. Esto implica medir el desempeño en términos de valor entregado y buscar cerrarla brecha entre lo planificado y lo obtenido, incrementando el impacto positivo en la organización.

Una métrica importante es la **Medida de Predictibilidad del ART**: compara el valor de negocio *planificado* vs *entregado* por cada equipo en un PI, y se resume como un porcentaje. Por ejemplo, si un equipo se comprometió a objetivos valuados en 40 puntos de negocio y entregó 35 (según evaluación de Business Owners), su predictibilidad es 88%. Un ART saludable suele lograr entre 80% y 100% en esa medida regularmente – lo que indica que planifica realista y cumple. Si la predictibilidad es baja (muy por debajo de 80%) o inconsistente, es área de mejora: quizá el ART está asumiendo demasiado (compromete más de lo que puede) o surgen muchas sorpresas. Mejorar resultados aquí significa **cumplir mejor los compromisos**, sea ajustando cómo se compromete (más realismo) o eliminando impedimentos que antes les impidieron alcanzar los objetivos.

Pero **mejorar resultados** no se limita a cumplir planes; también es mejorar el **valor intrínseco** entregado al cliente:
- Monitorear y elevar la **satisfacción del cliente** (ej. subir el NPS, reducir quejas de soporte).
- Conseguir **mejores métricas de producto**: más usuarios activos, mayor retención, transacciones más rápidas, menos caídas de servicio.
- Lograr **objetivos estratégicos**: por ejemplo, si el ART debía ayudar a reducir el tiempo de comercialización, medir que ahora lanzan features en 1 mes vs 3 meses hace un año, cumpliendo el objetivo.
- Aumentar el **ROI** de las inversiones: entregar más valor con esfuerzo similar (p. ej., mediante priorización correcta y no malgastando en features no usadas).

Para esto, el ART debe implementar un ciclo de **“construir-medir-aprender”**:
1. **Definir hipótesis de valor** para las iniciativas (features/épicas) con métricas esperadas. Ej: “Si implementamos chat en la app, esperamos aumentar satisfacción de soporte en 20%”.
2. **Medir resultados reales** tras entregar: encuestas, analíticas, ventas, etc.
3. **Aprender y ajustar**: Si el resultado no alcanzó la expectativa, analizar por qué. Quizá la hipótesis era errónea o la implementación insuficiente. Esto puede llevar a pivotar (cambiar enfoque) o iterar mejoras. Si sí alcanzó o superó, identificar prácticas exitosas a repetir.

SAFe promueve la transparencia en resultados. En el evento **Inspect & Adapt (I&A)** de cada PI, una actividad es revisar métricas objetivas del PI recién concluido: cumplimiento de PI Objectives, calidad (número de defectos), tiempo de ciclo, satisfacción de cliente (si se midió), etc. Con base en eso, se identifican acciones para mejorar. Por ejemplo, si se nota que cierta métrica de calidad bajó, se toma acción específica para el próximo PI (como más capacitación o refinar DoD). Así, *cada PI se usa como punto de aprendizaje para mejorar el siguiente en términos de outcomes*.

También es útil para el ART hacer retrospectivas a nivel de negocio ocasionalmente: ¿Estamos trabajando en las iniciativas correctas? ¿Hay formas de entregar más valor con menos costo? Esto puede involucrar a Lean Portfolio Management si se requiere realinear epics/objetivos.

**Ejemplo concreto:** Supongamos tras 2 PIs, el ART analiza que muchas features entregadas no están teniendo uso por clientes. Eso es un mal resultado: mucho esfuerzo, poco valor real. Deciden mejorar su enfoque de resultados incorporando más feedback de cliente en la priorización (mejora del flujo de *Continuous Exploration*), y adoptan la técnica de MVP (Producto Mínimo Viable) para probar en pequeño antes de desarrollar features enormes. En los siguientes PIs, ven que el porcentaje de features exitosas (usadas por clientes) sube. Han mejorado los resultados enfocándose en entregar *lo que sí agrega valor*.

En resumen, mejorar resultados es **afinar la efectividad** del ART: hacer lo necesario para que cada vez el esfuerzo conjunto produzca mayor valor tangible. Involucra alineación con objetivos estratégicos, satisfacción del cliente y realización de beneficios previstos. Con cada ciclo, el ART aprende de sus resultados pasados (buenos o malos) para incrementar su rendimiento futuro. Este foco incesante en resultados es lo que lleva finalmente a la **Agilidad Empresarial**: responder rápido a las necesidades y capturar oportunidades con éxito medible.

### 7.4 Comenzar el recorrido de mejora
La mejora continua en SAFe es un **recorrido sin fin**, pero dar los primeros pasos de ese camino puede ser desafiante. “Comenzar el recorrido de mejora” enfatiza que se debe *iniciar ya* la cultura de mejora, sin esperar condiciones ideales. SAFe provee un marco (eventos, principios) para institucionalizar la mejora, pero requiere voluntad y acción.

**Inspect & Adapt (I&A):** Al final de cada PI, el ART realiza el evento I&A, que consta de tres partes: PI System Demo, *Quantitativo* (repaso de métricas) y *Workshop de resolución de problemas*. En este último, los equipos y líderes juntos:
- Analizan las **principales problemáticas** que surgieron en el PI (pueden usar un *Fishbone diagram* o 5-Why para llegar a causas raíz).
- Identifican unas pocas causas raíz de mayor impacto.
- Proponen **soluciones factibles** (contramedidas) para esas causas.
- Esas soluciones se convierten en **Historias de mejora** o **Features de mejora** agregadas al backlog del próximo PI.
Por ejemplo, si la causa de frecuentes retrasos fue “falta de claridad en requisitos”, una solución podría ser “hacer refinamiento inter-equipo con más anticipación”; eso se concreta en una tarea planificada en el próximo PI (ej: agendar workshops de refinamiento). El resultado es que la mejora no queda en intención: se convierte en trabajo concreto a realizar.

**Cada ART mejora cada PI:** Esta frase del marco significa que con I&A repetido, el tren va subiendo de nivel iterativamente. Comenzar el recorrido es establecer ese hábito desde el primer PI. Incluso tras el primer PI pilot, hacer I&A sienta la base cultural de “siempre podemos ser mejores”. Ningún proceso inicial será perfecto, pero con el enfoque Kaizen, se mejorará.

**Pequeños pasos, grandes resultados:** SAFe recomienda enfocarse en mejoras viables en cada ciclo, no intentar cambiar todo de golpe. Por ejemplo, una mejora en un PI podría ser “vamos a implementar automatización de pruebas unitarias básicas”. En el siguiente, “ahora integremos análisis estático de código”. Poco a poco, acumulando mejoras, en un año el proceso del ART puede transformarse radicalmente en cuanto a calidad y velocidad.

**Cultura de seguridad para mejorar:** Para que aflore la mejora, es vital un ambiente donde los equipos se sientan seguros admitiendo problemas y errores. Los líderes deben fomentar la apertura (ej.: en retrospectivas, no culpar sino buscar soluciones conjuntas). “Mejora implacable” no significa culpar implacablemente, sino *aprender implacablemente*. *Fail fast, learn fast* – si algo salió mal en un PI, se asume como aprendizaje, no se esconde.

**Herramientas de mejora:** Además del I&A formal, la mentalidad de mejora se practica en:
- Retrospectivas de iteración (cada equipo afina su micro-proceso cada sprint, p. ej. “probemos estimar distinto porque nos hemos equivocado en esto”).
- Kaizen diario: Cualquier miembro puede sugerir una mejora en cualquier momento. Quizá entre iteraciones, un equipo reorganiza su tablero Kanban porque notó que otra visualización sería mejor. No esperar a retrospectiva para cada ajuste trivial.
- Experimentos controlados: Probar nuevas prácticas en un equipo o por un tiempo corto, y evaluar. Si funciona, extender. Ej: “Este PI, el Equipo 3 probará Mob Programming un día a la semana a ver si mejora calidad. Si resulta, más equipos lo adoptan”.

**Inicio de la Mejora para nuevos en SAFe:** Cuando una organización implementa SAFe, hay una **Curva de aprendizaje**. “Practicar SAFe” al comienzo implica seguir los eventos y procesos aún torpemente pero con disciplina. Tras cada ciclo, se reflexiona. Por ejemplo, tras la primera PI Planning, puede que identifiquen 10 cosas a hacer mejor la próxima vez (desde logística: “se nos acabó el tiempo en Team Breakout – reservemos más”, hasta conceptuales: “no involucramos lo suficiente a tal stakeholder – invitarlo la próxima”). Al aplicar esos ajustes, la siguiente PI Planning ya sale más fluida. Así se va dominando la práctica.

**Compartir y celebrar mejoras:** A medida que se implementan mejoras y dan frutos, es bueno comunicarlas y celebrarlas. “Gracias al esfuerzo en automatizar despliegues, este PI no tuvimos retrasos de release – ¡bien hecho equipo!” Este reconocimiento refuerza el comportamiento de mejora.

En conclusión, *comenzar* el recorrido de mejora significa no esperar a mañana: aprovechar **cada iteración y cada PI** para hacer retrospectiva, proponer cambios y experimentar. Con SAFe, esto está institucionalizado vía I&A y retrospectivas, pero depende de las personas ejecutarlo de verdad. La mejora constante es “implacable” porque nunca se da por terminada; siempre hay otro grado de madurez que alcanzar. Esta filosofía mantiene al ART competitivo y adaptativo en el largo plazo.

Al adoptar este ciclo de mejora continua, los equipos no solo mejoran su desempeño técnico, sino que también crecen en **moral y cohesión**, porque ven que sus ideas pueden cambiar positivamente su forma de trabajar. En última instancia, se trata de crear una **Cultura de Aprendizaje Continuo**, una de las 7 competencias de SAFe, donde la organización entera se vuelve experta en aprender de sí misma y reinventarse cuando hace falta. **El viaje de mejora comienza con el primer paso**, y en SAFe ese paso puede ser tan pronto como la primera retrospectiva o I&A del tren.

## 8. Práctica de SAFe
La “Práctica de SAFe” consiste en llevar todo lo aprendido a la realidad del día a día en tu equipo y ART. Tras entender los principios, roles, eventos y flujos, el siguiente paso es **aplicarlos consistentemente** en el trabajo. Esto implica compromiso, adaptación y colaboración continua.

**Aplicar el conocimiento:** Al regresar a su organización, un SAFe Practitioner comienza contribuyendo activamente en su ART:
- Participa en la **PI Planning** preparando su parte (refinando backlog de equipo) y colaborando con otros equipos durante el evento.
- En cada iteración, ejerce su rol (PO, SM o miembro del equipo) siguiendo las prácticas SAFe: planificar la iteración, colaborar en los Daily Stand-ups, mostrar el incremento en la Iteration Review y reflexionar en la retrospectiva para mejorar.
- Si es Scrum Master, facilita no solo en su equipo sino también apoya en eventos de ART (SoS, I&A). Si es Developer/Tester, colabora para cumplir DoD, automatizar pruebas, etc., elevando la calidad integrada. Si es PO, actúa de puente con Product Management y asegura mantener el backlog alineado al valor.

**Ajustar a la realidad:** Cada entorno tiene particularidades. Practicar SAFe no es seguir un libreto ciego; es adaptar las recomendaciones a tu contexto manteniendo los principios. Por ejemplo, si tu ART es distribuido globalmente, aprenderás a usar herramientas virtuales efectivas para PI Planning y syncs. Si tu producto es hardware, ajustarás las iteraciones para incluir desarrollo de prototipos físicos. La esencia de SAFe (colaboración, cadencia, flujo de valor) permanece, pero la implementación puede variar. Un buen Practitioner es flexible: *“Inspect and Adapt”* aplica también a cómo usan SAFe.

**Trabajo en equipo y comunicación:** SAFe es un esfuerzo de equipo de equipos. Practicarlo significa **comunicación constante**: levantando dependencias pronto, no esperando a que se vuelvan bloqueos; compartiendo conocimientos entre equipos; y fomentando la confianza. Recuerda los **Core Values**: *Transparencia* – sé abierto sobre problemas; *Orientación* – alinea tus decisiones con los objetivos comunes; *Calidad* – no comprometas la calidad en tu trabajo; *Ejecución* – cumple tus compromisos o renegocia abiertamente si no podrás.

**Apoyo continuo:** La práctica de SAFe no se hace en soledad. Apóyate en tu RTE, en los coaches, y en tus compañeros que también van aprendiendo. Por ejemplo, los **Communities of Practice** internos te ayudarán a resolver dudas (quizá un CoP de Scrum Masters donde discutes cómo mejorar la retrospectiva, o un CoP de DevOps compartiendo pipelines). La comunidad SAFe global también ofrece recursos (SAFe Studio, foros, conferencias) para seguir aprendiendo de experiencias de otros.

**Preparación para la certificación SP:** Si tu meta es certificarte como SAFe Practitioner, además de entender estos apuntes, la práctica es clave. Intenta relacionar cada concepto con algo que hayas visto o puedas imaginar en un proyecto real. Repasa términos clave (ver Glosario) y asegúrate de comprender no solo *qué es* cada cosa, sino *por qué existe* y *cómo interactúa con las demás*. Por ejemplo, no memorizar solo la definición de ROAM, sino entender cómo se utiliza en PI Planning para gestionar riesgos colaborativamente. La certificación evaluará tu entendimiento práctico (situacional) tanto como tu memoria.

**Iterar tu propia mejora:** A medida que practiques SAFe, aplica la mejora continua a ti mismo. Tras cada PI, reflexiona: ¿qué pude hacer mejor en mi rol? Quizá comunicar antes una dependencia, o mejorar cómo prioricé historias. Busca feedback de colegas y supérate en el próximo ciclo. Con el tiempo, serás un profesional más efectivo y versátil dentro del marco.

Por último, *practicar SAFe* es un proceso de **aprendizaje vivencial**. No te desalientes si al inicio las cosas son abrumadoras – es normal dado el alcance del framework. Empezar paso a paso, centrando en fundamentos (Lean-Agile mindset, entrega de valor al cliente, trabajo en equipo) te dará resultados incluso si no todo se aplica perfectamente. Recuerda que SAFe en sí evoluciona (vamos por versión 6.0), lo que refleja un espíritu de mejora permanente. Tú, como SAFe Practitioner, eres parte de esa evolución cada vez que encuentras una manera más eficiente de hacer las cosas en tu contexto.

En conclusión, estos apuntes te brindan un mapa teórico-organizativo. Ahora, la *práctica de SAFe* depende de cómo uses ese mapa para navegar los retos reales de tu tren ágil. Con mentalidad abierta, colaboración y perseverancia, estarás bien encaminado para impulsar la agilidad a escala en tu organización, y alcanzar el éxito en el examen SAFe® Practitioner (SP) y, más importante, en la entrega de valor continuo a tus clientes.

## Glosario de Términos Clave

- **Agile Release Train (ART) – Tren de Liberación Ágil:** Equipo de equipos (50-125 personas) que entrega una solución de manera continua y coordinada. Opera con sincronización de iteraciones y Program Increments. Incluye roles como RTE, Product Management, etc., y es la unidad básica de entrega en SAFe.
- **Business Owner (BO) – Responsable del Negocio:** Stakeholder clave del ART con responsabilidad de negocio y técnica sobre el valor entregado (ROI, gobernanza). Participa en PI Planning asignando valor de negocio a objetivos y velando alineación con la estrategia.
- **Cadencia:** Ritmo fijo y periódico para eventos y actividades. SAFe usa cadencias (ej. iteraciones de 2 semanas, PIs de 10 semanas) para aportar predictibilidad y sincronización entre equipos.
- **CALMR:** Acrónimo guía de la cultura DevOps: **C**ultura, **A**utomatización, **L**ean flow (Flujo Lean), **M**edición (Measurement) y **R**ecuperación. Define la mentalidad para implementar el **Continuous Delivery Pipeline**.
- **Capacidad (Capability):** Funcionalidad de alto nivel en soluciones grandes, que suele requerir múltiples ARTs para implementarse. Se subdivide en Features para ser entregada en un PI.
- **Continuous Delivery Pipeline (CDP) – Proceso de Entrega Continua:** Flujo de actividades automatizadas para idear, construir, validar y desplegar soluciones de forma continua. Incluye Exploración Continua (CE), Integración Continua (CI), Despliegue Continuo (CD) y Liberación Bajo Demanda.
- **DevOps:** Conjunto de prácticas y cultura que integra Desarrollo (Dev) y Operaciones (Ops) para habilitar entregas frecuentes y confiables. En SAFe, adopta CALMR e implementa pipelines automáticos de integración y despliegue.
- **DoD/DoR (Definition of Done/Ready):** Definición de listo/terminado. Criterios que debe cumplir un ítem antes de empezar (Ready) y al completarse (Done) para asegurar calidad incorporada en el proceso.
- **Epic – Épica:** Iniciativa de gran tamaño (portafolio o solución) que tiene una hipótesis de valor y normalmente requiere análisis y aprobación. Se descompone en Features para su implementación. Tiene un **Epic Owner** responsable y suele realizarse en varios PIs.
- **Feature – Característica:** Funcionalidad que aporta valor de negocio a un cliente o stakeholder, del tamaño adecuado para ser entregada por un ART en un PI. Se define con una **Hipótesis de Beneficio** y criterios de aceptación. Se divide en historias para su construcción.
- **Historia (Story):** Pequeña porción de funcionalidad que un equipo puede completar en una iteración. Escrita en formato usuario/negocio (Historia de Usuario) o técnica (Historia de Enabler). Incluye criterios de aceptación. Ejemplo: “Como [usuario] quiero [objetivo] para [beneficio]”. Variación: **Spike**, una historia tipo investigación o prototipo para aprender/resolver incógnitas.
- **House of Lean (Casa Lean):** Metáfora de pilares Lean en SAFe. Base: **Valor**. Pilares: **Respeto al gente y cultura**, **Flujo**, **Innovación**, **Mejora implacable**. Techo: **Objetivo** (valor). Representa la mentalidad Lean que deben adoptar equipos y líderes.
- **Inspect & Adapt (I&A) – Inspección y Adaptación:** Evento al cierre de cada PI para reflexionar y mejorar. Incluye la PI System Demo, revisión de métricas, y un taller de resolución de problemas y acciones de mejora. Genera historias de mejora para el siguiente PI.
- **Iteración (Sprint):** Ciclo de desarrollo corto, típicamente 2 semanas, donde un equipo planea, ejecuta, prueba y entrega un incremento de valor (historias completadas). Cada PI suele tener 4–6 iteraciones más una IP. Eventos clave: Planificación de Iteración, Daily Stand-ups, Revisión de Iteración, Retrospectiva.
- **Iteración IP (Innovation & Planning):** Iteración final de un PI dedicada a Innovación, Planificación y buffer. Se usa para hackathons, trabajo innovativo, finalizar pendientes, preparación de PI Planning e impartir entrenamiento. También durante IP se realiza el evento Inspect & Adapt.
- **Kanban del Equipo:** Tablero visual para gestionar flujo de trabajo. El Team Kanban gestiona historias del equipo con columnas (Por hacer, En curso, Hecho, etc.) y WIP limitado.
- **Lean-Agile Mindset – Mentalidad Lean-Agile:** Conjunto de creencias, actitudes y hábitos inspirados en Lean, el Manifiesto Ágil y el pensamiento sistémico. Incluye los pilares de la Casa Lean y los valores y principios SAFe. Es la cultura subyacente requerida para una implementación SAFe efectiva.
- **Objetivos del PI (PI Objectives):** Metas de negocio/técnicas que los equipos del ART se comprometen a lograr en el PI. Se consolidan a nivel ART. Pueden ser **comprometidos** o **estirados (stretch)**. Los Business Owners les asignan un valor de negocio (1–10) en PI Planning para indicar importancia, y luego al final del PI evalúan su logro.
- **Objetivos de Iteración:** Metas a corto plazo que un equipo se propone cumplir en una iteración, derivadas de las historias seleccionadas. Sirven para comunicar el propósito de la iteración a stakeholders y ayudar al equipo a enfocarse.
- **Portfolio SAFe (Nivel Portafolio):** Configuración de SAFe que agrega prácticas de gestión Lean de portafolio. Maneja Epics a través del **Portfolio Kanban**, alinea inversiones con estrategia mediante **Temas Estratégicos**, **Visión del Portafolio**, etc. (En SAFe for Teams, se menciona solo como contexto de dónde vienen algunas epics/estrategia).
- **Predictibilidad del ART:** Medida porcentual de qué tanto del valor de negocio planificado en los objetivos de PI se entregó realmente. Se calcula sumando para todos los equipos (por ejemplo, 100% indica todos los objetivos comprometidos se lograron; 80% es rango deseable; >100% ocurre si lograron objetivos stretch extra).
- **Product Owner (PO):** Rol a nivel equipo responsable de definir y priorizar el Team Backlog (historias) para maximizar el valor. Colabora con el equipo en clarificar requerimientos y acepta las historias terminadas. Asegura que el trabajo del equipo esté alineado con las necesidades del **Product Manager** (quien maneja backlog de programa).
- **Product Manager (PM):** Rol a nivel ART que gestiona el Program Backlog (features), define la Visión y Roadmap del producto, y prioriza features (a menudo con WSJF). Trabaja con clientes y stakeholders para entender necesidades. Durante PI Planning presenta la visión y prepara las features priorizadas.
- **Program Increment (PI)** Un **timebox** a nivel ART, usualmente de 8-12 semanas (por ejemplo 5 iteraciones + 1 IP) en el cual se entrega un incremento significativo de valor. Cada PI inicia con PI Planning y termina con un System Demo final e Inspect & Adapt. Equivale a un *sprint largo* del tren que agrupa las iteraciones.
- **PI Planning – Planificación del PI:** Evento obligatorio y cadenciado (cada inicio de PI) donde todo el ART planifica juntas las próximas iteraciones. Dura ~2 días. Resulta en objetivos de PI, plan por iteración de cada equipo, dependencias identificadas y un Program Board, así como riesgos ROAMed y un voto de confianza del plan.
- **Program Board (Tablero de planificación del ART):** Radiador visual creado en PI Planning que muestra, por iteración del PI, las Features que entregará cada equipo, las dependencias entre equipos (indicadas con flechas/post-its) y hitos importantes. Sirve para comunicar el plan global y destacar dependencias/huecos.
- **Release Train Engineer (RTE):** “Scrum Master” del ART. Líder servicial que facilita PI Planning, ART Sync (SoS/PO Sync), System Demos, I&A y en general coordina la ejecución del PI. Ayuda a eliminar impedimentos que afectan a múltiples equipos y promueve la mejora continua a nivel ART.
- **Retrospectiva:** Reunión al final de cada iteración (y también del PI a nivel ART) donde el equipo reflexiona sobre su proceso y dinámica para identificar mejoras. Es un componente clave de la **mejora implacable**, permitiendo ajustes frecuentes en la forma de trabajo.
- **Roadmap:** Calendario de alto nivel de las entregas futuras. El **PI Roadmap** detalla objetivos/feature previstos para los próximos pocos PIs (corto plazo). El **Roadmap a Largo Plazo** bosqueja hitos más allá (trimestres vista o más). Se actualiza constantemente con feedback y cambios de prioridad.
- **ROAM:** Acrónimo para clasificar el estado de los **riesgos** en PI Planning. Las categorías son:
  - **Resolved (Resuelto):** el riesgo se eliminó, ya no es un problema.
  - **Owned (Asumido):** alguien del ART se hace responsable de gestionarlo (tiene dueño para seguimiento).
  - **Accepted (Aceptado):** se reconoce que no se pueden tomar acciones efectivas; se acepta vivir con él y las posibles consecuencias.
  - **Mitigated (Mitigado):** se ha implementado o planificado una acción para reducir la probabilidad o impacto.  
  En PI Planning, tras identificar riesgos, el ART los discute y les asigna una de estas categorías. Solo los marcados Owned requieren seguimiento activo post-planificación.
- **Scrum of Scrums (SoS) / Coach Sync:** Reunión periódica (ej. semanal) de Scrum Masters/Team Coaches de los equipos de un ART, facilitada por el RTE, para sincronizar progreso, dependencias e impedimentos entre equipos. Permite coordinar la ejecución durante el PI. En SAFe 6.0 se usa “Coach Sync” para enfatizar que incluye a todos los coaches de equipo (no solo Scrum Masters).
- **Scrum Master / Team Coach:** Líder servicial de un equipo ágil. Facilita las ceremonias (Daily, Planning, Retro), elimina impedimentos y entrena al equipo en prácticas ágiles. Ayuda a coordinar con otros equipos (participando en SoS). “Team Coach” es un término inclusivo para contextos Kanban u otros donde “Scrum Master” puede no ser el título, pero el rol de coach de equipo persiste.
- **System Demo (Demostración del Sistema):** Evento regular al finalizar cada iteración donde el ART demuestra el estado integrado del sistema – es decir, las nuevas features de todos los equipos trabajando juntas en un entorno de prueba parecido a producción. Asisten stakeholders para proporcionar feedback del sistema completo, no solo piezas aisladas, muestra todo el valor entregado en el PI.
- **Valor de Negocio (Business Value):** Puntuación (1 a 10) que los Business Owners asignan a cada Objetivo de PI de un equipo durante PI Planning para indicar su importancia relativa. Al final del PI, se usa para evaluar objetivamente cuánto valor se logró (los BO puntúan de nuevo objetivos logrados). Esto alimenta la medida de predictibilidad. El “valor de negocio” es distinto de los puntos de historia (que son esfuerzo); aquí mide importancia/beneficio.
- **Velocidad (Velocity):** Cantidad de trabajo (en puntos de historia) que un equipo termina en una iteración. Se usa como referencia para planificar futuras iteraciones (capacidad esperada). Es histórica, no predeterminada. Ayuda a no sobrecargar al equipo durante planning.
- **Visión:** Descripción a mediano/largo plazo de hacia dónde va el producto o solución. Pinta el “final deseado” – qué problemas resolverá, en qué se diferenciará – para guiar a los equipos. Definida por Product Management con input de Business Owners y mercado. Se comunica en PI Planning para alinear a todos en el ART. La Visión de Portafolio opera a nivel más alto, alineando múltiples ARTs con la dirección estratégica.
- **WSJF (Weighted Shortest Job First):** Técnica de priorización usada para ordenar backlog de Features (y Epics) por valor relativo. Calcula un puntaje dividiendo el **Costo de Espera (valor + urgencia + reducción de riesgo)** entre el **tamaño (duración)** de la item. En SAFe, generalmente:
  - Costo de Espera = Valor de Negocio + Crítica por Tiempo + Reducción de Riesgo/Oportunidad habilitada.
  - Tamaño se suele aproximar con puntos (esfuerzo).  
  Un WSJF más alto indica que hacer ese trabajo produce mayor beneficio por unidad de tiempo, por lo que se atiende primero. Ayuda a Product Management a tomar decisiones económicas informadas.

!Intencion aprobar el examen SAFe Teams