# Exercise 1.2.9

## (a)

$$
f^{-1}(A) = [-2, 2]
$$

$$
f^{-1}(B) = [-1, 1]
$$

$$
f^{-1}(A \cap B) = f^{-1}([0, 4] \cap [-1, 1]) = f^{-1}([0, 1]) = [-1, 1] = [-2, 2] \cap [-1, 1] = f^{-1}([0, 4]) \cap f^{-1}([-1, 1]) = f^{-1}(A) \cap f^{-1}(B)
$$

$$
f^{-1}(A \cup B) = f^{-1}([0, 4] \cup [-1, 1]) = f^{-1}([-1, 4]) = [-2, 2] = [-2, 2] \cup [-1, 1] = f^{-1}([0, 4]) \cup f^{-1}([-1, 1]) = f^{-1}(A) \cup f^{-1}(B)
$$

## (b) -- part I

We need to show 

$$g^{-1}(A \cap B) = g^{-1}(A) \cap g^{-1}(B)$$

Let $g(x) = y$. 

Then,

$$
x \in g^{-1}(A \cap B) \implies y \in A \cap B \implies y \in A \land y \in B \implies x \in g^{-1}(A) \land x \in g^{-1}(B) \implies x \in g^{-1}(A) \cap g^{-1}(B)
$$

This demonstrates 

$$g^{-1}(A \cap B) \subseteq g^{-1}(A) \cap g^{-1}(B)$$

We also have

$$
x \in g^{-1}(A) \cap g^{-1}(B) \implies x \in g^{-1}(A) \land x \in g^{-1}(B) \implies y \in A \land y \in B \implies y \in A \cap B \implies x \in g^{-1}(A \cap B)
$$

This demonstrates 

$$g^{-1}(A) \cap g^{-1}(B) \subseteq g^{-1}(A \cap B)$$ 

and thus

$$g^{-1}(A \cap B) = g^{-1}(A) \cap g^{-1}(B)$$


## (b) -- part II

We need to show 

$$g^{-1}(A \cup B) = g^{-1}(A) \cup g^{-1}(B)$$

Let $g(x) = y$. 

Then,

$$
x \in g^{-1}(A \cup B) \implies y \in A \cup B \implies y \in A \lor y \in B \implies x \in g^{-1}(A) \lor x \in g^{-1}(B) \implies x \in g^{-1}(A) \cup g^{-1}(B)
$$

This demonstrates 

$$g^{-1}(A \cup B) \subseteq g^{-1}(A) \cup g^{-1}(B)$$

We also have

$$
x \in g^{-1}(A) \cup g^{-1}(B) \implies x \in g^{-1}(A) \lor x \in g^{-1}(B) \implies y \in A \lor y \in B \implies y \in A \cup B \implies x \in g^{-1}(A \cup B)
$$

This demonstrates 

$$g^{-1}(A) \cup g^{-1}(B) \subseteq g^{-1}(A \cup B)$$ 

and thus

$$g^{-1}(A \cup B) = g^{-1}(A) \cup g^{-1}(B)$$
