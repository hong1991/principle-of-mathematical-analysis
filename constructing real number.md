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
To prove this, let $A$ be a nonempty subset of $R$, and assume that $\beta\in R$ is an upper bound $A$. Define $\gamma$ to be the union of all $\alpha\in A$. In other words, $p\in\gamma$ if and only if $p\in\alpha$ for some $\alpha\in A$. We shall prove that $\gamma\in R$ and that $\gamma=\sup A$([[supremum and infimum|*]]).
Since $A$ is not empty, there exists an $\alpha_0\in A$. This $\alpha_0$ is not empty. Since $\alpha_0\subset\gamma$, $\gamma$ is not empty. Next, $\gamma\subset\beta$, and therefore $\gamma\ne Q$. Thus $\gamma$ satisfies property 1. To prove 2 and 3, pick $p\in\gamma$. Then $p\in\alpha_1$ for some $\alpha_1\in A$. If $q<p$, then $q\in\alpha_1$, hence $q\in\gamma$; this proves 2. If $r\in\alpha_1$ is so chosen that $r>p$, we see that $r\in\gamma$, and therefore $\gamma$ satisfies 3.
Thus $\gamma\in R$.
It is clear that $\alpha\le\gamma$ for every $\alpha\in A$.
Suppose $\delta<\gamma$. Then there is an $s\in\gamma$ such taht $s\notin\delta$. Since $s\in\gamma,s\in\alpha$ for some $\alpha\in A$. Hence $\delta<\alpha$ and $\delta$ is not an [[bounded|upper bound]] of $A$.
This gives the desired result: $\gamma=\sup A$.

### Step 4
If $\alpha\in R$ and $\beta\in R$, we define $\alpha+\beta$ to be the set fo all sums $r+s$, where $r\in\alpha$ and $s\in\beta$.
We define $0^*$ to be the set of all negative rational numbers. It is clear that $0^*$ is a cut. We verify that the axioms for addition([[field|*]]) hold in $R$, with $0^*$ playging the role of $0$.
1. We have to show that $\alpha+\beta$ is a cut. It is clear that $\alpha+\beta$ is a nonempty subset of $Q$. Take $r'\notin\alpha,s'\notin\beta$. Then $r'+s'>r+s$ for all choices of $r\in\alpha,s\in\beta$. Thus $r'+s'\notin\alpha+\beta$. It follows that $\alpha+\beta$ has property 1.<br>Pick$p\in\alpha+\beta$. Then $p=r+s$, with $r\in\alpha,s\in\beta$. If $q<p$, then $q-s<r$, so $q-s\in\alpha$, and $q=(q-s)+s\in\alpha+\beta$. Thus 2 holds.<br>Choose $t\in\alpha$ so that $t>r$. Then $p<t+s$$ and $t+s\in\alpha+\beta$. Thus 3 holds.
2. $\alpha+\beta$ is the set of all $r+s$, with $r\in\alpha,s\in\beta$. By the same definition, $\beta+\alpha$ is the set of all $s+r$. Since $r+s=s+r$ for all $r\in Q,s\in Q$, we have $\alpha+\beta=\beta+\alpha$.
3. As above, this follows from the associative law in $Q$.
4. If $r\in\alpha$ and $s\in0^*$, then $r+s<r$, hence $r+s\in\alpha$. Thus $\alpha+0^*\subset\alpha$.<br>To obtain the opposite inclusion, pick $p\in\alpha$, and pick $r\in\alpha,r>p$. Then $p-r\in0^*$, and $p=r+(p-r)\in\alpha+0^*$. Thus $\alpha\subset\alpha+0^*$. We conclude that $\alpha+0^*=\alpha$.
5. Fix $\alpha\in R$. Let $\beta$ be the set of all $p$ with the following property: There exists $r>0$ such that $-p-r\notin\alpha$.<br>In other words, some [[rational number]] smaller than $-p$ fails to be in $\alpha$. We show that $\beta\in R$ and that $\alpha+\beta=0^*$.<br>If $s\notin\alpha$ and $p=-s-1$. then $-p-1\notin\alpha$, hence $p\in\beta$. So $\beta$ is not empty. If $q\in\alpha$, then $-q\notin\beta$. So $\beta\ne Q$. Hence $\beta$ satisfies 1.<br>Pick $p\in\beta$ and $r>0$ so that $-p-r\notin\alpha$. If $q<p$, then $-q-r>-p-r$, hence $-q-r\notin\alpha$. Thus $q\in\beta$ and 2 holds. Put $t=p+(r/2)$. Then $t>p$ and $-t-(r/2)=-p-r\notin\alpha$, so that $t\in\beta$. Hence $\beta$ satisfies 3.<br>We have proved that $\beta\in R$.<br>If $r\in\alpha$ and $s\in\beta, then $-s\notin\alpha$, hence $r<-s$, $r+s<0$. Thus $\alpha+\beta\subset 0^*$.<br>To prove the opposite inclusion, [[To Do]]