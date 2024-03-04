```ad-important
A net homomorphism from net $N_1=(P_1, T_1, F_1, M_1)$ to net $N_2=(P_2, T_2, F_2, M_2)$ is a mapping $h : P_1 \cup T_1 \to P_2 \cup T_ 2$ such that
1. $h(P_1) \subseteq P_2 \quad \land \quad h(T_1) \subseteq T_2$
2. $\forall \ t \in T_1$, the restriction of $h$ to ${}^\circ t$ is a bijection between ${}^\circ t$ and ${}^\circ h(t)$, and similarly for $t^\circ$ and $h(t)^\circ$
3. the restriction of $h$ to $M_1$ is a bijection between $M_1$ and $M_2$ 
```

## Informally

```ad-info
A net homomorphism is a mapping between nets that preserves
1. The nature of nodes
2. The environment of transitions (but not necessarily that of places)
3. The initial marking
```
