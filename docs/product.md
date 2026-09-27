# Caso de producto

## Problema

Un mapa con líneas no basta para decidir cómo viajar. También importa saber en qué sentido circula una ruta, cuánto hay que caminar y qué parte de la información es una estimación. La especialización regional permite diseñar alrededor de esas preguntas, siempre que los datos locales estén verificados.

## Alcance

El prototipo utiliza recorridos demostrativos de Poza Rica y Coatzintla. El corredor regional previsto incluye Papantla y Tihuatlán, pero esa ampliación no se presenta como cobertura disponible.

El flujo principal permite seleccionar origen y destino, consultar alternativas directas y revisar el desglose del trayecto. Las posiciones de autobuses actuales son simuladas y se identifican como tales.

## Presentación visual

La portada editorial de Muvia usa una base azul oscuro, acentos claros y una línea abstracta de conexión. No representa una ruta de transporte.

Las capturas del README muestran componentes reales de Flutter en una vista de revisión: tarjeta de planificador, skeleton y estado con reintento. Se renderizan con fixtures de prueba, sin datos personales, ubicación del teléfono ni sesión de usuario. No son capturas de la aplicación publicada ni una demostración de GPS real.

## Criterios de experiencia

- Identificar la procedencia y la incertidumbre del tiempo estimado.
- Mantener útiles los estados vacíos y de error.
- Favorecer lectura, contraste y acciones claras.
- Preparar etiquetas semánticas y validar después con lectores de pantalla en dispositivos.

## Pendientes antes de uso operativo

Verificar que una unidad pueda alcanzarse después de caminar hasta la parada; cerrar casos de coordenadas desconocidas; comprobar calendarios, permisos y conectividad en campo. Las mejoras de accesibilidad actuales son una base de trabajo, no una certificación.
