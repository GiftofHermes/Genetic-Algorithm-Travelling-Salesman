# Genetic-Algorithm-Travelling-Salesman
An implementation of a genetic algorithm to solve the travelling salesman problem. 

Libraries used: 
- Numpy 
- Matplotlib 

Randomly generated points with x and y coordinates.  
It is assumed that all valid journeys start and end at the origin.  
Genes are every destination we need to visit in order.   
i.e  
1- 0,0
2- 12,2  
3- 3,5  
4- 4,8  
5- 0,0  

Fitness function is total euclidian distance between every two consecutive points. 

Initial generation is created by randomly shuffling the destinations list. 
Next generations are created by using ordered crossover. 

In the plots green line indicates the start and yellow line indicates the end. 
