# RefactorLab Pro - 15 Misiones de Diseño de Software

Este repositorio contiene una plataforma web interactiva ("RefactorLab") diseñada para evaluar competencias avanzadas en el diseño y arquitectura de código limpio (Clean Code) mediante simulaciones basadas en los patrones de refactorización de **Martin Fowler**.

## 🛠️ Contenido (15 Misiones Integradas)

El simulador evalúa en tiempo real, mediante reglas de análisis sintáctico, la resolución de 15 problemas clásicos ("Code Smells"):
1.  **Extract Method**: Aislamiento de lógica en métodos cohesivos.
2.  **Replace Magic Number**: Abstracción de literales numéricos a constantes.
3.  **Decompose Conditional**: Aclaración lógica de sentencias if/else.
4.  **Rename Variable**: Otorgamiento de semántica a identificadores vagos.
5.  **Inline Temp**: Eliminación de asignaciones innecesarias.
6.  **Extract Variable**: Clarificación de expresiones complejas.
7.  **Split Temporary Variable**: Corrección del principio de responsabilidad única en variables.
8.  **Remove Assignment to Parameters**: Mutabilidad protegida de inputs.
9.  **Guard Clauses**: Prevención del "Arrow Code" mediante salidas tempranas.
10. **Consolidate Duplicate Fragments**: Reubicación de código duplicado en ramificaciones.
11. **Consolidate Conditional**: Fusión de operadores lógicos condicionales.
12. **Remove Control Flag**: Abandono de patrones estructurados legacy (`boolean flag`) en favor de interrupciones de bucle (`break`).
13. **Encapsulate Field**: Implementación de ocultación de datos con getters/setters.
14. **Preserve Whole Object**: Reducción de parámetros largos pasando el objeto íntegro.
15. **Substitute Algorithm**: Utilización de la API Collections/Streams en lugar de bucles for-loop manuales.

## 🚀 Despliegue en el Aula mediante GitHub Pages

Puedes disponer del entorno completo en cuestión de minutos usando tu propio perfil de GitHub, sin necesidad de infraestructura de backend (100% Client-Side Javascript):

1. Sube los archivos `index.html` y `README.md` a la rama `main` de un repositorio nuevo (ej. `misiones-refactoring`).
2. Entra a **Settings > Pages** dentro de tu repositorio en GitHub.
3. En la sección **Build and deployment**, selecciona `Deploy from a branch`.
4. Elige la rama `main` y guarda.
5. Comparte la URL resultante (ej. `https://tu-usuario.github.io/misiones-refactoring/`) a través de vuestro LMS o plataforma educativa habitual.

## 🔑 Módulo Exclusivo para el Instructor

Como docente, dispones de un mecanismo de evaluación oculto (sin dependencias visibles en la UI) para cargar al instante el patrón de solución esperado propuesto por la literatura oficial:
* **Atajo rápido:** Pulsa `Ctrl + Shift + P` en el teclado.
* **Trigger gráfico:** Haz doble clic sobre el texto `🔒 Módulo Instructor` situado en la parte inferior del panel lateral izquierdo.
