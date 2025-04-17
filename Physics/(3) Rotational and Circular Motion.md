In the last unit we covered motion in straight and oblique lines and forces.
Now we move on to Rotational and Circular Motion.

![[(9) - fig 3]]
Here we have a circle with a center $O$ and radius $r$. We can see that $S$ (displacement) is an arc of this circle, which is made by an angle of $\theta$. (Note, We'll be using $radians$ and not degrees).

$$
\therefore S = r\theta
$$
## 3.1 Angular Velocity ($\omega$)
-----
Angular Velocity is the rate of change of angle $\theta$ in unit time and it's represented by simple-case omega "$\omega$".

$$
\omega = \frac{\Delta \theta}{\Delta t}
$$
So as an example, let's say an object makes a complete revolution around its axis under a minute.
$$
\begin{align*}
\text{Complete revolution} &= 2\pi \; \text{rad} \\
\text{Time Taken} &= 1 \; \text{minute} \\
                  &= 60 \; \text{seconds} \\
                  \\
\therefore \omega &= \frac{\cancel{2}\pi \; \text{rad}}{\cancel{60}^{30}s} \\
\omega &= \frac{\pi}{30} \text{rad/s}
\end{align*}
$$
## 3.2 Angular Acceleration ($\alpha$)
----------------------------------
Angular Acceleration is the rate of change _Angular Velocity_ in unit time. It's represent by simple-case alpha "$\alpha$".
$$
\alpha = \frac{\Delta \omega}{\Delta t}
$$
## 3.3 The nature of change in angular velocity vector
-------------------------------------------------------------
1. Changing **Magnitude** without changing direction.
	- $\alpha$ is parallel or anti-parallel to $\omega$.
2. Changing **Direction** without changing magnitude.
     - $\alpha \perp \omega$ 
3. Both Change.
     - $\alpha$ is at some arbitrary angle to $\omega$.

> **Period of Rotation**: $T = \frac{2 \pi}{\omega}$
> **Frequency**: $f = \frac{\omega}{2 \pi}$

Here's a diagram with every type talked so far,
![[(10) - fig 3.3]]
You can see that there's a $v$ in the diagram, This is _tangential velocity_. We can describe it as such.
$$
\begin{align*}
S &= r\theta \\
\Delta S &= r \cdot \Delta\theta \; \text{Divide } \Delta t\; \text{on both sides} \\
\frac{\Delta S}{\Delta t} &= \frac{r \cdot \Delta\theta}{\Delta t} \\
\therefore v &= r\omega
\end{align*}
$$
## 3.4 Some Cases with Acceleration
-----------------------------------------
Here, we'll be talking through some cases with velocities and acceleration in this rotational motion.

### 3.4.1 Case 1

![[(11) - fig 3.4.1]]

Here in this case there are 3 tangential velocities acting on the radius of the circle. Using $v = r\omega$
as a basis, we can say that $V_a > V_b > V_c$ 

and on that, since $v = r\omega$
$$
\begin{align*}
v &= r\omega \\
\Delta v &= r \cdot \Delta\omega \; \text{(Dividing by } \Delta t\text{)} \\
\frac{\Delta v}{\Delta t} &= \frac{r \cdot \Delta\omega}{\Delta t} \\
a_t &= r\alpha
\end{align*}
$$
($a_t$ is acceleration along tangent.)

Since $\omega$ is constant, we know for a fact that $\Delta \omega = 0$
$$
\begin{align*}
a_t &= r \cdot \frac{0}{\Delta t} \\
\therefore a_t &= 0
\end{align*}
$$
### 3.4.2 Case 2

![[(12) - fig 3.4.2]]
In this case we have three types of acceleration;
1. $a_t$ - tangential acceleration
2. $a_r$ - radial acceleration
3. $a_c$ - centripetal acceleration (acceleration towards the center)

We can define $a_c$ as follows,
$$
a_c = \frac{v^2}{r} = r\omega^2 = v\omega
$$
and we can define $a_r$ and $\phi$ the same way we do vectors.
$$
a_r = \sqrt{a_c^2+a_t^2}
$$
$$
\tan \Phi = \frac{a_t}{a_c} 
$$
now since know what $a_c$, we can define **Centripetal force**.
$$
\begin{align*}
F_c &= ma_c \\
F_c &= mv\omega
\end{align*}
$$
> We can use the kinematics formulas we described in [Mechanics]([[(1) Mechanics]]), by replacing $v$, $a$ and $s \; (d)$ with $\omega$, $\alpha$ and $\theta$
> e.g.
> $$
  \theta = ω_0​t+\frac{1}{2}​αt^2 \; \text{(analog of } s = ut + \frac{1}{2}​at^2\text{)}
  $$

## 3.5 Inertia in Rotational Motion.
--------------------------------------
In rotational motion we describe inertia with the radius and mass,
$$
I = mr^2
$$
$$
I = \sum^n_{i=1}m_ir_i^2
$$
## 3.6 Rotational Kinetic Energy
-----------------------------------
We can describe the energy used in a rotation as,
$$
E_{r.k} = \frac{1}{2}I\omega^2
$$
$$
\text{Where } I = \sum m_i r_i^2
$$
## 3.7 Angular Momentum
-----------------------------
Now we usually denote Angular momentum with $L$,

$$
\begin{align*}
L &= \sum L_i \\
  &= \sum (r_i \cdot p_{i,\perp}) \\
  &= \sum (r_i \cdot m_i v_{i,\perp})
\end{align*}
$$
Assuming the velocity is purely tangential (rotation about a fixed axis), $v_{i,\perp} = v_i = r_i \omega$:
$$
\begin{align*}
L &= \sum (r_i \cdot m_i \cdot r_i \omega) \\
  &= \sum (m_i r_i^2 \omega) \\
  &= \left( \sum m_i r_i^2 \right) \omega \\
L &= I \omega
\end{align*}
$$
## 3.8 Torque ($\tau$)
--------------
Torque is the moment of force in rotational movement.
$$
\begin{align*}
\tau &= F \cdot r \\
\tau &= I\alpha \\
\tau \cdot \Delta t &= \Delta L

\end{align*}
$$
And there's this form,
$$
τ = \frac{dL}{dt}​
$$
This is the rotational equivalent of [Newton's Second Law]([[(2) Newtonian Forces]]).

## 3.9 Recap
------------
Here's handy-dandy table with all of the formulas

| Concept                  | Formula                                   |
| ------------------------ | ----------------------------------------- |
| Arc length               | $S=rθ$                                    |
| Angular velocity         | $ω= \frac{\Delta\theta}{\Delta t}$        |
| Tangential velocity      | $v = r\omega$                             |
| Angular acceleration     | $\alpha = \frac{\Delta\omega}{\Delta t}$​ |
| Tangential acceleration  | $a_t = r\alpha$                           |
| Centripetal acceleration | $a_c = r\omega^2 = \frac{v^2}{r}$​        |
| Rotational KE            | $\frac{1}{2}I\omega^2$                    |
| Angular momentum         | $L = I\omega$                             |
| Torque                   | $\tau = I\alpha$                          |
| Moment of inertia        | $I = \sum m_i r_i^2$​                     |
With that this unit is complete.

---
---
Author: Sasen Perera