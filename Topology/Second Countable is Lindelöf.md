#lemma
### Types
- `X` : [[Second Countable]] Space
- `I` : Set
- $\left\{ U_{i} \right\}_{i\in I}$ : [[Covering]] of `X`
### Statement
There exists a [[countable]] [[Refinement of a Covering|refinement]] of $\left\{ U_{i} \right\}_{i\in I}$ for `X`. In other words, `X` is a [[Lindelöf Space]].
### Proof
Let $\mathcal{B}$ be a [[countable]] [[basis]] of `X`. let $\mathcal{B}'=\left\{B\in \mathcal{B}, \exists i \in I, B \subset U_{i}\right\}\subset \mathcal{B}$, which is also [[countable]] because a subset of a [[countable]] set is [[countable]]. For $B \in \mathcal{B}'$, denote by $V_{B}$ the set of $\left\{ U_{i} \right\}_{i\in I}$ which contains $B$, we have $\left\{ V_{i} \right\}_{i\in \mathcal{B}'}$ [[countable]], all left to do is to prove that it is a [[covering]] too.
Let $x \in X$, then $x \in U_{i}$ for some $i \in \mathbb{N}$, by definition of a [[basis]], there exists $B \in \mathcal{B}$ such that $x \in B \subset U_{i}$, but this means that $B \in \mathcal{B}'$, so $\exists V_{b}\in \left\{ V_{i} \right\}_{i\in \mathcal{B}'}$ such that $x\in B \subset V_{B}$, thus \exists $V_{b}\in \left\{ V_{i} \right\}_{i\in \mathcal{B}'}$ is a [[covering]] of `X`.