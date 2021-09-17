INPUT:  Undirected Graph (Refer: http://snap.stanford.edu/data/index.html)

OUTPUT: Number of communities/partitions, overall modularity, and visualizing the communities

(Task: Optimization modularity to get the best partitions)
To keep in mind:

Dataset that come in different formats: txt, .net, .paj, .gml

Edge list (can’t represent isolated vertices unless it has self loop)

Many datasets on SNAP have different fields of data

Different data types

Reference (https://github.com/taynaud/python-louvain)

TEST CASES: FOR MODULARITY

Girvan Graph: 128 vertices, 4 communities

Every node within a community has 0 modularity

Modularity is between -1 and 1

Modularity for undirected graphs? (Does that mean a diGraph is converted to an undirected graph?)

Modularity of an edgeless graph is not defined

Modularity is not defined when nodes are not in the community 

Disjoint cliques have a modularity close to 1-1/numofcliques

Ring clique: Modularity = 1 - 1/ numofclique - numofclique / numoflinks


TEST CASES: FOR PARTITIONING (Incomplete list)

No partitions for directed graph

Ring cliques

Karate club

Random graph 

Induced graph

Test if the edge weights have changed

Complete graph of twice the size divided into 2
(yet to complete)
