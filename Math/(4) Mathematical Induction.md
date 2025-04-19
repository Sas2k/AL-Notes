Mathematical Induction is a type of mathematical proof used to prove certain types of mathematical statements. Mathematical Induction is generally used to prove statements in the Domain of $\mathbb{N}$.

Mathematical Induction is broken down to 2 cases,
1. **Base Case**: Here we prove the statement is true for the first case. (Usually at $n = 0$ or $n = 1$)
2. **Induction Step**: We go through with this step with the assumption that the statement holds true for $n = k$, Then we prove that this is true for $n = k + 1$.

So in short, proof by induction is analogous to falling dominos. After the first domino falls so does the others.

Here's some statements proved with **Mathematical Induction**

## 4.1 Sum of $n$ natural numbers
----
### To be proved: Prove that for all $n \in \mathbb{N}, \; 1 + 2 + 3 + \cdots + n = \frac{n(n + 1)}{2}$ 

### Proof:
#### Base Case:
At $n = 1$,
$$
\begin{align*}
1 &= \frac{1 \cdot (1 + 1)}{2} \\
  &= \frac{1 \cdot 2}{2} \\
1 &= 1 \; (\text{Holds true at n = 1})
\end{align*}
$$
Thus, the base case is verifies the statement.
#### Inductive Step:
Assuming that the statement holds for some $n = k$,
$$
\begin{align*}
1 + 2 + 3 + \cdots + k &= \frac{k(k + 1)}{2}
\end{align*}
$$
We must prove that it also holds for $n = k + 1$,
$$
\begin{align*}
\underbrace{1 + 2 + 3 + \cdots + k} + (k + 1) &= \frac{(k + 1)[(k + 1) + 1]}{2} \\
\frac{k(k + 1)}{2} + (k + 1) &= \frac{(k + 1)[k + 1 + 1]}{2} \\
\frac{k(k + 1) + 2(k + 1)}{2} &= \frac{(k + 1)(k + 2)}{2} \\
\frac{(k + 1)(k + 2)}{2} &= \frac{(k + 1)(k + 2)}{2} \\
\end{align*}
$$
Thus,
$$
\text{L.H.S.} = \text{R.H.S.}
$$
$\therefore$ The statement holds at $n = k + 1$, and establishes the inductive step.

#### Conclusion:
Since we've proved that the formula holds at $n = 1$. We've proven that if the formula holds at $n = k$, then it also holds for $n = k + 1$. By **mathematical induction** the statement holds for all $n \in \mathbb{N}$. 
$\square$

## 4.2 Sum of $n$ powers of $2$

### To be proved: Prove that for all $n \in \mathbb{N}, \; 1 + 2 + 4 + \cdots + 2^{n - 1} = 2^n - 1$
### Proof:
#### Base Case:
at $n = 1$,
$$
\begin{align*}
1 &= 2^1 - 1 \\
  &= 2 - 1 \\
1 &= 1 
\end{align*}
$$
$\therefore$ the statement holds for the base case

#### Inductive Steps
Assuming that the statement holds for some $n = k$,
$$
\begin{align*}
1 + 2 + 4 + \cdots + 2^{k - 1} = 2^k - 1
\end{align*}
$$
We must prove that it also holds for $n = k + 1$,
$$
\begin{align*}
\underbrace{1 + 2 + 4 + \cdots + 2^{k - 1}}_{2^k - 1} + 2^{(k + 1) - 1} &= 2^{k  + 1} - 1 \\
2^k - 1 + 2^k &= 2^{k + 1} - 1 \\
2\cdot2^{k} - 1 &= 2^{k + 1} - 1 \\
2^{k + 1} - 1 &= 2^{k + 1} - 1 
\end{align*}
$$
Thus,
$$
\text{L.H.S.} = \text{R.H.S.}
$$
$\therefore$ The statement holds at n = k + 1, and established the Inductive Steps.

#### Conclusion:
Since we've proved that the statement holds at the base case. We've proven that that if the statement holds at $n = k$ then it also holds at $n = k + 1$. By mathematical induction,
$$
1 + 2 + 4 + \cdots + 2^{n - 1} = 2^n - 1
$$
holds for every $n \in \mathbb{N}$.