# Pathway visualization

This is a simple Angular project implementing a force-directed graph visualization using D3.js.

## Project Overview

This project aims to demonstrate the integration of Angular with D3.js to create interactive force-directed graphs. The D3 force chart visualizes relationships between entities using a physics-based simulation.

### Key Features

- **Force-Directed Graph**: The project visualizes a force-directed graph, where nodes are connected by edges and positioned based on simulated physical forces.
- **Search and Highlight**: Users can search for specific nodes by their labels, and the corresponding node will be highlighted in the graph.
- **Zoom and Pan**: Users can zoom in and out of the graph and pan across the visualization canvas.
- **File Upload**: Users can upload JSON files containing graph data, and the graph will be dynamically rendered based on the uploaded data.
- **Dynamic Data Loading**: Enables dynamic loading of graph data by allowing users to upload JSON files containing node and edge information.
- **Text Box Creation**: Allows users to dynamically create text boxes on the canvas, providing a way to annotate or add additional information to the graph.
- **Hierarchical Navigation**: Supports hierarchical navigation through graph data, allowing users to explore different levels or layers of the graph.
- **Tooltip Display**: Displays tooltips with node details on hover, providing additional context and information about individual nodes.
- **Brush Selection**: Implements brush selection functionality to select multiple nodes within a defined area, facilitating targeted analysis of subsets of the graph.
- **Hierarchy stack**: Users can traverse between the different layers. Like user opened an ORGANELLE file and double click on a node, it will expand the child and also user can go back to that ORGANELLE file.

## Dependencies

The project uses the following dependencies:

- Angular (Core, HttpClient)
- D3.js
- Angular Material (for UI components)

## Installation

To install and run the project locally, follow these steps:

1. Clone the repository:
   ```
