# NetworkAnalysis

This repository contains a collection of jupyter notebooks in python for network analysis.

### BipartiteNetwork

This notebook describes the process of restructuring table data to make it suitable for representation as a network graph. The network is bipartite, i.e. it contains two different node types (treaties & countries) which only connect to the other node-set. The data was scraped from an online database (https://www.ieg-friedensvertraege.de/vertraege). See the PeaceTreaties notebook in the WebScraping repository.

The network graph is generated with networkX and visualized with networkX draw. For a more sophisticated visualization see this Observable notebook: https://observablehq.com/@yaslena/dynamic-network-graph
