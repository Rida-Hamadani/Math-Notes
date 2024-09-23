#definition
### Types
- `X` `X'` : Nonempty Set
- `f` : `x` $\to$ `X'`
- $\mathcal{A}'$ : [[Sigma Algebra]] on `X'`
### Definition
$\mathcal{A} = f^{-1}\left(A'\right)=\lbrace f^{-1}\left(A\right);A'\in\mathcal{A'}\rbrace$ is the *preimage sigma algebra* on `X`.
#### Proof that it is a [[Sigma Algebra]]
- $X=f^{-1}(X')$ and $X'\in \mathcal{A'}$, thus $X\in\mathcal{A}$.
- $A \in \mathcal{A} \implies A = f^{-1}(A')$ and $A'\in \mathcal{A'} \implies \overline{A}=\overline{f^{-1}(A')}=f^{-1}\left(\overline{A'}\right)$.
- $\left(A_j\right)_{j \in \mathbb{N}}\subset \mathcal{A} \implies \forall j \in \mathbb{N}, A_j\in \mathcal{A}\implies\forall j\in\mathbb{N},A_j=f^{-1}\left(A_j'\right)$ and $A_j' \in \mathcal{A}'\implies \bigcup\limits_{j\in\mathbb{N}}A_j=\bigcup\limits_{j\in\mathbb{N}}f^{-1}\left(A_j'\right)=f^{-1}\left(\bigcup\limits_{j\in\mathbb{N}}A_j'\right)\in\mathcal{A}$.