# Exercise 1.2.5

## (a)

Since 

```math
x \in (A \cup B)^c \implies x \notin (A \cup B) \implies x \notin A \land x \notin B \implies x \in A^c \land x \in B^c \implies x \in A^c \cap B^c
```

we have

```math
(A \cup B)^c \subseteq A^c \cap B^c
```

## (b)

Since 

```math
x \in (A \cap B)^c \implies x \notin (A \cap B) \implies x \notin A \lor x \notin B \implies x \in A^c \lor x \in B^c \implies x \in A^c \cup B^c
```

we have

```math
(A \cap B)^c \subseteq A^c \cup B^c
```

## (c)

From part (a), we already know that 

```math
(A \cup B)^c \subseteq A^c \cap B^c
```

Now, observe that

```math
x \in A^c \cap B^c \implies x \in A^c \land x \in B^c \implies x \notin A \land x \notin B \implies x \notin (A \cup B) \implies x \in (A \cup B)^c
```

Hence, 

```math
A^c \cap B^c \subseteq (A \cup B)^c 
```

which means that, by definition,

```math
(A \cup B)^c = A^c \cap B^c
```
