# Exercise 1.2.1

## (a) -- part I

Suppose, by way of contradiction, that there exist naturals $p, q$ such that $q \neq 0$, $gcd(p, q) = 1$ and

```math
\frac{p}{q} = \sqrt{3}
```

Then, 

```math
p^2 = 3q^2
```

But observe that $3 | p^2 \implies 3 | p$ because

if $p = 3k + 1$ then 

```math
p^2 = (3k + 1)^2 = 9k^2 + 6k + 1 = 3(3k^2 + 2k) + 1 \implies 3 \nmid p^2
```

and if $p = 3k + 2$ then

```math
p^2 = (3k + 2)^2 = 9k^2 + 12k + 4 = 3(3k^2 + 4k + 1) + 1 \implies 3 \nmid p^2
```

Hence, we've shown that $3 \nmid p \implies 3 \nmid p^2$, which proves the original lemma by contrapositive.

Now, since  $3 | p^2 \implies 3 | p$, let $p = 3k$. Then,

```math
p^2 = 3q^2 \implies 9k^2 = 3q^2 \implies q^2 = 3k^2 \implies 3 | q
```

by the same lemma

However, since $3 | p$ and $3 | q$, $3$ is a common factor (i.e. $gcd(p, q) > 1$). Contradiction! 

Thus, $\sqrt{3}$ is irrational.

## (a) -- part II

Suppose, by way of contradiction, that there exist naturals $p, q$ such that $q \neq 0$, $gcd(p, q) = 1$ and

```math
\frac{p}{q} = \sqrt{6}
```

Then, 

```math
p^2 = 6q^2
```

But observe that $6 | p^2 \implies 6 | p$ because

```math
p \equiv k \pmod{6} \text{ where } 1 \leq k \leq 5 \implies p^2 \equiv k^2 \pmod{6}
```

and 

```math
\begin{align*}
&1^2 &&\equiv 1 &&\pmod{6} \\
&2^2 &&\equiv 4 &&\pmod{6} \\
&3^2 &&\equiv 3 &&\pmod{6} \\
&4^2 &&\equiv 4 &&\pmod{6} \\
&5^2 &&\equiv 1 &&\pmod{6} \\
\end{align*}
```

Hence, we've shown that $6 \nmid p \implies 6 \nmid p^2$, which proves the original lemma by contrapositive.

Now, since  $6 | p^2 \implies 6 | p$, let $p = 6k$. Then,

```math
p^2 = 6q^2 \implies 36k^2 = 6q^2 \implies q^2 = 6k^2 \implies 6 | q
```

by the same lemma

However, since $6 | p$ and $6 | q$, $6$ is a common factor (i.e. $gcd(p, q) > 1$). Contradiction!

Thus, $\sqrt{6}$ is irrational.

## (b)

The same proof fails to apply to $\sqrt{4}$ because $4 | p^2 \nRightarrow 4 | p$. Consider $p = 2$ for instance. $4 | 2^2 = 4$ but $4 \nmid 2$
