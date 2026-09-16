# 🔍 Introducción a Grafos

## ¿Qué es un Grafo?

Un **grafo** es una estructura de datos compuesta por:
- **Vértices (Nodos)**: Representan entidades
- **Aristas (Edges)**: Conexiones entre vértices

### Notación Matemática
```
G = (V, E)
```
- V: Conjunto de vértices
- E: Conjunto de aristas (pares de vértices)

## Ejemplo Visual

```
    1 -----> 2
    |        |
    v        v
    3 -----> 4
```

En este grafo:
- **Vértices**: {1, 2, 3, 4}
- **Aristas**: {(1,2), (1,3), (2,4), (3,4)}

## Conceptos Clave

### 1. **Grado de un Vértice**
- Número de aristas conectadas a un vértice
- Ejemplo: El vértice 1 tiene grado 2

### 2. **Camino**
- Secuencia de vértices conectados por aristas
- Ejemplo: 1 → 2 → 4

### 3. **Ciclo**
- Camino que comienza y termina en el mismo vértice
- Ejemplo: 1 → 2 → 4 → 3 → 1

### 4. **Conectividad**
- Un grafo es **conexo** si hay un camino entre cualquier par de vértices
- Un grafo es **desconexo** si tiene componentes aisladas

## Propiedades Importantes

| Propiedad | Descripción |
|-----------|-------------|
| **Dirigido** | Las aristas tienen dirección (→) |
| **No Dirigido** | Las aristas no tienen dirección (--) |
| **Ponderado** | Las aristas tienen pesos/costos |
| **No Ponderado** | Las aristas no tienen pesos |
| **Acíclico** | No contiene ciclos |
| **Cíclico** | Contiene al menos un ciclo |

## Aplicaciones en el Mundo Real

- 🗺️ **Mapas y Navegación**: GPS, rutas
- 🌐 **Redes Sociales**: Conexiones entre usuarios
- 🔗 **Internet**: Routing de paquetes
- 🎮 **Videojuegos**: IA y pathfinding
- ⚙️ **Sistemas**: Dependencias entre tareas
- 🧬 **Biología**: Redes de proteínas

## Siguientes Pasos

Continúa con [Representación de Grafos](./02-representacion.md) para aprender cómo implementarlos en código.