###### Node degree
Degree of a node $v \in V$ is $deg(v) = \sum_{u \in V} a(u,v)$, where $a(u,v)$  is the weight of the edge betwen $v$ and $u \in V$.

For unweighted graphs $deg(n) = |N(v)| = \textrm{\# neighbours of v}$.

###### Degree sequence
The degree sequence is $d = (deg(v_1),..., deg(v_n))$ 

with non-decreasing order i.e. $deg(v_1) \leq deg(v_2) \leq ... \leq deg(v_n))$.

###### Degree distribution
The degree distribution $d_l$ is the fraction of nodes with degree $l$, i.e. $d_l = \frac{n_l}{n}$ where $n_l$ is the number of nodes of degree $l$.

###### Average degree
The *average degree* in the unweighted graph $G$ is 
$$<k> = 1/n \sum_{v \in V} deg(v) = \sum_{v \in V}l * d_l = \frac{2m}{n}$$.

######  Moment of the degree 
For any $s \in \mathbb{N}$ the *s*th moment of the degree sequence is defined as 
$$<k^s> = \frac{1}{n}\sum_{v \in V} deg(v)^s = \sum_{l \in \mathbb{N}}l^s *d_l$$

Note that if random variable $X$ is uniformaly distributed over the set of nodes $V$, then we can simply write $<k^s> = \mathbb{E}[deg(v)^s]$.

Particulary, 
- $<k^1>$ is called *expected value* and is just the arithmetic mean value.
- $<k^2>$ is called *[variance](https://en.wikipedia.org/wiki/Variance)*.
- $<k^3>$ is called *[skewness](https://en.wikipedia.org/wiki/Skewness)*.
- $<k^4>$ is called *[kurtosis](https://en.wikipedia.org/wiki/Kurtosis "Kurtosis")*.
