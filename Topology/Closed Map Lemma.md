#lemma #todo 
### Types
- `X` : [[Compact Space]]
- `Y` : [[Hausdorff Space]]
- $f : X \to Y$
### Statement
If $f$ is [[Continuity|continuous]], then:
- $f$ is a [[closed map]]. 
- if $f$ is surjective, it is a [[quotient map]].
- if $f$ is injective, then it is a [[topological embedding]].
- if $f$ is bijective, then it is a [[homeomorphism]].
### Proof
If $A$ is [[closed set|closed]] in $X$, then it is [[compact space|compact]] by [[Every Closed Subset of Compact is Compact]].
As [[Continuity Preserves Compactness]], $f\left( A \right)$ is [[Compact Space|compact]] in $Y$, thus it is [[Closed Set|closed]] in $Y$ because [[Every Compact Subset of Hausdorff is Closed]]. Thus $f$ is a [[closed map]].
The rest of the conditions are the first condition combined with the lemmas:
- [[Open Or Closed Continuous Injections Are Embeddings]].
- [[Open Or Closed Continuous Surjection is a Quotient Map]].
- [[Open Or Closed Continuous Bijections are Homeomorphisms]].