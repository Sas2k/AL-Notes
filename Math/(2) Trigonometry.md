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
