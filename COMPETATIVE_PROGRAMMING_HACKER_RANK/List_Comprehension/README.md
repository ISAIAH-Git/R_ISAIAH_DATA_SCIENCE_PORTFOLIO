# Let's learn about list comprehensions! You are given three integers  and  representing the dimensions of a cuboid along with an integer .
Print a list of all possible coordinates given by  on a 3D grid where the sum of  is not equal to n. Here, . Please use list comprehensions rather than multiple loops,
as a learning exercise.

# Constraints:

Print the list in lexicographic increasing order.

# Sample Input 0

1
1
1
2
# Sample Output 0

[[0, 0, 0], [0, 0, 1], [0, 1, 0], [1, 0, 0], [1, 1, 1]]

# Sample Input 1

2
2
2
2

# Sample Output 1

[[0, 0, 0], [0, 0, 1], [0, 1, 0], [0, 1, 2], [0, 2, 1], [0, 2, 2], [1, 0, 0], [1, 0, 2], [1, 1, 1], [1, 1, 2], [1, 2, 0], [1, 2, 1], [1, 2, 2], [2, 0, 1], [2, 0, 2], [2, 1, 0], [2, 1, 1], [2, 1, 2], [2, 2, 0], [2, 2, 1], [2, 2, 2]]
