# Exercise 1.2.4

Let $A_1$ be the set of all naturals that cannot be written as a prime power (i.e. $p^n$ where $p \in \mathbb{N}_{\text{prime}}$ and $n \in \mathbb{N}$).

This set includes, for example, $1$ (or $6$).

Let

```math
\begin{align*}

&A_2 &&= \{ k \in \mathbb{N} : k = 2^n, n \in \mathbb{N} \} \\

&A_3 &&= \{ k \in \mathbb{N} : k = 3^n, n \in \mathbb{N} \} \\

&A_4 &&= \{ k \in \mathbb{N} : k = 5^n, n \in \mathbb{N} \} \\

\\ && \dots \\

&A_p &&= \{ \text{ all the powers of the } (p - 1) \text{-th prime} \}
\end{align*}

```

Due to the prime factorization theorem, we have

```math
\cup_{i = 1}^{\infty} A_i = \mathbb{N}
```

and 

```math
A_i \cap A_j \text{ where } i, j \in \mathbb{N} \text{ such that } i \neq j = \mathbb{N}
```

as desired.
