Applications of Integrals
=========================

Now that we have learned some techniques for integration, lets look at 2
more applications of integrals.

Arc Length
----------

The arc length of a curve is the distance along the curve. The arc
length is derived from the following formulas,

$$\begin{aligned}
L= \int ds \\
ds = \sqrt{1+(\frac{dy}{dx})^2}dx \quad \quad y =f(x) \\
ds = \sqrt{1+(\frac{dx}{dy})^2}dy \quad \quad x = h(y)\end{aligned}$$

Following these formulas, we can calculate the arc length of a curve.

Determine the arc length of the following functions on their given
intervals.

1.  $y =x^2 \quad \quad x = 0 \quad \text{to} \quad x = 3$

2.  $y = \frac{x^3}{6}+\frac{1}{2x} \quad \quad \frac{1}{2} \leq x \leq 1$

In these examples, this book is really just focused on the setup; You
have to do the integration for yourself to derive the final answer.

1.  $y =x^2 \quad \quad x = 0 \quad \text{to} \quad x = 3$\
    $$\begin{aligned}
    f^{\prime}(x)=2x \\
    \int^{3}_{0} \sqrt{1+(2x)^2}dx \\
    =\frac{1}{4}ln|\sqrt{37}+6|+\frac{3}{2}\sqrt{37}\end{aligned}$$

2.  $y = \frac{x^3}{6}+\frac{1}{2x} \quad \quad \frac{1}{2} \leq x \leq 1$\
    $$\begin{aligned}
    f^{\prime}(x)=\frac{x^2}{2}-\frac{1}{2x^2} \\
    \int^{1}_{\frac{1}{2}} \sqrt{1+[\frac{x^2}{2}-\frac{1}{2x^2}]^2}dx \\
    \frac{31}{48}\end{aligned}$$

Surface Area
------------

When calculating the surface area we are look at the area around a 3d
shape that has either been rotated around the x-axis or the y-axis. The
following properties are used to calculate the surface area,

1.  $s = \int 2 \pi y,ds \quad \quad \text{Rotating around the x-axis}$

2.  $s = \int 2 \pi x ,ds \quad \quad \text{Rotating around the y-axis}$

3.  $ds = \sqrt{1+(\frac{dy}{dx})^2}dx \quad \quad y =f(x)$

4.  $ds = \sqrt{1+(\frac{dx}{dy})^2}dy \quad \quad x =h(y)$

Knowing this, lets look at some examples,

Find the surface area of the following

1.  $y=\sqrt{4-x^2} \quad -1\leq x \leq 1 \quad \quad \text{around the x-axis}$

2.  $x=\frac{1}{3} (y^2+2)^{\frac{3}{2}} \quad 1\leq y \leq 2 \quad \quad \text{around the y-axis}$

```{=html}
<!-- -->
```
1.  $y=\sqrt{4-x^2} \quad -1\leq x \leq 1 \quad \quad \text{around the x-axis}$\
    $$\begin{aligned}
    R = y \\
    r(x) = \sqrt{4-x^2} \\
    f(x) = (4-x^2)^\frac{1}{2} \quad \quad f^{\prime}(x)= \frac{-x}{\sqrt{4-x^2}} \\
    (f^{\prime}(x))^2=\frac{x^2}{4-x^2} \\
    s= 2 \pi \int^{1}_{-1} \sqrt{4-x^2}\sqrt{1+\frac{x^2}{4-x^2}} \\
    2 \pi \int^{1}_{-1} \sqrt{4-x^2+x^2}dx \\
    2 \pi \int^{1}_{-1}2dx \\
    2 \pi (2x)]^{1}_{-1} = 4\pi (x)]^{1}_{-1} \\
    4\pi [1-(-1)]=4\pi(2)=8\pi\end{aligned}$$

2.  $x=\frac{1}{3} (y^2+2)^{\frac{3}{2}} \quad 1\leq y \leq 2 \quad \quad \text{around the y-axis}$\
    $$\begin{aligned}
    R(y)=y \\
    \frac{dx}{dy}= \frac{1}{3}*\frac{3}{2}(y^2+2)^\frac{1}{2}(2y) \\
    \frac{dx}{dy}= y \sqrt{y^2+2} \\
    (\frac{dx}{dy})^2=(y \sqrt{y^2+2})^2 \\
    (g^{\prime}(y))^2=y^4+2y^2 \\
    S = 2 \pi \int^{2}_{1} y \sqrt{1+y^4+2y^2}dy \\
    2 \pi \int^{2}_{1} y \sqrt{(y^2+1)^2} dy \\
    2 \pi \int^{2}_{1} y (y^2+1)dy \\
    \frac{y^4}{4}+\frac{y^2}{2}]^{2}_{1} (2 \pi) \\
    2 \pi [4+2-\frac{1}{4}-\frac{2}{4}] = 2 \pi (\frac{21}{4}) = \frac{21 \pi}{2} \end{aligned}$$