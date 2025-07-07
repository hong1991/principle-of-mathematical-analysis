**Definition:**
A **complex number** is an ordered pair $(a, b)$ of [[real field|real numbers]]. "Ordered" means that $(a,b)$ and $(b,a)$ are regarded as distinct if $a\ne b$.
Let $x=(a,b)$, $y=(c,d)$ be two complex numbers. We write $x=y$ if and only if $a=c$ and $b=d$. We define $$x+y=(a+c,b+d)$$$$xy=(ac-bd, ad+bc).$$
**Definition:** $i=(0,1).$

**Theorem**
These definitions of addition and multiplication turn the set of all complex numbers into a [[field]], which $(0,0)$ and $(1,0)$ in the role of $0$ and $1$.
**Proof:** We simply verify the field axioms. Let $x=(a,b)$, $y=(c,d)$, $z=(e,f)$.
Addition axioms:
1. is clear.
2. $x+y=(a+c,b+d)=(c+a,d+b)=y+x$.
3. $(x+y)+z=(a+c,b+d)+(e,f)=(a+c+e,b+d+f)=(a,b)+(c+e,d+f)=x+(y+z)$.
4. $x+0=(a,b)+(0,0)=(a,b)=x$.
5. Put $-x=(-a,-b). Then $x+(-x)=(0,0)=0$.

Multiplication axioms:
1. is clear.
2. $xy=(ac-bd,ad+bc)=(ca-db,da+cb)=yx$.
3. $(xy)z=(ac-bd,ad+bc)(e,f)=(ace-bde-adf-bcf,acf-bdf+ade+bce)$$=(a,b)(ce-df,cf+de)=x(yz)$.
4. $1x=(1,0)(a,b)=(a,b)=x$.
5. If $x\ne0$ then $(a,b)\ne(0,0)$, which means that at least one of the real numbers $a$, $b$, is different from $0$. Hence $a^2+b^2>0$, by [[ordered field|proposition 4]], and we can define $$\frac{1}{x}=(\frac{a}{a^2+b^2},\frac{-b}{a^2+b^2}).$$Then $$x\cdot \frac{1}{x}=(a,b)(\frac{a}{a^2+b^2},\frac{-b}{a^2+b^2})=(1,0)=1.$$

Distributive law:
$x(y+z)=(a,b)(c+e,d+f)=(ac+ae-bd-bf,ad+af+bc+be)$$(ac-bd,ad+bc)+(ae-bf,af+be)=xy+xz.$

**Theorem:** $i^2=-1$.
**Proof:** $i^2=(0,1)(0,1)=(-1,0)=-1$.

Theorem: If $a$ and $b$ are real, then $(a,b)=a+bi$.
**Proof:** $a+bi=(a,0)+(b,0)(0,1)=(a,0)+(0,b)=(a,b)$.

**Defintion:**
If $a$, $b$ are real and $z=a+bi$, then the complex number $\bar{z}=a-bi$ is called the **conjugate** of $z$. The numbers $a$ and $b$ are the **real part** and the **imaginary part** of $z$, respectively.
$\Re(z)=a, \Im(z)=b$ 

