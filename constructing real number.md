### Step 1
The members of $R$ will be certain subsets of [[rational number]] $Q$, called **cuts**. A cut is, by definition, any set $\alpha\subset Q$ with the following three properties.
1. $\alpha$ is not empty, and $\alpha\ne Q$.
2. If $p\in\alpha,q\in Q$, and $q<p$, then $q\in\alpha$.
3. If $p\in\alpha$, then $p<r$ for some $r\in\alpha$.
The letters $p,q,r,...$ will always denote rational numbers, and $\alpha,\beta,\gamma,...$ will denote cuts.
Note that 3 simply says that $\alpha$ has no largest member; 2 implies two fact which will be used freely:
+ If $p\in\alpha$ and $q\notin\alpha$ then $p<q$.
+ If $r\notin\alpha$ and $r<s$ then $s\notin\alpha$.
### Step 2
Define "$\alpha<\beta$" to mean: $\alpha$ is a proper subset of $\beta$.
Let us check that this meets the requirements of [[ordered set]].
If $\alpha<\beta$ and $\beta<\gamma$ it is clear that $\alpha<\gamma$. It is also clear that at most one of the three relations can hold for any pair $\alpha,\beta$.

### Step 3
The ordered set $R$ has the [[least-upper-bound property]].
To prove this, let $A$ be a nonempty subset of $R$, and assume that $\beta\in R$ is an upper bound 