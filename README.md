# A-Search
Implementación del algoritmo de búsqueda **A\*** para encontrar el camino óptimo entre dos puntos de un laberinto generado proceduralmente. Trabajo de la asignatura de Inteligencia Artificial.
 Unity versión 6000.0.63f1
Controles

Tecla | Acción                                                                  
P: genera las posiciones de inicio (color naranja) y meta (color amarillo) 
C: clacula los pasos del algoritmo                                         
A: hace la animación del recorrido del camino calculado algoritmo          
M: muestra el camino óptimo             

## Cómo funciona

A* expande siempre el nodo con menor f(n) = g(n) + h(n):

- g(n): el coste real desde el inicio hasta el nodo.
- h(n): la heurística, distancia euclídea hasta la meta.

En cada iteración ("search") se toma el nodo actual y se evalúan sus 4 vecinos, descartando muros, límites del mapa y nodos en CLOSED, se añaden o actualizan en OPEN y se mueve a CLOSED el de menor f. Al llegar a la meta, "GetPath" reconstruye el camino siguiendo el "parent" de cada nodo hasta el inicio.

## Trabajo realizado por 

- Angeleau Pierre Jeudi ---> Enlace al Blog Ç("")
