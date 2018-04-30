# Constructing a road network 

In this article, I explain how we can use graphs to represent road networks. Before proceeding, let’s establish the meaning of key concepts. A network structure refers to any structure that comprises of nodes and edges. In any graph, a node is a vertex and an edge is a link between two vertices. Many nodes and edges constitute a network. A road network here simply refers to the geography of routes. For example, the different streets that constitute a map of any location are what would be considered a road network. 

## Architecture of the road network

![image](https://user-images.githubusercontent.com/26033554/39447500-8faa7b3e-4cdf-11e8-816c-895a4396a71d.png)  

The image above illustrates how spatial characteristics of an observed road network can be abstracted to its most important features. The nodes, which are represented by the orange circles, capture the shape of the space such that each node represents a turning point in the network. The edges between any pair of nodes represent the road that leads from one to another. By thinking of road networks in terms of nodes and edges, we can reduce a multidimensional space into two-dimensional space. The 2-D representation of a road network would look like the network images shown below.

![image](https://user-images.githubusercontent.com/26033554/39447510-95abd6a4-4cdf-11e8-806f-ff88bc27c417.png) ![image](https://user-images.githubusercontent.com/26033554/39447514-9b4229ba-4cdf-11e8-8dc2-302f5b21693c.png)

Thus, instead of mapping out the entire landscape to visualize the geography of a place, we can simply record the turning points as nodes and the lanes between them as edges. In the two images above, the directionality of arrows reveal the direction that the cars travel in-between any two lanes. Overall, such a technique would enable road network designers to construct the shape of a space in an accessible and intuitive manner. 
