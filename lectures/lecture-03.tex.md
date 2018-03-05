# Lecture 3: Congruences

Even integers are those that can be written as $2k$ for some integer $k$. The
odd integers are those that can be written as $2k + 1$ for some integer $k$.

We can split the integers into three classes; those that are $3k$ for some
integer $k$, those that are $3k + 1$ for some integer $k$, and those that are
$3k + 2$ for some integer $k$.

These classes also have particular properties. For example, the some of an
integer in the second class and an integer in the third class will always be in
the first class.

We don't have to stop with 3. We could divide integers into 4 different classes
according to their remainders when divided by 4, and so on.

## 3.1 Congruences

Let $n$ be a positive integer and let $a$ and $b$ be integers.

Basically $a \equiv b$ (mod $n$) means that $a$ and $b$ have the same remainder
when you divide them by $n$.

**Definition** We say $a \equiv b$ (mod $n$) if $n$ divides $a - b$.

**Equivalent definition** We say $a \equiv b$ (mod $n$) if $a = kn + b$ for some
integer $k$.

Note we are talking about "congruence modulo _n_" as a relation here, which is
not quite the same as using a mod operation.

Really "$a \stackrel{\equiv}{n}b$" would be netter notation thatn "$a \equiv b$ (mod $n$)".
