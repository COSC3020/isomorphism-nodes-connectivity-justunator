[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11754454&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Graph A and B have the same number of nodes and edges as both graphs are compelely connected. The definition of isomorphic means that there is a one-to-one and onto function between the graphs. Because Graph $A$ and $A$ have the same number of nodes and are completely connected, we can say there is some node in $A$ and can match another node in $B$ and have no extra nodes. Because both graphs are completely connected, this means every node as an edge between every other node and in turn, means that every edge in graph $A$ can also mapped in graph $B$. Therefore, graphs with the same number of nodes and are completely connected must be isomorphic.
