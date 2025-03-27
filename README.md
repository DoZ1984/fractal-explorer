# Explorador de Fractales en Tiempo Real

Este proyecto es una demostración de lo que se puede lograr con WebGL y shaders GLSL en menos de 100 líneas de código efectivo. Es un explorador interactivo de fractales que genera visualizaciones matemáticas complejas en tiempo real.

## 🌟 Características

- **Generación de Fractales en Tiempo Real**: Utiliza la GPU para calcular y renderizar fractales complejos a alta velocidad
- **Múltiples Tipos de Fractales**: Julia, Mandelbrot y Burning Ship
- **Interactividad Total**: Zoom, desplazamiento y exploración con el ratón o pantalla táctil
- **Esquemas de Color Dinámicos**: Varios modos de color con animaciones fluidas
- **Compartir Vistas**: Genera URLs para compartir exactamente lo que estás viendo
- **Optimizado para Rendimiento**: Funciona suavemente incluso en dispositivos móviles

## 🧠 ¿Por qué es impresionante?

Este proyecto demuestra varias técnicas avanzadas en un espacio de código muy reducido:

1. **Computación Paralela en GPU**: Utiliza WebGL para aprovechar el procesamiento paralelo masivo de la GPU
2. **Matemáticas Complejas**: Implementa algoritmos fractales completos en shaders GLSL
3. **Optimización de Rendimiento**: Mantiene altos FPS incluso con cálculos matemáticos intensivos
4. **Interactividad Fluida**: Maneja eventos de usuario y actualiza visualizaciones sin interrupciones
5. **Técnicas de Antialiasing**: Implementa suavizado logarítmico para bordes más naturales

## 🔧 Tecnologías Utilizadas

- **WebGL**: API de gráficos de bajo nivel para navegadores
- **GLSL**: Lenguaje de shaders para programación GPU
- **JavaScript**: Para la lógica de la interfaz y gestión de eventos
- **HTML5/CSS3**: Para la estructura y estilo de la aplicación

## 📈 Cómo Funciona

El código utiliza un shader de fragmentos que ejecuta cálculos matemáticos complejos para cada píxel de la pantalla en paralelo. Para cada punto en el plano complejo:

1. Aplica iterativamente la función fractal correspondiente
2. Determina si el punto escapa al infinito y a qué velocidad
3. Asigna colores basados en la velocidad de escape y el esquema seleccionado
4. Aplica efectos visuales adicionales como brillo en los bordes

Todo esto ocurre en tiempo real, permitiendo explorar los infinitos detalles de estas estructuras matemáticas fascinantes.

## 🚀 Pruébalo Ahora

Simplemente abre el archivo index.html en un navegador moderno o visita la [versión en línea](https://doz1984.github.io/fractal-explorer/).

---

Creado con ❤️ y matemáticas. Un proyecto que demuestra el poder de la programación moderna con código mínimo pero impactante.