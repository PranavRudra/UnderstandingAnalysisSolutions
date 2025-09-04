# Exercise 1.2.12

## (a)

The base case is self-evident

$$
y_1 = 6 > -6
$$

For the inductive hypothesis, assume that for some $k \in \mathbb{N}^{\geq 2}$

$$
y_k = \frac{2y_{k - 1} - 6}{3} > -6
$$

For the inductive step, we have

$$
\begin{align*}
y_{k + 1} &= \frac{2y_k - 6}{3} \\
&> \frac{2(-6) - 6}{3}\ (\text{by the inductive hypothesis}) \\
&= \frac{-18}{3} \\
&= -6
\end{align*}
$$

as desired

## (b)

For the base case, we have

$$
y_2 = \frac{2y_1 - 6}{3} = \frac{2(6) - 6}{3} = \frac{6}{3} = 2 < 6 = y_1
$$

For the inductive hypothesis, assume that for some $k \in \mathbb{N}^{\geq 3}$

$$
y_k < y_{k - 1}
$$

For the inductive step, we have

$$
\begin{align*}
y_{k + 1} &= \frac{2y_k - 6}{3} \\
&< \frac{2y_{k - 1} - 6}{3}\ (\text{by the inductive hypothesis}) \\
&= y_k
\end{align*}
$$
