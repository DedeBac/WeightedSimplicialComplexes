# WeightedSimplicialComplexes

This repository contains data from the collaboration simplicial complex built in the paper "Title" by Baccini F., Geraci, F., and Bianconi, G.
The folder **WeightedCollaborationSimplicialComplex** is organized as follows:

- **collaboration_network_labels.png** is a high resolution image of the weighted network skeleton of the collaboration simplicial complex. Nodes are labelled with the names of authors, and different colours denote different clusters individuated as explained in the paper.
- **nodelist_complete.txt**, **edgelist_complete.txt**, **trianglelist_complete.txt** contain the list of nodes, edges and triangles of the whole graph of collaboration.
- **Metadata_2017_2021_multilayer_coauthorship** contain the original metadata of the articles considered for the construction of the simplicial complex of collaborations.
- **nodelist_ConnComp.txt** contains the list of node IDs of the main connected component of the coauthorship network (356 nodes);

- **edgelist_ConnComp.txt** contains the list of edge IDs of the main connected component of the coauthorship network (1172 edges)

- **trianglelist_ConnComp.txt** contains the list of triangle IDs of the of the coauthorship network (2614 triangles)

- **edges_matrix_with_Mn_ConnComp.csv** is the matrix of Mn coefficients referred to the largest connected component of the network, structured as follows. 
  - Rows represent edges (pairs of coauthors).
  - The first two columns (:,0) and (:,1) are the node ids of each edge endpoints. 
  - The element of index (i,n), for n=2,...,20 of the matrix is the coefficient m_n expressing the number of papers with n authors written by the couple (edge) i. 	

- **triangles_matrix_with_Mn_ConnComp.csv**  is the same as above but for triangles, i.e.
	- Rows represent triangles (groups of three authors with at least 1 collaboration).
	- The first three columns (:,0) and (:,1) and (:,2) are the node ids of each triangle vertex. 
	- The element of index (i,n), for n=3,...,20 of the matrix is the coefficient m_n expressing the number of papers with n authors written by the triangle i. 	

- **edgelist_weighted.txt** is the weighted edgelist where weights are computed as in Eq. 64 of the paper by Baccini et al. (2022);
- **trilist_weighted.txt** is the weighted list of triangles where weights are computed as in Eq. 64 of the paper by Baccini et al. (2022).


