#lemma
### Types
- `n` : $\mathbb{N}$
- `M` : [[Topological Manifold]] of dimension `n` 
### Statement
`M` has a [[countable]] [[basis]] of [[regular coordinate ball]]s. 
### Proof
Since `M` is [[Locally Euclidean Space|locally Euclidean]], every point of `M` is contained in a [[coordinate neighborhood]], and since `M` is [[second countable]], a [[countable]] collection $\left\{ U_{i}, i \in \mathbb{N} \right\}$ of such neighborhoods covers M since [[Second Countable is Lindelöf]]. Since `M` is [[Locally Euclidean Space|locally Euclidean]], we can associate to each $U_{i}$ a [[homeomorphism]] $\varphi_{i} : U_{i} \to \hat{U_{i}} \subset \mathbb{R}^n$, where $\hat{U_{i}}$ is [[open set|open]], implying that $\forall x \in \hat{U_{i}}, \exists r(x)>0, B_{r\left( x \right)}\left( x \right) \subset\hat{U_{i}}$.
Let $x\in \hat{U_{i}}$, $r$ any strictly positive rational number less than $r \left( x \right)$, then due to [[Preimage of Smaller Coordinate Ball Under Homomorphism is Regular]], $\varphi_{i}^{-1}\left(B_{r}\left( x \right)\right)$ is a [[regular coordinate ball]]. Let $\mathcal{B}$ be the set of all [[Open Set|open]] subsets of `M` of this form, then they are [[countable]] since there are countably many such balls for each $U_{i}$, and they also form a [[basis]] of `M`, clearly they are [[open set|open]]. Let $U$ be open subset of `M`, then it can be written as union of $\mathcal{B}$ as follows:
$$
\begin{aligned}
U &= \bigcup\limits_{{i\in I}}U_{i}\\
&= \bigcup\limits_{{i\in I}}\varphi^{-1}\left(U_{i}\right)\\
&= \bigcup\limits_{{i\in I}}\varphi^{-1}\left(\bigcup\limits_{x\in U_{i}}B_{r\left( x \right) }\left( x \right) \right)\\
&= \bigcup\limits_{{i\in I}}\bigcup\limits_{{x \in U_{i}}} \varphi^{-1} \left( B_{r\left( x \right) }\left( x \right)  \right) 
\end{aligned}
$$