Applications Of The Integral
============================

In this final chapter of Calculus 1, we are going to talk about the
applications of the integrals we learned in the previous section. Alot
of these applications are used in physics, engineering and other stem
topics.

Average Value Of A Function
---------------------------

In this section, we are going to do exactly what the title says, we are
going to find the average value of a definite integral.

Average Value Of a Function The average value of $f(x)$ on \[a,b\] is
defined by, $$f_{\text{avg}} = \frac{1}{b-a} \int^{b}_{a} f(x),dx$$

Mean Value Theorem Let f(x) be continuous on the closed interval
\[a,b\]. There exists a point such that,
$$f(c)=\frac{1}{b-a} \int^{b}_{a} f(x),dx$$ Further simplification,
$$\int^{b}_{a} f(x)dx = f(c)(b-a)$$

Lets work on some examples of each of these theorems, lets start with
the average value of a function first.

Solve the following problems by finding the average value of a function.

1.  $f(x)=2x-4 \quad \quad [1,5]$

2.  $f(x)=\frac{1}{x} \quad \quad [1,3]$

We just use the formula we derived above to solve these examples.

1.  $f(x)=2x-4 \quad \quad [1,5]$\
    $$\begin{aligned}
    f_{\text{avg}} = \frac{1}{5-1} \int^{5}_{1} (2x-4)dx \\
    \frac{1}{4}[x^2-4x]^{5}_{1} \\
    \frac{1}{4}[(5^2-4(5))-(1^2-4(1))] \\
    2\end{aligned}$$

2.  $f(x)=\frac{1}{x} \quad \quad [1,3]$\
    $$\begin{aligned}
    \frac{1}{3-1} \int^{3}_{1} \frac{1}{x},dx \\
    \frac{1}{2} ln|x|]^{3}_{1} \\
    \frac{1}{2} [ln|3|-ln|1|] \\
    f_{\text{avg}} = 0.549\end{aligned}$$

```{=html}
<!-- -->
```
1.  $f(x)=x^2 \quad \quad [0,4]$

2.  $f(x)=2x+3 \quad \quad [2,10]$

```{=html}
<!-- -->
```
1.  $f(x)=x^2 \quad \quad [0,4]$\
    $$\begin{aligned}
    \int^{4}_{0} x^2,dx = c^2(4-0) \\
    \frac{x^3}{3}]^{4}_{0} \\
    \frac{4^3}{3}-\frac{0^3}{3} = 4c^2 \\
    \frac{64}{3}=4c^2 \\
    c^2 = \frac{16}{3} \\
    c= \pm \frac{4}{\sqrt{3}} \\
    c = \frac{\pm 4 \sqrt{3}}{3}\end{aligned}$$

2.  $f(x)=2x+3 \quad \quad [2,10]$\
    $$\begin{aligned}
    \int^{10}_{2} (2x+3),dx =(2c+3)(10-2) \\
    x^2+3x]^{10}_{2} = (2c+3)(8) \\
    [10^2+3(10)]-[2^2+3(2)]=(2c+3)(8) \\
    130-10=(2c+3)(8) \\
    15 = (2c+3) \\
    c=6\end{aligned}$$

Work
----

Another application of integrals is work. Work a key concept in physics
and it is defined as Force X Distance. $$W=Fd$$ Furthermore, we can
define work as the following, $$W = \int^{b}_{a}F(x)dx$$

Applications of work are best seen through example,

1.  Find the work done in pushing a car a distance of 15m with a
    constant force of 500N

2.  How much work is needed to lift a 300lb crate up a distance of 200
    ft using a rope that weighs 4lbs/ft.

3.  A force of 60N is required to hold a spring that has been stretched
    from its natural length of 12cm to 17cm. How much work is done in
    stretching the spring from 15cm to 20cm?

```{=html}
<!-- -->
```
1.  Find the work done in pushing a car a distance of 15m with a
    constant force of 500N $$\begin{aligned}
    W =Fd \\
    W= (500)(15) \\
    W = 7500 Joules\end{aligned}$$

2.  How much work is needed to lift a 300lb crate up a distance of 200
    ft using a rope that weighs 4lbs/ft.\
    $$\begin{aligned}
    W = Fd = (300)(200) = 60,000lbs*ft \\
    F(x)=4x \\
    W = \int^{200}_{0} 4x,dx = 2x^2 +c \\
    [2(200)^2]-[0] = 80,000 lbs*ft
    80,000+60,000=140,000 lbs*ft\end{aligned}$$

3.  A force of 60N is required to hold a spring that has been stretched
    from its natural length of 12cm to 17cm. How much work is done in
    stretching the spring from 15cm to 20cm?\
    $$\begin{aligned}
    F=Kx \\
    K=\frac{F}{x}=\frac{60}{0.05} = 1200 \frac{N}{m} \\
    F(x)=1200x \\
    \int^{0.08}_{0.03} 1200x,dx \\
    600x^2]^{0.08}_{0.03} \\
    3.3 Joules\end{aligned}$$

Area Between Different Curves
-----------------------------

When trying to calculate the area between two different curves as
follows,

\*\*Graphics Only Available On the Pdf\*\*

we take the integral of the \"bigger\" function subtracted from the area
of the \"smaller\" function.

The area between two curves on the x-axis,
$$A=\int^{b}_{a}(\text{Top Function}) - (\text{Bottom Function}),dx \quad \quad a\leq x \leq b$$
The area between two curves on the y-axis,
$$A = \int^{b}_{a} (\text{Right-most Function})- (\text{Left-most Function}),dy \quad \quad c \leq y \leq d$$

Now that we have the definitions and some geometrical intuition, lets
work on some examples.

Find the area between the following two curves,

1.  $y=x \quad \quad y=x^2$

2.  $y=x^2 \quad \quad x=y^2$

3.  $x = 1-y^2 \quad \quad x=y^2-1$

We just use the formulas we derived above.

1.  $y=x \quad \quad y=x^2$\
    $$\begin{aligned}
    When graphing the following functions, we can see that y=x is higher on the x axis than y=x^2 \\
    A = int^{1}_{0} [x-x^2]dx \\
    A = \frac{x^2}{2}-\frac{x^3}{3}]^{1}_{0} \\
    A = [\frac{1}{2}-\frac{1}{3}]-[0] \\
    A = \frac{1}{6}\end{aligned}$$

2.  $y=x^2 \quad \quad x=y^2$\
    $$\begin{aligned}
    y=x^2 \quad \quad \sqrt{x}=y \\
    A = \int^{1}_{0} [x^{\frac{1}{2}}-x^2]dx \\
    \frac{2x^{\frac{3}{2}}}{3}-\frac{x^3}{3}]^{1}_{0} \\
    A = [\frac{2}{3}-\frac{1}{3}]-[0] \\
    A = \frac{1}{3}\end{aligned}$$

3.  $x = 1-y^2 \quad \quad x=y^2-1$\
    $$\begin{aligned}
    A = \int^{1}_{-1} [1-y^2]-[y^2-1]dy \\
    \int^{1}_{-1} 2-2y^2 dy \\
    2y-\frac{2}{3}y^3]^{1}_{-1} \\
    A = [2(1)-\frac{2(1)^3}{3}]-[2(-1)-2(-1)^3] \\
    A = \frac{8}{3}\end{aligned}$$

Sometimes you have to convert one of your equations in order for both of
the equations to be of the same variable.

Disk And Washers Method
-----------------------

Another one of the applications of integrals is the disk and washers
method. The disk and washers method works with the fact that we can
calculate the volume of a solid be splitting it into infinitely many
circle and adding together the area of each of these circles. Below is
some geographical intuition,

\*\*Graphics Only Available On the Pdf\*\*

Disk and Washers Method The formula to find the volume,
$$V = \int^{b}_{a} A(x),dx \quad \quad \quad V=\int^{b}_{a}A(y),dy$$ The
first formula is the area when the rotation is about the x-axis, while
the second is about the y-axis. Furthermore, A(x) and A(y) are the area.
The formula for the area is the following.
$$A=\pi((\text{Outside Radius})^2-(\text{Inside Radius})^2)$$

Knowing this, lets work on some practice problems.

Using our formulas, solve the following.

1.  Region bounded by $y=\sqrt{x}$ and $y=\frac{1}{2}x$ about the
    x-axis.

2.  Region bounded by $y=x$ and $y=x^3$ from x=0 to 1 about the x-axis.

In order to solve these we just refer back to the formula.

1.  Region bounded by $y=\sqrt{x}$ and $y=\frac{1}{2}x$ about the
    x-axis.\
    $$\begin{aligned}
    V=\int^{4}_{0} \pi(\sqrt{x})^2 dx - \int^{4}_{0} \pi (\frac{1}{2}x)^2 dx \\
    \frac{\pi}{2}x^2]^{4}_{0}-\frac{\pi}{8}x^2]^{4}_{0} \\
    [[\frac{\pi}{2}(4)^2]-[\frac{\pi}{2}(0)^2]]-[[\frac{\pi}{8}(4)^2]-[\frac{\pi}{8}(0)^2]] \\
    [[8\pi]-[0]]-[[2\pi]-[0]] \\
    V = 6\pi\end{aligned}$$

2.  Region bounded by $y=x$ and $y=x^3$ from x=0 to 1 about the x-axis.
    $$\begin{aligned}
    V = \int^{1}_{0} \pi (x)^2- \pi (x^3)^2 dx \\
    \pi \int^{1}_{0} x^2-x^6 dx \\
    \pi(\frac{1}{3}x^3-\frac{1}{7}x^7)]^{1}_{0} \\
    \pi([\frac{1}{3}-\frac{1}{7}]-[0-0]) \\
    =0.598...\end{aligned}$$

Cylindrical Shells Method
-------------------------

Different from the Disk and Washers method, the Cylindrical Shells
method. The fundamental idea is the same, but the shape we are going to
be using to measure the volume of our functions is going to be
different.

Shells Method The formulas for the Volume are the same,
$$V=\int^{b}_{a} A(x)dx \quad \quad \quad V=\int^{b}_{a} A(y)dy$$
However, we are going to be using a different area formula (area of a
cylinder), $$A=2 \pi(r)(h)$$

Using this definition, lets work on some examples,

Solve the following volume problems using the shells method.

1.  Rotate the area between $x=1-(y-1)^2$ and the y-axis about the
    x-axis.

2.  Rotate the area between $y=e^{x^2}$ and $x=1$ about the x-axis.

Plug in the formula and bam\... We get the volume.

1.  Rotate the area between $x=1-(y-1)^2$ and the y-axis about the
    x-axis.\
    $$\begin{aligned}
    V= 2 \pi \int^{2}_{0} y(1-(y-1)^2)dy  \\
    2 \pi \int^{2}_{0} 2y^3-y^2 dy \\
    2 \pi (\frac{y^4}{2}-\frac{y^3}{3}) = 2 \pi (8-\frac{8}{3}-0) \\
    \frac{32 \pi}{3}\end{aligned}$$

2.  Rotate the area between $y=e^{x^2}$ and $x=1$ about the x-axis.\
    $$\begin{aligned}
    V = 2 \pi \int^{1}_{0} xe^{x^2} dx \\
    u = x^2 \\
    du = 2x dx \\
    \frac{du}{2x} = dx \\
    \pi \int^{1}_{0} e^u du \\
    \pi (e-1)\end{aligned}$$

The key thing to note here is the setup. Solving the integrals is easy,
the hard part is the setup. Focus on learning the setup.
