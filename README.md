# Network-Analysis-of-Game-of-Thrones-Characters

## Introduction

### Social Network Analysis

A Social Network is a combination of appropriate actors or nodes, who are connected to each other and form a Network relation. Here, we assign the Characters as the nodes and observe and study the pattern and trends made. The corresponding approach is based on the intuitive idea that characters' placement in social network networks has significant effects on those other characters. We are looking to identify a variety of trends in our analysis. And they work to identify the circumstances in that one of those patterns emerges and to ascertain the effects.

The social network approach is based on the intuitive idea that characters' placement in social network patterns has significant effects on those other characters. We are looking to identify a variety of trends in our analysis. Additionally, they seek to understand the causes of these patterns as well as their effects. A group can use SNA to complete the process of "understanding and grasping the networks that operate in a specific field”. Thanks to this complex type of mind mapping, the group is able to highlight the communication patterns within the network as well as identity networks.

The base structure of the plot is formed by the relationships between the characters. As a result, plot information such as major roles and corresponding cliques can be determined through social network analysis among characters. Most books progress through characters, and the author narrates the story and relationships between characters through relationships through them.  As a result, the thread connecting the characters which weaves through and from the whole is more effective than co-appearance in establishing character social networks.

## Modules

### 1.	Pandas: 
A Python package that provides several data structures and methods for handling arithmetical data and longitudinal data is an accessible library that is developed over the NumPy library. Our dataset, which is in CSV format, is loaded into pandas in the structure of a data frame, enabling analysis in Python really simple. For data cleansing and visualisation, we would use a number of pandas methods, such as pd.read csv(), pd.describe(), and pd.fillna ()

### 2.	NumPy: 
We will use NumPy array to support pandas as the majority of its actions are array-based.

### 3.	Matplotlib.pyplot: 
To obtain a strong visual exploratory study, we would use this package for visual analytics.

### 4.	Sea Born: 
This is a good framework for creating graphs that go well and creating some maps utilizing our data.

### 5.	NetworkX API: 
We would be able to incorporate network analysis paradigms with the aid of a very crucial tool in our project. In addition, we may make use of its potent graph-creation features.

## Chosen approach 

### Centrality measures:
	Centrality measures are essential for comprehending networks, which are commonly referred to as graphs. These methods perform use graphs to identify the importance of any particular node in a network. They all work in different ways, but they all show parts of the network that need attention by sifting through noisy data.

### Degree Centrality:
	The degree centrality of a node is the number of links that lead to it. In-degree and out-degree are two different measurements of centrality measures that are defined if the network is directed. The number of edges a node has determined its degree of centrality, which is the easiest to compute. The higher the degree, the more centrally positioned the node is.
 
### Betweenness Centrality:
	Betweenness centrality quantifies how dependent a vertex is on links between other vertices. Because they have more power over how information moves between nodes, vertices with high betweenness may have a massive impact (importance) inside a network.

### Closeness Centrality:
	The number of edges or links connecting two nodes (a and b) on the shortest path (i.e., path with the fewest edges) between them is known as the geodesic distance, or d. Geodesic length can be defined mathematically as follows:

### Page Rank: 
The Page Rank score for a given page/node is based on the links made to that said page/node from other pages/nodes. The links to a given page/node are called the backlinks/in-degrees for that page/node. The web/social network thus becomes a democracy where pages/nodes vote for the importance of other pages by linking to them. It is a variant of the Eigenvector value, but because it uses backlinks/in-degrees it is used in directed networks. Directed networks are networks that allow handles (the node or webpage) to follow another without that page or node following back.

### Average shortest path:

	The average number of steps along the shortest paths for all potential pairs of network nodes is known as average shortest-path length, which is a notion in network topology. It is a way to gauge how well people can move large amounts of data through a network.
	
### Diameter:

Diameter is the length of the longest path (in a number of edges) between two nodes.

### Transitivity: 

	A network's transitivity or clustering coefficient serves as a gauge for the nodes' propensity to group together. A network with high transitivity has internal node communities or clusters that are closely connected to one another.
 
### Density: 
Density refers to the "connections" between participants. Density is defined as the number of connections a participant has divided by the total possible connections a participant could have
	
### Clustering Coefficient and Average Clustering Coefficient:

A graph's local clustering coefficient measures how near a vertex's neighbours are to forming a clique (complete graph).

### Power Law:

In statistics, a power law is a functional relationship between two quantities, where a relative change in one quantity results in a proportional relative change in the other quantity, independent of the initial size of those quantities: one quantity varies as a power of another.

## Conclusion

We have ventured to Game of Thrones to explore the fundamental network science methods. Using an empirical approach, we discovered communities and prominent individuals in our network. Our Network analysis supported certain hypotheses and revealed fresh information about this vividly envisioned narrative. To present an alluring glimpse of network science's potential, we have developed a fantastical application. There are many more important uses, and network science promises to be crucial for comprehending our contemporary networked lives. Wider quantitative approaches to other fields of literary research, such as drama, tv, movie, rhythm, category, canonicity, literature, history, and fantasy, may be inspired by the finding of trends of plausibility, cognition, and unpredictability through computational methods.
