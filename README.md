# ADA6 - Implementación de Arboles
Este programa consiste en una estructura de tipo árbol. A partir del nodo raíz se crearan nodos hijo cuya información serán las raíces cuadradas de los nodo padre. Esto se logra mediante dos clases:
### Nodo:
En esta clase se se generan los modos hijos del árbol, cuya información serán las n ráices del nodo raíz dependiendo del índice del nodo hijo; también se generarán los niveles que el árbol tendrá, este definido por el usuario.

### Arbol:
Esta clase se encarga de imprimir todo el árbol usando identación en sus nodos y valores.

Después de definir las clases se crea un objeto a partir de la clase 'Arbol', dicha clse tiene dos parametros, 'valor_matriz' y 'max_nivel', que se definen mediante dos inputs del mismo nombre. Por último imprime el árbol mediante el llamado del objeto 'arbol' seguido de su función 'imprimir()'.
