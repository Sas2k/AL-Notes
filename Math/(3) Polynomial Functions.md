## 3.1 Intro to Polynomials
----------------------------
A Polynomial is a mathematical expression built with indeterminates and coefficients that only has addition, subtraction, multiplication, division and exponentiation to non-negative powers.

Polynomials can be classified according to how many terms they have,

1. **Monomial** has only one term  $\rightarrow x, 4x, 3x^2$
2. **Binomial** has only two terms $\rightarrow x + 5, 3x - 2, 5x^2 - 4$
3. **Trinomials** has only three terms $\rightarrow x^2 + 2x + 1, x^3+2x+4x^3$

And anything from trinomials and larger is usually referred as a **Polynomial** _('Poly' means many)_

## 3.2 Quadratic Functions
-----------------------------
Functions of the form,
$$
f(x) = ax^2 + bx + c \rightarrow (1)
$$
are considered to be quadratic functions. They have a standard form of $f(x) = a(x - h)^2 +k$. Making $x$ the subject in (1) when $f(x)$ is 0. you get,
$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$
The above formula is known as the quadratic formula, it's used to find the roots of the equation

Now since the function and the general form are equal we can find the values of $h$ and $k$ with respect to  $a$,$,b$ and $c$
$$
\begin{align*}
ax^2 + bx + c &= a(x-h)^2 + k \\
\cancel{ax^2} + bx + c &= \cancel{ax^2} - 2ahx + ah^2 + k \\
bx + c &= -2ahx + (ah^2 + k) \\
\because b = -2ah & \text{ and } c = ah^2 + k \\
\therefore h &= \frac{b}{-2a} \rightarrow (1) \\
\\
c &= ah^2 + k \rightarrow (2)\\
\text{Sub } &(1) \text{ in } (2); \\
c &= a \cdot\biggl(\frac{b}{-2a}\biggr)^2 + k \\
c &= \cancel{a} \cdot \frac{b^2}{4a^\cancel{2}} + k \\
k &= c - \frac{b^2}{4a}
\end{align*}
$$

```desmos-graph
y=x^2 + 2x + 1
```

The point created with the variables $h$ and $k$ in the standard form gives the vertex of the parabola. (The curve like shape created by a Quadratic Functions)

Let's see if we can figure out the function of the above graph. We can see that the turning point is the vertex point of this graph.
$$
(h, \;k) = (-1, 0)
$$
Now, we can these values to the standard formula first.
$$
\begin{align*}
f(x) &= a(x - h)^2 + k \\
     &= a(x - (-1))^2 + 0 \\
f(x) &= a(x + 1)^2
\end{align*}
$$
now that we have this we need to figure out the value of $a$, since the parabola is turning upwards $a$ must be positive. After looking at the graph we see that $(0, \;1)$ is also a point on the graph we can sub these points into the above as $x$ and $f(x)$ to figure out $a$.
$$
\begin{align*}
1 &= a(0 + 1)^2 \\
  &= a  \cdot 1^2 \\
1 &= a
\end{align*}
$$

Therefore, we can say that the function is $f(x) = (x + 1)^2$

 Every quadratic function has it's domain in the $\mathbb{R}$ (Real) Domain.

It's Range though differs according to the status of the variable $a$
$$
\begin{align*}
\text{In } f(x) &= ax^2+bx+c \\
R \; \text{(when a > 0)}&: \biggl[f\biggl(-\frac{b}{2a}\biggl), \infty \biggr] \\
R \; \text{(when a < 0)}&: \biggl(-\infty,  f\biggl(-\frac{b}{2a}\biggl)\biggr] \\
\end{align*}
$$
$$
\begin{align*}
\text{In } f(x) &= a(x - h)^2 + k \\
R \;(\text{when a > 0}) &: f(x) \ge k \\
R \;(\text{when a < 0}) &: f(x) \le k
\end{align*}
$$

## 3.3 Power Functions
------------------------
A power function is a continuous and smooth graph with a general equation like this,
$$
\begin{gather*}
f(x) = \underbrace{k}_\text{Coefficient}\cdot x^p \\
k, \;p \in \mathbb{R}
\end{gather*}
$$
There are two types of power functions,
1. Even Power Functions - Functions which have an **even number** as the power
2. Odd Power Functions - Functions which have an **odd number** as the power

> Tip: Click on the Cell to view the graph

| Value of $k$ | Even Power Functions                                                                                                                | Odd Power Functions                                                                                                                                                                               |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| $k > 0$      | ```desmos-graph<br>y = x^4<br>```<br><br>$\begin{align*}\text{as } x \rightarrow \pm \infty,\; f(x) \rightarrow \infty\end{align*}$ | ```desmos-graph<br>y = x^5<br>```<br><br>$\begin{align*}\text{as } x \rightarrow \infty&,\; f(x) \rightarrow \infty \\ \text{as } x \rightarrow -\infty&,\; f(x) \rightarrow -\infty\end{align*}$ |
| $k < 0$      | ```desmos-graph<br>y = -x^4<br>```<br>$$<br>\text{as } x \rightarrow \pm\infty, f(x) \rightarrow -\infty<br>$$                      | ```desmos-graph<br>y = -x^5<br>```<br>$\begin{align*}\text{as } x \rightarrow \infty&,\; f(x) \rightarrow -\infty \\ \text{as } x \rightarrow -\infty&,\; f(x) \rightarrow \infty\end{align*}$    |
The behavior of the function when x gets infinitely larger or infinitely smaller is called the "End Behavior" of the function.



## 3.4 Polynomial Functions
-------------------------------
A polynomial function consists of either 0 or the sum of a finite number of non-zero terms raised to non-negative exponents.

Below is the general form of polynomial functions

$$
f(x) = a_nx^n + a_{n-1}x^{n-1} + \cdots + a_2x^2 + a_1x + a_0
$$
The term $a_nx^n$ is known as the **Leading Term** and $a_n$ is the **Leading Coefficient**.

Any Degree Polynomial Graphs are a **Continuous function** of **smooth curves**

> Continuous function $\rightarrow$ A graph with no breaks in them (It can be draw without lifting the pen up.)
> Smooth Curves $\rightarrow$ A graph with no sharp corners

If a graph follows the above two properties it's a polynomial function

```desmos-graph
a = 0.8
b = -3
c = 0.8
d = 2.7
f(x) = ax^3 + bx^2 + cx + d
\left(0,\ 2.7\right) | Blue
\left(2.35868,\ -1.6054\right) | Black
\left(0.14132,\ 2.7554\right) | Black
\left(-0.76119,\ 0\right) | Green
\left(1.44699,\ 0\right) | Green
\left(3.0642,\ 0\right) | Green
```
The 2 **Black** Points are referred to as the turning points. The singular **Blue** point is known as the y-intercept and the 3 **Green** points are referred as the x intercepts.

> Note: A Polynomial of $n$-th degree will have at most $n$ $x$-intercepts and and $n - 1$ turning points.


## 3.5 Division of Polynomials
---------------------------------

Division of polynomials is done by either long division or synthetic division.

### 3.5.1 Long Division of polynomials

Long division is the simplest method as it uses the same method if we to divide normal numbers, and it would yield a result like this

$$
f(x) = d(x)q(x) + r(x)
$$

where $d(x)$, $q(x)$ and $r(x)$ are the dividend, quotient and remainder of the $f(x)$ polynomial.

The $r(x)$ is either 0 or a polynomial with a degree strictly lower than $d(x)$. When $r(x)$ is 0, then $q(x)$ and $d(x)$ are factors of $f(x)$ 

### 3.5.2 Synthetic Division of polynomials

Synthetic division is a short-cut that's used when the divisor of the polynomial is in the form of $(x - k)$

The difference here is that we only use the coefficients of the polynomials then we bring down multiply and add. The way I just said is a bit confusing but here's the steps explaining it.

1. Write $k$ for the divisor.
2. Write the coefficients of the dividend.
3. Bring the lead coefficient down.
4. Multiply the lead coefficient by $k$. Write the product in the next column.
5. Add the terms of the second column.
6. Multiply the result by $k$. Write the product in the next column.
7. Repeat steps 5 and 6 for the remaining columns.
8. Use the bottom numbers to write the quotient. The number in the last column is the remainder. The next number from the right has degree 0, the next number has degree 1, and so on. ^[1.]

![[Synthetic-Division.png]]
_Taken from OpenStax Precalculus 2e_
## 3.6 Remainder Theorem
------------------------------

From what the division algorithm states, that if a polynomial $f(x)$ is divided by $d(x)$, There it must exist unique polynomials such as $q(x)$ and $r(x)$.

$$
f(x) = d(x)\cdot q(x) + r(x)
$$
Now, the remainder theorem says that _If the polynomials is divided by $x - k$, the result can be obtained by evaluating the function at k_

We can prove this by replacing $d(x)$ with $x - k$., Since of that $d(x)$ is a linear function which means the remainder is a constant. Now, to prove this we'll evaluate it at $x = k$.

$$
\begin{align*}
f(x) &= (x - k) \cdot q(x) + r \\
f(k) &= (k - k) \cdot q(k) + r \\
     &= 0 \cdot q(k) + r \\ \\
\therefore f(k) &= r \; \square
\end{align*}
$$

Now, since we know this we can apply this to evaluate functions at a specific point.

>**Remainder Theorem**: If a polynomial $f(x)$ is divided by, $x−k$, then the remainder is the value $f(k)$.^[2.]

### 3.6.1 Evaluating Functions with the Remainder Theorem

When a polynomial $f(x)$ is given, you can evaluate the polynomial at $x = k$, by applying synthetic division with the divisor being $x - k$.

Here's and example, where the polynomial is $f(x) = 6x^4 - x^3 - 15x^2 + 2x - 7$ at $x = 2$. For this we simply let the divisor be $x - 2$ and divide.


$$
\begin{array}{c|rrr}
  & 6 & -1 & -15 &  2 & -7\\
2 &   & 12 & 22  & 14 & 32\\
\hline
  & 6 & 11 & 7   & 16 & 25\\
\end{array}
$$
with this we identified that $f(2) = 25$, we can also confirm this by simplifying the function at $x = 2$ using substitution.

$$
\begin{align*}
f(2) &= 6\cdot2^4 - 2^3 - 15\cdot2^2 + 2\cdot2 - 7 \\
     &= 6\cdot16 - 8 - 15\cdot4 + 4 - 7 \\
     &= 96 - 8 - 60 - 3 \\
     &= 96 - 71 \\
f(2) &= 25
\end{align*}
$$

## 3.7 Factor Theorem
------------------------
Now, if we recall the remainder theorem which we just discussed about now. We can know that it tells us that.
$$
f(x) = (x -k)q(x) + r
$$
if we let $k = 0$ then, the function at $k$ will also be a zero and therefore we get, $f(x) = (x - k)q(x)$
In this form, $x - k$ is a factor of $f(x)$, We can conclude that $f(k)$ must be a zero of the function, then $x - k$ is a factor of $f(x)$.

in a similar manner, if $(x - k)$ is a factor of $f(x)$, the division algorithm says that $f(x) = (x -k)q(x) + r$ is 0. which means $k$ is 0.

As the pair of implications would have it, this would mean that the polynomial of $n^{th}$ degree would have $n$ roots/zeros in the complex plane. Therefore we can use the Factor theorem to factor out the $n$ terms and get the zeros.

> **Factor Theorem**: _According to the Factor Theorem, kk is a zero of f(x)f(x) if and only if (x−k)(x−k) is a factor of f(x)._ ^[3.]

### 3.7.1 Getting the factors of a polynomial when a single factor is already given with the Factor Theorem

For this, we simply do synthetic division with the given factor as the dividend to see if the final remainder is 0. Then we write it as a product of dividends to quadratic quotients. Then if it's possible we factor the quadratic we get.
Then we write the polynomial out of the factors we got.

Here's an example,
1. Show that $(x + 2)$ is a factor of $f(x) = x^3−6x^2−x+30$, Find the remaining factors and the zeros/roots of the function.
	  - We first use synthetic division with $(x + 2)$ to show that it's a factor.
	    $$
	    \begin{array}{c|rrr}
		   & 1 & -6 & -1 &  30\\
		-2 &   & -2 & 16 & -30\\
		\hline
		   & 1 & -8 & 15 &  0 \\
		\end{array}
	     $$
	    with this, we can confirm that $(x + 2)$ is indeed a factor
	- Now, we can rewrite the function as a product,
	  $$f(x) = (x + 2)(x^2 - 8x + 15)$$
	- We also notice that we can factor the quadratic quotient
	  $$
	   \begin{align*}
	   f(x) &= (x + 2)(x^2 -3x - 5x + 15) \\
	        &= (x + 2)[x(x - 3) -5(x - 3)] \\
	   f(x) &= (x + 2)(x - 5)(x - 3)
	   \end{align*}
	   $$
	- Now, we can firmly say that the roots of this equation are at, $x = -2$, $x = 3$, and $x = 5$.

## 3.8 Rational Zero Theorem
--------------------------------

> **Rational Zero Theorem**: _The Rational Zero Theorem states that, if the polynomial $f(x)=a_nx^n+a_{n−1}x^{n−1}+...+a_1x+a_0$ has integer coefficients and $a_n≠0$, then every rational zero of $f(x)$ has the form $pq$ where $p$ is a factor of the constant term $a_0$ and $q$ is a factor of the leading coefficient $a_n$.
>When the leading coefficient is 1, the possible rational zeros are the factors of the constant term._^[4.]

Simply said, the Rational Zero Theorem is a way to narrow down the number of rational numbers we can test for roots with the Factor Theorem.

Now the way, that the Rational Zero Theorem takes numbers is by taking the list of the factors of the leading coefficient (to be $q$) and the factors of the leading constant(to be $p$), and evaluating the function at $f(\frac{p}{q})$ to see if it evaluates to zero.

Here's an example where the polynomial is, $f(x) = 2x^4 − 5x^3 + x^2 − 4$. And here's how we find all possible rational zeros
$$
\begin{align*}
p &\longrightarrow \pm1, \pm2, \pm4 \\
q &\longrightarrow \pm1, \pm2 \\
\frac{p}{q} &= \biggl\{\frac{\pm1}{\pm1}, \frac{\pm1}{\pm2}, \frac{\pm2}{\pm1}, \frac{\pm2}{\pm2}, \frac{\pm4}{\pm1}, \frac{\pm4}{\pm2}\biggr\} \rightarrow\text{All Options} \\
\text{Since, }\frac{\pm2}{\pm1} = \frac{\pm4}{\pm2} &\text{ and } \frac{\pm1}{\pm1} = \frac{\pm2}{\pm2}, \text{We can replace them with } \pm 2 \text{ and } \pm 1\\
\therefore \frac{p}{q} &= \biggl\{\frac{\pm1}{\pm2}, \pm1, \pm 2, \pm4 \biggr\}
\end{align*}
$$

## 3.9 Finding the zeros of a Polynomial function
-------------------------------------------------------
1. Use the Rational Zero Theorem to identify all possible rational zeros
2. Use, the synthetic division method on every candidate and see if the final remainder is 0, if so then it's a zero/root. If possible continue this until the quotient is a _quadratic_.
3. Find the roots of the _quadratic quotient_, by either factoring the equation or using the quadratic formula

Something we can also use is the **Fundamental Theorem of Algebra**, every polynomial has at least one **complex solution**. We can use this argue and say that for a polynomial $f(x)$ with degree $n > 0$ and $a$ is a non-zero real number, the $f(x)$ has at least $n$ linear factors

>See Complex Numbers in [Replace this with the note of Complex Numbers]


$$
f(x) = a(x - c_1)(x - c_2)\cdots(x - c_n)
$$
Where $c_1, c_2, \cdots, c_n$ are complex numbers. Therefore $f(x)$ has $n$ roots if allow for multiplicities.

## 3.10 Descartes's Rule of Signs
------------------------------------
The most straightforward way one could ascertain the number of positive and negative roots of a polynomial is with _Descartes's Rule of Signs_. The Rules says that when the input is changed it's sign, the number of sign changes within the polynomial says the number of negative roots of a polynomial. For example;
$$
\begin{align*}
f(x)  &= x^4 + x^3 + x^2 + x - 1 \\
f(-x) &= (-x)^4 + (-x)^3 + (-x)^2 + (-x) - 1\\
      &= x^4 - x^3 + x^2 - x -1
\end{align*}
$$
In this case there's 3 sign changes in $f(-x)$. This tells us that $f(x)$ can have 3 negative roots or 1 negative root.

----

Also when describing Intervals, Domains, Ranges and Asymptotes we have 2 methods
1. [Interval Notation]([[(1 - A) Interval Notation]]) which we described in [[(1) Functions and Graphs]]
2. [Arrow Notation]([[(3 - A) Arrow Notation]]) which is similar to interval notation except it's arrows.

## 3.11 Modelling using Variation
------------------------------------
Variation is where you recreate a relation with an equation model a behavior and predict an outcome. There are multiple types of variations
1. Direct Variation - _The ratio between the variables are directly proportional to each other._
	- We can use $y = kx^n$ to describe these types of variation, with $k$ being the multiple which they are proportional.
2. Inverse Variation - _The ratio between the variables are inversely proportional to each other_.
	- We can use $y = \frac{k}{x^n}$ to describe this.

With that this unit is over.

---
---
Author: Sasen Perera

Citations:
- [1.] - https://openstax.org/books/precalculus-2e/pages/3-5-dividing-polynomials 
-  [2.]  [3.]  [4.] -  https://openstax.org/books/precalculus-2e/pages/3-6-zeros-of-polynomial-functions
