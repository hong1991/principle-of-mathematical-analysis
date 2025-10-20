---
keywords:
  - diameter
  - Cauchy sequence
---

A [[sequence]] $\{p_n\}$ in a [[metric space]] $X$ is siad to be a **Cauchy sequence** if for every $\epsilon>0$ there is an integer $N$ such that $d(p_n,p_m)<\epsilon$ if $n\ge N$ and $m\ge N$.

Let $E$ be a nonempty subset of a metric space $X$, and let $S$ be the set of all real numbers of the form $d(p,q)$, with $p\in E$ and $q\in E$. The [[supremum and infimum|sup]] of $S$ is called the **diameter** of $E$.

If $\{p_n\}$ is a sequence in $X$ and if $E_N$ consists of the points $p_N,p_{N+1},p_{N+2},...$, it is clear from the two preceding definitions that $\{p_n\}$ is a Cauchy sequence if and only if $$\lim_{N\to\infty}\operatorname{diam} E_N=0.$$

