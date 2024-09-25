#definition
### Types
- `X` : Nonempty Set
- `E` : Subset `X`
- $\mathcal{A}$ : [[Sigma Algebra]] on `X`
### Definition
The intersection of `E` with every set in $\mathcal{A}$ is a [[sigma algebra]] on `E` named the *trace sigma algebra*.

### Notation
$\mathcal{A}\Big/E$
#### Proof that it is a [[Sigma Algebra]]
- $E = E \cap X$, and $E \in \mathcal{A}$, so, $E \in \mathcal{A}\big/E$.
- $B\in A\big/E \implies B = E \cap A$, and $A \in \mathcal{A}$, thus $E- B = E \cap \overline{B} = E \cap \left(\overline{E}\cup\overline{A}\right) = \left(E\cap\overline{E}\right)\cup\left(E\cap\overline{A}\right)=E\cup\overline{A}\in\mathcal{A}\big/E$.
- $(B_j)_{j\in\mathbb{N}}\subset\mathcal{A}\big/E \implies \forall j\in\mathbb{N},B_j\in\mathcal{A}\big/E\implies \forall j\in\mathbb{N},B_j\cap A_j$ and $A_j \in \mathcal{A}$, therefore $\bigcup\limits_{j\in\mathbb{N}}B_j=\bigcup\limits_{j\in\mathbb{N}}E\cup A_j = E \cup \bigcup\limits_{j\in\mathbb{N}}A_j \in \mathcal{A}\big/E$.
