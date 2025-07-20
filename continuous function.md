Suppose $X$ and $Y$ are [[metric space]], $E\subset X$, $p\in E$, and $f$ [[function|maps]] $E$ into $Y$. Then $f$ is said to be **continuous** at $p$ if for every $\epsilon>0$ there exists a $\delta>0$ such that $$d_Y(f(x),f(p))<\epsilon$$for all points $x\in E$ for which $d_X(x,p)<\delta$.
If $f$ is continuous at every point of $E$, then $f$ is said to be **continuous on $E$**.
It should be noted that $f$ has to be defined at the point $p$ in order to be continuous at $p$. (Compare this with the remark following [[limit of function]].)
If $p$ is an [[elements and subsets of metric space|isolated point]] of $E$, then our definition implies that every function $f$ which has $E$ as its domain of definition is continuous at $p$. For, no matter which $\epsilon>0$ we choose, we can pick $\delta>0$ so that the only point $x\in E$ for which $d_X(x,p)<\delta$ is $x=p$; then $$d_Y(f(x),f(p))=0<\epsilon.$$

**Theorem**
Assume also that $p$ is a [[elements and subsets of metric space|limit point]] of $E$. Then $f$ is continuous at $p$ if and only if $\lim_{x\to p}f(x)=f(p)$.
**Proof:** This is clear if we compare with the definition of [[limit of function]].