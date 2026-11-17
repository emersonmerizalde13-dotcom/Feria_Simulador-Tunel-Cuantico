# Simulador del efecto túnel cuántico — UNEMI

## Uso
1. Abre esta carpeta en Visual Studio Code.
2. Abre `index.html` con Live Server, o directamente en un navegador moderno.
3. Ingresa al simulador y pulsa **📝 Realizar evaluación** en el panel derecho.
4. Introduce nombre y edad. Responde las diez preguntas (máximo dos intentos por pregunta).
5. Al finalizar se muestra la calificación sobre 10.

## Modificar y publicar
- `index.html`: estructura de la página y de la evaluación.
- `style.css`: colores, distribución y estilos.
- `script.js`: cálculos, animaciones, preguntas y evaluación.
- Para cambiar preguntas, edita el arreglo `preguntas` al final de `script.js`.
- Para publicar, sube **los tres archivos** al mismo directorio de tu alojamiento web.
- Los resultados se guardan en `localStorage` **solo en el navegador del participante**. No existe un registro centralizado para el docente; para eso se requiere un servidor o base de datos.
- Verifica el modelo físico con fuentes científicas antes de la presentación académica.

## Nuevas secciones educativas
Dentro del simulador se incluyen «Variables iniciales y ejemplo paso a paso», «Retos de aprendizaje» (5 retos con respuestas desplegables) y «Conceptos y fórmulas de apoyo». Se pueden editar directamente en `index.html` y sus estilos están al final de `style.css`.
