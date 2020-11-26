Various Integration Techniques
==============================

In our calculus 1 class, we learned about integration and the concepts
behind integration and some of its applications. However, we didn't look
at many ways behind solving integrals, we only looked at solving
integrals by substitution. The problem with this is that it leaves us
with a whole lot of functions that we just cant find the integral to
with just a substitution. For example, try to find the integral of the
following, $$\int \frac{2}{(x-3)^6 \sqrt{-x^2+6x-5}}dx$$ What do we do?
GIVE UP? No. This section is going to look at various techniques to find
the integrals of \"other\" functions.

Integration by Parts
--------------------

The first method we are going to look at is integration by parts.
Integration by parts steps from the power rule when taking the
derivative of a function. The formula for integration by parts,

$$\int fg^{\prime}dx= fg- \int f^{\prime}gdx$$

we can substitution different variable as the following,
$$u = f(x) \quad \quad v=g(x) \quad \quad du = f^{\prime}(x)dx \quad \quad dv=g^{\prime}(x)dx$$

Doing this we get the following formula,

$$\int u dv = uv - \int v du$$

An for when we want to find the definite integral we use the following
formula, $$\int^{b}_{a} u dv = uv]^{b}_{a} - \int^{b}_{a} v du$$

Now that we have derived the formulas lets work on some examples

Solve the following integrals, integration by parts.

1.  $\int xe^xdx$

2.  $\int x \sin(x) dx$

3.  $\int x \cos(3x) dx$

4.  $\int x^2e^{3x}dx$

In order to solve the examples, we just refer back to the formulas we
learned.

1.  $\int xe^xdx$\
    $$\begin{aligned}
    u=x \quad \quad dv = e^xdx \\
    du = dx \quad \quad v = e^x \\
    \int xe^xdx = xe^x-\int e^xdx \\
    xe^x-e^x+c\end{aligned}$$

2.  $\int x \sin(x) dx$\
    $$\begin{aligned}
    u = x \quad \quad dv=\sin(x)dx \\
    du=dx \quad \quad v=-\cos(x) \\
    \int xsinx dx = x(-cos(x))- \int(-\cos(x))dx \\
    -x\cos(x)+\int \cos(x)dx \\
    -x\cos(x)+\sin(x)+c\end{aligned}$$

3.  $\int x \cos(3x) dx$\
    $$\begin{aligned}
    u=x \quad \quad dv = \cos(3x)dx \\
    du = dx \quad \quad v = \frac{1}{3} \sin(3x) \\
    \int x\cos(3x)dx = x \frac{1}{3}\sin(3x)-\int \frac{1}{3} \sin(3x) dx \\
    \frac{1}{3}x\sin(3x)-\frac{1}{3}\int \sin(3x)dx \\
    \frac{1}{3}x\sin(3x)-(\frac{1}{3}) \frac{-\cos(3x)}{3} +c \\
    \frac{x\sin(3x)}{3} + \frac{\cos(3x)}{9} +c\end{aligned}$$

4.  $\int x^2e^{3x}dx$\
    This one is a little more tricky because we have to integrate my
    parts twice. $$\begin{aligned}
    u =x^2 \quad \quad dv=e^{3x}dx \\
    du =2xdx \quad \quad v = \frac{1}{3} e^{3x} \\
    \int x^2e^{3x}dx = x^2(\frac{1}{3})e^{3x} - \int \frac{1}{3}e^{3x}(2x)dx \\
    \frac{x^2e^{3x}}{3} - \frac{2}{3}\int xe^{3x} dx \\\end{aligned}$$
    Right here we have to integrate by parts again. $$\begin{aligned}
    u = x \quad \quad dv = e^3x dx \\
    du =dx \quad \quad v = \frac{1}{3}e^{3x} \\
    \int x^2e^{3x}dx = \frac{1}{3}x^2 e^{3x}-\frac{2}{3} \int xe^{3x}dx \\
    \frac{1}{3}x^2 e^{3x} - \frac{2}{3}(x\frac{1}{3}e^{3x}-\int \frac{1}{3}3^{3x}dx) \\
    \frac{1}{3}x^2e^{3x} - \frac{2}{3}(\frac{1}{3}xe^{3x}-\frac{1}{3}\int e^{3x}dx) \\
    \frac{1}{3}x^2e^{3x}-\frac{2}{9}xe^{3x}+\frac{2}{9} \frac{e^{3x}}{3} +c \\
    \frac{x^2e^{3x}}{3} - \frac{2xe^{3x}}{9}+\frac{2e^{3x}}{27} +c\end{aligned}$$

Techniques for Trigonometric Integrals
--------------------------------------

The next type of integral we are look to solve are trigonometric
integrals. We already know the integrals of the basic trigonometric
functions however we want to go a step farther. First we have to list
the identities of trig functions,

1.  $\sin(\alpha) \cos(\beta)=\frac{1}{2}[\sin(\alpha-\beta)+\sin(\alpha + \beta)]$

2.  $\sin(\alpha) \sin(\beta)= \frac{1}{2}[\cos(\alpha-\beta)-\cos(\alpha+\beta)]$

3.  $\cos(\alpha) \cos(\beta) = \frac{1}{2}[\cos(\alpha-\beta)+\cos(\alpha+\beta)]$

4.  $sin^2x+cos^2x=1$

5.  $tan^2x+1=sec^2x$

6.  $1+cot^2x=csc^2x$

Knowing these from our geometry and trigonometry classes, we just use
the appropriate formula when solving trigonometric integrals. Lets look
at examples,

1.  $\int sin^3x cos^2x dx$

2.  $\int sin^2x dx$

3.  $\int sin^4x dx$

```{=html}
<!-- -->
```
1.  $\int sin^3x cos^2x dx$\
    $$\begin{aligned}
    \int \sin x  sin^2x cos^2x dx \\
    \int \sin x [1-cos^2x]cos^2x dx \\
    u = cos(x) \\
    du = -sin(x)dx \\
    dx = \frac{du}{-sin(x)} \\
    -\int [1-u^2][u^2] du \\
    = \frac{u^5}{5}-\frac{u^3}{3} +c \\
    \frac{1}{5}cos^5x-\frac{1}{3}cos^3x+c\end{aligned}$$

2.  $\int sin^2x dx$\
    $$\begin{aligned}
    cos(2x)=1-2sin^2x \\
    sin^2x=\frac{1}{2}(1-cos(2x)) \\
    \frac{1}{2}[\int dx - \int cos(2x) dx] \\
    \frac{1}{2}[x-\frac{1}{2}sin(2x)]+c \\
    \frac{1}{2}x-\frac{1}{4}sin(2x)+c\end{aligned}$$

3.  $\int sin^4x dx$\
    $$\begin{aligned}
    sin^2x = \frac{1}{2}[1-cos(2x)] \\
    \int [\frac{1}{2}[1-cos(2x)]]^2 dx \\
    \frac{1}{4} \int [1-cos(2x)]^2 dx \\
    \frac{1}{4} \int [1-cos(2x)][1-cos(2x)] dx \\
    \frac{1}{4} \int[1-2cos(2x)+cos^2(2x)]dx \\
    cos(2x)=2cos^2x-1 \\
    1+cos(2x)=2cos^2x \\
    \frac{1}{2}[1+cos(2x)]=cos^2x \\
    \frac{1}{4} \int [1-2cos(2x)+\frac{1}{2}(1+cos(4x))] dx \\
    \frac{1}{4} \int [\frac{3}{2}-2cos(2x)+\frac{1}{2}cos(4x)] dx \\
    \frac{1}{4}[\frac{3}{2}x-sin(2x)+\frac{1}{8}sin(4x)]+c\end{aligned}$$

Trigonometric Substitutions
---------------------------

Different from trigonometric integrals, we now have trigonometric
substitution. A trigonometric substitution is similar to the u
substitution we learned in Calculus 1. Trigonometric substitutions
follow 3 rules,

1.  When $x^2+a^2$ is in the integrand, use $x = a\tan(\theta)$

2.  When $a^2-x^2$ is in the integrand, use $x =a\sin(\theta)$

3.  When $x^2-a^2$ is in the integrand, use $x=a\sec(\theta)$

It's these three rules that make make our method of trigonometric
substitutions. When we say \"use\", we mean use it as a substitution.

Lets work on some examples,

Solve using the trig substitutions.

1.  $\int \frac{\sqrt{x^2+1}}{x}dx$

2.  $\int x^3\sqrt{4-9x^2}dx$

We try to manipulate the integrad until it fits one of our trig
substitutions.

1.  $\int \frac{\sqrt{x^2+1}}{x}dx$\
    $$\begin{aligned}
    x = tan(\theta) \quad \quad dx=sec^2(\theta)d\theta \\
    \int \frac{\sqrt{x^2+1}}{x}dx= \int \frac{\sqrt{tan^2\theta+1}}{tan \theta} sec^2 (\theta) d\theta \\
    \int \frac{\sqrt{sec^2(\theta)}}{tan \theta} sec^2(\theta) d\theta \\
    \int \frac{sec(\theta)}{tan(\theta)}sec^2(\theta)d\theta \\
    \int \frac{sec^3(\theta)}{tan(\theta)} \\
    \int \frac{sec \theta sec^2\theta}{tan \theta} d \theta \\
    \int \frac{sec\theta(1+tan^2\theta)}{tan \theta} d\theta \\
    \int \frac{cos \theta}{sin \theta} * \frac{1}{cos \theta} * (1+tan^2 \theta) d\theta \\
    \int \frac{1+tan^2 \theta}{sin \theta} d \theta \\
    \int \frac{1}{sin \theta} (1+(\frac{sin \theta}{cos \theta})^2)d \theta \\
    \int (\frac{1}{sin \theta} + \frac{sin \theta}{cos^2 \theta}) d \theta \\
    \int (\csc \theta + \frac{1}{cos \theta} * \frac{sin \theta}{cos \theta}) d \theta \\
    \int (csc \theta + sec\theta tan \theta) d \theta \\
    =ln|csc \theta - cot \theta| + sec\theta +c\end{aligned}$$ Now we
    have to go back to our substitution. We have to think of the trig
    functions as if we were in a geometry class (in terms of right
    triangles). $$\begin{aligned}
    tan \theta = x \\
    a^2+b^2=c^2 \\
    x^2+1^2= c^2 \\
    sec \theta = \frac{\sqrt{x^2+1}}{1} \\
    csc \theta = \frac{\sqrt{x^2+1}}{x} \\
    ln|\frac{\sqrt{x^2+1}}{x}-\frac{1}{x}|+\sqrt{x^2+1}+c\end{aligned}$$

2.  $\int x^3\sqrt{4-9x^2}dx$\
    $$\begin{aligned}
    x = \frac{2}{3}sin \theta \\
    dx = \frac{2}{3}cos \theta d \theta \\
    2 \int x^3 \sqrt{1-(\frac{3x}{2})^2} dx = 2 \int (\frac{2}{3}sin \theta)^3 \sqrt{1-(\frac{3}{2}(\frac{2}{3}sin\theta))^2}\frac{2}{3}cos \theta d \theta \\
    \frac{32}{81} \int sin^3\theta cos^2\theta d\theta \\
    \frac{32}{81} \int sin \theta(1-cos^2\theta)cos^2\theta d \theta \\
    \frac{32}{81} \int sin \theta(\cos^2 \theta - cos^4 \theta) d \theta \\
    u = cos \theta \quad \quad du = -sin \theta \\
    -\frac{32}{81} \int (u^2-u^4) d \theta \\
    -\frac{32}{81}(\frac{u^3}{3}-\frac{u^5}{5})+c \\
    -\frac{32}{81}(\frac{(cos \theta)^3}{3}-\frac{(cos \theta)^5}{5}) +c \\
    sin \theta = \frac{3x}{2} \\
    cos \theta = \frac{\sqrt{4-9x^2}}{2} \\
    -\frac{4}{243}(4-9x^2)^\frac{3}{2}+\frac{1}{405}(4-9x^2)^\frac{5}{2}+c\end{aligned}$$

Partial Fractions
-----------------

When integrating by partial fractions, we refer back the algebra idea of
fraction decomposition. We decompose a large fraction into smaller ones
that we can solve. When looking at the decomposition of partial
fractions we look a the factor in the denominator then we can infer the
term in the partial fraction.

Here is the correlation between the factor in the denominator and the
term in the partial fraction decomposition

1.  $ax+b \quad \Rightarrow \quad \frac{A}{ax+b}$

2.  $(ax+b)^k \quad \Rightarrow \quad \frac{A_1}{ax+b}+\frac{A_2}{(ax+b)^2}+...+\frac{A_k}{(ax+b)^k}$

3.  $ax^2+bx+c \quad \Rightarrow \quad \frac{Ax+B}{ax^2+bx+c}$

4.  $(ax^2+bx+c)^k \quad \Rightarrow \quad \frac{A_1x+B_1}{ax^2+bx+c}+\frac{A_2x+B_2}{(ax^2+bx+c)^2}+...+\frac{A_kx+B_k}{(ax^2+bx+c)^k}$

With these properties of partial fraction decomposition, when dealing
with integrals that require the use of partial fractions to solve, we
separate the function into simpler ones then we solve. This is best
shown by example, so lets look at some.

In all of these example, we are going to have to decompose the fraction.

1.  $\int \frac{2x+3}{x^2-9}dx$

2.  $\int \frac{3-x}{x(x^2+1)}dx$

3.  $\int \frac{cos(x)}{sin^3(x)+sin(x)}dx$

After decomposing the fraction we just split the integral and solve for
each of the fractions separately.

1.  $\int \frac{2x+3}{x^2-9}dx$\
    $$\begin{aligned}
    \int \frac{2x+3}{(x+3)(x-3)}dx \\
    \int (\frac{A}{x+3}+\frac{B}{x-3}) dx \\
    A(x-3)+B(x+3)=2x+3 \\
    A = \frac{1}{2} \quad \quad B=\frac{3}{2} \\
    \int (\frac{\frac{1}{2}}{x+3}+\frac{\frac{3}{2}}{x-3})dx \\
    \frac{1}{2}ln|x+3|+\frac{3}{2}ln|x-3|+c\end{aligned}$$

2.  $\int \frac{3-x}{x(x^2+1)}dx$\
    $$\begin{aligned}
    \int (\frac{A}{x}+\frac{Bx+C}{x^2+1})dx \\
    A(x^2+1)+(Bx+C)x=3-x \\
    A= 3 \quad \quad B=-3 \quad \quad C=-1 \\
    \int (\frac{3}{x}+\frac{-3x-1}{x^1})dx \\
    \int (\frac{3}{x}+\frac{-3x}{x^2+1}+\frac{-1}{x^2+1}) dx \\
    3ln|x|-\frac{3}{2}ln|x^2+1|-tan^{-1}(x)+c\end{aligned}$$

3.  $\int \frac{cos(x)}{sin^3(x)+sin(x)}dx$\
    $$\begin{aligned}
    u = sin(x) \quad \quad du=cos(x)dx \\
    \int \frac{1}{sin^3(x)+sin(x)}cos(x) dx \\
    \int \frac{1}{u^3+u} du \\
    \int \frac{1}{u(u^2+1)}du \\
    \int (\frac{A}{u}+\frac{Bu+c}{u^2+1})du
    A(u^2+1)+(Bu+C)u=1 \\
    A=1 \quad \quad B=-1 \quad \quad C=0 \\
    \int (\frac{1}{u}+\frac{-u}{u^2+1})du \\
    ln|u|-\frac{1}{2}ln|u^2+1|+c \\
    ln|sin(x)|-\frac{1}{2}ln|sin^2x+1|+C\end{aligned}$$

Simpson's Rule
--------------

Simpsons rule is an approximation method. Just like Newton's method (an
approximation method we learned in calculus 1), values outputed are
estimates, not the exact number.

To solve, the definite integral is split into an even number of
intervals, \"n\". Each of those intervals has the width,
$$\Delta x = \frac{b-a}{n}$$

Then we estimate using,

$$\int^{b}_{a} f(x)dx \approx \frac{\Delta x}{3} [f(x_0)+4f(x_1)+2f(x_2)+4f(x_3)+2f(x_4)+...+4f(x_{n-1})+f(x_n))]$$

That being said, this is that patter that follows,

$$1,4,2,4,2,...,4,2,4,1$$

Now lets work on one example to depict this estimation method,

Solve the following using Simpson's rule.

1.  $\int^{10}_{2} x^3 dx \quad \quad n=4$

Using Simpson's approximation method, we just derive our values and plug
them into the formula.

1.  $\int^{10}_{2} x^3 dx \quad \quad n=4$\
    $$\begin{aligned}
    \Delta x = \frac{10-2}{4} = 2 \\
    S_4 = \frac{2}{3}[f(2)+4f(4)+2f(6)+4f(8)+f(10)] \\
    S_4 = \frac{2}{3}[8+4(64)+2(216)+4(512)+1000] \\
    S_4 = 2496\end{aligned}$$

Improper Integrals
------------------

### Infinite Interval

An infinite integral is an integral that is in the form of,

$$\int^{\infty}_{1} \frac{1}{x} dx \quad \quad \text{or} \quad \quad \int^{10}_{- \infty} \frac{1}{x} dx \quad \quad \text{or} \quad \quad \int^{\infty}_{- \infty} \frac{1}{x}dx$$

Now lets look at how we can deal with such integrals,

1.  $\int^{\infty}_{a} f(x)dx = \lim_{t \rightarrow \infty} \int^{t}_{a}f(x)dx$

2.  $\int^{b}_{- \infty} f(x)dx = \lim_{t \rightarrow - \infty} \int^{b}_{t} f(x)dx$

3.  $\int^{\infty}_{- \infty} f(x)dx = \int^{c}_{- \infty} f(x)dx + \int^{\infty}_{c} f(x)dx$

The functions must be continuous in the interval and the limits must
exist and converge.

### Convergence

Now just a quick refresher on convergence.

If the limit/sum etc of a function approaches a finite number then we
say the limit/sum etc is convergent.

If the limit/sum etc of a function doesn't approach a finite number
(approaches $\infty \quad \text{or} \quad - \infty$ or undefined) we say
that the limit/sum etc is divergent.

### Discontinuity

Again referring back to a calculus 1 idea, we know that integrals have
to be continuous on there intervals in order for us to solve them. When
there is a discontinuity in the interval, we have an improper fraction.
That being said lets look at some properties that deal with the
discontinuity in some intervals,

1.  If f(x) is not continuous on the upper-bound of the interval then,
    $$\int^{b}_{a}f(x) dx = lim_{t \rightarrow b^-} \int^{t}_{a} f(x)dx$$

2.  If f(x) is not continuous on the lower-bound of the interval then,
    $$\int^{b}_{a}f(x) dx = lim_{t \rightarrow a^+} \int^{b}_{t} f(x)dx$$

3.  If f(x) is not continuous on a point that is bound inside the
    interval then,
    $$\int^{b}_{a}f(x)dx=\int^{c}_{a}f(x)dx+\int^{b}_{c} f(x)dx$$

### Examples

Now lets look at some examples,

1.  $\int^{1}_{0}\frac{1}{x^2}dx$

2.  $\int^{4}_{0} \frac{1}{\sqrt{4-x}}dx$

```{=html}
<!-- -->
```
1.  $\int^{1}_{0}\frac{1}{x^2}dx$\
    $$\begin{aligned}
    \lim_{t \rightarrow 0^+} \int^{1}_{t} \frac{1}{x^2}dx \\
    \lim_{t \rightarrow 0^+} \frac{-1}{x}]^{1}_{t} = \frac{-1}{1}+\lim_{t \rightarrow 0^+} (\frac{1}{t}) \\
    -1+\infty \\
    \infty \quad \quad \text{This integral is divergent}\end{aligned}$$

2.  $\int^{4}_{0} \frac{1}{\sqrt{4-x}}dx$\
    $$\begin{aligned}
    lim_{t \rightarrow 4^-} \int^{t}_{0} \frac{1}{\sqrt{4-x}} dx \\
    u = 4-x \quad \quad du = -dx \quad \quad -du =dx \\
    -\int \frac{1}{\sqrt{u}} du \\
    = -2\sqrt{u}\\
    = -2 \sqrt{4-x} \\
    lim_{t \rightarrow 4^-} -2\sqrt{4-x}]^{t}_{0} \\
    lim_{t \rightarrow 4^-} [-2\sqrt{4-t}]+[2\sqrt{4}] \\
    4 \quad \quad \text{Converges}\end{aligned}$$