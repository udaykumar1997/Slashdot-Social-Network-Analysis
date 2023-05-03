# Slashdot Social Network Analysis
This project aims to perform Social Network Analysis (SNA) on the Slashdot dataset to understand the relationships and interactions between users within the Slashdot community. The dataset consists of friend and foe relationships between the users of Slashdot, gathered in February 2009.


## Dataset Information

Source: Slashdot Zoo social network from February 2009 [Link](https://snap.stanford.edu/data/soc-Slashdot0902.html)

Nodes: 82,168

Edges: 948,464

First 10 lines of the dataset:
```txt
# Directed graph (each unordered pair of nodes is saved once): Slashdot0902.txt 
# Slashdot Zoo social network from February 0 2009
# Nodes: 82168 Edges: 948464
# FromNodeId	ToNodeId
0	0
0	1
0	2
0	3
0	4
0	5
```


## Stages of the Project

Data Preparation: In this stage, we will preprocess the dataset, clean it, and transform it into a suitable format for analysis. This may involve removing duplicates, handling missing data, and formatting the dataset into a network graph.

Exploratory Data Analysis (EDA): EDA will be performed to obtain a better understanding of the dataset, including node and edge distributions, degree distributions, and other relevant statistics.

Community Detection: We will identify and analyze communities within the Slashdot network. This may involve using clustering algorithms or modularity-based approaches to group users with similar interests or relationships.

Centrality Measures: We will compute and analyze various centrality measures such as degree centrality, betweenness centrality, closeness centrality, and eigenvector centrality to identify influential users within the network.

Link Prediction: We will apply link prediction techniques to predict potential new relationships between users based on their current network structure. This can help identify users who are likely to become friends or foes in the future.

Visualization: We will create visualizations to better understand the network structure, including node-link diagrams, adjacency matrices, and heatmaps.

## Potential Outcomes

Understanding the community structure and dynamics

Visual representations of the network structure, communities and other findings

---

Identification of influential users within the Slashdot community

Prediction of potential new relationships between users
