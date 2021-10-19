Chung-Lu model $G(w)$ is random graph with expected degree sequence $w$.

Let $w=(w_1, w_2,..., w_n)$ be any vector of $n$ positive real numbers, and let $W=\sum_{i=1}^n w_i$.
Each pair of nodes i,j is independently samples as an edge with probability given by:
$$p_{i,j}\left\{ \begin{array}{ll}      \frac{w_i w_j}{W} & if \quad i \neq j \\ \frac{(w_i)^2}{2W} & if \quad i = j \\ \end{array}  \right. $$

This model can be generalized to [[Binomal Random Graph]] if $w=(pn,pn,...,pn)$ and self-loops are ignored then $G(w) = G(n,p)$.

For any $i \in [n]$,
$$\mathbb{E}[deg(i)] = w_i$$
