# Fault Impact Footprint Mapping in Power Networks

## Project Overview

Fault Impact Footprint Mapping in Power Networks is a graph-based simulation project that models how a fault at one location can affect other interconnected nodes in a power-network structure.

The project analyzes the impact of a simulated fault based on network connectivity and distance from the fault location, and visualizes the resulting impact across the network.

## Objectives

- Model an interconnected power-network structure.
- Simulate the impact of a fault at a selected network node.
- Identify network nodes affected by the fault.
- Quantify the relative voltage deviation caused by the simulated fault.
- Classify the level of impact across affected nodes.
- Visualize the fault impact across the network.

## Technologies Used

- Python
- NetworkX
- NumPy
- Matplotlib
- Google Colab
- Graph-Based Network Modeling
- Data Analysis and Visualization

## Methodology

1. Create a 20-node interconnected network using NetworkX.
2. Define Node 1 as the substation.
3. Select Node 6 as the fault location.
4. Calculate the normal voltage level of each node based on its shortest-path distance from the substation.
5. Apply distance-based voltage sag factors to simulate the effect of the fault.
6. Calculate the relative voltage deviation for each node.
7. Classify the impact as High, Medium, or Low based on the deviation.
8. Visualize the network and fault-impact distribution.

## Results

The simulation generates:

- A modeled interconnected power-network graph.
- A simulated fault at the selected fault node.
- Normal and fault-affected voltage values for network nodes.
- Relative voltage deviation for each node.
- High, Medium, and Low impact classifications.
- A visualization showing the distribution of fault impact across the network.

## My Contribution

- Worked on the implementation of the fault-impact analysis approach.
- Worked with a simulated power-network model and fault conditions.
- Contributed to identifying affected network components.
- Worked on analyzing and presenting the resulting fault-impact information.

## Project Structure

```text
fault-impact-footprint-mapping/
├── README.md
└── proj_fault.ipynb
```

## Applications

Fault-impact mapping can be useful for:

* Power-system fault analysis
* Identification of affected network components
* Understanding fault propagation
