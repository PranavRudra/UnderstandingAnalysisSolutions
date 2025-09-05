# Exercise 1.2.10

## (a)

False, let $a = b$.

## (b)

False, let $a = b$

## (c)

This is true. For the forward case, i.e. 

$$
a \leq b \implies a < b + \epsilon\ (\forall \epsilon > 0)
$$

observe that there are two cases

$$
a = b \implies a - b = 0 \implies a - b < \epsilon\ (\forall \epsilon > 0) \implies a < b + \epsilon
$$

and 

$$
a < b \implies a < b + \epsilon\ (\forall \epsilon > 0)
$$

For the reverse case, i.e. 

$$
a < b + \epsilon\ (\forall \epsilon > 0) \implies a \leq b
$$

we can prove this by contradiction. Suppose that

$$
a < b + \epsilon\ (\forall \epsilon > 0) \implies a - b < \epsilon
$$

but $a \not \leq b$. Then, 

$$
a \not \leq b \implies a > b \implies a - b > 0
$$

Let $a - b = \epsilon_0 > 0$. However, since 

$$
a - b < \epsilon\ (\forall \epsilon > 0) 
$$

it must be true that $a - b < \epsilon_0$. But both 

$$
a - b = \epsilon_0 \text { and } a - b < \epsilon_0
$$

can't be true at the same time. Contradiction!
