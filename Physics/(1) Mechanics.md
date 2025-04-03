## 1.1 Quantities
-----------------

Quantities in physics can be classified into two,
1. Scalar - Quantities which only have a **magnitude** : Distance, Speed, Mass, Time
2. Vector - Quantities which have a **magnitude** and a **direction** : Displacement, Velocity

In physics we the SI units are based on the **[Metric system](https://en.wikipedia.org/wiki/Metric_system)**, A few of them is in the table below.

| Unit                                  | What it measures                |
| ------------------------------------- | ------------------------------- |
| Gram ($g$)                            | Mass                            |
| Newton ($N$)                          | Force                           |
| Meter/Metre ($m$)                     | Distance/Displacement           |
| Pascals ($Pa$)                        | Pressure                        |
| Joule ($J$)                           | Energy                          |
| Watt ($W$)                            | Rate of energy transfer (power) |
| Meters per second ($ms^{-1}$)         | Speed/Velocity                  |
| Meters per second squared ($ms^{-2}$) | Accelaration                    |
| Second ($s$)                          | Time                            |
| Hertz ($Hz$)                          | frequency                       |
> Newtons are derived from $kg \cdot ms^{-2}$
## 1.2 Displacement, Velocity and Acceleration
-----------------------------------------------------
### 1.2.1 Displacement and Distance

When an object moves, we usually measure the distance to see how far it had moved.

> _Distance is the amount of length travelled._

While on the other hand we have _Displacement_ which tells us where the point is and it's relative direction.

>Displacement is the **distance between where the object started and where it ended up**

so, a path may take a car 400m to get from A to B. But displacement tells us it only ends up going 300m West.

We can define displacement as such, ($F$ = Final, $O$ = Original/Initial)
$$
d = x_F - x_O
$$

### 1.2.2 Velocity and Speed

Now, we know speed to be the change of distance or the rate of distance travelled in a unit time.
$$
Speed \; (s) = \frac{Distance \; (d)}{Time \; (t)} = ms^{-1}
$$

On the other hand we have Displacement which is the rate of displacement travelled in a unit time.
$$
Velocity \;(v) = \frac{Displacement \; (d)}{Time \; (t)} = ms^{-1}
$$
$\therefore$ we can use the displacement definition for velocity as well,
$$
\bar{v} = \frac{x_F - x_O}{t}
$$
Note that when we describe _Velocity_ there are two types of it.
1. Average Velocity - $\bar{v}$
2. Instantaneous Velocity - $v$

Average Velocity is calculated from the total displacement and the total time taken, while Instantaneous Velocity calculates the velocity as time gets closer and closer to 0.
$$
v = \lim_{t\rightarrow0} \frac{\Delta x}{\Delta t}
$$
> The $\Delta$ symbol is used to denote change within the variable

### 1.2.3 Acceleration

And finally _Acceleration_ the rate of change of Velocity. The thing determining how fast a _Porche_ can accelerate from 0 to a 100!.

Acceleration is calculated as below,

$$
Acceleration \; (\bar{a}) = \frac{Velocity \; (v)}{Time \; (t)} = \frac{v}{t} = \frac{v_F - v_O}{t} = \frac{\Delta v}{\Delta t} 
$$
## 1.3 Motion in 1 Dimension
--------------------------------

Now, before we tackle 2 Dimensions we must flatten down to a singular line of motion. Here we're allowed to move forwards and backwards. (Or East and West if you prefer that.)

Here, displacement can be taken from the change of the x axis,
$$
d_x = x_F - x_O
$$
since this is a change of the variable $x$ we can also represent displacement as $\Delta x$ as well.

### 1.3.1 Handling Constant Speed/Velocity

In a scenario where the object of interest is moving at a constant velocity or speed we can simple use the formula we have used since Grade 10.

$$
d = vt \longrightarrow (1)
$$
Here we can use $v$ and $\bar{v}$ since they both share the same value as the velocity doesn't change.
now, what we can do here is we can replace $d$ with the change of $x$. And find a formula to find the final velocity.

$$
\begin{align*}
x_F - x_O &= v_xt \\
x_F       &= v_xt + x_O \longrightarrow (2)
\end{align*}
$$

Example Problems;
1. A bus travels at a speed of $40ms^{-1}$ for $200km$, what is the time taken to travel the distance?
	  - We can use the $d = vt$
		  $$
		  \begin{align*}
		  v_O &= 40ms^{-1}\\
		  d &= 200km\\
		  \text{(Since the units don't}& \text{ match convert this to meters)}\\
		  d &= 200\cancel{km} \cdot \frac{1000m}{1\cancel{km}} \\
		  d &= 200000m
		  \\ \\
		  d &= v\cdot t \\
		  t &= \frac{d}{v} \\
		    &= \frac{200000\cancel{m}}{40\cancel{m}s^{-1}} \\
		  t &= 500s
		  \end{align*}
		 $$
### 1.3.2 Handling Constant Acceleration

Alright, now we've let the this object speed up. Now $v$ and $\bar{v}$ have different values and purposes.
so, now the (1) equation changes to,

$$
d = \bar{v}_xt \longrightarrow (3)
$$
Now, since $\bar{v}$ is average velocity we can take it as the average of the final and initial velocity.
$$
\bar{v}_x = \frac{v_F + v_O}{2} \longrightarrow (4)
$$
Now we can use this definition of $\bar{v}$ in (3),
$$
d = \frac{1}{2}(v_f + v_O) \cdot t \longrightarrow (5)
$$

We can derive more formulas from one of the equations which define acceleration which is,
$$
\bar{a} = \frac{v_F - v_O}{t}
$$
Now we can define the final velocity in terms of the others as,
$$
v_F = v_O + at \longrightarrow (6)
$$
there's another equation we can get which is,
$$
v_F^2 = v_O^2 + 2ad \longrightarrow (7)
$$

If you're wondering if there's more of these the answer is yes there is one left in this plane for existence. To derive it we need to use some of the previous equations.

we start with the definition of the displacement, then work our way up.

$$
\begin{gather*}
d = \bar{v}t \longrightarrow(3) \\
\text{"Replace } \bar{v} \text{ with (4)"} \\
d = \frac{v_F + v_O}{2} \cdot t \\
\text{"Use equation (6) to sub } v_f \text{"} \\
d = \frac{((v_O + at) + v_O) \cdot t}{2} \\
d = \frac{(2v_O + at) \cdot t}{2} \\
d = \frac{2v_Ot + at^2}{2} \\
d = v_Ot + \frac{1}{2} at^2 \longrightarrow (8)
\end{gather*}
$$
with, this equation we can find the final displacement with just the time, initial velocity and time.

### 1.3.3 Free Falling Objects

Before we unflatten ourselves a dimension we must first talk about free falling. Yes, just falling in accordance to gravity. (~~Sure wish you could jump of that building ey?~~) Now, a free falling object also moves in accordance to the above equations.

> However, there's a new force acting on the object which will be **Air Resistance** which is a type of **drag force**. But before we apply this we first must know how a free fall will occur _without air resistance_.

Here's a cube falling for 3 seconds then hits the ground.

![[(1) - fig 1.3.3]]
now, from this diagram we know that;
$$
\begin{align*}
v_{O} &= 0ms^{-1} \\
v_{F} &= -29.4ms^{-1} \\
t &= 3s \\
g &= -9.8ms^{-2}
\end{align*}
$$
now if we don't know any of them we can use the above equations to find it. (taking g as a)

let's say if want to find the final velocity we can use (6)
$$
\begin{align*}
v_F &= v_O + at \\
    &= 0ms^{-1} + (-9.8ms^{-2}) \cdot 3s \\
    &= -9.8ms^{\cancel{-2}-1} \cdot 3\cancel{s} \\
v_F &= -29.4ms^{-1}
\end{align*}
$$

But there is one thing we didn't find out from just the figure alone, we don't know what the displacement of the object is. For that we can use (5) for this.
$$
\begin{align*}
d &= \frac{1}{2}(v_F + v_O) \cdot t \\
  &= \frac{1}{2}(-29.4ms^{-1} + 0ms^{-1}) \cdot 3s \\
  &= \frac{-29.4m\cancel{s^{-1}} \cdot3 \cancel{s}}{2} \\
  &= \frac{-88.2}{2}m \\
d &= -44.1m
\end{align*}
$$
with that, we're done with 1 Dimensional Motion. Now let's move out of there and into the next dimension.

## 1.4 Motion in 2-Dimensions
----------------------------------
Now, that we covered everything for 1 Dimension, now we can move to 2 dimensional motion.
Every motion in 2 Dimensions can be represented as vectors which is why most the math used for Vectors can also be used here.

On another note the displacement formula used for 1 Dimension can changed and used for both the $x$ (horizontal) and $y$ (vertical) axis

$$
\begin{gather}
d_x = x_F - x_O \\
d_y = y_F - y_O
\end{gather}
$$
Now, there are 3 main types of movements a projectile/object could move.
1. The object is dropped horizontally of a cliff
2. The object is thrown at an angle upward of the horizontal surface and lands back on the surface
3. The object is thrown at an angle upward of the cliff and lands on the ground below.

### 1.4.1 Type 1

![[(2) - fig 1.4.1]]

Now, the only thing we're aware in this situation is that the initial velocity is 0 and the acceleration is gravity.

We can derive an equation for this using (8).

$$
\begin{align*}
d &= v_Ot + \frac{1}{2}at^2 \\
d_y &= v_{Oy} t + \frac{1}{2}(-g)t^2 \; \text{(We can replace initial velocity with 0)} \\
h &= -\frac{gt^2}{2} \longrightarrow (9) \\
t &= \sqrt{\frac{2h}{g}} \longrightarrow (10)
\end{align*}
$$
from this we derived a method to take the height and we can also rewrite it for time as well.
Now, we can use the $d = vt$ to find the Range.

$$
\begin{align*}
d &= vt \\
d_x &= v_x \cdot t \; (\text{sub t with (10)}) \\
R &= v_x \cdot t\\
R &= v_x \cdot \sqrt{\frac{2h}{g}} \longrightarrow (11)
\end{align*}
$$

### 1.4.2 Type 2

![[(3) - fig 1.4.2]]

Here's the second type of _Projectile Motion_, In here the object is launched with an angle $\theta$ above the horizontal. At a certain Velocity, though we can't distinguish what $v_x$ and $v_y$ is directly but using vector addition. [needs to be cited when it's done in the maths portion] It can be found out like this, 
![[(4) - fig 1.4.2]]

$$
\begin{gather*}
V = \sqrt{v_x^2 + v_y^2} \longrightarrow (21) \\
\theta = \tan^{-1}{(\frac{v_y}{v_x})} \longrightarrow (22)
\end{gather*}
$$
Here, we used Pythagoras's Theorem to express $V$ and used trigonometry to describe the angle $\theta$ created by the two vectors. 

with this we can express $v_x$ and $v_y$ using the trigonometry.
$$
\begin{align*}
v_y &= V \cdot \sin{(\theta)} \\
v_x &= V \cdot \cos{(\theta)}
\end{align*}
$$
now that we have described the $v_x$ and $v_y$, we can now derive equations which describe relations in this setup. Firstly let's find the _time_ taken for the object to reach point _B_.

now, if we set our final velocity at that point it will be 0, since it's at max y point.

$$
\begin{align*}
v_{yF} &= v_{yO} + a_yt \\
0      &= v_{yO} + a_yt \\
       &= V \cdot \sin{(\theta)} + (-g)t \\
    gt &= V \cdot \sin{(\theta)} \\
t_{a \rightarrow b} & = \frac{V\cdot \sin{(\theta)}}{g}
\end{align*}
$$
Since, the graph is symmetrical we can say that $t_{a \rightarrow b} = t_{b \rightarrow c}$
$$
\begin{align*}
t &= 2 \cdot t_{a \rightarrow b} \\
t &= \frac{2 \cdot v \cdot \sin{(\theta)}}{g} \longrightarrow (12)
\end{align*}
$$
Now since we know the time taken we can find out the Max height and the Range. We can use  equation (7) and the definition for displacement.
$$
\begin{align*}
v_{yF}^2 &= v_{yO}^2 + 2a_yd_y \\
       0 &= (V \cdot \sin{(\theta)})^2 + 2(-g)H \\
-V^2\cdot\sin^2(\theta) &= -2gH \\
\frac{V^2 \cdot \sin^2(\theta)}{2g} &= H \longrightarrow (13)
\end{align*}
$$
We can use the displacement definition to find the Range (or displacement of x).
$$
\begin{align*}
d &= vt \\
R &= v_xt \\
  &= (V \cdot \cos{(\theta)}) \cdot t \; \text{(sub t with (12))} \\
  &= V \cdot \cos{(\theta)} \cdot \frac{2 \cdot V \cdot \sin{(\theta)}}{g} \\
  &= \frac{V^2 \cdot 2 \cdot \cos{(\theta)} \cdot \sin{(\theta)}}{g} \; \text{(Use Double Angle Identity)} \\
R &= \frac{V^2 \cdot \sin{(2\theta)}}{g} \longrightarrow (14)
\end{align*}
$$

> The "Double-Angle Identity" is an identity used in Trigonometry. See [[(2) Trigonometry]] _Eq. 4_
### 1.4.3 Type 3
![[(5) - fig 1.4.3]]

Here, not only are we pushing this object off a cliff, we're also shooting it upwards at an angle $\theta$ upward as well. Now to derive equations relative to this, we need to use the equations we used from both of the previous two types.

Now if were to just use the equation of $H$ and $R$ from the previous equations, we'll just get values relative to the ABD.

first, we have to calculate the amount of time taken for the object.

$$
\begin{align*}
\underbrace{d} &= v_O t + \frac{1}{2}at^2 \\
y_F - y_O &= v_{yO}t + \frac{1}{2}a_y t^2 \\
      y_F &= v_{yO}t + \frac{1}{2}a_yt^2 + y_O \; \text{(Sub } y_F \text{ with 0 since, it's at the max point)} \\
      0 &= \frac{1}{2} a_yt^2 + v_{yO}t + y_O \; \text{(Substitute values one more time.)} \\
      0 &= \frac{1}{2}gt^2 + V \cdot \sin{(\theta)} \cdot t + h \; \text{(This is now in quadratic form)} \\
\therefore t_{a \rightarrow c} &= \frac{-b\pm\sqrt{b^2-4ac}}{2a} \longrightarrow (15) \\
                               &= \frac{-V\sin^2{(\theta)} \pm \sqrt{V^2\sin^2{(\theta)} -(\cancel{4}^2\cdot-\frac{g}{\cancel{2}}h)}}{\cancel{2} \cdot\frac{-g}{\cancel{2}}} \\
                               &= \frac{-V\sin^2{(\theta)}\pm\sqrt{V\sin^2{(\theta)}^2+2gh}}{ -g}\\
\therefore t_{a \rightarrow c} &= \frac{V\sin^2{(\theta)}\pm\sqrt{V\sin^2{(\theta)}^2+2gh}}{g} \longrightarrow (16)\\
\end{align*}
$$

>Note: When using always take a **Positive** value for time, since time cannot be negative.

There's another way of deriving the time taken by using the two separate equations for AB Portion and BC Portion using the above two types.

$$
\begin{align*}
t_{a \rightarrow b} &= \frac{V \cdot \sin{(\theta)}}{g} \\
h &= \frac{1}{2} at^2 \; \text{(Substitute h)} \\
h + h &= \frac{1}{2} gt^2 \\
\frac{2 \cdot y_{max}}{g} &= t^2 \\
t_{b \rightarrow c} &= \sqrt{\frac{2 \cdot y_{max}}{g}} \; \text{(This is a derivation of (10))} \\
t_{a \rightarrow c} &= t_{a \rightarrow b} + t_{b \rightarrow c} \\
\therefore t_{a \rightarrow c} &= \frac{V \cdot \sin{(\theta)}}{g} + \sqrt{\frac{2 \cdot y_{max}}{g}} \longrightarrow (17)
\end{align*}
$$

with, this method you don't have to solve using quadratics.

Now, we can head on over to Range. not that we know the total time ($t_{a \rightarrow c}$) we can use that to find the Range.
$$
\begin{align*}
R &= v_x \cdot t \; \text{(velocity of x is constant)} \\
R &= V \cdot \cos{(\theta)} \cdot t \longrightarrow (18) \\
\end{align*}
$$
And here's the way to figure out the final velocities derived from using (6)
$$
\begin{align*}
v_F &= v_O +at \longrightarrow(6) \\ \\
v_{Fy} &= v_{Oy} + at \\
v_{Fy} &= V \cdot \sin{(\theta)} + gt_{a \rightarrow c} \longrightarrow (19) \\ \\
v_{Fx} &= v_{Ox} + at \\
v_{Fx} &= V \cdot \cos{(\theta)} + gt_{a \rightarrow c} \longrightarrow (20)
\end{align*}
$$
With that, this unit is complete!

----
---
Author: Sasen Perera



