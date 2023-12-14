[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=13164467&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Consider the following two graphs that are not completely connected. Graphs A and B have one vertex that is not connected by an edge to the other. In this case that would be vetex 3 to 1, and vertex X to Z. 

Graph A: $V_1={1, 2, 3}; E_1={(1,2), (2,3)}$
Graph B: $V_2={X, Y, Z}; E_2={(X,Y), (Y,Z)}$

The bijection (f) of graphs A and B is the following: 

$f(1)=X, f(2)=Y, f(3)=Z$

Now the isomorphism conditions can be checked. 

$(1, 2)$ is in $E_1$ and $(f(1), f(2))=(X, Y)$ is in $E_2$. 
$(2, 3)$ is in $E_1$ and $(f(2), f(3))=(Y, Z)$ is in $E_2$. 

Checking the isomorphism conditons shows that the bijection (f) satifies the requirements for every edge in $E_1$. Therefore graph A and graph B are isomorphic even when they're not completely conncected. 
