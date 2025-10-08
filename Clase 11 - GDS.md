Gestión Desarrollo de Software – 2025
Prof. Politi Raul
Clase 11 (Unidad 4)

Criterios de Aceptación de un Proyecto de Software

Introducción
En el ciclo de vida de un proyecto de software, uno de los aspectos más críticos es definir cuándo se considera que un producto está “terminado” y aceptado por el cliente o usuario final.
Para ello existen los criterios de aceptación, que son un conjunto de condiciones, parámetros o métricas que deben cumplirse para que el producto sea considerado satisfactorio.

Los criterios de aceptación representan la frontera entre lo que el equipo desarrolla y lo que el cliente espera recibir, garantizando claridad, transparencia y alineación de expectativas.

Definición
Los criterios de aceptación son condiciones específicas y verificables que un producto, servicio o entregable debe cumplir para ser considerado aceptado por el cliente, usuario o parte interesada.
Se establecen desde el inicio del proyecto (o en etapas tempranas) y se documentan claramente en los requerimientos, historias de usuario o especificaciones funcionales.

Importancia de los criterios de aceptación
1. Claridad de expectativas: Evitan malentendidos entre el cliente y el equipo de desarrollo.
2. Base para pruebas: Sirven como guía para el diseño de casos de prueba y validaciones.
3. Estandarización de calidad: Definen qué significa "terminado" para cada funcionalidad o entregable.
4. Prevención de retrabajos: Al dejar claros los límites de aceptación, se evitan devoluciones y cambios no planificados.
5. Facilitan la comunicación: Ayudan a que todas las partes (desarrolladores, testers, clientes, project managers) hablen el mismo idioma.

Características de unos buenos criterios de aceptación
- Claros y comprensibles: Evitar ambigüedades.
- Medibles y verificables: Deben poder comprobarse objetivamente (ejemplo: “el sistema debe cargar la página en menos de 2 segundos").
- Alcanzables y realistas: Deben estar dentro de las capacidades técnicas y del alcance definido.
- Relevantes: Deben estar alineados con los objetivos del proyecto.
- Específicos: Cada criterio debe corresponder a un requerimiento o funcionalidad concreta.

Ejemplos de criterios de aceptación
Funcionalidad:
- El usuario debe poder registrarse con correo electrónico y contraseña.
- Al registrarse, debe recibir un correo de confirmación en menos de 1 minuto.

Rendimiento:
- El sistema debe procesar 500 transacciones por minuto sin fallos.

Usabilidad:
- El formulario de registro debe estar disponible en español e inglés.

Seguridad:
- Las contraseñas deben almacenarse en la base de datos utilizando un algoritmo de encriptación seguro (por ejemplo, bcrypt).

Compatibilidad:
- La aplicación web debe funcionar correctamente en los navegadores Chrome, Firefox y Edge en sus últimas dos versiones.

Relación con metodologías ágiles y tradicionales
En metodologías tradicionales (cascada, RUP, etc.), los criterios de aceptación suelen estar incluidos en el documento de requerimientos y sirven como punto de validación al finalizar el desarrollo.
En metodologías ágiles (Scrum, Kanban, XP), los criterios de aceptación forman parte de las historias de usuario y se redactan como condiciones que deben cumplirse para considerar que la historia está “hecha”.

Ejemplo (Scrum):
Historia de usuario: "Como cliente quiero poder pagar con tarjeta de crédito."
Criterios de aceptación:
- El sistema debe validar la tarjeta en tiempo real.
- Debe mostrar un mensaje de confirmación en caso de éxito.
- Debe mostrar un mensaje de error si la tarjeta no es válida.

Documentación de los criterios de aceptación
Los criterios de aceptación pueden documentarse en:
- El documento de requerimientos (en cascada).
- Las historias de usuario (en ágil).
- Los planes de pruebas de aceptación.
- La matriz de trazabilidad de requerimientos, vinculando cada requerimiento con su criterio de aceptación y prueba asociada.

Conclusión
Los criterios de aceptación son una herramienta clave para garantizar calidad, satisfacción del cliente y alineación del equipo. Representan la definición objetiva de cuándo un entregable está listo y cumplen un rol fundamental tanto en proyectos ágiles como en enfoques tradicionales.
En definitiva, constituyen la base sobre la cual se mide el éxito de un proyecto de software.

Preguntas
1. Explica con tus palabras qué son los criterios de aceptación y por qué son importantes en un proyecto de software.
2. Menciona tres características que debe tener un buen criterio de aceptación y da un ejemplo práctico de cada una.
3. ¿Cómo se documentan los criterios de aceptación en metodologías ágiles frente a metodologías tradicionales?
4. Redacta tres criterios de aceptación para una historia de usuario: 'Como usuario quiero poder recuperar mi contraseña si la olvido'.
5. ¿Qué problemas podrían surgir en un proyecto si no se definen criterios de aceptación claros desde el inicio?
