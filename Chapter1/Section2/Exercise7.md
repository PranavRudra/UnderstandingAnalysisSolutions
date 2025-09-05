# Exercise 1.2.7

## (a)

$$
f(A) = [0, 4]
$$

$$
f(B) = [1, 16]
$$

$$
f(A \cap B) = f([0, 2] \cap [1, 4]) = f([1, 2]) = [1, 4] = [0, 4] \cap [1, 16] = f(A) \cap f(B)
$$

$$
f(A \cup B) = f([0, 2] \cup [1, 4]) = f([0, 4]) = [0, 16] = [0, 4] \cup [1, 16] = f(A) \cup f(B)
$$

## (b)

Let $A = \\{-2 \\}$ and $B = \\{ 2 \\}$. Then,

$$
f(A \cap B) = f(\\{-2\\} \cap \\{2\\}) = f(\emptyset) = \emptyset \neq \\{4\\} = \\{4\\} \cap \\{4\\} = f(\\{-2\\}) \cap f(\\{2\\})
$$

## (c)


$$
y \in g(A \cap B) \implies \exists x \in A \cap B \text{ such that } g(x) = y \implies x \in A \land x \in B \implies y \in g(A) \land y \in g(B) \implies y \in g(A) \cap g(B)
$$ 

Hence, 

$$
g(A \cap B) \subseteq g(A) \cap g(B)
$$

## (d)

We will show that 

$$
g(A) \cup g(B) \subseteq g(A \cup B)
$$

To do, observe

$$
y \in g(A) \cup g(B) \implies y \in g(A) \lor y \in g(B) \implies [\exists x \in A \text{ such that } g(x) = y] \lor [\exists x \in B \text{ such that } g(x) = y] \implies x \in A \cup B \implies y \in g(A \cup B)
$$
