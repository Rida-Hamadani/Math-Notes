#lemma
### Types
- `X` : [[Topological Space]] 
### Statement
The identity function $Id_X : X \to X$ is [[Continuity|continuous]].
### Proof
Let `U` be an [[Open Set|open]] subset of `X`, then:
$$
\begin{aligned}
Id_X^{-1}\left(U\right)&=\left\{ x\in X | Id_{X}\left( x \right)\in U  \right\} \\
&=\left\{ x\in X|x\in U \right\} \\
&= U 
\end{aligned}
$$
which is [[Open Set|open]] in `X`, so $Id_X$ is [[Continuity|continuous]].