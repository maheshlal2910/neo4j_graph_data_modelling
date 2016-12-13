# neo4j_graph_data_modelling
This repostitory contains code snippets for the book Neo4J Graph Data Modelling.
Please feel free to download and use the snippets to understand data modelling in Graph databases better.


## Loading the Data
It may be useful to load all of the data for the book before starting reading. To load all of the data in one fell swoop on a POSIX based machine, clone this repo then run the following command 

```
find . -name "*cqy" -exec ../neo4j-shell --file {} \;
```
