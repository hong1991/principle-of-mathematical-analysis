For every [[real field|real]] $x>0$ and every integer $n>0$, there is one and only one positive real $y$ such that $y^n=x$. This number $y$ is written $\sqrt[n]{x}$ or $x^{1/n}$.
**Proof:** 
That there is at most one such $y$ is clear, since $0<y_1<y_2$ implies $y_1^n<y_2^n$.
Let $E$ be the set consisting of all positive real numbers $t$ such that $t^n<x$. If $t=x/(1+x)$ then $0\le t<1$. Hence $t^n\le t < x$. Thus $t\in E$, and $E$ is not empty.
If $t>1+x$ then $t^n\ge t>x$ so that $t\ne E$. Thus $1+x$ is an [[bounded|upper bound]] of $E$. Hence [[real field]] implies the existence of $y=\sup E$.
To prove that $y^n=x$ we will show that each of the inequalities $y^n<x$ and $y^n>X$ leads to a contradiction.
[[To Do]]