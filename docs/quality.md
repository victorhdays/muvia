# Calidad y validación

Estado documentado el 26 de septiembre de 2026. Las cifras siguientes proceden de ejecuciones locales del proyecto privado.

| Capa | Evidencia | Límite |
|---|---|---|
| Flutter / Dart | Análisis sin incidencias y 157 tests aprobados | No sustituye pruebas en teléfonos |
| Backend | 104 tests aislados aprobados | SQLite usa sustitutos de funciones espaciales |
| Android | Compilación APK debug aprobada | No es una build firmada para distribución |
| PostGIS | 3 tests de integración disponibles | Excluidos por falta de instancia accesible |
| CI | Workflow de calidad preparado | Ejecución remota todavía no verificada |

## Qué se comprueba

- Procedencia de estimaciones y posiciones.
- Recorridos lineales y circularidad explícita.
- Comparación de alternativas con tiempos incompletos.
- Parsing de respuestas, estados y componentes de interfaz.
- Sustitución del proveedor de catálogo mediante inyección.
- Rechazo de configuraciones inseguras de producción y staging.
- Respuestas de salud sin detalles internos y control de CORS.

## Límites abiertos

La factibilidad de alcanzar el autobús, la validación espacial real, los horarios y las coordenadas incompletas siguen requiriendo trabajo. Las pruebas de mapas usan un entorno de red controlado; que aprueben no demuestra disponibilidad de mapas en campo.

## Distribución

El código, los datos internos, los binarios y las claves de firma no se distribuyen en este repositorio de presentación. La futura publicación en Play Store requiere su propio proceso de revisión, firma, privacidad y pruebas de lanzamiento.
