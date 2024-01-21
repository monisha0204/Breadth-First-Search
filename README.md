# Breadth-First-Search
 BFS CODE
 BFS ALGORITHM
 Explore all the immediate neighbours first then continue to explore all the immediate neighbours of them
 Use a QUEUE to keep track of paths/nodes to explore. Explore nodes in the order they were added.
 Add start node to QUEUE and visited list and repeat below:
 - Get current node by removing from front of the QUEUE and print as BFS path node.
 - Append all neighbours of current node to the QUEUE, if not already visited(to avoid revisiting) and
 - also add these nodes to the visited list
 repeat until all the elements in the queue are removed
 
