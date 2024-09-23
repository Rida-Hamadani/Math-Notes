#lemma
### Types
- `X I` : Nonempty Set
- $\left(\tau_\alpha\right)_{\alpha\in I}$ : Family of Subsets of `X`
### Statement
$\bigcap\limits_{\alpha\in I}\left(\tau_\alpha\right)_{\alpha\in I}$ is a [[topology]] on `X`.
### Proof
- $\varnothing, X$ are in every [[topology]], so they are in every intersection of topologies.
- $A \in \bigcap\limits_{\alpha \in I} \tau_\alpha \implies A \in \tau_\alpha, \forall \alpha \in I$ and $B \in \bigcap\limits_{\alpha \in I} \tau_\alpha \implies B \in \tau_\alpha, \forall \alpha \in I$, thus $A \cap B \in \tau_\alpha, \forall \alpha \in I$, which implies that $A \cap B \in \bigcap\limits_{\alpha\in I}\left(\tau_\alpha\right)_{\alpha\in I}$.
- Let $\left(\tau_\beta\right)_{\beta\in J}$ such that $A_\beta \in \bigcap\limits_{\alpha\in I}\tau_\alpha, \forall \beta \in J$, so $\forall\alpha \in I, \forall \beta \in J$,$A_\beta\in\tau_\alpha$. By the stability of union axiom in $\tau_\alpha$, $\bigcup\limits_{\beta\in J}A_\beta \in \tau_a$ for all $\alpha \in I$, therefore $\bigcup\limits_{\beta\in J}A_\beta \in \bigcap\limits_{\alpha \in I}\tau_a$ .