# Electric Grid Optimization

This project models and optimizes an interurban electrical grid using graph algorithms.

Cities are represented as vertices and possible transmission lines as edges.  
The objective is to compute an optimal network that connects all municipalities with minimum total cost.

## University project

This project was developed as part of a university course on **Data Structures and Algorithms**.

Some of the base data structures and graphical interface were provided as part of the coursework.  
My main contribution focuses on implementing the algorithm that computes the **optimal electrical network**.

## Optimization algorithm

The optimal grid is obtained by computing a **Minimum Spanning Tree (MST)** of the graph using **Kruskal’s algorithm**.

This algorithm selects the set of edges that connects all cities while minimizing the total cost of the network.

## Running the program

To run the graphical application:

1. Open the project in **BlueJ**.
2. Navigate to the folder: aplicaciones.
3. Execute the main method of the class GUIKruskal.
4. In the text field, enter one of the following problem instances: P1 or P2.
5. Press **Cargar Problema** and then **Calcular Óptima** to compute the optimal electrical network.

These correspond to two predefined problem instances included in the project.

## Technologies

- Java
- Graph algorithms
- Data structures
- BlueJ

