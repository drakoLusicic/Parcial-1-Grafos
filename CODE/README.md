# Código Fuente C++

### 📌 Algoritmos de Consulta en Grafos
Este repositorio contiene el código fuente en C++ del proyecto sobre algoritmos de consulta en grafos, desarrollado como aplicación de consola. El programa permite cargar, ejecutar y comparar distintos algoritmos clásicos sobre grafos ponderados, ya sean dirigidos o no dirigidos.

### ✨ Funcionalidades:
El programa desarrollado tiene como objetivo principal aplicar distintos algoritmos clásicos de consulta en grafos y mostrar sus resultados de forma clara y comparable. Para ello, permite cargar grafos (manualmente o desde archivo), ejecutar algoritmos de búsqueda y optimización, y finalmente visualizar la salida con rutas, costos y tiempos de ejecución.

Estas funcionalidades hacen posible estudiar desde recorridos simples como BFS, hasta algoritmos más complejos como Dijkstra, Floyd-Warshall, Bellman-Ford, A*, Prim y Kruskal, integrados en un mismo sistema. De esta manera, el programa sirve tanto para el análisis académico de los algoritmos como para experimentar con diferentes configuraciones de grafos y verificar su comportamiento.
#### 📋 Carga de grafos:
- Manualmente desde la consola
  
- Automáticamente desde un archivo de texto con formato predeterminado.

#### 📳 Algoritmos incluidos:
  - **BSF:** Algoritmo de búsqueda en anchura que recorre un grafo nivel por nivel, útil para encontrar el camino más corto en grafos no ponderados.
    
  - **DIJKSTRA:** Encuentra el camino más corto desde un nodo origen a todos los demás en un grafo con aristas de pesos no negativos.
    
  - **FLOYD-WARSHALL:** Algoritmo de programación dinámica que calcula las distancias mínimas entre todos los pares de vértices en un grafo.
    
  - **BELLMAN-FORD:** Determina el camino más corto desde un origen, incluso en grafos con pesos negativos, detectando ciclos negativos.
    
  - **A*:** Algoritmo de búsqueda informada que combina costo real y heurística para hallar el camino más corto de forma eficiente.
    
  - **PRIM/KRUSKAL (MST):** Algoritmos que construyen un árbol recubridor mínimo (MST) de un grafo ponderado, minimizando el costo total de conexión.
    
#### ✔️ Resultados mostrados:
- Distancia mínima

Código: https://drive.google.com/file/d/1F5_zyYAp6_EkDJM2Ru1kduMVBbmuLJjc/view?usp=drive_link
  
- Ruta/árbol encontrado
  
- Complejidad teórica usada
  
- Tiempo de ejecución medido
