

## Guía de Estudio Definitiva: Gestión de Desarrollo de Software – 2025

Este documento está estructurado siguiendo las unidades y clases del material, consolidando las definiciones clave y, fundamentalmente, respondiendo a las preguntas de cada sección para una preparación completa del examen.

### **Unidad 1: Fundamentos del Software y Requerimientos**

#### **Clase 1: Definición y Características del Software**
*   **Definición:** El software es el conjunto intangible de instrucciones, datos o programas que le indican a una computadora cómo realizar tareas específicas. Es la parte lógica que "da vida" al hardware.
*   **Definición Formal (IEEE):** “Conjunto de programas y procedimientos, junto con la documentación asociada, que permiten realizar determinadas tareas en un sistema informático.”
*   **Características Clave:**
    *   **Intangible:** No se puede tocar, pero su comportamiento es observable.
    *   **No se desgasta físicamente:** No sufre corrosión, pero sí **obsolescencia** o **"pudrición del software" (software rot)** cuando el entorno cambia o el mantenimiento es deficiente.
    *   **Complejo:** Incluso software simple puede tener miles de líneas de código e interdependencias.
    *   **Fácilmente replicable:** Copiarlo es trivial y no tiene el costo de fabricación de un producto físico.
    *   **Evolutivo:** Siempre está sujeto a cambios, mejoras y adaptaciones.
*   **Tipos de Software:**
    *   **Sistema:** Gestiona el hardware (Sistemas Operativos, Controladores).
    *   **Aplicación:** Tareas para el usuario (Navegadores, Hojas de cálculo).
    *   **Desarrollo:** Herramientas para crear software (Compiladores, IDEs).

#### **Clase 2: Diferencias entre Proceso y Producto de Software**
*   **Concepto Central:** El **producto** es "el qué" (el software entregado), mientras que el **proceso** es "el cómo" (las actividades y metodologías para crearlo).
*   **Producto:** Es el conjunto final de programas, datos y documentación. Se mide por su **calidad**, funcionalidades y satisfacción del usuario. Componentes: código ejecutable, documentación de usuario, documentación técnica.
*   **Proceso:** Es el conjunto estructurado de actividades para desarrollar, mantener y evolucionar el producto. Se mide por su **eficiencia**, productividad y cumplimiento de plazos. Actividades típicas: Especificación, Diseño, Implementación, Verificación y Mantenimiento.
*   **Relación:** Un buen proceso aumenta la probabilidad de un buen producto. Un mal proceso puede generar productos defectuosos, aunque el equipo sea talentoso. Es posible tener un buen producto con un mal proceso (ej., con "crunch" o trabajo excesivo), pero es un modelo insostenible y arriesgado.

#### **Clase 3: Conceptos básicos de Ingeniería de Requerimientos (IR)**
*   **Definición:** La disciplina para **identificar, documentar, validar y gestionar** las necesidades de los stakeholders para asegurar que el producto final las cumpla. Es la base de todo el proyecto.
*   **Tipos de Requerimientos:**
    *   **Funcionales:** Describen **QUÉ** debe hacer el sistema. Son observables y medibles. (Ej: "El sistema debe permitir registrarse con email y contraseña").
    *   **No Funcionales:** Describen **CÓMO** debe comportarse el sistema. Son restricciones de calidad. (Ej: "El sistema debe responder en menos de 2 segundos para 100 usuarios concurrentes").
    *   **De Dominio:** Vienen del área de negocio específica. (Ej: "La transacción debe cumplir con la normativa PCI DSS" para un sistema bancario).
*   **Etapas de la IR:**
    1.  **Elicitación:** Obtener la información (entrevistas, talleres, prototipos).
    2.  **Análisis:** Detectar inconsistencias, ambigüedades y conflictos.
    3.  **Especificación:** Documentar de forma clara (historias de usuario, casos de uso).
    4.  **Validación:** Confirmar con los stakeholders que lo documentado es correcto.
    5.  **Gestión de Cambios:** Manejar las modificaciones de forma controlada.
*   **Consecuencia de una mala IR:** El ejemplo real de la **sonda Mars Climate Orbiter de la NASA** (1999), que se perdió por una confusión entre unidades imperiales y métricas en los requerimientos, costando 327 millones USD.

### **Unidad 2: La Propuesta y Planificación Inicial del Proyecto**

#### **Clase 4: Elementos Clave de una Propuesta de Proyecto**
*   **Definición:** Documento formal que describe un problema, la solución propuesta, los recursos necesarios y los beneficios esperados. Su objetivo es **convencer** y obtener aprobación.
*   **Elementos Clave:**
    1.  **Portada y Resumen Ejecutivo:** La parte más importante para captar la atención.
    2.  **Contexto y Justificación:** El porqué del proyecto.
    3.  **Objetivos (General y Específicos):** El objetivo general es la meta global, los específicos son los resultados concretos y medibles que llevan a ella.
    4.  **Alcance Preliminar:** Qué se incluye y qué se excluye.
    5.  **Metodología, Recursos, Cronograma y Presupuesto:** Una visión inicial.
    6.  **Beneficios Esperados y Riesgos Preliminares.**

#### **Clase 5: Metodología para Elaborar la Propuesta de Proyecto**
*   **Flujo de Trabajo en 6 Etapas:**
    1.  **Recolección de Información Inicial:** Entender el problema real (entrevistas, análisis de datos). No saltar a la solución.
    2.  **Definición del Problema y Justificación:** Redactar el problema con datos concretos (Ej: "La empresa pierde $20.000 mensuales por...").
    3.  **Diseño de la Solución Propuesta:** Describir el enfoque a un alto nivel.
    4.  **Estimación de Recursos, Tiempo y Costos:** Dar una visión preliminar de la viabilidad.
    5.  **Identificación de Riesgos Preliminares:** Mostrar que se han previsto obstáculos.
    6.  **Redacción y Presentación:** Compilar todo de forma clara, profesional y persuasiva.

#### **Clase 6: Definición y Formulación Clara de Objetivos (SMART)**
*   **¿Qué es un Objetivo?** Un resultado deseado, no una tarea. Es una meta final o intermedia que permite evaluar el éxito.
*   **La Técnica SMART:** Un marco para que los objetivos sean efectivos.
    *   **S (Specific - Específico):** ¿Qué, quién, cómo, para qué?
    *   **M (Measurable - Medible):** Con indicadores cuantitativos/cualitativos.
    *   **A (Achievable - Alcanzable):** Realista con los recursos disponibles.
    *   **R (Relevant - Relevante):** Aporta valor real al cliente/organización.
    *   **T (Time-bound - Temporal):** Con un plazo definido.
*   **Ejemplo Corregido (de la clase):**
    *   **Mal Objetivo:** "Hacer una app para mejorar la comunicación con los clientes."
    *   **Objetivo SMART:** "Desarrollar una aplicación móvil para clientes del gimnasio (S) que permita agendar clases y recibir notificaciones, logrando un aumento del 20% en la asistencia a clases (M) y una reducción del 15% en consultas telefónicas (M) para el final del tercer trimestre (T), utilizando la infraestructura de servidores actual (A) para mejorar la retención de clientes (R)."

#### **Clase 7: Definición del Alcance del Proyecto y su Importancia**
*   **Definición:** Define los **límites** del proyecto. Establece qué trabajo se hará, qué entregables se generarán y **qué queda fuera**. Actúa como un "mapa" o contrato conceptual.
*   **Elementos Esenciales del Documento de Alcance:**
    *   Objetivos del proyecto.
    *   Descripción del producto/servicio.
    *   **Entregables:** Productos concretos (aplicación web, manual de usuario).
    *   **Criterios de aceptación.**
    *   **Exclusiones:** Lo que explícitamente no se hará.
    *   **Restricciones y Supuestos.**
*   **Scope Creep:** El riesgo más común de un alcance mal definido. Es el **crecimiento incontrolado del proyecto** por cambios no planificados, afectando tiempo, costo y calidad.

### **Unidad 3: Detallando el Alcance y los Interesados**

#### **Clase 8: Identificación y Documentación de Inclusiones**
*   **Definición:** Responden a la pregunta: “¿Qué es lo que **SÍ** está dentro del proyecto?”. Son los componentes, funcionalidades y resultados específicos que el equipo se compromete a entregar.
*   **Importancia:** Aportan claridad, evitan malentendidos y son la base para la planificación (cronograma, costos) y la medición del éxito.
*   **Documentación Sugerida:** Título, descripción breve, criterios de aceptación y dependencias.

#### **Clase 9: Identificación y Documentación de Exclusiones**
*   **Definición:** Responden a: “¿Qué es lo que **NO** se hará?”. Son funcionalidades, características o actividades que explícitamente no forman parte del proyecto.
*   **Importancia:**
    *   **Evitan malentendidos:** El cliente sabe qué no esperar.
    *   **Protegen al equipo de desarrollo:** Evitan trabajo extra no planificado.
    *   **Facilitan la gestión de cambios:** Si se quiere incluir algo excluido, se debe seguir un proceso formal.
    *   **Permiten priorizar recursos.**

#### **Clase 10: Registro y Gestión de Interesados del Proyecto (Stakeholders)**
*   **Definición:** Todas las personas, grupos u organizaciones que pueden influir en el proyecto o verse afectados por él (clientes, usuarios, desarrolladores, gerencia, etc.).
*   **Clasificación (Matriz de Poder-Interés):** Herramienta clave para definir estrategias de gestión.
    *   **Alto Poder / Alto Interés:** Gestionar de cerca, involucrar estrechamente.
    *   **Alto Poder / Bajo Interés:** Mantener satisfechos.
    *   **Bajo Poder / Alto Interés:** Mantener informados.
    *   **Bajo Poder / Bajo Interés:** Monitorear con mínimo esfuerzo.
*   **Registro de Interesados:** Documento que detalla quiénes son, su rol, intereses, nivel de influencia y la estrategia para gestionarlos.

### **Unidad 4: Criterios, Supuestos y Restricciones**

#### **Clase 11: Criterios de Aceptación de un Proyecto de Software**
*   **Definición:** Condiciones **específicas y verificables** que un producto, servicio o entregable debe cumplir para ser considerado aceptado por el cliente. Definen qué significa "terminado".
*   **Importancia:** Evitan malentendidos, son la base para las pruebas (testing), estandarizan la calidad y previenen retrabajos.
*   **Características:** Deben ser claros, medibles/verificables, alcanzables y relevantes.
*   **Documentación:**
    *   **Metodologías Tradicionales (Cascada):** En el documento de requerimientos.
    *   **Metodologías Ágiles (Scrum):** Dentro de cada historia de usuario.

#### **Clase 12: Análisis y Documentación de Supuestos del Proyecto**
*   **Definición:** Creencias, condiciones o afirmaciones que se consideran **verdaderas en el momento de planificar**, pero que no están 100% confirmadas.
*   **Relación con los Riesgos:** Un supuesto no validado es un **riesgo potencial**.
    *   **Supuesto:** "El cliente proveerá el contenido gráfico para la web a tiempo".
    *   **Riesgo:** Si el cliente no entrega el contenido, el desarrollo de la interfaz se retrasará.
*   **Importancia de Documentarlos:** Aportan claridad a la planificación, son la base para la gestión de riesgos y facilitan la toma de decisiones informada si un supuesto cambia.

#### **Clase 13: Identificación y Gestión de Restricciones del Proyecto**
*   **Definición:** Limitaciones o condiciones impuestas que el equipo debe respetar y que no pueden ser modificadas fácilmente. Condicionan la planificación y ejecución.
*   **La "Triple Restricción":** Modelo clásico que muestra la interdependencia entre:
    1.  **Tiempo:** Plazos de entrega.
    2.  **Costo:** Presupuesto.
    3.  **Alcance:** Funcionalidades.
    *Un cambio en una de ellas, inevitablemente afecta a las otras.*
*   **Otros Tipos de Restricciones:** Técnicas (uso obligatorio de una tecnología), de calidad, legales o normativas (GDPR), de recursos.

***

### **Preguntas Clave de Cada Clase y sus Respuestas**

Esta sección aborda directamente las preguntas de los PDFs para que puedas verificar tu conocimiento.

*   **Clase 2: Proceso vs Producto**
    *   **¿Podrías tener un buen producto con un mal proceso?** Sí, es posible, como en el caso de videojuegos exitosos desarrollados con mucho "crunch" (trabajo excesivo). Sin embargo, este modelo es arriesgado, insostenible, desmotivador para el equipo y no garantiza resultados repetibles. Un buen proceso busca que el éxito sea predecible y sostenible.

*   **Clase 3: Ing. de Requerimientos**
    *   **¿Qué consecuencias puede tener no validar correctamente los requerimientos?** Puede llevar al desarrollo de un producto que no resuelve la necesidad real del cliente (un fracaso funcional), generar retrabajo costoso en etapas tardías, crear conflictos entre el equipo y el cliente, y resultar en la pérdida de recursos y credibilidad, como en el caso de la sonda de la NASA.

*   **Clase 4: Propuesta de Proyecto**
    *   **¿Diferencia entre objetivo general y específicos?** El **objetivo general** es la meta global y de alto nivel (el "qué" final, Ej: "Optimizar la gestión de inventario de la farmacia"). Los **objetivos específicos** son las metas concretas, medibles y escalonadas que se deben cumplir para alcanzar el objetivo general (el "cómo", Ej: "1. Reducir las pérdidas por vencimiento en un 40%. 2. Automatizar el proceso de pedido a proveedores.").

*   **Clase 5: Metodología de la Propuesta**
    *   **¿Cuál es el primer paso al elaborar una propuesta y por qué?** El primer paso es la **recolección de información inicial** para **comprender el problema**. Es crucial porque sin un entendimiento profundo de la necesidad real, la solución propuesta podría ser irrelevante, ineficaz o no abordar la causa raíz del problema, llevando a una propuesta débil y a un proyecto fallido.

*   **Clase 6: Objetivos SMART**
    *   **¿Qué riesgos enfrenta un proyecto con un objetivo ambiguo?** Un objetivo ambiguo ("Mejorar el sistema") provoca desalineación (cada uno entiende algo distinto), imposibilidad de medir el éxito (¿cuándo está "mejorado"?), "scope creep" (se agregan tareas sin fin), desmotivación del equipo (no hay una meta clara) y una alta probabilidad de que el resultado final no satisfaga al cliente.

*   **Clase 7: Alcance del Proyecto**
    *   **¿Por qué las exclusiones son tan importantes?** Porque establecen límites claros, gestionan las expectativas del cliente (evitando que espere más de lo acordado), protegen al equipo de desarrollo del "scope creep", y ayudan a enfocar los recursos (tiempo y dinero) en lo que es verdaderamente esencial para el proyecto.

*   **Clase 9: Exclusiones**
    *   **¿Qué riesgos enfrenta un proyecto si las exclusiones no se documentan?** El riesgo principal es el **scope creep**, donde el cliente o los stakeholders asumen que ciertas funcionalidades están incluidas, generando discusiones, trabajo extra no planificado, retrasos en el cronograma y sobrecostos. También lleva a la desmotivación del equipo y a posibles conflictos contractuales.

*   **Clase 10: Stakeholders**
    *   **¿Cómo utilizarías la matriz de poder-interés para decidir el nivel de comunicación?**
        *   **Alto Poder/Alto Interés (Patrocinador):** Comunicación constante, detallada y proactiva (reuniones semanales, reportes de avance).
        *   **Alto Poder/Bajo Interés (Gerente General):** Comunicación concisa y ejecutiva para mantenerlo satisfecho (resumen mensual por email).
        *   **Bajo Poder/Alto Interés (Usuarios finales):** Comunicación regular para mantenerlos informados y gestionar sus expectativas (demos, newsletters).
        *   **Bajo Poder/Bajo Interés (Otro departamento):** Comunicación mínima o reactiva, solo cuando sea necesario.

*   **Clase 11: Criterios de Aceptación**
    *   **¿Qué problemas surgen si no se definen criterios de aceptación claros desde el inicio?** Surgen ambigüedades sobre cuándo una tarea está "terminada", lo que lleva a retrabajo; las pruebas de calidad no tienen una base objetiva sobre la cual validar el software; hay malentendidos y disputas con el cliente sobre si el producto cumple con lo esperado; y el equipo no tiene una definición clara de "hecho" (Definition of Done), lo que genera ineficiencia.

*   **Clase 12: Supuestos**
    *   **¿Qué relación existe entre supuestos y riesgos? Da un ejemplo.** La relación es directa: **un supuesto es una potencial fuente de riesgo**. Si un supuesto resulta ser falso, el riesgo asociado se materializa.
        *   **Supuesto:** "Se asume que la API de terceros para el procesamiento de pagos estará disponible y funcionará correctamente."
        *   **Riesgo:** Si la API presenta fallos o no está disponible, la funcionalidad de pago del sistema se verá bloqueada, retrasando el lanzamiento del proyecto.

*   **Clase 13: Restricciones**
    *   **¿Cuál es el impacto de no identificar las restricciones desde el inicio?** El impacto es severo: se crea un plan de proyecto **irrealista** que no considera las limitaciones existentes. Esto lleva a plazos y presupuestos que son imposibles de cumplir, a la elección de una arquitectura técnica inadecuada, y a un constante estado de crisis y re-planificación, aumentando la probabilidad de fracaso del proyecto.

***

### **Parte Práctica Resuelta: Sistema para Drugstore (Versión Completa y Detallada)**

**Proyecto:** Sistema de Gestión Integral para Drugstore "SaludTotal"

1.  **Funcionalidades (2 de c/u):**
    *   **Ventas:**
        1.  Registro de ventas mediante escaneo de código de barras, con cálculo automático de totales e impuestos.
        2.  Aplicación de descuentos por producto o por total de la venta.
    *   **Inventario:**
        1.  Control de stock en tiempo real, actualizándose automáticamente con cada venta o ingreso de mercadería.
        2.  Generación de un reporte de productos con stock por debajo del mínimo configurable para facilitar los pedidos.

2.  **Alcance (Descripción Total):**
    El proyecto consiste en el desarrollo de un sistema de escritorio para la gestión centralizada del punto de venta e inventario del drugstore "SaludTotal". El software deberá ser intuitivo para los cajeros, permitiendo un proceso de cobro ágil y sin errores. A su vez, proporcionará al administrador herramientas para un control de stock preciso, gestión de productos (precios, descripciones, stock mínimo) y la generación de reportes clave para la toma de decisiones. El objetivo es modernizar la operación, reducir pérdidas y optimizar el capital de trabajo inmovilizado en el inventario.

3.  **Inclusiones (4):**
    1.  Módulo de Punto de Venta (POS) con funcionalidad de apertura y cierre de caja diario.
    2.  Módulo de gestión de inventario que permita registrar ingresos de mercadería (compras a proveedores).
    3.  Reporte de ventas diarias y reporte de stock bajo.
    4.  Módulo de gestión de usuarios con dos roles: Administrador y Cajero, con permisos diferenciados.

4.  **Exclusiones (4):**
    1.  No se desarrollará una plataforma de e-commerce.
    2.  No se integrará con sistemas contables o de facturación electrónica. La facturación será manual o externa al sistema.
    3.  El sistema no gestionará programas de lealtad o puntos para clientes.
    4.  No se incluirá soporte para múltiples sucursales (el sistema es para una única tienda).

5.  **Stakeholders (4), Rol, Responsable y Matriz:**
    *   **Stakeholder 1:** **Ana Pérez (Dueña del Drugstore)**
        *   **Rol:** Patrocinadora. Responsable de aprobar el presupuesto, definir los objetivos de negocio y validar la entrega final.
    *   **Stakeholder 2:** **Carlos Gómez (Cajero Principal)**
        *   **Rol:** Usuario final clave. Responsable de participar en las pruebas de usabilidad y proveer feedback sobre el flujo de ventas.
    *   **Stakeholder 3:** **Distribuidora Farma (Proveedor Principal)**
        *   **Rol:** Proveedor Externo. Responsable de proveer listados de productos actualizados para la carga inicial.
    *   **Stakeholder 4:** **Equipo de Desarrollo (Liderado por el Gerente de Proyecto)**
        *   **Rol:** Equipo Interno. Responsable de diseñar, desarrollar y entregar el software cumpliendo el alcance.

    *   **Matriz de Poder-Interés (Ubicación):**
        *   **Ana Pérez:** Alto Poder / Alto Interés (Gestionar de cerca).
        *   **Carlos Gómez:** Bajo Poder / Alto Interés (Mantener informado, involucrar en pruebas).
        *   **Distribuidora Farma:** Bajo Poder / Bajo Interés (Monitorear).
        *   **Equipo de Desarrollo:** Alto Poder (sobre la ejecución) / Alto Interés (Gestionar de cerca).

6.  **Supuestos (3):**
    1.  Se asume que el drugstore proporcionará un listado completo y depurado de todos sus productos en formato Excel para la carga inicial de datos.
    2.  Se asume que los empleados dedicarán 4 horas semanales durante la fase de pruebas para la validación del sistema.
    3.  Se asume que no habrá cambios en la normativa fiscal que afecten el proceso de venta de productos de drugstore durante el desarrollo del proyecto.

7.  **Objetivo SMART (aplicar):**
    "Desarrollar e implementar el sistema de gestión de POS e inventario (S) en el drugstore 'SaludTotal' en un plazo máximo de 3 meses (T). El éxito se medirá por una **reducción del 90% en el tiempo dedicado al control manual de stock** y una **disminución del 30% en los errores de cobro** reportados en el primer mes de uso (M). Este objetivo es **alcanzable** con el equipo de dos desarrolladores asignado (A) y es **relevante** para mejorar la eficiencia operativa y la rentabilidad del negocio (R)."
