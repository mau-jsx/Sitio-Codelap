# Sistema de Recomendación Musical

Un sistema interactivo que recomienda géneros musicales basado en tus preferencias de bandas de rock alternativo.

## Características principales

- Interfaz moderna con diseño de vidrio esmerilado (glassmorphism)
- Sistema de calificación de 1 a 10 para bandas populares
- Algoritmo de recomendación basado en TensorFlow.js
- Visualización atractiva de resultados con emojis y puntuaciones
- Diseño responsivo y adaptable a diferentes dispositivos

## Tecnologías utilizadas

- HTML5
- CSS3 (con efectos modernos como backdrop-filter)
- JavaScript (ES6)
- TensorFlow.js (para el cálculo de recomendaciones)

## Cómo funciona

1. El usuario califica bandas de rock/alternativo en una escala del 1 al 10
2. El sistema analiza estas calificaciones usando un modelo de álgebra lineal simple
3. Calcula la afinidad del usuario con diferentes géneros musicales
4. Muestra un ranking de géneros ordenados por preferencia

## Bandas incluidas

- Nirvana
- Nine Inch Nails
- Stone Temple Pilots
- Alice in Chains
- Marilyn Manson
- Tool
- Pearl Jam

## Géneros analizados

- Grunge
- Rock
- Industrial
- Alternative
- Metal
- Progressive

## Instalación y uso

No se requiere instalación. Simplemente abre el archivo HTML en cualquier navegador moderno:

1. Clona este repositorio o descarga el archivo HTML
2. Abre `index.html` en tu navegador
3. Califica las bandas según tus preferencias
4. Haz clic en "Mis Gustos Musicales" para ver tus resultados

## Personalización

Puedes modificar fácilmente:

- Las bandas editando el array `bands`
- Los géneros editando el array `genres`
- Las características de cada banda en `bandFeatures`
- El diseño CSS en la sección de estilos

## Contribuciones

Las contribuciones son bienvenidas. Por favor abre un issue o pull request para sugerir mejoras.

## Licencia

MIT License
