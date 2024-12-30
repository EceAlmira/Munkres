# Munkres (Hungarian) Algorithm Implementation

# Overview

This repository contains an implementation of the Munkres (Hungarian) algorithm, which is a combinatorial optimization algorithm that solves the assignment problem in polynomial time. The algorithm finds the optimal assignment of tasks to agents while minimizing the total cost.

The notebook includes visualizations and numerical results to help users understand how the algorithm works step by step.

# Features

Solves the assignment problem for square cost matrices.

Supports both minimization and maximization problems.

Includes detailed comments and explanations for better understanding.

Here is a simple example of using the Munkres algorithm:

```
from munkres import Munkres

# Define the cost matrix
cost_matrix = [
    [4, 1, 3],
    [2, 0, 5],
    [3, 2, 2]
]

# Initialize the Munkres object
m = Munkres()

# Compute the optimal assignments
assignments = m.compute(cost_matrix)

# Output the result
print("Assignments:", assignments)
```

License
This project is licensed under the MIT License. 

See the LICENSE file for details.
