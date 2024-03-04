```ad-important
1. $\forall \ q \in Q: |{}^\circ q| \leq 1 \land |q^\circ| \leq 1$
2. the transitive closure (causal order) $G^+$ of $G$ is irreflexive
3. $\forall \ x \in Q \cup V$ the set $\{y \ | \ (y,x) \in G^+\}$ is finite
4. $M_0$ quals the minimal set of places in $K$ under $G^+$, i.e. $$M_0 = {}^\circ K := \{q \in Q \ | \ {}^\circ q =  \emptyset \}$$
```

# Informally
1. It has no place branches: at most one arc ends/starts in a place
2. It is acyclic
3. Each sequence of arcs (flows) has a unique first element
4. Initial marking contains all places without incoming arcs
