Let $\Omega$ be the family of all labelled graphs on the set of nodes $[n]$ and exactly $m$ edges.

The uniform random graph $G(n,m)$ assigns to every graph $G \in \Omega$ the same probability, that is,
$\mathbb{P}(G) = \frac{1}{|\Omega|} = \binom{N}{m}$.

Moreover, $G(n,m) \approx G(n,p)$, when $m \approx \binom{n}{2}p$.

Alternatively, $G(n,m)$ can be generated using the following random process *Erdős-Rényi random graph process*. 
Start with *n* labelled nodes and *no edges*. At each step, add one new edge chosen *uniformly at random* from the set of missing edges. Stop once the graph has exactly m edges. What we get is the $G(n,m)$.

