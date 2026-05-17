# complex-networks-L6-motifs

Small project for motif analysis in complex networks.  
The notebook compares motif counts in a real Facebook graph vs a Barabási–Albert random graph, then checks robustness under random failures and targeted attacks.

## Repository contents
- `sample.ipynb` — full analysis workflow (motifs, plots, quick statistical checks, attack/failure scenarios)
- `facebook_graph.pkl` — real network used in the analysis
- `g_ba_model.pkl` — BA baseline graph for comparison

## Dataset
Source: https://networkrepository.com/fb-pages-tvshow.php

This dataset is a Facebook Pages network for TV shows. Nodes are pages and edges are links between pages (see source page for full definition/metadata).

The included `facebook_graph.pkl` has:
- **3,892 nodes**
- **17,262 edges**
- **undirected, connected graph**
