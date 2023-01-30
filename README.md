# Graphs with distance sensors
Class project - M2 ORCO - UGA

Given a graph G and a set **S** of vertices equipped with "distance sensors" (that is, the pairwise distances between the vertices of **S** in G can be determined at all times by the sensors). We say that **S** can detect edge-failures if for any edge e, the removal of e in G changes the distance between *at least* one pair of vertices of **S**.

**What is the minimum size of a set of vertices that can detect edge-failures ?**

An Integer Programming model has been designed and implemented. The following library provided us a Python implementation of graphs and Dijkstra's algorithm: https://github.com/ahojukka5/Dijkstra/tree/master/dijkstra. We also used its random graph generator to test the robustness of our model.

The report (*Graphs_project_report.pdf*) contains explanations about the modelling part, as well as theoretical results that were found (especially bounds on the size of **S**).
