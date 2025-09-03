# SUITE DE ALGORITMOS DE GRAFOS EN C++
### Integrantes: 
Ignacio Griboff; Drako Lusicic; Facundo Zampetti.;
### Introduccion:
En este repositorio se encuentra la documentacion con las explicaciones claras del concepto de Grafos y su aplicacion en diferentes algoritmos que calculan rutas con costos, saltos y obstaculos.
### Los algoritmos que se demuestran son:
  - BSF: Algoritmo de búsqueda en anchura que recorre un grafo nivel por nivel, útil para encontrar el camino más corto en grafos no ponderados.
    
  - DIJKSTRA: Encuentra el camino más corto desde un nodo origen a todos los demás en un grafo con aristas de pesos no negativos.
    
  - FLOYD-WARSHALL: Algoritmo de programación dinámica que calcula las distancias mínimas entre todos los pares de vértices en un grafo.
    
  - BELLMAN-FORD: Determina el camino más corto desde un origen, incluso en grafos con pesos negativos, detectando ciclos negativos.
    
  - A*: Algoritmo de búsqueda informada que combina costo real y heurística para hallar el camino más corto de forma eficiente.
    
  - PRIM/KRUSKAL (MST): Algoritmos que construyen un árbol recubridor mínimo (MST) de un grafo ponderado, minimizando el costo total de conexión.
    
Ademas se proporciona un sistema programado en lenguaje C++, que integra de manera homogenea todos los algoritmos basados en un grafo que puede ser cargado manualmente o mediante un archivo con un formato predeterminado, para la comprension del usuario y para la prueba de los diferentes algoritmos basandose en una sola funcion de carga manual y una de carga desde archivo compatible para los 6.
Como equipo esperamos que sea de facil comprension y lo disfrute!
