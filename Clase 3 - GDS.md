Gestión Desarrollo de Software – 2025
Prof. Politi Raul
Clase 3 (Unidad 1)

Conceptos básicos de Ingeniería de Requerimientos

[Image with text "INGENIERIA DE REQUISITOS" and a lightbulb icon with gears]

1. Introducción
En el desarrollo de software, ningún proyecto puede tener éxito si no entiende correctamente lo que el cliente o usuario necesita.
La Ingeniería de Requerimientos (IR) es la disciplina que se encarga de identificar, documentar y mantener actualizadas esas necesidades, asegurando que el producto final las cumpla.
Frase clave: “Un software bien desarrollado pero con requerimientos mal definidos es un fracaso seguro.”

2. Definición
Según el IEEE, la Ingeniería de Requerimientos es:
“El proceso de establecer los servicios que un sistema debe proporcionar y las restricciones bajo las cuales operará y será desarrollado.”
En términos simples:
• Es descubrir qué se quiere.
• Documentarlo con claridad.
• Asegurarse de que todos lo entiendan igual.
• Mantenerlo actualizado si cambian las necesidades.

3. Objetivos de la Ingeniería de Requerimientos
1. Capturar las necesidades del cliente/usuario.
2. Definir el alcance del sistema.
3. Evitar malentendidos entre stakeholders.
4. Reducir cambios costosos en etapas avanzadas del proyecto.
5. Asegurar trazabilidad (poder vincular cada funcionalidad a su requerimiento original).

4. Tipos de requerimientos
4.1. Requerimientos funcionales
• Describen qué debe hacer el sistema.
• Ejemplo: "El sistema debe permitir a los usuarios registrarse con email y contraseña.”
• Son observables y medibles desde el comportamiento del software.

4.2. Requerimientos no funcionales
• Describen cómo debe comportarse el sistema o restricciones que debe cumplir.
• Ejemplo: “El sistema debe responder en menos de 2 segundos para 100 usuarios concurrentes.”
• Pueden incluir:
  o Rendimiento
  o Seguridad
  o Usabilidad
  o Compatibilidad
  o Escalabilidad

4.3. Requerimientos de dominio
• Vienen del área de negocio o industria específica.
• Ejemplo: En banca, “La transacción debe cumplir con la normativa PCI DSS.”

5. Etapas de la Ingeniería de Requerimientos
1. Elicitación
   o Técnicas para obtener información:
     ▪ Entrevistas
     ▪ Cuestionarios
     ▪ Observación de procesos
     ▪ Talleres colaborativos
     ▪ Prototipado rápido
2. Análisis
   o Detectar inconsistencias, ambigüedades y conflictos.
3. Especificación
   o Documentar de forma clara y estructurada (documento de especificación, historias de usuario, casos de uso).
4. Validación
   o Confirmar que los requerimientos reflejan fielmente lo que el cliente necesita.
5. Gestión de cambios
   o Mantener actualizada la lista de requerimientos si el contexto o las necesidades cambian.

6. Errores comunes en la gestión de requerimientos
• Requerimientos vagos: "El sistema debe ser rápido” (¿qué significa rápido?).
• No involucrar a todos los stakeholders relevantes.
• No priorizar: tratar todos los requerimientos como igual de importantes.
• No documentar: depender solo de conversaciones orales.
• No gestionar cambios: aceptar cambios sin análisis de impacto.

7. Herramientas y técnicas para trabajar requerimientos
• Modelos visuales: diagramas de casos de uso, diagramas de flujo, wireframes.
• Lenguajes estructurados: plantillas estandarizadas de historias de usuario.
• Software de gestión: Jira, Confluence, Trello, Azure DevOps.

8. Importancia en la gestión de desarrollo
Una buena ingeniería de requerimientos:
• Reduce el riesgo de retrabajo.
• Mejora la comunicación entre cliente y equipo.
• Facilita la estimación de tiempo y costo.
• Sirve como contrato funcional entre las partes.

Ejemplo real:
En 1999, la NASA perdió la sonda Mars Climate Orbiter porque un equipo usó unidades imperiales y otro métricas en la interpretación de requerimientos. Costo: 327 millones USD.

9. Cierre conceptual
• El documento de requerimientos es la base de todo el proyecto.
• Cualquier ambigüedad o falta de precisión inicial se multiplicará en costos y problemas en fases posteriores.
• La Ingeniería de Requerimientos no es un evento puntual: es un proceso continuo.

Preguntas de entrega – Clase 3
1. Define con tus palabras qué es la Ingeniería de Requerimientos.
2. Menciona la diferencia entre requerimientos funcionales y no funcionales, y da un ejemplo de cada uno.
3. Explica qué es un requerimiento de dominio y da un ejemplo de tu entorno local o conocido.
4. Nombra dos técnicas de elicitación de requerimientos y explica brevemente en qué consisten.
5. ¿Qué consecuencias puede tener no validar correctamente los requerimientos antes de empezar el desarrollo?
