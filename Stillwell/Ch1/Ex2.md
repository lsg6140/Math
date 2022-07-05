## 1.2.1 
What property of $n^{2}$ _does_ follow from the equation $n^2=3m^2$.  

$n^2$ is a multiple of 3

## 1.2.2
Use this property to devise a proof that $\sqrt{3}$ is irrational.

$$
\begin{align}
3n^2=m^2\Rightarrow& m^2 \text{ is a multiple of } 3\\
\Rightarrow&m \text{ is a multiple of } 3 \\
\Rightarrow&m = 3m' \\
\Rightarrow&3n^2=(3m')^2 \\
\Rightarrow&n^2=3m'^2 \\
\Rightarrow&n \text{ is a multiple of } 3 \\
\Rightarrow&n=3n'\\
\Rightarrow&(3n')^2=3m'^2\\
\Rightarrow& 3=m'^2/n'^2 ~~~ (\text{  where } m' < m \text{ and } n' < n).\\
\end{align}
$$

So, for any pair $m,n$ of natural numbers with $3=m^2/n^2$ there is a _smaller_ pair $m',n'$ with the same property, and we therefore have an infinite descending sequence of natural numbers, which is impossible.
