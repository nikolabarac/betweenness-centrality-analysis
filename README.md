# Betweenness Centrality Analysis

The objective of this analysis is to extract a specific transport network from OpenStreetMap using the `osmnx` library and perform betweenness centrality analysis on both nodes and edges. Two approaches are demonstrated: one combines both visualizations in a single static plot, while the other displays interactive maps of node and edge centrality results separately. 

The implemented functions are flexible and can be customized for enhanced visual presentation, different weighting schemes, or alternative OSM feature filters. Toward the end of the notebook, an example demonstrates how to generalize the functions using a custom OSM filter, allowing the analysis to be applied to a variety of transport networks.

Interactive maps functionality does not work in GitHub's preview mode. To fully experience the interactivity, it should be run locally.

## Example of Copenhagen Bike Network

![Screenshot of Betweenness Centrality Analysis](https://github.com/nikolabarac/betweenness-centrality-analysis/blob/master/combined_bc.png)

### Interactive Maps

![Screenshot of Betweenness Centrality Analysis](https://github.com/nikolabarac/betweenness-centrality-analysis/blob/master/nodes_bc_interactive.PNG)

![Screenshot of Betweenness Centrality Analysis](https://github.com/nikolabarac/betweenness-centrality-analysis/blob/master/edges_bc_interactive.PNG)

## Example of London Railway Network 

![Screenshot of Betweenness Centrality Analysis](https://github.com/nikolabarac/betweenness-centrality-analysis/blob/master/custom_filter_bc.png)

### Interactive Maps

![Screenshot of Betweenness Centrality Analysis](https://github.com/nikolabarac/betweenness-centrality-analysis/blob/master/custom_filter_nodes_interactive.PNG)

![Screenshot of Betweenness Centrality Analysis](https://github.com/nikolabarac/betweenness-centrality-analysis/blob/master/custom_filter_edges_interactive.PNG)
