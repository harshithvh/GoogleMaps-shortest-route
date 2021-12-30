# GoogleMaps-shortest-route
Data Structures

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/GoogleMaps-shortest-route/blob/main/img/img-1.jpg" />

# About

---

Google Maps is a web mapping platform and consumer application offered by Google. It offers satellite imagery, aerial photography, street maps, 360° interactive panoramic views of streets, real-time traffic conditions, and route planning for travelling by foot, car, air and public transportation.

In 2003, Brothers Lars and Jens Rasmussen at Where 2 Technologies, created a desktop application with C++, which was intended to be downloaded by users on their systems.

# Requirements

---

How to Store geo-locations?

Let’s suppose right now there are 16 cities/states in the maps database. Let’s use their longitudes and latitudes to plot them on the map. Where one city will be connected to some other cities. We will represent these connections using edges between these nodes. 

How to find the best route between these locations?

After locating all the location points and joining all the edges representing possible routes for navigation from a source location to destination location.

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/GoogleMaps-shortest-route/blob/main/img/img-2.png" />

# Graph Datastructure

---

A Graph is a non-linear data structure consisting of nodes and edges. The nodes are sometimes also referred to as vertices and the edges are lines or arcs that connect any two nodes in the graph.

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/GoogleMaps-shortest-route/blob/main/img/img-3.png" />

NODES

A node is a basic unit of a data structure, such as a linked list or tree data structure. Nodes contain data and also may link to other nodes. Links between nodes are often implemented by pointers.

COST

Represents the total length of the network measured in real transport distances.

EDGE

Edge − Edge represents a path between two vertices or a line between two vertices. In the following example, the lines from A to B, B to C, and so on represent edges. We can use a two-dimensional array to represent an array as shown in the following image.

# Best route - A* Search Algorithm

---

This algorithm uses the heuristic approach

<img align="left" alt="Visual Studio Code" width="820px" margin-bottom="5px" src="https://github.com/harshithvh/GoogleMaps-shortest-route/blob/main/img/img-4.png" />
<br>
<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/GoogleMaps-shortest-route/blob/main/img/img-5.png" />

Now we were able to find the best route possible 

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/GoogleMaps-shortest-route/blob/main/img/img-6.png" />

But what if the next edge is not connected to our final destination?

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/GoogleMaps-shortest-route/blob/main/img/img-7.png" />

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/GoogleMaps-shortest-route/blob/main/img/img-8.png" />

<img align="left" alt="Visual Studio Code" width="820px" src="https://github.com/harshithvh/GoogleMaps-shortest-route/blob/main/img/img-9.png" />


