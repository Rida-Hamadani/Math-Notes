#definition
### Types
- `F` : Set
- $+, \times : F \times F \to F$ 
### Definition
$\left( F, +, \times \right)$ is a *field* if for every $a, b, c \in F$, the following properties are satisfied:
- *Associativity*: $a + (b + c) = (a + b) + c$ and $a\times (b\times c) = (a\times b) \times c$.
- *Commutativity*: $a+b = b + a$ and $a\times b = b\times a$.
- *Identity*: there exist two distinct elements 0 and 1 in `F` such that $a + 0 = a$ and $a \times 1 = a$.
- *Additive Inverse*: for every $a$ in `F`, there exists $-a$ in `F` such that $a + (-a) = 0$.
- *Multiplicative Inverse*: for every $a$ in $F - \left\{ 0 \right\}$, there exists $a^{-1}$ in `F` such that $a \times a^{-1} = 1$.
- *Distributivity*: $a \times (b + c) = a \times b + a \times c$.