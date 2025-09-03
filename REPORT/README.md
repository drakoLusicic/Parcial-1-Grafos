# 📑 Informe del Proyecto
### 📌 Introduccion
Este repositorio contiene el informe breve del proyecto desarrollado en torno a los algoritmos de consulta en grafos. El documento tiene como objetivo analizar y reflexionar sobre el uso de cada algoritmo, sus complejidades, decisiones de representación y limitaciones conocidas.

El informe se presenta como un complemento teórico al código y a las pruebas realizadas, proporcionando una visión más profunda sobre las decisiones adoptadas durante el desarrollo.

### 📜 Contenido del Informe
- **Cuando conviene cada algoritmo:**
  
  Explicación de los contextos y casos de uso más adecuados para BFS, Dijkstra, Floyd-Warshall, Bellman-Ford, A* y Prim/Kruskal (MST).
  
- **Complejidades y decisiones de representación:**
  
  Análisis de la eficiencia temporal y espacial de cada algoritmo, junto con la justificación de las estructuras de datos utilizadas (listas de adyacencia, matrices, etc.).

- **Limitaciones conocidas:**
  
  Identificación de restricciones y comportamientos particulares, como por ejemplo:
  - A* con heurística h=0 degenera en Dijkstra.
  - Bellman-Ford es más costoso que Dijkstra, pero necesario con aristas negativas.
  - Floyd-Warshall, aunque resuelve el problema de todos los pares, puede ser ineficiente en grafos muy grandes.

### 🙌 Importancia de incluir un informe en un proyecto tecnológico
La inclusión de un informe en un proyecto de programación o investigación tecnológica es fundamental porque:
- Permite documentar las decisiones técnicas adoptadas durante el desarrollo.
- Brinda un marco teórico que ayuda a comprender cuándo y por qué utilizar cada algoritmo.
- Expone las limitaciones y posibles mejoras, lo que facilita la evolución futura del proyecto.
- Ayuda a que otros estudiantes, docentes o programadores puedan replicar, validar o reutilizar el trabajo.
- Refuerza el aprendizaje, ya que obliga a reflexionar críticamente sobre lo realizado en lugar de limitarse a la implementación práctica.
