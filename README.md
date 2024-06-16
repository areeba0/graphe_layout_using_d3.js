# GRAPHI - Graph Layout Website

# Overview
GRAPHI is a software for visualizing graph layouts using custom algorithms in D3.js. It enables users to upload an adjacency matrix, classify the graph type, and visualize it using various layout options tailored to the graph's characteristics.

![graphi_homepage](https://github.com/areeba0/graphe_layout_using_d3.js/assets/136759791/da70e94a-271b-438a-9da8-3a467bf13542)


The project is divided into several components, each handling a different type of graph layout. This README overviews the project structure, setup instructions, and a brief component description.

# Technologies
- html
- CSS
- javascript
- D3.js

# Features
- File Upload: Upload adjacency matrix files for graph visualization.
- Graph Analysis: Identify cycles, check connectivity, and classify the graph as a General Graph, Directed Acyclic Graph (DAG), or a Tree.
- Custom Layouts:
   -General Graph: Grid Layout, Chord Diagram.
   -DAG: Sugiyama Layout, Radial Sugiyama Layout.
   -Tree: Rheingold Tilford Layout, Icicle Layout.

# General Graph
- Grid Layout: Nodes are arranged in a grid based on chosen criteria such as alphabetical order or node degree.
- Chord Diagram: Nodes are arranged in a circular layout with edges represented as SVG curves.

# Directed Acyclic Graph (DAG)
- Sugiyama Layout: Nodes are layered based on the heuristic discussed in class, ignoring crossing minimization.
- Radial Sugiyama Layout: Similar to Sugiyama Layout but with nodes arranged radially.

# Tree
- Rheingold Tilford Layout: Bottom-up traversal using Depth First Search, with subtrees merged as discussed in class.
- Icicle Layout: Nodes are arranged in an icicle plot with equal-sized leaf nodes.
