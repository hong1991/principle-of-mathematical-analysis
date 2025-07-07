A **rational number** is the numbers of the form $m/n$, where $m$ and $n$ are integers and $n\ne 0$, denoted $Q$. It's a [[ordered field]].

**Example**
We show that $$p^2=2\quad(1)$$is not satisfied by any rational $p$. If there were such a $p$, we could write $p=m/n$ where $m$ and $n$ are integers that are not both even. Let us assume this is done.
Then $(1)$ implies $$m^2=2n^2\quad(2)$$this shows that $m^2$ is even. Hence $m$ is even, and so $m^2$ is divisible by $4$. It follows that the right side of $(2)$ is divisible by $4$, so that $n^2$ is even, which implies that $n$ is even.
The assumption that $(1)$ holds thus lead to the conclusion that both $m$ and $n$ are even, contrary to our choice of $m$ and $n$. Hence $(1)$ is impossible for rational $p$.

Let $A$ be the set of all positive rationals $p$ such that $p^2\lt 2$ and let $B$ consists of all positive rationals $p$ such that $p^2>2$.
For every $p$ in $A$ we can find a rational $q$ in $A$ such that $p<q$, and for every $p$ in $B$ we can find a rational $q$ in $B$ such that $q<p$.
To do this, we associate with each rational $p>0$ the number $$q=p-\frac{p^2-2}{p+2}=\frac{2p+2}{p+2}\quad(3)$$then $$q^2-2=\frac{2(p^2-2)}{(p+2)^2}\quad(4)$$If $p$ is in $A$ then $p^2-2<0$, $(3)$ shows that $q>p$, and $(4)$ shows that $q^2<2$. Thus $q$ is in $A$.
If $q$ is in $B$ then $p^2-2>0$, $(3)$ shows that $0<q<p$, and $(4) shows that $q^2>2$. Thus $q$ is in $B$.
Thus $A$ contains no largest number and $B$ contains no smallest number.

**Remark** 
The example above has been to show that the rational number system has certain gaps, in spite of the fact that between any two rationals there is another: If $r<s$ then $r<(r+s)/2<s$. The [[real field|real number system]] fills these gaps. This is the principal reason for the fundamental role which it plays in analysis.