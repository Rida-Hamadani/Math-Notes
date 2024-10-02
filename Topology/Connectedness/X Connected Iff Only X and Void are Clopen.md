#lemma
### Types
- `X` : [[Topological Space]]
### Statement
`X` is [[Connected Space||connected]] if and only if `X` and $\varnothing$ are the only subsets of `X` that are [[open set|open]] and [[closed set|set]] at the same time. 
### Proof
Suppose there is a subset of `X` that is [[closed set|set]] and open, named it `U`, which is different from `X` and $\varnothing$. As `U` is closed, $X - U$ is open,  and both are nonempty, their union is `X`, so `X` is [[Disconnected Space|disconnected]], which is the contrapositive of the first implication.
Suppose that `X` is [[Disconnected Space|disconnected]], then there exists two subsets of `X`, `U` and `V` such that they are nonempty, open, with $U \cup V = X$ and $U \cap V = \varnothing$. This implies that $V = X - U$, so `V` is closed because `U` is open, so there exists a set other than `X` and `U` that is clopen.