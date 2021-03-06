# $\mathcal{B}([a, b])\ =\ ?$

赖睿航  518030910422  March 30, 2020



Let $(\mathbb{R}, \tau)$ be the usual topology of $\mathbb{R}$.

According to the definition of Borel $\sigma$-algebra, $\mathcal{B}(\mathbb{R})$ is the $\sigma$-algebra generated by all sets in $\tau$.

But consider interval $[a, b]$. We want to ask what is $\mathcal{B}([a, b])$?

We need to know the definition of **Subspace Topology**:

Given the usual topology space $(\mathbb{R}, \tau)$ and a subset $S$ of $\mathbb{R}$, the subspace topology on $S$ is defined by:
$$
\tau_S = \{S \cap U \mid U \in \tau\}
$$
So according to the definition above, the subspace topology on $[a, b]$ is:
$$
\tau_{[a, b]} = \{[a, b] \cap U \mid U \in \tau \}
$$
Therefore, let $U_1 := (a - 1, b + 1), U_2 := (a - 1, x), U_3 := (y, b + 1)$ with $x, y \in (a, b)$. Obviously $U_1, U_2, U_3 \in \tau$. Then we have:
$$
\begin{align*}
	[a, b] &= [a, b] \cap U_1 \Rightarrow [a, b] \in \tau_{[a, b]} \\
	[a, x) &= [a, b] \cap U_2 \Rightarrow [a, x) \in \tau_{[a, b]} \\
	(y, b] &= [a, b] \cap U_3 \Rightarrow (y, b] \in \tau_{[a, b]}.
\end{align*}
$$
It means that we can regard $[a, b], [a, x), (y, b]$ as "open sets" on $[a, b]$. And $\mathcal{B}([a, b])$ is the $\sigma$-algebra generated by all sets in $\tau_{[a, b]}$, which includes $[a, b], [a, x), (y, b]$ as well.


