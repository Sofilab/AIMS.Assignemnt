# AIMS.Assignemnt

This project solves the problem of finding the maximum saving in a network by removing redundant connections while keeping the network connected.

The solution uses Kruskal’s Minimum Spanning Tree algorithm and is implemented using only the Python Standard Library, as required.

## How it works
1. The network is read as an adjacency matrix.
2. All edges and their costs are extracted.
3. The total cost of the network is calculated.
4. Kruskal’s algorithm is applied to find the Minimum Spanning Tree.
5. Maximum saving = Total cost – MST cost.

## How to run

Open `assignment.py` and run:

```python
print(maximum_saving(input_network))

