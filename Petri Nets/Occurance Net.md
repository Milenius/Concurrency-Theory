```ad-important
A net $K=(Q, V, G, M_0)$ is an occurrence net if
1. $\forall q \in Q: |{}^\circ q| \leq 1$
2. the transitive closure $G^+$ of G is irreflexive
3. $\forall x \in Q \cup V:$ the set $\{y \ | \ (y,x) \in G^+\}$ is finite
4. no transition $v\in V$ is in self-[[Conflict]]
5. $M_0$ quals the minimal set of places in $K$ under $G^+$, i.e. $$M_0 = {}^\circ K := \{q \in Q \ | \ {}^\circ q =  \emptyset \}$$
```

# Remarks
* Occurrence nets additionally admit output (but no input) branching for places
- Every [[Causal Net]] is also an occurrence net.