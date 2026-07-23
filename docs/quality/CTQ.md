# Matriz CTQ - Critical to Quality

| ID | Necesidad del usuario/negocio | CTQ | Métrica | Umbral aceptable | Evidencia | Prioridad | Issue |
|---|---|---|---|---|---|---|---|
| CTQ-001 | El visitante necesita que la página cargue rápido, sin esperas largas | Rendimiento de carga | Tiempo de carga de la página (Lighthouse Performance) | <= 2 segundos / Score >= 85 | Reporte Lighthouse | Must | #1 |
| CTQ-002 | El visitante necesita navegar y contactar al negocio fácilmente desde cualquier dispositivo | Usabilidad y diseño responsivo | % de elementos visibles y funcionales en móvil y escritorio | 100% de secciones visibles sin scroll horizontal | Prueba manual en 2+ resoluciones | Must | #2 |
| CTQ-003 | El negocio necesita que la página esté siempre disponible y sin errores visibles | Confiabilidad del contenido | Enlaces rotos / imágenes caídas / errores de consola | 0 errores críticos | Validación HTML + revisión de consola del navegador | Should | #3 |

## Reglas de trazabilidad
- Cada CTQ deberá tener un issue asociado.
- Cada issue deberá indicar evidencia esperada.
- Ningún CTQ Must podrá cerrarse sin cumplir el DoD.