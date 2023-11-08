[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12784442&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Proof

Considering two graphs, A and B, with the same number of nodes and are completely connected:

Graph A: $G_1 = (V_1, E_1)$

Vertices: $V_1 = {A, B, C}$

Edges: $E_1 = {(A, B), (A, C), (B, C)}$

Graph B: $G_2 = (V_2, E_2)$

Vertices: $V_2 = {X, Y, Z}$

Edges: $E_2 = {(X, Y), (X, Z), (Y, Z)}$

Both graphs have the same number of nodes, which is three.

Bijection function $f: V_1 \rightarrow V_2$ that makes Graph A isomorphic to Graph B:

$f(A) = X$

$f(B) = Y$

$f(C) = Z$

It is evident that this function is a one-to-one and onto (bijection) function, as it maps all nodes in Graph A to all nodes in Graph B in a one-to-one and onto manner.

For any edge $(u, v) \in E_1$, there is a corresponding edge $(f(u), f(v)) \in E_2$:

For edge (A, B) in Graph A, we have (X, Y) in Graph B.

For edge (A, C) in Graph A, we have (X, Z) in Graph B.

For edge (B, C) in Graph A, we have (Y, Z) in Graph B.

Thus, the condition for isomorphism is met: for any edge $(u, v) \in E_1$, we have $(f(u), f(v)) \in E_2$.

