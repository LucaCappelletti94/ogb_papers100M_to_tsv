# OGB papers100M to tsv
Convert the OGB's papers100M custom data format to TSVs.

[CURRENTLY UPLOADING DATA ON INTERNET ARCHIVE, I HAVE BAD INTERNET]

## What is OGB
The [Open Graph Benchmark (OGB)](https://github.com/snap-stanford/ogb) is a collection of datasets designed to facilitate research in graph machine learning (ML). It includes a diverse range of datasets covering a variety of domains, including social and information networks, biological networks, molecular graphs, source code abstract syntax trees (ASTs), and knowledge graphs. The OGB project provides a unified evaluation protocol with meaningful application-specific data splits and evaluation metrics for each dataset, as well as benchmark experiments to test the scalability and generalization of different approaches to graph ML. In addition, OGB includes an automated end-to-end pipeline for graph ML that simplifies and standardizes the process of data loading, experimental setup, and model evaluation.

## Why does this pipeline exist
One aspect of OGB that may be challenging for some users is that it includes a number of highly variable custom data formats that are not standardized. This means that it can be difficult to integrate OGB data into existing libraries without using the OGB Python library. If you want to access the OGB data directly using a language other than Python, you may need to deal with the Python library as a middleman. This may be inconvenient for some users, particularly if you want to avoid using Python in your workflow.

## Computing the data yourself

## Downloading the computed data

# Graph report

## OGB Papers 100M

The undirected graph papers100M has 111.06M heterogeneous nodes and 1.61G edges. The graph contains 151 connected components, with the largest one containing 111.06M nodes and the smallest one containing two nodes. The RAM requirements for the nodes and edge data structures are 8.85GB and 9.78GB, respectively.

### Degree centrality

The minimum node degree is 1, the maximum node degree is 251.47K, the mode degree is 1, the mean degree is 29.07, and the node degree median is 11.

The nodes with the highest degree centrality are 14812794 (degree 251.47K and unknown node type), 45749209 (degree 199.42K and unknown node type), 49187261 (degree 188.85K and unknown node type), 51155644 (degree 153.75K and unknown node type) and 78812714 (degree 102.95K and unknown node type).

### Node types

The graph has 172 node types, of which the 10 most common are arxiv cs sc (96.81K nodes, 0.09%), arxiv hep lat (84.67K nodes, 0.08%), arxiv cs se (78.36K nodes, 0.07%), arxiv cs ir (68.15K nodes, 0.06%), arxiv chem ph (44.68K nodes, 0.04%), arxiv physics ins det (42.73K nodes, 0.04%), arxiv q bio qm (35.24K nodes, 0.03%), arxiv cs mm (32.48K nodes, 0.03%), arxiv cs ar (31.93K nodes, 0.03%) and arxiv physics bio ph (30.20K nodes, 0.03%). The RAM requirement for the node types data structure is 2.71GB.

#### Unknown node types

Nodes with unknown node types are nodes with a node type that was not provided during the creation of the graph, which may be desired as the output of a node-label holdout. The graph contains 109.51M nodes with unknown node types, which are 0 (degree 1), 1 (degree 8), 2 (degree 7), 3 (degree 3), 4 (degree 5), 5 (degree 12), 6 (degree 46), 7 (degree 23), 8 (degree 44) and 9 (degree 10), plus other 109.51M nodes with unknown node types, making up 98.61 of the nodes.

### Topological Oddities

A topological oddity is a set of nodes in the graph that may be derived by an error during the generation of the edge list of the graph and, depending on the task, could bias the results of topology-based models. In the following paragraph, we will describe the detected topological oddities.

#### Node tuples

A node tuple is a connected component composed of two nodes. We have detected 87 node tuples in the graph, involving 174 nodes and 87 edges. The detected node tuples are:

-   Node tuple containing the nodes 108108175 (unknown node type) and 108782480 (unknown node type).
    
-   Node tuple containing the nodes 106972261 (unknown node type) and 109474651 (unknown node type).
    
-   Node tuple containing the nodes 106045523 (unknown node type) and 109039423 (unknown node type).
    
-   Node tuple containing the nodes 105375187 (unknown node type) and 108767955 (unknown node type).
    
-   Node tuple containing the nodes 99564587 (unknown node type) and 99722179 (unknown node type).
    
-   Node tuple containing the nodes 98775460 (unknown node type) and 109929289 (unknown node type).
    
-   Node tuple containing the nodes 98258927 (unknown node type) and 108593145 (unknown node type).
    
-   Node tuple containing the nodes 97225248 (unknown node type) and 100232243 (unknown node type).
    
-   Node tuple containing the nodes 97064774 (unknown node type) and 101130419 (unknown node type).
    
-   Node tuple containing the nodes 96784996 (unknown node type) and 97919012 (unknown node type).
    
-   Node tuple containing the nodes 96054592 (unknown node type) and 100895457 (unknown node type).
    
-   Node tuple containing the nodes 95376981 (unknown node type) and 96739755 (unknown node type).
    
-   Node tuple containing the nodes 94504261 (unknown node type) and 96272476 (unknown node type).
    
-   Node tuple containing the nodes 94438997 (unknown node type) and 96523165 (unknown node type).
    
-   Node tuple containing the nodes 93864953 (unknown node type) and 103914566 (unknown node type).
    

And other 72 node tuples.

#### Isomorphic node groups

Isomorphic groups are nodes with exactly the same neighbours and node types (if present in the graph). Nodes in such groups are topologically indistinguishable, that is swapping their ID would not change the graph topology. We have detected 106.96K isomorphic node groups in the graph, involving a total of 251.87K nodes (0.23%) and 6.50M edges (0.20%), with the largest one involving 195 nodes and 51.85K edges. The detected isomorphic node groups, sorted by decreasing size, are:

1.  Group with 29 nodes (degree 1.79K and unknown node type): 9546421, 15885567, 10172535, 49801124, 10898295 and other 24.
    
2.  Group with 32 nodes (degree 1.55K and unknown node type): 102838658, 102839998, 102829175, 102819571, 102843925 and other 27.
    
3.  Group with 33 nodes (degree 1.03K and unknown node type): 110335893, 110405824, 110358827, 110337667, 110324974 and other 28.
    
4.  Group with 44 nodes (degree 657 and unknown node type): 109022730, 108926302, 108887923, 108920200, 109008333 and other 39.
    
5.  Group with 2 nodes (degree 11.86K and unknown node type): 7673427 and 7900147.
    
6.  Group with 111 nodes (degree 207 and unknown node type): 108319265, 108312738, 108410665, 108385956, 108339480 and other 106.
    
7.  Group with 17 nodes (degree 952 and unknown node type): 74319032, 74298698, 73119721, 73490165, 73256945 and other 12.
    
8.  Group with 24 nodes (degree 652 and unknown node type): 74144295, 74067389, 73750842, 74004354, 73249420 and other 19.
    
9.  Group with 34 nodes (degree 381 and unknown node type): 74481038, 73888044, 73039673, 73096184, 73197120 and other 29.
    
10.  Group with 17 nodes (degree 759 and unknown node type): 58178651, 10177429, 59393970, 16252205, 74499999 and other 12.
    
11.  Group with 16 nodes (degree 769 and unknown node type): 103727554, 103745984, 103700834, 103758595, 103746881 and other 11.
    
12.  Group with 73 nodes (degree 166 and unknown node type): 74398533, 74277569, 72990041, 73353048, 73236476 and other 68.
    
13.  Group with 8 nodes (degree 1.37K and unknown node type): 73891446, 73559237, 73157867, 73581059, 73312138 and other 3.
    
14.  Group with 20 nodes (degree 539 and unknown node type): 105466402, 105472152, 105511129, 105528514, 105514939 and other 15.
    
15.  Group with 7 nodes (degree 1.53K and unknown node type): 50132822, 12524607, 10937267, 51050256, 15662517 and other 2.
    

And other 106.94K isomorphic node groups.

#### Trees

A tree is a connected component with n nodes and n-1 edges. We have detected 10 trees in the graph, involving a total of 65 nodes and 110 edges, with the largest one involving 9 nodes and 16 edges. The detected trees, sorted by decreasing size, are:

1.  Tree starting from the root node 328449 (degree 3), and containing 9 nodes, with a maximal depth of 3, which are 2367540, 5709515 (degree 3), 6079521 (degree 3), 1353552 and 3593280.
    
2.  Tree starting from the root node 90333328 (degree 2), and containing 9 nodes, with a maximal depth of 4, which are 83403283 (degree 3), 89811392, 82294666, 92787188 and 93791173.
    
3.  Tree starting from the root node 1826038 (degree 3), and containing 7 nodes, with a maximal depth of 2, which are 516134, 949535 (degree 4), 5456609, 679989 and 5899485.
    
4.  Tree starting from the root node 108814112 (degree 3), and containing 7 nodes, with a maximal depth of 2, which are 73090295, 86208414, 108831616 (degree 4), 77604399 and 101986241.
    
5.  Tree starting from the root node 5839376 (degree 2), and containing 6 nodes, with a maximal depth of 2, which are 5441024, 5578000 (degree 3), 5223431, 5213496 and 6303705.
    
6.  Tree starting from the root node 77998506 (degree 2), and containing 6 nodes, with a maximal depth of 2, which are 5265511 (degree 3), 78006877, 5364849, 46002503 and 78036642.
    

And other 4 trees.

#### Dendritic trees

A dendritic tree is a tree-like structure starting from a root node that is part of another strongly connected component. We have detected 114.22K dendritic trees in the graph, involving a total of 719.62K nodes (0.65%) and 1.44M edges (0.04%), with the largest one involving 2.44K nodes and 4.88K edges. The detected dendritic trees, sorted by decreasing size, are:

1.  Dendritic tree starting from the root node 12303941 (degree 5.85K), and containing 2.44K nodes, with a maximal depth of 3, which are 21794, 22334, 38011, 41433 and 41555.
    
2.  Dendritic tree starting from the root node 57425067 (degree 35.76K), and containing 2.17K nodes, with a maximal depth of 4, which are 57056258, 57512793, 58166459, 59031382 and 60837622.
    
3.  Dendritic tree starting from the root node 48012433 (degree 37.89K), and containing 1.56K nodes, with a maximal depth of 4, which are 3147379, 11695037, 12220688, 58427778 and 58820203.
    
4.  Dendritic tree starting from the root node 74065759 (degree 7.76K), and containing 1.41K nodes, with a maximal depth of 3, which are 1801, 67645, 117834, 132271 and 133465.
    
5.  Dendritic tree starting from the root node 59572249 (degree 34.14K), and containing 809 nodes, with a maximal depth of 3, which are 56709921, 56761568, 57192818, 57285760 and 57344502.
    
6.  Dendritic tree starting from the root node 20756471 (degree 2.90K), and containing 716 nodes, with a maximal depth of 4, which are 423476, 891077, 1122635, 1255379 and 1393612.
    

And other 114.22K dendritic trees.

#### Stars

A star is a tree with a maximal depth of one, where nodes with maximal unique degree one are connected to a central root node with a high degree. We have detected 45 stars in the graph, involving a total of 186 nodes and 282 edges, with the largest one involving 9 nodes and 16 edges. The detected stars, sorted by decreasing size, are:

1.  Star starting from the root node 109366892 (degree 8), and containing 9 nodes, with a maximal depth of 1, which are 55765870, 64282326, 77560705, 79973951 and 80690961.
    
2.  Star starting from the root node 109322245 (degree 8), and containing 9 nodes, with a maximal depth of 1, which are 80657653, 85371817, 102380991, 105299546 and 105623853.
    
3.  Star starting from the root node 108607601 (degree 7), and containing 8 nodes, with a maximal depth of 1, which are 66086596, 77529183, 82201504, 83146771 and 85661422.
    
4.  Star starting from the root node 9623788 (degree 6), and containing 7 nodes, with a maximal depth of 1, which are 1725003, 5232689, 5279567, 5405581 and 5417195.
    
5.  Star starting from the root node 5992752 (degree 6), and containing 7 nodes, with a maximal depth of 1, which are 2481491, 5352434, 5366039, 5823377 and 6102782.
    
6.  Star starting from the root node 4920284 (degree 5), and containing 6 nodes, with a maximal depth of 1, which are 5014297, 5636782, 5806866, 6005779 and 6229172.
    

And other 39 stars.

#### Dendritic stars

A dendritic star is a dendritic tree with a maximal depth of one, where nodes with maximal unique degree one are connected to a central root node with high degree and inside a strongly connected component. We have detected 2.22M dendritic stars in the graph, involving a total of 6.12M nodes (5.51%) and 12.24M edges (0.38%), with the largest one involving 602 nodes and 1.20K edges. The detected dendritic stars, sorted by decreasing size, are:

1.  Dendritic star starting from the root node 72995056 (degree 3.89K), and containing 602 nodes, with a maximal depth of 1, which are 558618, 812063, 941149, 1367045 and 3109975.
    
2.  Dendritic star starting from the root node 41971496 (degree 2.08K), and containing 489 nodes, with a maximal depth of 1, which are 1744, 23904, 25382, 26723 and 49497.
    
3.  Dendritic star starting from the root node 12566545 (degree 14.91K), and containing 446 nodes, with a maximal depth of 1, which are 7861356, 8146048, 8246626, 8444813 and 9233592.
    
4.  Dendritic star starting from the root node 12481765 (degree 6.23K), and containing 274 nodes, with a maximal depth of 1, which are 369081, 869419, 1164192, 2530874 and 2613725.
    
5.  Dendritic star starting from the root node 55892907 (degree 9.89K), and containing 273 nodes, with a maximal depth of 1, which are 302852, 443485, 759386, 1287795 and 1996513.
    
6.  Dendritic star starting from the root node 85563027 (degree 17.90K and unknown node type), and containing 270 nodes, with a maximal depth of 1, which are 594028 (unknown node type), 1044885 (node type arxiv astro ph), 1507511 (unknown node type), 1597537 (unknown node type) and 1602811 (unknown node type). Its nodes have 22 node types, of which the 10 most common are arxiv cs ir (29 nodes), arxiv physics ins det (10 nodes), arxiv hep lat (8 nodes), arxiv cs sc (7 nodes), arxiv chao dyn (6 nodes), arxiv stat me (6 nodes), arxiv math ph (5 nodes), arxiv math sg (4 nodes), arxiv q bio qm (3 nodes) and arxiv dg ga (3 nodes).
    

And other 2.22M dendritic stars.

#### Dendritic tendril stars

A dendritic tendril star is a dendritic tree with a depth greater than one, where the arms of the star are tendrils. We have detected 113.60K dendritic tendril stars in the graph, involving a total of 551.55K nodes (0.50%) and 1.10M edges (0.03%), with the largest one involving 287 nodes and 574 edges. The detected dendritic tendril stars, sorted by decreasing size, are:

1.  Dendritic tendril star starting from the root node 19641360 (degree 613), and containing 287 nodes, with a maximal depth of 3, which are 3092684, 5219263, 5263359, 5297125 and 5310131.
    
2.  Dendritic tendril star starting from the root node 45378575 (degree 1.93K), and containing 284 nodes, with a maximal depth of 2, which are 771788, 943203, 1684354, 3491116 and 3619863.
    
3.  Dendritic tendril star starting from the root node 66279871 (degree 952), and containing 261 nodes, with a maximal depth of 2, which are 710752, 809841, 1929016, 4322969 and 4501770.
    
4.  Dendritic tendril star starting from the root node 25776882 (degree 1.40K), and containing 243 nodes, with a maximal depth of 2, which are 266701, 549888, 775419, 793304 and 1144474.
    
5.  Dendritic tendril star starting from the root node 85578003 (degree 588), and containing 230 nodes, with a maximal depth of 2, which are 374912, 678297, 781046, 1018767 and 1049195.
    
6.  Dendritic tendril star starting from the root node 22000818 (degree 395), and containing 204 nodes, with a maximal depth of 2, which are 97274, 402507, 442266, 643726 and 689643.
    

And other 113.60K dendritic tendril stars.

#### Free-floating chains

A free-floating chain is a tree with maximal degree two. We have detected 3 free-floating chains in the graph, involving a total of 12 nodes and 18 edges. The detected free-floating chains are:

-   Free-floating chain starting from the root node 63044200 (degree 2), and containing 4 nodes, with a maximal depth of 2, which are 33227119, 65052084 and 78022663.
    
-   Free-floating chain starting from the root node 88228893 (degree 2), and containing 4 nodes, with a maximal depth of 2, which are 91360200, 91992940 and 98962572.
    
-   Free-floating chain starting from the root node 89511966 (degree 2), and containing 4 nodes, with a maximal depth of 2, which are 95087496, 96417540 and 95519490.
    

#### Tendrils

A tendril is a path starting from a node of degree one, connected to a strongly connected component. We have detected 7.94M tendrils in the graph, involving a total of 8.20M nodes (7.38%) and 16.39M edges (0.51%), with the largest one involving 7 nodes and 14 edges. The detected tendrils, sorted by decreasing size, are:

1.  Tendril starting from the root node 86669415 (degree 3), and containing 7 nodes, with a maximal depth of 7, which are 91482461, 87803048, 97971168, 90539916 and 96108163.
    
2.  Tendril starting from the root node 81429298 (degree 22), and containing 7 nodes, with a maximal depth of 7, which are 101128140, 97732708, 91375198, 96307390 and 88596425.
    
3.  Tendril starting from the root node 17792050 (degree 3), and containing 6 nodes, with a maximal depth of 6, which are 43091281, 63157589, 65349096, 37326493 and 41147137.
    
4.  Tendril starting from the root node 90695882 (degree 4), and containing 6 nodes, with a maximal depth of 6, which are 94216253, 88321137, 84150708, 93457451 and 91572587.
    
5.  Tendril starting from the root node 93621876 (degree 8), and containing 6 nodes, with a maximal depth of 6, which are 90869240, 93529903, 88992627, 88233693 and 87176965.
    
6.  Tendril starting from the root node 93554975 (degree 5), and containing 6 nodes, with a maximal depth of 6, which are 57285580, 92948523, 100185830, 108433293 and 93642131.
    

And other 7.94M tendrils.
