# NetworkAnalysis

This repository contains a collection of jupyter notebooks in python for network analysis. 

Useful tutorials online:
- Exploring and Analyzing Network Data with Python by John R. Ladd, Jessica Otis, Christopher N. Warren, and Scott Weingart https://programminghistorian.org/en/lessons/exploring-and-analyzing-network-data-with-python (small size undirected graph)

- https://coderzcolumn.com/tutorials/data-science/network-analysis-in-python-important-structures-and-bipartite-graphs-networkx#5 

- https://ericmjl.github.io/Network-Analysis-Made-Simple/04-advanced/01-bipartite/ (especially for bipartite graphs)

The documentation for the networkx package can be found here: https://networkx.org/documentation/stable/index.html.

### BipartiteNetwork

This notebook describes the process of restructuring table data to make it suitable for representation as a network graph. The network is bipartite, i.e. it contains two different node types (treaties & countries) which only connect to the other node-set. The data was scraped from an online database (https://www.ieg-friedensvertraege.de/vertraege). See the PeaceTreaties notebook in the WebScraping repository.

The network graph is generated with networkX and visualized with networkX draw. For a more sophisticated visualization see this Observable notebook: https://observablehq.com/@yaslena/dynamic-network-graph
