Applications Of The Derivative
==============================

In this section, we are going to look at the applications of the
derivative, where are derivatives used in real life. The sections in
this chapter are not going to look at specific applications bit various
methods that are used when applying the math that we learnt in the
previous chapter. For example, we are going to be learning about minima
and maxima in the chapter, minima and maxima can be used anywhere from
engineering to finance to rocket science. All these concepts are
applicable nearly everywhere.

Identity Of Functions + Concavity
---------------------------------

### First Derivative

First lets go back to what we learnt in the last chapter, a derivative
is\...

rate of change. The derivative denotes the rate of change of curve. Now
when modeling in the real world, rate of change is the rate at which
something is either growing or shrinking or staying constant of course.
If we take the derivative of a function, and set it equal to zero, then
we can find all the points where the function constant, not decreasing
nor increasing.

Critical Points. Points on the graph where the first derivative is 0 or
where the first derivative does not exist.

Now that we know the definition of critical points lets look at two
examples,

Find the critical points of these functions.

1.  $f(x)=(x^3 -25x)^\frac{2}{3}$

2.  $f(x)= \frac{x^2+2x+1}{3x-5}$

```{=html}
<!-- -->
```
1.  $f(x)=(x^3 -25x)^\frac{2}{3}$\
    $$\begin{aligned}
    \frac{2}{3}(x^3-25x)^\frac{-1}{3}(3x^2-25) \\
    \frac{6x^2-50}{3\sqrt[3]{x^3-25x}} \\
    6x^2-50=0 \\
    x = \pm \sqrt{\frac{25}{3}} \\
    x^3-25x=0 \\
    x(x^2-25) = 0 \\
    x = 0 \\
    x = \pm 5\end{aligned}$$

2.  $f(x)= \frac{x^2+2x+1}{3x-5}$\
    $$\begin{aligned}
    \frac{[(2x+2)(3x-5)]-[(x^2+2x+1)(3)]}{(3x-5)^2} \\
    \frac{3x^2-10x-10}{(3x-5)^2} \\
    3x-5=0 \\
    x = \frac{5}{3} \\
    3x^2-10x-10 =0 \\
    x=4.138,-0.8053\end{aligned}$$

### Higher Order Derivatives

Now lets talk about the applications of the higher order derivatives
that we learned in the last chapter. In the last chapter we learned that
a higher order derivative is a derivative of another already taken
derivative. Higher order derivatives are used to model the rate of
change of the rate of change. A first order derivative models the slope
of a curve, while a second order derivative models the concavity of the
curve. The concavity is the rate of change of the slope.

If the first derivative is positive then the function is increasing

If the first derivative is negative then the function is decreasing

If the second derivative is positive then the function is concave up
($\cup$)

If the second derivative is negative then the function in concave down
($\cap$)

The first and second derivatives can come in really handy when graphing
or sketching a function. The critical points and the inflection points
of those functions hold key areas where the behaviors of the function
changes.

Absolute Extrema
----------------

Finding the absolute extrema of a curve is really important. In the real
world, practically nothing is linear, so calculus is needed to model
behaviors.

Again to reiterate, the critical points of a curve are really important,
as they tell us at what point is the function constant.

Finding the absolute extrema,

1.  The function has to be continuous on the interval

2.  Find the critical points in the function

3.  Now find the absolute extrema, and make sure to include the end
    point.

If the function is in a closed interval, then use the endpoints, if it
is an open interval,never use the endpoints.

Lets look at examples,

Find the absolute extrema for the following functions in their
respective intervals.

1.  $f(x)=2x^4-16x^3+20x^2-7$ on \[-2,6\]

2.  $g(x)=8-12x^5-25x^6+\frac{90}{7}x^7$ on \[-1,1\]

3.  $h(x)=\frac{6+9x+x^2}{1+x+x^2}$ on \[-6,0\]

4.  $i(x)=3\cos(2x)-5x$ on \[0,6\]

Find the critical points of the function, then plug them in to find the
maximum and minimum values. (don't forget about the endpoints)

1.  $f(x)=2x^4-16x^3+20x^2-7$ on \[-2,6\]\
    $$\begin{aligned}
    f^{\prime}(x) = 8x^3-48x^2+40x =8x(x^2-6x+5) \\
    x = 0,1,5 \\
    f(-2)= 233 \\
    f(0)= -7 \\
    f(1)= -1 \\
    f(5)= -257 \\
    f(6)= -151 \\
    max = -2 \\
    min = 5\end{aligned}$$

2.  $g(x)=8-12x^5-25x^6+\frac{90}{7}x^7$ on \[-1,1\]\
    $$\begin{aligned}
    g^{\prime}(x)=-60x^4-150x^5+90x^6 \\
    30x^4(-2-5x+3x^2) \\
    x = 0, 2, \frac{-1}{6} \\
    x = -1,1 \\
    f(-1) = \frac{-125}{7}  \\
    f(-\frac{1}{6}) = 8.001  \\
    f(0) = 8 \\
    f(1) = \frac{-113}{7} \\
    f(2) = \frac{-2312}{7} \\
    min = 2 \\
    max = \frac{-1}{6}\end{aligned}$$

3.  $h(x)=\frac{6+9x+x^2}{1+x+x^2}$ on \[-6,0\]\
    $$\begin{aligned}
    h^{\prime}(x) = \frac{-8x^2-10x+3}{(1+x+x^2)^2} \\
    x = \frac{-3}{2}, \frac{1}{4} \\
    x = 0, -6 \\
    f(-6) = \frac{-12}{31} \\
    f(\frac{-3}{2}) = -3\\
    f(0) = 6 \\
    f(\frac{1}{4}) = \frac{19}{3} \\
    min = \frac{-3}{2} \\
    max = \frac{1}{4}\end{aligned}$$

4.  $i(x)=3\cos(2x)-5x$ on \[0,6\]\
    $$\begin{aligned}
    i^{\prime}(x)= -6\sin(2x)-5 \\
    \sin(2x) = \frac{-5}{6} \\
    2x = 5.29074 + 2\pi n \\
    2x = 4.1267 + 2\pi n \\
    x = 2.6490 + \pi n \\
    x = 2.0634 + \pi n \\
    x = 2.6490, 2.0634, 5.7906, 5.20499, 0,6 \\
    f(0) =  3\\
    f(2.0634) = -11.97507  \\
    f(2.6490) = -11.58687 \\
    f(5.20499) = -27.68303 \\
    f(5.7906) = -27.294837 \\
    f(6) = -27.4684 \\
    min = 5.205 \\
    max = 0\end{aligned}$$

Relative Extrema
----------------

Relative are useful went graphing extrema that are not necessary the
highest or lowest points on a graph. Sometimes, graphs have relative
extrema, they are relative maximums or minimums.

Relative extrema are the highest or lowest on some interval around the
function. An important thing to note about relative extrema is that
relative maximums or minimums can never happen at the endpoints of an
interval.

When finding the relative maximum/minimum:

1.  Take the first derivative of the function

2.  Set the derivative = 0 or where the function does not exist

3.  Solve for x

In order to find out whether the critical point we are looking we put
the critical points in a number line and we plug in points that satisfy
each interval of the number line. Or we use something called the second
derivative test. The second derivative test tells us that if we find the
second derivative of the function and plug in the critical point into
the second derivative,

1.  If $f^{\prime \prime}< 0$ then f has a relative maximum value at x
    = c.

2.  If $f^{\prime \prime}> 0$ then f has a relative minimum value a x
    = c.

It really depends what method you want to use, most of the time one is
easier than the other.

Find all of the relative extrema of the following functions in their
given intervals.

1.  $f(x)=(x-2)^2+1$ on \[-1,1\]

2.  $g(x)=e^{3-x}$ on \[-1,3\]

3.  $h(x)=cos(x)+2$ on \[$\frac{1}{2},1$\]

4.  $i(x)=\frac{4x}{x^2+1}$

Find the relative extrema be taking the first derivative. Then by either
the line test or the second derivative test find wether the critical
points are a relative maxima or minima.

1.  $f(x)=(x-2)^2+1$ on \[-1,1\]\
    $$\begin{aligned}
    f^{\prime}(x)=2(x-2)=2x-4 \\
    2x-4=0 \\
    x=2 (out of the interval)\\
    R.Min = none \\
    R.Max = none\end{aligned}$$

2.  $g(x)=e^{3-x}$ on \[-1,3\]\
    $$\begin{aligned}
    g^{\prime}(x)=-e^{3-x} \\
    No solution for for g^{\prime}(x)=0 \\
    R.Max = none \\
    R.Min = none \end{aligned}$$

3.  $h(x)=\cos(x)+2$ on \[$\frac{1}{2},1$\]\
    $$\begin{aligned}
    h^{\prime}(x)=-\sin(x) \\
    -sin(x)=0 \\
    x = 2 \pi n \\
    x = \pi + 2 \pi n \\
    None are on the interval \\
    R.Max = none \\
    R.Min = none\end{aligned}$$

4.  $i(x)=\frac{4x}{x^2+1}$\
    $$\begin{aligned}
    i^{\prime}(x) = \frac{-4x^2+4}{(x^2+1)^2} \\
    x = \pm 1 \\
    i^{\prime}(2) = - \\
    i^{\prime}(0) = + \\
    i^{\prime}(-2) = - \\
    R.Max = -1 \\
    R.Min = 1 \\\end{aligned}$$

Optimization
------------

Optimization is the second of the hardest concepts in calculus 1. We
said that related rates was one of them, but now optimization is the
second. Optimization stems around the idea of our absolute maxima and
minima. Optimization is really important in basically all applications
of calculus in the real world. The methods used are the first derivative
test and the second derivative test in this section.

The key to these problems, just like with related rates,

1.  Draw a sketch of whats going on in the problem

2.  Label what you are given, and what you are finding

3.  Solve and plug into the into the other equation

4.  Solve for the variable you are looking for

Again these are best looked at with examples, everything needed to solve
these, we learnt in the two previous sections.

Solve the following problems.

1.  Find two numbers whose sum is 50 and whose product is a maximum.

2.  What is the largest possible volume of a box with a square base and
    an open top that can be produced using $900cm^2$ of material?

3.  Find the point on the line $y=6-2x$ that is closest to the origin.

4.  A box with an open top is to be constructed from a square piece of
    cardboard that is 5 feet wide by cutting out a square form each side
    of the four corners and bending up the sides. Find the maximum
    volume of the box.

In order to solve, have the equation you are trying to solve for in
terms of one variable and one variable only.

1.  Find two numbers whose sum is 50 and whose product is a maximum.\
    $$\begin{aligned}
    s = x+y \quad \quad p=xy \\
    60 = x+y \\
    y = 60-x \\
    p = x(60-x) \\
    p = 60x-x^2 \\
    p^{\prime} = -2x+60 \\
    -2x+60 = 0 \\
    x=30 \\
    60-30 = 30 \\
    y = 30 \\
    p =(30)(30) = 900\end{aligned}$$

2.  What is the largest possible volume of a box with a square base and
    an open top that can be produced using $900cm^2$ of material?\
    $$\begin{aligned}
    SA = x^2 + 4xy \\
    V = x^2y \\
    900 = x^2 + 4xy \\
    900-x^2 = 4xy \\
    \frac{225}{x}-\frac{1}{4}x= y \\
    v = (x^2)(\frac{225}{x}-\frac{1}{4}x) \\
    v = 225x - \frac{1}{4}x^3 \\
    v^{\prime} = 225 - \frac{3}{4}x^2=0 \\
    x = 17.32 \\
    v = 225(17.32)-\frac{1}{4}(17.32)^3 \\
    v =2598.1 cm^3\end{aligned}$$

3.  Find the point on the line $y=6-2x$ that is closest to the origin.\
    $$\begin{aligned}
    y=-2x+6 \\
    D^2 = x^2 + y^2 \\
    x = 3 \\
    D = [x^2+(6-2x)^2]^\frac{1}{2} \\
    D^{\prime} = \frac{2x-4(6-2x)}{2\sqrt{x^2+(6-2x)^2}} \\
    2x-4(6-2x) = 0 \\
    2x-24+8x = 0 \\
    10x-24 = 0 \\
    x =2.4 \\
    y = 1.2 \\
    (1.2,2.4)\end{aligned}$$

4.  A box with an open top is to be constructed from a square piece of
    cardboard that is 5 feet wide by cutting out a square form each side
    of the four corners and bending up the sides. Find the maximum
    volume of the box.\
    $$\begin{aligned}
    v = lwh \\
    v = (4-2x)^2 x \\
    v^{\prime} = (4-2x)[4-6x] = 0 \\
    x = 2, \frac{2}{3} \\
    v = 2(0)^2 = 0  \quad wrong\\
    v = \frac{2}{3}(4-2*\frac{2}{3})^2 \\
    v = \frac{128}{27}\end{aligned}$$

Newton's Method
---------------

Newtons method is used to find the solutions to functions f(x) that = 0.
Newtons method is an approximation method, it is not a defined theorem.
This approximation method gives you a more accurate answer the more you
iterate it.

Newtons Method

If $x_{n}$ is an approximation a solution of $f(x) = 0$ and if
$f^{\prime}(x_{n})\neq 0$ the approximation is,
$$x_{n+1}=x_{n}-\frac{f(x_{n})}{f^{\prime}(x_{n})}$$

Note that the equations have to be in the format of f(x)=0 or newtons
method will not work.

Lets look at examples,

Find $x_{2}$ for the given functions.

1.  $f(x) = 7-e^{2x-3} \quad x_{0} = 5$

2.  $g(x)=2x^3 - 9x^2+17x+20 \quad x_{0} = 0$

3.  $h(x)=cos(3x)-sin(x) \quad x_{0} = 0$

```{=html}
<!-- -->
```
1.  $f(x) = 7-e^{2x-3} \quad x_{0} = 5$\
    $$\begin{aligned}
    f^{\prime}(x)=-2e^{2x-3} \\
    x_{n+1} = x_{0} - \frac{7-e^{2x-3}}{-2e^{2x-3}} \\
    x_{1} = 5 - \frac{7-e^{2(5)-3}}{-2e^{2(5)-3}} \\
    x_{1} = 4.5032 \\
    x_{2} = 4.5032 - \frac{7-e^{2(4.5032)-3}}{-2e^{2(4.5032)-3}} \\
    x_{2} = 4.0118\end{aligned}$$

2.  $g(x)=2x^3-9x^2+17x+20 \quad x_{0} = 0$\
    $$\begin{aligned}
    g^{\prime}(x)= 6x^2-18x+17 \\
    x_{n+1} = x_{0} - \frac{6x^2-18x+17}{2x^3-9x^2+17x+20} \\
    x_{1} = -0.85 \\
    x_{2} = 15.949266 \end{aligned}$$

3.  $h(x)=\cos(3x)-\sin(x) \quad x_{0} = 0$\
    $$\begin{aligned}
    h^{\prime}(x)=-3\sin(3x)-\cos(x) \\
    x_{n+1} = x_{0} - \frac{\cos(3x)-\sin(x)}{-3\sin(3x)-\cos(x)} \\
    x_{1} = 1
    x_{2} = -0.900524\end{aligned}$$

Newtons method does not work of the time, sometimes the results diverge.
Beware.

Newtons method can come useful when you want to find the roots of an
equation, however it isnt always the most practical.

Rectilinear Motion
------------------

Rectilinear motion is one of the heavy applications of mathematics in
physics. More precisely calculus. We know that the first derivative is
the rate of change of an object, the rate of change in physics is
denoted as the velocity of can object. The second derivative is physics
is the acceleration, or in mathematics the rate of change of the rate of
change.

When the first derivative of an object is positive then the object is
moving forward

When the first derivative of an object is negative then the object is
moving backwards

When the second derivative of an object is positive then the object is
speeding up

When the second derivative of an object is negative then the object is
slowing down

Now example time,

The position of an object is given by $s(t)=t^3-6t^2+9t$. (t seconds, s
meters).

1.  What is the velocity after 2 seconds? After 4 seconds?

2.  When is the object at rest?

3.  When is the object moving forward?

4.  Find the acceleration after 4 seconds.

5.  When is the object speeding up or slowing down?

The position of an object is given by $s(t)=t^3-6t^2+9t$. (t seconds, s
meters).

1.  What is the velocity after 2 seconds? After 4 seconds?\
    $$\begin{aligned}
    s^{\prime}(t)=3t^2-12t+9 \\
    s^{\prime}(2)=3(2)^2-12(2)+9 \\
    -3\end{aligned}$$

2.  When is the object at rest?\
    $$\begin{aligned}
    3t^2-12t+9= 0 \\
    t^2-4t+3 = 0 \\
    x = 1,3\end{aligned}$$

3.  When is the object moving forward?\
    $$\begin{aligned}
    (-\infty,1)\cup(3,+\infty)\end{aligned}$$

4.  Find the acceleration after 4 seconds.\
    $$\begin{aligned}
    s^{\prime \prime}(t)= 6t-12 \\\end{aligned}$$

5.  When is the object speeding up or slowing down?\
    $$\begin{aligned}
    6t-12 =0 \\
    t = 2\\
    Speeding = (2,+\infty) \\
    Slowing = (-\infty,2)\end{aligned}$$

Mean Value Theorem + Rolle's Theorem
------------------------------------

These two theorems are nice applications of our knowledge of
derivatives. The mean value theorem gives this nice correlations between
the average rate of change of a function and the derivative of a
function. The Rolle's theorem is a special case of the mean value
theorem.

### Mean Value Theorem

Lets first discuss what the mean value theorem states, then look at the
interpretation geometrically/graphically then finally lets work on some
examples.

Mean Value Theorem If $f(x)$ is defined and continuous on the interval
\[a,b\], and differentiable on (a,b), then there is a number c in the
interval of (a,b) such that a\<c\<b and
$$f^{\prime}(c)=\frac{f(b)-f(a)}{b-a}$$

Now the graphic interpretation of the Mean Value Theorem. \*\*Graphics
are only available on the pdf version.\*\*

Finally lets work on a couple of examples,

Verify that the function satisfies the conditions of the Mean Value
Theorem. Then find all numbers c that satisfy the conclusion of the Mean
Value Theorem.

1.  $f(x)=x^2+4x+5 \quad \quad [0,4]$

2.  $f(x)=\frac{x}{x+3} \quad \quad [-1,3]$

We just use our mean value theorem to find our solutions.

1.  $f(x)=x^2+4x+5 \quad \quad [0,4]$\
    $$\begin{aligned}
    f^{\prime} = \frac{f(b)-f(a)}{b-a} \\
    2x+4= \frac{f(4)-f(0)}{4} \\
    8x+16 = 4^2+4(4)+5-5 \\
    8x+16 = 16+16\\
    x =2 \\
    c= 2 \\
    f^{\prime}(2)=2(2)+4=8\end{aligned}$$

2.  $f(x)=\frac{x}{x+3} \quad \quad [-1,3]$\
    $$\begin{aligned}
    f^{\prime}(x)=\frac{(x+3)(1)-x(1)}{(x+3)^2} = \frac{3}{(x+3)^2} \\
    \frac{3}{(x+3)^2} = \frac{f(3)-f(-1)}{3--1} = \frac{1}{4} \\
    12 = (x+3)^2 \\
    x = -3 \pm 2\sqrt{3} = 0.464, -6.464 \\
    \text{The only c that works because of the interval restriction is 0.464}\end{aligned}$$

### Rolle's Theorem

Again as noted in the beginning, Rolle's theorem is just a special case
of the mean value theorem.

Rolle's Theorem If we have a function $f(x)$ that has all of the
following:

1.  $f(x)$ is continuous on the closed interval $[a,b]$

2.  $f(x)$ is differentiable on the open interval (a,b)

3.  $f(a) = f(b)$

Then there is a constant c, where c is a\<c\<b and $f^{\prime}(c)=0$.
When the derivative of any function is equal to 0, then that is a
critical point.

Lets look at a couple of examples,

Verify that the function satisfies the conditions of Rolle's Theorem on
the given interval. Then find all numbers c that satisfy the conclusion
of Rolle's Theorem.

1.  $f(x)=x^2-3x+2 \quad \quad [0,3]$

2.  $f(x)=2x^3+3x^2-36x-54 \quad \quad [\frac{-3}{2},3\sqrt{2}]$

In these examples all we have to do is verify that we can use Rolle's
theorem, so we just find c and make sure that it is within the interval.

1.  $f(x)=x^2-3x+2 \quad \quad [0,3]$\
    $$\begin{aligned}
    f^{\prime}(x)=2x-3 \\
    f^{\prime}(c)=2c-3=0 \\
    2c=3 \\
    c = \frac{3}{2} \\\end{aligned}$$

2.  $f(x)=2x^3+3x^2-36x-54 \quad \quad [\frac{-3}{2},3\sqrt{2}]$\
    $$\begin{aligned}
    f(\frac{-3}{2})=2(\frac{-3}{2})^3+3(\frac{-3}{2})^2-36(\frac{-3}{2})-54= 0 \\
    f(3\sqrt{2})= 2(3\sqrt{2})^3+3(3\sqrt{2})^2-36(3\sqrt{2})-54= 0 \\
    f^{\prime}(x)=6x^2+6x-36=0 \\
    f^{\prime}(c)=6c^2+6c-36=0 \\
    f^{\prime}(c)=6(c+3)(c-2) \\
    c = -3 \\
    c = 2 \\
    \text{2 is the only possible c because it is the only one that is in the interval}\end{aligned}$$