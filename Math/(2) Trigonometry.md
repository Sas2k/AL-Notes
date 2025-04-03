> **Trigonometry** (from [Ancient Greek](https://en.wikipedia.org/wiki/Ancient_Greek_language "Ancient Greek language") [τρίγωνον](https://en.wiktionary.org/wiki/%CF%84%CF%81%CE%AF%CE%B3%CF%89%CE%BD%CE%BF%CE%BD#Ancient_Greek "wikt:τρίγωνον") _(_trígōnon_)_ 'triangle' and [μέτρον](https://en.wiktionary.org/wiki/%CE%BC%CE%AD%CF%84%CF%81%CE%BF%CE%BD#Ancient_Greek "wikt:μέτρον") _(_métron_)_ 'measure')[1](https://en.wikipedia.org/wiki/Trigonometry#cite_note-1) is a branch of [mathematics](https://en.wikipedia.org/wiki/Mathematics "Mathematics") concerned with relationships between [angles](https://en.wikipedia.org/wiki/Angle "Angle") and side lengths of triangles. ^[1.]

Now, we'll talk about triangles. Primarily Right Angled Triangles. Trigonometry allows us to identify the missing angles or sides of a triangle and calculate them.

## 2.1 Sine, Cosine and Tangent
------------------------------------------------------------------
Now there are 3 trigonometric functions. Which are **Sine, Cosine and Tangent**, They are described as _ratios between the sides of the triangle_. The functions are abbreviated as _sin, cos and tan_. 

When describing the 3 sides of the right-angled triangle,
1. the side with the longest length is called the "Hypotenuse". 
2. The side directly opposite to the angle we're using is the "Opposite Side"
3. the side which is adjacent to the angle we're using is called the "Adjacent Side". 
(Yes, quite literally so.)

Now, the 3 main functions are described as below.
$$
\begin{align*}
Sine &= \frac{Opposite}{Hypotenuse} \\
Cosine &= \frac{Adjacent}{Hypotenuse} \\
Tangent &= \frac{Opposite}{Adjacent}
\end{align*}
$$
The thing with fractions that their reciprocals also exist. So does this exist here as well yes they do exist like this,
$$
\begin{align*}
Secant &= \frac{1}{Cosine} \\
Cosecant &= \frac{1}{Sine} \\
Cotangent &= \frac{1}{Tangent} \\
\end{align*}
$$
**Secant, Cosecant and Cotangent** are the reciprocals of the trigonometric rations, They are abbreviated as _Sec, Csc and Cot_.

### 2.1.1 More on Trigonometric Ratios

![[(2) - fig 2.1]]
Here, we have a Right Angled Triangle called $ABC$, with the $\angle BAC = \theta$. If we were to apply our trig ratios to the angle $\theta$ we get this,

$$
\begin{align*}
\sin \theta &= \frac{BC}{AC} & \csc \theta &= \frac{AC}{BC} \\
\cos \theta &= \frac{AB}{AC} & \sec \theta &= \frac{AC}{AB} \\
\tan \theta &= \frac{BC}{AB} & \cot \theta &= \frac{AB}{BC}\\
\end{align*}
$$
Now, if were to look at $\tan \theta$, we can observe that, $\tan \theta = \frac{\sin \theta}{\cos \theta}$ and since $\cot \theta$ is just the reciprocal of this it's equal to $\cot \theta = \frac{\cos \theta}{\sin \theta}$.

now, the $\angle ACB$ can be described as $90 - \theta$ since all angles in a triangle add up to $180^\circ$
if were to take the $\sin$, $\cos$ & $\tan$ values of that angle we get,
$$
\begin{align*}
\sin{(90 - \theta)} &= \frac{AB}{AC} \\
\cos{(90 - \theta)} &= \frac{BC}{AC} \\
\tan{(90 - \theta)} &= \frac{AB}{BC}
\end{align*}
$$
We can see that, coincidently that these match up with $\cos \theta$, $\sin \theta$ and $\cot \theta$ respectfully. therefore we can say that,
$$
\begin{align*}
\sin \theta &= \cos{(90 - \theta)} \\
\cos \theta &= \sin{(90 - \theta)} \\
\cot \theta &= \tan{(90 - \theta)} \\
\tan \theta &= \cot{(90 - \theta)}
\end{align*}
$$
### 2.1.2 Measuring angles more than $90^\circ$

Usually getting the Trigonometry Value for an angle between $0^\circ$ and $90^{\circ}$ is quite straightforward as the value can be directly taken. But for values greater than $90^{\circ}$ the method of acquiring is different.
In order to get a Trig Value for more than $90^{\circ}$, we first need to find a _Reference Angle_.

Firstly let's draw up a unit-circle on a graph. What's a unit circle you ask? a unit circle is a circle with radius one centered on the origin of the graph

```desmos-graph
left=-3; right=3; top=2; bottom=-2;
degreeMode=degrees;
---
x^2 + y^2 = 1 | Black
(1, 0)|label:0 deg or 360 deg
(0, 1)|label:90 deg
(-1, 0)|label:180 deg
(0, -1)|label:270 deg
a = 240
y=\left(\tan a\right)\cdot x\left\{0<x<\cos a\right\}|Blue
y=\left(\tan a\right)\cdot x\left\{\cos a<x<0\right\}|Blue
x=\cos(a)\left\{0<y<\sin(a)\right\}|Blue
x=\cos(a)\left\{\sin(a)<y<0\right\}|Blue
```
Using this, we can find a reference angle.

Now, let's try to find the value of $\sin{(240^\circ)}$.
Since $240^\circ > 180^\circ$ we can determine that the angle must fall in the 3rd quadrant.

Drawing a line to the circle at an angle of $240^{\circ}$ anticlockwise from origin, you get the Terminal Ray (the red line) in Quadrant 3, what we can do now, is draw a perpendicular from the intersection point of the Terminal Ray and circle to the _x axis_

now the Reference angle will be the angle in-between the x axis and the terminal ray. Which would be the difference of the angle in the function with $180^{\circ}$
$$
\begin{align*}
240^\circ - 180^\circ &= R \\
\therefore R &= 60^\circ
\end{align*}
$$
which would be the same if you had measured the angle in the diagram as well
the other thing we can also say that in a unit circle is that the _opposite and adjacent side_ directly equal to $\sin$ and $\cos$, therefore since both the $x$ and $y$ are negative in $Q3$ we can say that,
$$
\begin{align*}
\sin{(240^\circ)} &= -\sin{(60^\circ)} \; \therefore \sin{(240^\circ)} = -\frac{\sqrt{3}}{2} \\
\cos{(240^\circ)} &= -\cos{(60^\circ)} \; \therefore \cos{(240^\circ)} = -\frac{1}{2}
\end{align*}
$$
for the other Quadrants we can use these to calculate the Reference Angle,

$$
\begin{align*}
Q_1 \longrightarrow R &= \theta \; (0 \le\theta < 90) \\
Q_2 \longrightarrow R &= 180 -\theta \; (90 < \theta < 180) \\
Q_3 \longrightarrow R &= \theta - 180 \; (180 < \theta < 270) \\
Q_4 \longrightarrow R &= 360 - \theta \; (270 < \theta < 360)
\end{align*}
$$
If the angle exceeds $360^\circ$, We firstly need to substract $360^{\circ}$ then we apply the above formulas. With this we can now get the values of any angle.

## 2.2 Trigonometric Identities
---------------------------------
Now with trigonometric functions there are multiple identities and formulas used to simplify equations.

### 2.2.1 Pythagorean Identity

**Pythagoras's Theorem** states that the squares of the **adjacent side length and opposite side length** is equal to the **square of the hypotenuse side length**.

If we go back to our Unit circle we can describe a relation,

```desmos-graph
left=-3; right=3; top=2; bottom=-2;
degreeMode=degrees;
---
x^2 + y^2 = 1 | Black
(0, 0) | label:A | Black
(\cos a, \sin a) | label:C | Black
(\cos a, 0) | label:B | Black
a = 45
y=\left(\tan a\right)\cdot x\left\{0<x<\cos a\right\}|Green
y=\left(\tan a\right)\cdot x\left\{\cos a<x<0\right\}|Green
x=\cos(a)\left\{0<y<\sin(a)\right\}|Blue
x=\cos(a)\left\{\sin(a)<y<0\right\}|Blue
y = \left\{0\ \le\ x\ \le\ \cos\left(a\right):\ 0\right\} | Red
```

Now we know that the radius (green) is 1, since that's what defines a unit circle. Since the triangle is constructed to be a right-angled triangle we can apply Pythagoras's Theorem here. Firstly we need to describe the sides. We let $\angle CAB = \theta$ 
$$
\begin{align*}
\sin \theta &= \frac{BC}{AC} \\
            &= \frac{BC}{1} \\
\sin \theta &= BC \\ \\
\cos \theta &= \frac{AB}{AC} \\
            &= \frac{AB}{1} \\
\cos \theta &= AB
\end{align*}
$$
Now, if we apply these values to the theorem we get this,
$$
\sin^2\theta+\cos^2\theta = 1 \longrightarrow (1)
$$
Which is the first Pythagorean Identities the next two  can be obtained by dividing $\sin^2$ and $\cos^2$ from both sides of the equation.
$$
\begin{gather*}
1 + \cot^2\theta = \csc^2 \theta \longrightarrow (2) \\ 
\tan^2 + 1 = \sec^2 \theta \longrightarrow(3)
\end{gather*}
$$
### 2.2.2 Odd and Even Trigonometric functions

We have covered what Odd and Even functions are in [[(1) Functions and Graphs]], Here are the Trig functions that fall into these 2 categories

| Even   | Odd    |
| ------ | ------ |
| $\sin$ | $\cos$ |
| $\tan$ | $\sec$ |
| $\csc$ |        |
| $\cot$ |        |
### 2.2.3 Double Angle Identities

Here are the identities used when the input angle is doubled when inputted.

>Note: I won't go into how to derive these equations from here

$$
\begin{align*}
\sin 2\theta &=  2 \cdot \sin\theta \cdot \cos\theta \longrightarrow (4) \\
\cos 2\theta &= \cos^2 \theta-\sin^2\theta \longrightarrow (5) \\
             &= 1 - \sin^2\theta \longrightarrow (6) \\
             &= 2\cdot\cos^2\theta - 1 \longrightarrow (7) \\
\tan 2\theta &= \frac{2\tan\theta}{1 - \tan^2\theta} \longrightarrow (8)
\end{align*}
$$
### 2.2.4 Half Angle Identities

The identities used when the angles are half of what they were.

$$
\begin{align*}
\sin{\Biggl(\frac{\theta}{2}\Biggr)} &= \pm\sqrt{\frac{1-\cos\theta}{2}} \longrightarrow (9)\\
\cos{\Biggl(\frac{\theta}{2}\Biggr)} &= \pm\sqrt{\frac{1+\cos\theta}{2}} \longrightarrow (10) \\
\tan{\Biggl(\frac{\theta}{2}\Biggr)} &= \pm\sqrt{\frac{1-\cos\theta}{1+\cos\theta}} \longrightarrow (11) \\
                                     &= \frac{1-\cos\theta}{\sin\theta} \longrightarrow (12) \\
                                     &= \frac{\sin\theta}{1+\cos\theta} \longrightarrow (13)
\end{align*}
$$
### 2.2.5 Sum & Difference Formulas

These are the identities used to describe a form where inside the function two values are either added or substracted.

$$
\begin{align*}
\sin{(\alpha \pm \beta)} &= \sin\alpha \cdot \cos\beta \pm \cos\alpha \cdot \sin\beta \longrightarrow (14) \\
\cos{(\alpha \pm \beta)} &= \cos\alpha \cdot\cos\beta \mp \sin\alpha \cdot \sin \beta \longrightarrow (15) \\
\tan{(\alpha \pm \beta)} &= \frac{\tan\alpha \pm \tan\beta}{1 \mp \tan\alpha \cdot \tan\beta} \longrightarrow (16)
\end{align*}
$$

### 2.2.6 Power reducing formulas

These are the formulas used to sub in trig values with small powers.

$$
\begin{align*}
\sin^2 \theta &= \frac{1 - \cos 2\theta}{2} \longrightarrow (17) \\
\cos^2 \theta &= \frac{1 + \cos 2\theta}{2} \longrightarrow (18) \\
\tan^2 \theta &= \frac{1 - \cos 2\theta}{1 + \cos 2\theta} \longrightarrow (19)
\end{align*}
$$

### 2.2.7 Products to Sum formulas

As the heading suggests these turn products into a series of sums

$$
\begin{align*}
\sin\alpha \cdot \sin\beta &= \frac{1}{2} [\cos(\alpha-\beta) - \cos(\alpha - \beta)] \longrightarrow (20) \\
\cos\alpha \cdot \cos\beta &= \frac{1}{2} [\cos(\alpha-\beta) + \cos(\alpha - \beta)] \longrightarrow (21) \\
\sin\alpha \cdot \cos\beta &= \frac{1}{2} [\sin(\alpha-\beta) + \sin(\alpha-\beta)] \longrightarrow (22) \\
\cos\alpha \cdot \sin\beta &= \frac{1}{2} [\sin(\alpha-\beta) - \sin(\alpha-\beta)] \longrightarrow (22)
\end{align*}
$$
### 2.2.8 Sum to Product formulas

Here's the other way around
$$
\begin{align*}
\sin\alpha + \sin\beta &= 2 \cdot \sin\biggl(\frac{\alpha+\beta}{2}\biggr) \cdot \cos\biggl(\frac{\alpha-\beta}{2}\biggr) \longrightarrow (23) \\
\sin\alpha - \sin \beta &= 2 \cdot \sin\biggl(\frac{\alpha-\beta}{2}\biggr) \cdot \cos\biggl(\frac{\alpha+\beta}{2}\biggr) \longrightarrow (24) \\
\cos\alpha + \cos\beta &= 2 \cdot \cos\biggl(\frac{\alpha+\beta}{2}\biggr) \cdot \cos\biggl(\frac{\alpha-\beta}{2}\biggr) \longrightarrow (25) \\
\cos\alpha - \cos\beta &= -2 \cdot \sin\biggl(\frac{\alpha+\beta}{2}\biggr) \cdot \cos\biggl(\frac{\alpha-\beta}{2}\biggr) \longrightarrow (26)
\end{align*}
$$
That's all of the Identities (we need that is.)

## 2.3 Law of Sines
-------------------
Let's say you don't know a side or an angle of a triangle, so you plan to use trigonometry but the triangle is not a right-angled triangle. So can you still use Trigonometry?
The answer is yes, you can! Using the Law of Sines.

![[(2) - fig 2.3]]
Here we have a triangle with 3 sides names $a$, $b$ and $c$, the angle directly opposite to them are named according to the side (i.e. the angle opposite to side $b$ is $\angle B$).

Now, the "Law of Sines" states that this equality should hold.
$$
\frac{\sin A}{a} = \frac{\sin B}{b} = \frac{\sin C}{c}
$$
now, by substitution you can find the missing values.

## 2.4 Law of Cosines
-----------------------
Here's another law but instead of $\sin$ it uses $\cos$,
$$
c^2 = a^2 + b^2 - 2ab \cdot \cos C
$$
> There's another law called "Law of Tangents". But it's rarely used but anyways,
> $$\frac{a - b}{a + b} = \frac{\tan[\frac{1}{2}(A - B)]}{\tan[\frac{1}{2}(A + B)]}$$

## 2.5 Heron's Formula
------------------------
This isn't entirely about trigonometry but it is related to triangles. There's a way to get the area of a triangle by knowing it's **perimeter** and the **lengths of the 3 sides** using this formula

$$
\begin{align*}
&\text{let } a, b,c = \text{side lengths of the triangle} \\
&\text{let } s =  \text{half of the perimeter of the triangle}
\end{align*}
$$
$$
Area = \sqrt{s (s - a)(s - b)(s - c)}
$$
With that this topic is complete

---
---
Author: Sasen Perera

Citations:
1. https://en.wikipedia.org/wiki/Trigonometry