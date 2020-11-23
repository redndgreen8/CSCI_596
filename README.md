# CSCI_596
## Variant Graph Visualization

I want to build a program for visualization of dense network graphs. The graphs I am interested in are variant or repeat graphs that aid in assembly of polymorphic regions of a human genome.


---

Here is an example of a variant graph called de-brujin graph.

**G=(V,E)**

V : k-mer representaion of variant in genome

E : overlap between two k-mers, Sequencing Reads


![De-brujin Graph](dbg.png)
*Identifying and Classifying Trait Linked Polymorphisms in Non-Reference Species by Walking Coloured de Bruijn Graphs.PLoS ONE*


## Current Setup 
1. Build graph by streaming reads across variants
2. Load onto gephi ![Gephi](download.png)
