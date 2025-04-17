In this section we'll be talking about Newton's 3 laws of Motion, Tension, Rotations and Circular motion

> **Force**: Force is the cause of motion, The study of Force is known as _"Kinematics"_
> **Net Force**: Resultant/Total Force of an object.

## 2.1 Newton's 3 Laws of motion.
--------------------------------------
During the 17th century, English Physicist and Mathematician **Isaac Newton** devised 3 laws to describe motion.

### 2.1.1 Law $I$: The Law of inertia

> Until an unbalanced force is acted on an object, An object at rest remains at rest while an object with uniform velocity will continue to move.

Simply, said if an object is moving it will continue to move until someone stops it or apply a force to change it's direction or momentum.

When the object is as at rest or moving at a constant velocity the _Net Force_ is 0.

**Inertia** is a **Scalar** quantity. we can describe it as,
$$
F = ma
$$
which is newton's 2nd law.

### 2.1.2 Law $II$: The Acceleration of an object is directly proportional to it's Net Force while Inversely proportional to it's Mass

Here Newton describe the relationship between the Force, Acceleration and Mass within the system of objects.

The law directly states that $F_{net} \; \alpha \; a$  and $F_{net} \; \alpha \; \frac{1}{m}$. Therefore we can rewrite the law as $F_{net} = ma$.

Usually Momentum is defined as $P = mv$, but we can also rewrite it as $P = \Delta m \Delta v$.
Since $a = \frac{\Delta v}{\Delta t}$. We can rewrite Net Force like this.
$$
\begin{align*}
F_{net} &= ma \\
        &= m \cdot \frac{\Delta v}{\Delta t} \\
\therefore F_{net} &= \frac{\Delta P}{\Delta t} \\
\end{align*}
$$

### 2.1.3 Law $III$: Every action has an equal and opposite reaction.

The last of the 3 laws which govern the motion of object, In short this describes the reaction of an object when a force is applied. As an example When you throw something heavy in a certain object you get push backed in the opposite direction.

so in short,
$$
F_a = -F_b
$$
With that the 3 laws of motion has been described.

$$
\begin{align*}
\sum F_x = F_{net} &= F_a - f \\
                   &= ma_x \\
\sum F_y = \underbrace{F_n}_\text{Normal} - mg &= 0 \; \text{(Under equilbrium)}
\end{align*}
$$

## 2.2 Impulse and Friction
-----------------------------
Now we move on to discuss about Impulse and Friction. Impulse is the **change of momentum** over a period of time and Friction is the **resistance** that one surface or object encounters when moving over another

### 2.2.1 Impulse
We can define Impulse as $Impulse  = Force \cdot \text{Change of time}$ So we can write it as,
$$
\begin{align*}
I = F\cdot\Delta t
\end{align*}
$$
Now if we go back to this equation from earlier, and subject $\Delta P$ 
$$
\begin{align*}
F_{net} &= \frac{\Delta P}{\Delta t} \\
\Delta P &= F_{net} \cdot \Delta t \\
\end{align*}
$$
After subjecting $\Delta P$ we got the Formula for Impulse on the right side over here.
Therefore we can say that,
$$
I = \Delta P
$$
This is known as the **Impulse-Momentum Theorem**.

### 2.2.2 Friction
Friction comes in 3 distinct flavors depending where it's applied,
1. Static Friction - The friction you feel when you apply the force while the object is at **rest**.
2. Limiting Friction - The friction that happen when the object at rest **begins to move**.
3. Dynamic Friction - The friction that happens when the object is **moving**

Usually the highest friction out of these Limiting Friction, and the lowest is Dynamic Friction. (Assuming that the object stays on the same type of surface in it's entire journey)

The main factors of **Friction** are the **nature of surfaces** and the **Normal Reaction Force**. Therefore we usually write Friction is terms of the **Normal force ($N$)** and the **Co-efficient of friction ($\mu$)**.
$$
f = \mu N
$$
As of now, if we draw a free body diagram of everything we covered it'll look like this

![[(6) - fig 2.2.2]]

## 2.3 Tension Force
---------------------
A tension force is a pulling/stretching force transmitted axially along an object such as a rope or a rod (This is the opposite of Compression).

![[(7) - fig 2.3]]
Here we have an object being pulled by a Force $T$ at an angle of $\theta$. This is a prime example of a tension force. Now using Vectors we can define $T_x$ and $T_y$.
$$
\begin{align*}
T_x &= T \cdot \cos \theta \\
T_y &= T \cdot \sin \theta \\
\theta &= \tan^{-1}\biggl(\frac{T_y}{T_x}\biggr) \\
T   &= \sqrt{T_x^2 + T_y^2}
\end{align*}
$$

Therefore we can figure out the $F_x$ ($F_{net}$) and $F_y$ in terms of $T_x$ and $T_y$.
$$
\begin{align*}
\sum F_x &= T_x - f = ma_x \\
\sum F_y &= F_n + T_y - mg = 0 \; \text{(Box is not lifted nor dropped)}
\end{align*}
$$
since $F_n + T_y - mg = 0$ we can subject out $F_n$,
$$
\begin{align*}
F_n + T_y - mg &= 0 \\
F_n &= mg - T_y \\
F_n &= mg - T \cdot \sin \theta
\end{align*}
$$

## 2.4 Contact force exerted between two objects
---------------------------------------------------------
![[(8) - fig 2.4]]

Here we'll be talking about the forces which are acted between two objects. When we're calculating forces in a system with 2 objects we calculate it as if the 2 objects are a singular object. Therefore we take $m$ as $m_a + m_b$, since we're treating this is a single object $a$ will be constant.

The force applied will be $F = (m_a + m_b) \cdot a$

Therefore we can write $F_{ab}$ accordingly,
$$
\begin{align*}
F_{a\rightarrow b} &= \frac{m_b}{m_a + m_b} \cdot F
\end{align*}
$$
Since $(m_a + m_b$) is common in $F$ and the fraction we can rewrite this as,
$$
\begin{align*}
F_{a\rightarrow b} = m_b \cdot a \;
\end{align*}
$$
We can use this same method when figuring out for systems of more than 2 objects, In this case we just calculate contact force of the first two then use that for the next two and so forth.

With that, This unit is complete.

-----------
----

Author: Sasen Perera