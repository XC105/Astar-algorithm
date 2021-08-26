# Route Planning Algorithm

#Astar
A is the most popular choice in route search because it is quite flexible and can be used in a variety of situations. Like other graph search algorithms, Algorithm A potentially searches a large area in the graph. Like Dijkstra, A can be used to search for the shortest path. Like BFS, A can use heuristic functions. In simple cases, it is as fast as the best search algorithm. In the case of a concave obstacle, A finds a path as good as Dijkstra's algorithm:


#RRT
RRT (Rapid Exploration Random Tree) is a universal method, no matter what type of robot, no matter how many degrees of freedom, no matter how complicated the constraints are. And its principle is very simple, which is one of the main reasons for its popularity in the robotics field. However, its shortcomings are also obvious. The path it obtains is generally not of good quality, for example, it may contain edges and corners, is not smooth enough, and is usually far away from the optimal path.
