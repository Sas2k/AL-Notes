## 5.1 Limits
------------
### 5.1.1 A slight introduction into limits
A **limit** is a value which a **function** or **series** approaches as the argument (index) approaches some value.

In notation a limit is written down as follows,
$$
\lim_{x \rightarrow a}{f(x)} = L
$$
This is read as "the limit of $f$ of $x$ as $x$ approaches $a$ is equal to $L$". Note that we use [[(3 - A) Arrow Notation|Arrow Notation]] to describe the approach of $x$.

```desmos-graph
f(x) = \frac{x^2 - 4}{x - 2}
(2, 4)
```

This is a function where $f(x) = \frac{x^2 - 4}{x - 2}$. Now the reason I've colored the point $(2, 4)$ is because the function at $x = 2$ is undefined. Since if we substitute, $x = 2$ into this function we get,

$$
\begin{align*}
f(2) &= \frac{2^2 - 4}{2 - 2} \\
     &= \frac{0}{0} \\
f(2) &= \text{undefined}
\end{align*}
$$

>Points of graphs with this type of behavior are called "holes" and is usually represented by a circle. (without a color fill) _Due to limitations of Obsidian-Desmos I cannot show how it looks so, I'll stick with the green circle._

So, how does the function behave around the point $x = 2$. This is why we use limits, Now if we apply a limit to this function when $x \rightarrow 2$. We may find what the $f(x)$ approaches.

$$
\lim_{x \rightarrow 2}f(x) = 4
$$
as clearly on the graph, we can say the limit of $f$ of $x$ as $x$ approaches $2$ is equal to $4$.
Before we move on further into limits, there are 2 basic types of limits you should know about.

$$
\begin{align*}
\text{let } a \in \mathbb{R} &\text{ and } c \text{ be a constant.} \\
\lim_{x\rightarrow a} x &= a \\
\lim_{x\rightarrow a} c &= c
\end{align*}
$$
There are 2 observations we can get from this,
1. For limit No. 1, We observe that as $x \rightarrow a$,  so does $f(x)$. $\because f(x) = x$. $\therefore \lim_{x\rightarrow a} x = a$.
2. For limit No. 2, We observe that as $x \rightarrow a$, the $f(x)$ stays constant at $c$ regardless of the value at $x$. So we have to conclude that $\lim_{x\rightarrow a} c = c$.

>Another key point: The limit of a function to exist at a point, the functional value must approach a **single real-number** value at that point.[^1] If this does not occur, then the **limit does not exist**. 


### 5.1.2 One Sided Limits
Here we'll talk about one-sided limits. In this case depending on which side $x$ approaches from the limit $L$ changes.
```desmos-graph
g(x) = \frac{\abs(x - 2)}{x - 2}
```
As an example, let's let the function $g(x) = \frac{|x - 2|}{(x - 2)}$. Now if we let $x$ just approach $2$, we won't get a singular real-value. $\therefore \lim_{x \rightarrow 2}{g(x)} = \text{D.N.E.}$[^2]. Since this answer doesn't let us grasp the entire behavior of the function around that point we use one sided Limits.

$$
\begin{align*}
\lim_{x\rightarrow 2^-}{g(x)} &= -1 \rightarrow (1) \\
\lim_{x\rightarrow 2^+}{g(x)} &= 1 \rightarrow (2)
\end{align*}
$$

$(1)$ The function when approached from the left of the point, approaches the value $-1$ as seen in the graph.
$(2)$ The function when approached from the right of the point approached the value $1$ as seen in the graph.

$$
\begin{array}{c | r}
\hline \\
&\lim_{x\rightarrow a}{f(x)} = L\text{ If and only if } \lim_{x\rightarrow a^+}{f(x)} = L \text{ and } \lim_{x\rightarrow a^-}{f(x)} = L& \\ \\
\hline
\end{array}
$$

### 5.1.3 Infinite Limits
If a function gets larger and larger or smaller and smaller without approaching a singular value. We mathematically express it as approaching positive/negative infinity. There are 3 main categories with 2 types each.

1. Infinite Limits from the **left**. ($x < a$)
	1. $\lim_{x\rightarrow a^-}{f(x)} = -\infty$
	2. $\lim_{x\rightarrow a^-}{f(x)} = \infty$
2. Infinite Limits from the **right**. ($x > a$)
	1. $lim_{x\rightarrow a^+}{f(x)} = -\infty$
	2. $lim_{x\rightarrow a^+}{f(x)} = \infty$
3. **Two Sided** Infinite Limits. ($x \ne a$)
	1. $lim_{x\rightarrow a}{f(x)} = -\infty$
	2. $lim_{x\rightarrow a}{f(x)} = \infty$

Now, there are some forms of functions where the limit is infinite. H.ere are some of them.
1. If $n$ is an even power,
	$$
    \lim_{x\rightarrow a}{\frac{1}{(x - a)^n}} = \infty
    $$
2. if $n$ is an odd power,
  $$
 \lim_{x \rightarrow a^+}{\frac{1}{(x- a)^n}} = \infty \text{ and } \lim_{x \rightarrow a^-}{\frac{1}{(x- a)^n}} = -\infty
 $$
3. if $x = a$ is a Vertical Asymptote
	$$
	\begin{align*}
    \lim_{x \rightarrow a}{f(x)} &= \infty \text{ or } -\infty \\
    \lim_{x \rightarrow a^-}{f(x)} &= \infty \text{ or } -\infty \\
    \lim_{x \rightarrow a^+}{f(x)} &= \infty \text{ or } -\infty
    \end{align*}
	$$
[^1]: https://openstax.org/books/calculus-volume-1/pages/2-2-the-limit-of-a-function#:~:text=limit%20of%20a%20function%20to%20exist%20at%20a%20point%2C%20the%20functional%20values%20must%20approach%20a%20single%20real%2Dnumber%20value%20at%20that%20point.

[^2]: $\text{D.N.E.} = \text{Does not exist}$
