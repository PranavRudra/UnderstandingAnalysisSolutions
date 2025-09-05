# Exercise 1.2.8

## (a)

Let $f(n) = 2n$ where $n \in \mathbb{N}$. Then $f$ is 1-1 because

$$
f(a) = f(b) \implies 2a = 2b \implies a = b
$$

However, $f$ is not onto because no odd number is mapped to. 

## (b)

Let

$$
f(n) = \begin{cases}
    \frac{n}{2} & \text{if } 0 \equiv n \mod{2} \\
    \frac{n + 1}{2}   & \text{if } 1 \equiv n \mod{2} \\
\end{cases}
$$

i.e. $f(2) = f(1) = 1$, $f(4) = f(3) = 2$, $f(6) = f(5) = 3$

Then, $f$ is onto because $f(2n) = n$ for every $n \in \mathbb{N}$

However, $f$ is not 1-1 because $f(2n) = f(2n - 1) = n$ even though $2n \neq 2n - 1$

## (c)

Impossible since $Z$ has more elements than $N$
