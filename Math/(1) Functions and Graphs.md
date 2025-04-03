## 1.1 Functions
----------------------------

Functions are normally described as machines which take in a specific input and yields exactly one output. 
$$\underbrace{f(x)}_{\text{read as function of x (or f of x)}} = y$$
A relation is a set or ordered pairs as $\{(1,2),(2,4),(3,6),(4,8),(5,10)\}$

where the inputs are the **Domain** while the output are the **Range** (which will be explained later on.)

see [[(1 - A) Interval Notation]] for the systematic way of describing inequalities

this is the standard notation for describing functions, the variable y represents the vertical axis of a cartesian plane. below is a graph of $$f(x) = x$$

```desmos-graph
y=x
```


Below, is an example of using an output to determine the input of the function.
$$
\begin{align*}
f(x) &= 2 \cdot | x - 5 | - 8 \\
\text{when } f(x) &= 10 \; \text{what is x?} \\
\\
f(x) &= 2 \cdot | x - 5 | - 8 \\
10 &= 2 \cdot | x - 5 | - 8 \\
10 + 8 = &= 2 \cdot | x - 5  | \\
\frac{18}{2} &= | x - 5 | \\
9 + 5 = x &\text{ or } -9 + 5 = x \\
14 = x &\text{ or } -4 = x
\end{align*}
$$

```desmos-graph
left=-5
right=15
top=11
bottom=-10
---
y = 2 \cdot \abs(x - 5) - 8
(14, 10)
(-4, 10)
```

### 1.1.1 Minimums and Maximums (and their relative counterparts)

A maximum or a minimum is a point in the graph which is the highest/lowest value achieved by the function.

```desmos-graph
f(x) = (x + 1) ^ 2 + 2
f(x) = -(x - 1) ^ 2 - 1
f(x) = -2x^{3}+3x\ +\ 1
\left(-0.70711,\ -0.41421\right)
\left(0.70711,\ 2.41421\right)
```

In the following 3 functions (Blue, Purple and Green), We can only identify Minimums and Maximums from the Blue and Green Curves. With the Green Curve having a **Maximum** while the Blue Curve having a **Minimum**

in the **Purple Curve** we can get a relative minimum and maximum since their actual min and max are negative and positive infinity.

the relative minimum of the purple curve would be the **black** point and the relative maximum would be the **red** point

### 1.1.2 Parts of a Cartesian Plane
A Cartesian Plane can be divided into 4 sectors otherwise known as quadrants. In an anticlockwise order, it can be named Q1, Q2, Q3 and Q4.

```desmos-graph
(2.5, 2.5)|Label:Q1
(-2.5, 2.5)|Label:Q2
(-2.5, -2.5)|Label:Q3
(2.5, -2.5)|Label:Q4
```

## 1.2 Piecewise Functions
------------------------
A Piecewise function is quite literally a function in pieces, more accurately said a piecewise function acts on different functions depending on the range of the input.

$$
\begin{gather*}
f(x) = \begin{cases}
-1 & \text{if } x \leq -1,\\
x  & \text{if } x \in [-1, 1],\\
1  & \text{if } x \geq 1.
\end{cases}
\end{gather*}
$$
here, the value of the output is -1 if the input is less than or equal to -1, the output is itself if it's -1 or 1 and if it's greater than or equal to 1 it outputs 1.

```desmos-graph
f\left(x\right)\ =\ \left\{x\ \le\ -1:\ -1,\ \operatorname{abs}\left(x\right)\ =\ 1:\ x,\ x\ \ge1:\ 1\right\}
```

## 1.3 Difference Quotient 
------------------------

$$\frac{f(x + h) - f(x)}{h}$$

The difference quotient is the average rate of change in the function. And it may seem like the limit definition of the derivative. I assure you it is not. The difference quotient takes in average rate of change **between 2 points**. while the derivative indicates the **instantaneous change**

As to how this formula was derived, we must first remember the gradient formula where we take the x and y values from 2 points and divide them, 
$$m =\frac{y_2 - y_1}{x_2 - x_1} = \frac{\Delta y}{\Delta x} \, (\Delta\text{ is used to represent the change of difference of a variable})$$
we can say that the difference between $x_2$ and $x_1$ is $h$ (or height). And since we know that $y_2$ takes in $x_2$ which is $x_1 + h$ we can rewrite it as functions.

$$
\begin{align*}
\frac{y_2 - y_1}{x_2 - x_1} &= \frac{y_2 - y_1}{x + h - x} \\
                            &= \frac{f(x + h) - f(x)}{h}
\end{align*}
$$

## 1.4 Composite Functions
---------------------------
_Functions inside of functions_ are defined as **Composite Functions**.

$$
\begin{align*}
f(x) &\leftarrow \text{f of x} \\
g(x) &\leftarrow \text{g of x} \\
\\
f[g(x)] &\rightarrow \mathbf{composite \; function}
\end{align*}
$$
the notations is usually written as, $$(f \circ g)(x)$$
and an important thing to note is $f(x) \cdot g(x) \neq (f \circ g)(x)$.

in this, the output of $g(x)$ is the input of $f(x)$, so if were to write the composition in reverse as $(g \circ f)(x)$ it would be an entirely different function.

examples,
1. let $f(x) = \frac{1}{x + 4}$ and $g(x) = 2x + 4$, find $(f \circ g)(x)$
$$
\begin{align*}
(f \circ g)(x) &= f[g(x)] \\
               &= f[2x + 4] \\
               &= \frac{1}{(2x + 4) + 4} \\
(f \circ g)(x) &= \frac{1}{2x + 8}
\end{align*}
$$
2. What is the Domain and Range of the above composite function?
	-  since $(f \circ g)(x)$ is a fraction, we can use the asymptotes to get the Domain and Range
	 $$
	 \begin{align*}
	 \text{V.A:  }2x + 8 &= 0\\
	 2x &= - 8 \\
	 x &= \frac{-8}{2} \\
	 \text{V.A.} = (x &= - 4)
	 \end{align*}
	 $$
	H.A = $y = 0$
     The degree of the polynomial in the denominator is greater than the degree of the polynomial in the numerator, the horizontal asymptote is $y = 0$
	  $\therefore$ Domain = $D(-\infty,-4) \cup(-4, \infty)$ and Range = $R(-\infty, 0)\cup(0, \infty)$

## 1.5 Inverse Functions
----------------------

As of now, we've figured out how functions work, no we'll find how to find the functions which gives us the input from the output.

so to break it down,  if $f(2) = 3$ then it's inverse should do $f^{-1}(3) = 2$

now let's say a function is defined as $f(x) = x^2 + 4x - 5$, first we replace $f(x)$ as $y$, then we subject out x.
$$
\begin{align*}
f(x) &= x^2 + 4x - 5 \\
y    &= x^2 + 4x - 5 \\
y + 5 + 4 &= x^2 + 4x + 4 \\
y + 9 &= (x + 2)^2 \\
\sqrt{y + 9} &= x + 2 \\
x &= \pm\sqrt{y + 9} - 2 \\
\end{align*}
$$
At this stage we swap the two variables and voilà we have the inverse which is, $f^-1(x) = \pm\sqrt{y + 9} - 2$

```desmos-graph
y = x^2 + 4x - 5
y = \sqrt{x + 9} - 2
```
[Note that the graph only shows the positive root option (the graph does not support plus or minus)]

### 1.5.1 Proving two functions are inverses through composite functions.

Now, what if we were given two functions and were told us to prove that these two are the inverses of each other.  We could enter values on one side and input it's output into the other and see if we get the original input. But this is hasty. So we turn to Composite Functions (which simplifies all of this)

$$
\begin{gather*}
\text{if} \\
(f \circ g)(x) = x \text{ and } (g \circ f)(x) = x \\
\text{Then, } f(x) \text{ and } g(x) \text{ are inverses of each other.}
\end{gather*}
$$

for example, we can use the above example to test this right now
$$
\begin{gather*}
\text{Let }f(x) = x^2 + 4x - 5 \text{ and } g(x) = \pm\sqrt{y + 9} - 2 \\
\text{T.B.P: f(x) and g(x) are inverses of each other} \\ \\
\end{gather*}
$$
$$
\begin{align*}
(f \circ g)(x) &= f[g(x)] \\
               &= f[\sqrt{x + 9} - 2]\\
               &= (\sqrt{x + 9} - 2)^2 + 4(\sqrt{x + 9} - 2) - 5\\
               &= x + 13 - 4\sqrt{x+ 9} + 4\sqrt{x + 9} - 13\\
(f \circ g)(x) &= x \\
\\
(g \circ f)(x) &= g[f(x)] \\
               &= g[x^2 + 4x - 5] \\
               &= \sqrt{x^2 + 4x - 5 + 9} - 2] \\
               &= \sqrt{x^2 + 4x + 4} - 2 \\
               &= \sqrt{(x + 2)^2} - 2\\
               &= x + 2 - 2\\
(g \circ f)(x) &= x \\
\\
\therefore f(x) \text{ and } g(x) \text{ are inverses of each other.} \; \square
\end{align*}
$$

## 1.6 Transformations of Functions
-----------------------------------

A transformation is a distortion or change to the parent graph. Where it's usually moved around, stretched and Dilated it. Here we'll talk about a few of them.

for starters here's the parent graph we'll be using, $f(x)\ =\ -1x^{3}+0.8x^{2}+2x\ +\ 0.7$

### 1.6.1 Translations

```desmos-graph
f(x) = -1x^{3}+0.8x^{2}+2x\ +\ 0.7
f(x) + 4
f(x) - 4
f(x + 4)
f(x - 4)
```

| Change     | What it does            | Graph  |
| ---------- | ----------------------- | ------ |
| $f(x) + a$ | Vertical Upward Shift   | Green  |
| $f(x) - a$ | Vertical Downward Shift | Purple |
| $f(x + a)$ | Horizontal Left Shift   | Black  |
| f(x - a)   | Horizontal Right Shift  | Red    |
### 1.6.2 Dialation

```desmos-graph
f(x) =\ -1x^{3}+0.8x^{2}+2x\ +\ 0.7
2 \cdot f(x)
0.5 \cdot f(x)
f(2x)
f(0.5x)
```

| Change           | What it does           | Graph  |
| ---------------- | ---------------------- | ------ |
| $a \cdot f(x)$   | Vertical Stretch       | Green  |
| $\frac{f(x)}{a}$ | Vertical Compression   | Purple |
| $f(x + a)$       | Horizontal Compression | Black  |
| $f(x - a)$       | Horizontal Stretch     | Red    |

### 1.6.3 Reflection

```desmos-graph
f(x)\ =\ -1x^{3}+0.8x^{2}+2x\ +\ 0.7
-f(x)
f(-x)
-f(-x)
```

| Change   | What it did            | Graph  |
| -------- | ---------------------- | ------ |
| $-f(x)$  | Reflection on $x$ axis | Green  |
| $f(-x)$  | Reflection on $y$ axis | Purple |
| $-f(-x)$ | Reflection on $origin$ | Black  |

## 1.7 Absolute Value Functions
------------------------------

Here we will be subtly talking about functions with Absolute Values (_abs_ for short). The Absolute Value function can be defined as a piecewise function like below.
$$
f(x) = |x| = \begin{cases}
x & \text{if } x \geq 0,\\
-x  & \text{if } x \lt 0.
\end{cases}
$$
where, in short it will just return the number, without the sign. So, $|-10| = 10$ and $|10| = 10$
and it's transformations are just the same as any other function.

when solving it we need to solve it in both of it's positive and negative cases Here's an example question, $8 = |2x - 6 |$.
$$
\begin{align*}
8 = |2x - 6| &\text{ or } -8 = |2x - 6| \\
8 = 2x - 6 &\text{ or } -8 = 2x - 6 \\
8 + 6 = 2x &\text{ or } -8 + 6 = 2x \\
\frac{14}{2} = x &\text{ or } \frac{-2}{2} = x \\
7 = x &\text{ or } -1 = x
\end{align*}
$$


**Note**: For real numbers $A$ and $B$, an equation of the form $|A|=B$,  with $B≥0$, will have solutions when $A=B$ or $A=−B$. If $B<0$, the equation $|A|=B$ has **no solution**.^[1.]

With this, the unit note is complete.

***
***
Author: Sasen Perera

Citations: 
1. https://openstax.org/books/precalculus-2e/pages/1-6-absolute-value-functions