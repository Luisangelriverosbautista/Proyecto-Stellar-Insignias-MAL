Plan de Calidad Simplificado - Proyecto SCF de Stellar
1. Introducción

Este documento presenta un Plan de Calidad simplificado, diseñado para guiar el desarrollo de la aplicación Stellar MicroLoans dApp, un proyecto propuesto dentro de la Stellar Community Fund (SCF).
Basado en los principios de CMMI y MoProSoft, este plan busca garantizar que el producto final no solo funcione correctamente, sino que cumpla con los estándares de calidad de la industria y las expectativas de la comunidad Stellar.

El objetivo es proporcionar una estructura clara para el desarrollo, asegurando la calidad desde las etapas iniciales hasta el despliegue en producción.

2. Gestión de la Calidad del Proyecto

La gestión de la calidad es un proceso continuo que abarca todas las fases del proyecto, desde la planificación hasta el mantenimiento.

2.1. Métricas de Calidad

Métricas de Código:

Cobertura de Pruebas Unitarias: Porcentaje del código cubierto por pruebas automáticas.
Objetivo: ≥ 80%.

Métricas de Rendimiento:

Tiempo de Respuesta de la API: El tiempo promedio en que el sistema responde a solicitudes de micropréstamos.
Objetivo: ≤ 500 ms.

Métricas de Requisitos y Diseño:

Retroalimentación de Usuarios Beta: Calificación promedio en encuestas de usabilidad.
Objetivo: ≥ 4 de 5 estrellas.

Métricas de Seguridad:

Número de Vulnerabilidades Críticas Detectadas:
Objetivo: 0.

3. Procedimientos y Actividades de Calidad
3.1. Procedimientos de Revisión

Revisión de Requisitos: Antes del desarrollo, los requisitos de la dApp (funcionalidades de préstamos, pagos y reportes) serán revisados por el equipo y validados con miembros de la comunidad Stellar.

Revisión de Diseño: La arquitectura de smart contracts y la interfaz de usuario serán revisadas para prevenir problemas técnicos antes de su implementación.

Revisión de Código (Code Review): Todo el código será revisado por al menos un miembro del equipo antes de fusionarse con la rama principal. Se verificará seguridad, estilo y cumplimiento de estándares.

3.2. Políticas de Pruebas

Pruebas Unitarias: Cada smart contract y componente de la interfaz deberá contar con pruebas automatizadas que validen su correcto funcionamiento de forma aislada.

Pruebas de Integración: Validar la comunicación entre la dApp y la red Stellar.

Pruebas de Aceptación del Usuario (UAT): Se realizarán pruebas con un grupo de usuarios beta para verificar que el sistema cumple con las necesidades de la comunidad.

4. Gestión de la Configuración y Liberación

La gestión de la configuración asegura el control de las versiones de software y documentos.

Control de Versiones: El código y la documentación se gestionarán en GitHub, usando ramas para el desarrollo de nuevas funcionalidades y fusiones solo después de revisiones exitosas.

Etiquetado de Versiones (Versioning): Cada despliegue importante se marcará con una versión (ej. v1.0.0) para mantener un historial claro.

Plan de Liberación: Cada versión incluirá una lista de funcionalidades, calendario de despliegue y los procedimientos para comunicar cambios a la comunidad.

5. Documentación

La documentación es un entregable esencial de calidad.

Documentación de Código: Todo el código deberá estar comentado y cumplir estándares de legibilidad.

Manual del Usuario: Se entregará un manual sencillo que guíe a los usuarios en el uso de la dApp.

Documentación de Arquitectura: Se mantendrá un documento técnico con la arquitectura del sistema, flujos de datos y componentes utilizados.

Conclusión

Este plan servirá como guía práctica para el equipo responsable del proyecto Stellar MicroLoans dApp, garantizando que la calidad se integre en todas las fases del ciclo de vida del software. Con este enfoque, se busca entregar a la comunidad Stellar una solución confiable, segura y alineada con sus necesidades.
