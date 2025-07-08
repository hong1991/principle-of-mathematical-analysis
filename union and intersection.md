Let $A$ and $\Omega$ be sets, and suppose that with each element $\alpha$ of $A$ there is assocaited a subset $\Omega$ which we denote by $E_\alpha$.
The set whose elements are the sets $E_\alpha$ will be denoted by $\{E_\alpha\}$. Instead of speaking of sets of sets, we shall sometimes speak of a collection of sets, or a family of sets.

### Union
The **union** of the set $E_\alpha$ is defined to be the set $S$ such that $x\in S$ if and only if $x\in E_\alpha$ for at least one $\alpha\in A$. We use the notation $$S=\bigcup_{\alpha\in A}E_\alpha.$$
If $A$ consists of the integers $1,2,...,n$, one usually writes $$S=\bigcup_{m=1}^nE_m$$or $$S=E_1\cup E_2\cup\cdots\cup E_n.$$If $A$ is the set of all positive integers, the usual notation is $$S=\bigcup_{m=1}^\infty E_m.$$The symbol $\infty$ merely indicates that the union of a [[countable]] collection of sets is taken, and should not be confused with the symbols $+\infty$, $-\infty$, introduced in [[extended real number system]].

### Intersection
The **intersection** of the sets $E_\alpha$ is defined to be the set $P$ such that $x\in P$ if and only if $x\in E_\alpha$ for every $\alpha\in A$. We use the notation $$\bigcap_{\alpha\in A}E_\alpha,$$or $$P=\bigcap_{m=1}^n E_m=E_1\cap E_2\cap\cdots\cap E_n,$$or $$P=\bigcap_{m=1}^\infty E_m,$$as for unions. If $A\cap B$ is not empty, we say that $A$ and $B$ **intersect**; otherwise they **disjoint**.