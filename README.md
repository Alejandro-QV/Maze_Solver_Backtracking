# Maze Solver - Backtracking

Un solucionador de laberintos desarrollado en Python que utiliza el algoritmo **Backtracking** para encontrar una ruta desde un punto de inicio hasta un destino, considerando obstáculos y un sistema de vidas limitadas.

## Descripción

El laberinto se representa mediante una matriz bidimensional de 9 × 9, donde cada celda define una condición de movimiento. El algoritmo explora las rutas disponibles y retrocede cuando encuentra un camino inválido o se queda sin vidas.

## Características

- Representación del laberinto mediante matrices.
- Búsqueda automática del punto de inicio y destino.
- Detección de paredes y movimientos válidos.
- Sistema de vidas con penalizaciones por casillas especiales.
- Exploración de movimientos mediante recursividad.
- Uso de Backtracking para explorar rutas alternativas.
- Visualización de la ruta encontrada y de la matriz solución.

## Reglas del laberinto

| Símbolo | Significado |
|:---:|---|
| `I` | Punto de inicio |
| `F` | Punto de destino |
| `1` | Casilla transitable |
| `0` | Obstáculo o pared |
| `-1` | Resta una vida |
| `-2` | Resta dos vidas |

El jugador comienza con **3 vidas**. Si las vidas llegan a cero, la ruta explorada se considera inválida.

## Tecnologías utilizadas

- **Lenguaje:** Python 3
- **Conceptos:** matrices, funciones, recursividad y backtracking.

## Ejecución

1. Instala Python 3.
2. Descarga o clona este repositorio.
3. Ejecuta el archivo principal desde la terminal:

```bash
python laberinto.py
```

Si utilizas otro nombre para el archivo, reemplaza `laberinto.py` por el nombre correspondiente.

## Funcionamiento del algoritmo

1. Identifica las coordenadas de inicio y destino.
2. Verifica si cada movimiento es válido.
3. Explora las casillas adyacentes en cuatro direcciones: abajo, derecha, arriba e izquierda.
4. Actualiza las vidas al ingresar en casillas con penalizaciones.
5. Retrocede cuando una ruta no permite alcanzar el destino.
6. Muestra el resultado y la matriz de solución cuando encuentra una ruta válida.

## Objetivo académico

Aplicar el algoritmo Backtracking para resolver un problema de búsqueda de caminos, utilizando recursividad y control de restricciones dentro de una matriz.

---

**Proyecto académico | Python | Algoritmos y Estructuras de Datos**
