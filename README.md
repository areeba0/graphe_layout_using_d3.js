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
  ![grAPHI_fileupload](https://github.com/areeba0/graphe_layout_using_d3.js/assets/136759791/c9c7ca21-831b-4bed-9181-b7d631e51071)

- Graph Analysis: Identify cycles, check connectivity, and classify the graph as a General Graph, Directed Acyclic Graph (DAG), or a Tree.
- Custom Layouts:
   -General Graph: Grid Layout, Chord Diagram.
   -DAG: Sugiyama Layout, Radial Sugiyama Layout.
   -Tree: Rheingold Tilford Layout, Icicle Layout.

# General Graph

- Grid Layout: Nodes are arranged in a grid based on chosen criteria such as alphabetical order or node degree.
  ![grid](https://github.com/areeba0/graphe_layout_using_d3.js/assets/136759791/4302e171-0878-4702-90c3-7a66d3bd6fa4)


- Chord Diagram: Nodes are arranged in a circular layout with edges represented as SVG curves.
  ![chord1](https://github.com/areeba0/graphe_layout_using_d3.js/assets/136759791/7646c572-ecbe-4d95-a586-ddabd3d5c40c)


# Directed Acyclic Graph (DAG)
- Sugiyama Layout: Nodes are layered based on the heuristic discussed in class, ignoring crossing minimization.
  ![sg](https://github.com/areeba0/graphe_layout_using_d3.js/assets/136759791/fa46978f-71df-483f-bf20-22061cd43dca)


- Radial Sugiyama Layout: Similar to Sugiyama Layout but with nodes arranged radially.
  ![Screenshot 2024-06-16 181304](https://github.com/areeba0/graphe_layout_using_d3.js/assets/136759791/8c19b4a4-5e1c-4f91-8db2-f57652b550f6)


# Tree
- Rheingold Tilford Layout: Bottom-up traversal using Depth First Search, with subtrees merged as discussed in class.
  ![RT](https://github.com/areeba0/graphe_layout_using_d3.js/assets/136759791/a5992c6e-1a27-4858-952a-126760a248fc)


- Icicle Layout: Nodes are arranged in an icicle plot with equal-sized leaf nodes.
  ![ICICDE](https://github.com/areeba0/graphe_layout_using_d3.js/assets/136759791/5e8bdf81-d53c-4723-8fbe-18ff7ccf14aa)

