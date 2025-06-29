An [[ordered set]] $S$ is said to have the **least-upper-bound property** if the following is true:
If $E\subset S$, $E$ is not empty, and $E$ is [[bounded]] above, then $\sup E$([[supremum and infimum|*]]) exists in $S$.

Theorem below shows that every ordered set with the least-upper-bound property also has the **greatest-lower-bound property**. 

**Theorem**
Suppose $S$ is an ordered set with least-upper-bound property, $B\subset S$, $B$ is not empty, and $B$ is bounded below. Let $L$ be the set of all lower bounds of $B$. Then $$\alpha=\sup L$$exists in $S$, and $\alpha =\inf B$. In particular, $\inf B$ exists in $S$.
**Proof:** Since $B$ is bounded below, $L$ is not empty. Since $L$ consists of exactly those $y\in S$ which satisfy the inequality $y\le x$ for every $x\in B$, we see that every $x\in B$ is an upper bound of $L$. Thus $L$ is bounded above. Our hypothesis about $S$ implies therefore that $L$ has a supremum in $S$; call it $\alpha$.
If $\gamma<\alpha$ then $\gamma$ is not an upper bound of $L$, hence $\gamma\notin B$. It follows that $\alpha\le x$ for every $x\in B$. Thus $\alpha\in L$.
If $\alpha<\beta$ then $\beta\notin L$, since $\alpha$ is an upper bound of $L$.
We have show that $\alpha\in L$ but $\beta\notin L$ if $\beta>\alpha$. In other words $\alpha is a lower bound of $B$, but $\beta$ is not if $\beta>\alpha$. This means that $\alpha=\inf B$.

**Examples**
1. Consider the sets $A$ and $B$ of [[rational number|Example]] of the ordered set $Q$. The set $A$ is bounded above. In fact, the upper bounds of $A$ are exactly the members of $B$. Since $B$ contains no smallest member, $A$ has no **least upper bound** in $Q$.<br>Similarly, $B$ has no **greatest lower bound** in $Q$.
2. If $\alpha=\sup E$ exists, then $alpha$ may or may not be a member of $E$. For instance, let $E_1$ be the set of all $r\in Q$ with $r<0$. Let $E_2$ be the set of all $r\in Q$ with $r\le0$. Then $$\sup E_1=\sup E_2=0,$$and $0\notin E_1$, $0\in E_2$.
3. Let $E$ consists of all numbers $1/n$, where $n=1,2,3,...$. Then $\sup E=1$, which is in $E$, and $\inf E = 0$, which is not in $E$.