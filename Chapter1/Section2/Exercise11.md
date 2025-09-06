# Exercise 1.2.11

## (a)

Negation: there exist real numbers satisfying $a < b$ such that for all $n \in \mathbb{N}$

$$
a + \frac{1}{n} \geq b
$$

The original statement, i.e. for all real numbers satisfying $a < b$, there exists $n \in \mathbb{N}$

$$
a + \frac{1}{n} < b
$$

is true. Note that

$$
a + \frac{b - a}{2} < a + (b - a) = b
$$

since $b - a > 0$. As a result, we can satisfy the statement if we choose $n$ such that

$$
a + \frac{1}{n} < a + \frac{b - a}{2} < b \implies \frac{1}{n} < \frac{b - a}{2} \implies n > \frac{2}{b - a} \implies n \geq \lceil \frac{2}{b - a} \rceil
$$


## (b)

Negation: for all real numbers $x > 0$, there exists $n \in \mathbb{N}$ such that

$$
x \geq \frac{1}{n}
$$

This negation statement is intuitively true. 

## (c)

Negation: there exist real numbers $x < y$ such that for all $q \in \mathbb{Q}$, $q < x$ or $q > y$

The original statement, i.e. between every two distinct real numbers there exists a rational number, is intuitively true. Even if one (or both) of these $x, y$ are irrational, 
the irrationals just populate "holes" in the rational line -- moving $\epsilon$ to the left or to the right of them gives you a rational number again
