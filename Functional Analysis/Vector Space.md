#definition
### Types
- $F$ : [[Field]]
- `V` : Nonempty Set
- $+ : V \times V \to V$
- $\cdot : F \times V \to V$
### Definition
`V` is a *vector space* if for all $u, v, w \in V$ and $a, b \in F$ the following properties are satisfied:
- $u + (v + w) = (u + v) + w$.
- $u + v = v + u$.
- There exists an element $0$ in `V` such that for all $v \in V, v + 0 = v$.
- $\forall v \in V, \exists (-v)\in V: v + (-v) = 0$.
- $a\cdot(b\cdot v)=(a\cdot b)\cdot v$.
- $1 \cdot v = v$.
- $a \cdot (u+v) = a \cdot u + a \cdot v$.
- $(a + b) \cdot v = a\cdot v+ b\cdot v$.
##### Notes
- Note that although the addition binary operation on the [[field]] is different from that on the *vector field*, we use the same symbol for both, leaving the mission of inferring the type of the operation on the reader. Same thing regarding multiplication.