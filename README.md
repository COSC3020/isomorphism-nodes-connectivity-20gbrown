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

**Considering two graphs, A and B, with the same number of nodes and are completely connected:**

Graph A: $G_1 = (V_1, E_1)$

Graph B: $G_2 = (V_2, E_2)$

**Bijection function:**

$f: A ↔ B$

V<sub>A<sub>1</sub></sub> ↔ V<sub>B<sub>1</sub></sub>

V<sub>A<sub>2</sub></sub> ↔ V<sub>B<sub>2</sub></sub>

. . .

V<sub>A<sub>n</sub></sub> ↔ V<sub>B<sub>n</sub></sub>

**Foward direction:**

For any edge $(u, v) \in E_1, \exists (f(u), f(v)) \in E_2$

For each edge $(u, v) \in E_1$, we have $(f(u), f(v)) \in E_2$ due to the bijection $f$. This ensures that the forward direction of the isomorphism condition is satisfied.

**Reverse direction:**

For any edge $(x, y) \in E_2, \exists (f^{-1}(x), f^{-1}(y)) \in E_1$, where $f^{-1}$ is the inverse of the bijection $f$

For each edge $(x, y) \in E_2$, we have a corresponding edge $(f^{-1}(x), f^{-1}(y))$ in $E_1$ because of the inverse bijection $f^{-1}$. This confirms that the reverse direction of the isomorphism condition is met.




