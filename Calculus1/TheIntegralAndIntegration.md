The Integral + Integration
==========================

This sections is the third key concept in calculus. This concept is
fundamental to calculus as through the fundamental theorem of calculus
it connects with the derivative. This concept in fact is so important
that most of calculus 2 focuses on it.

The Idea Behind Integrals
-------------------------

Integrals are the least fundamental idea of calculus that we are going
to learn in calculus 1. In essence an integral is the area under a
curve. You might be thinking, we do we need to introduce something new
don't we already know how to find the area under shapes? While that's
true, that only for some certain shapes, we cant find the area under
$3x^3+58x-3$ (as of right now), but we can find the area of a rectangle
($A=length*width$). So to recap, the fundamental idea on why we would
use an integral, is to find the area.

Lets start by an intuitive understanding of what it really means to find
the area under a curve for us,

\*\*Graphic Is Only Available On the Pdf\*\*

What we are going to be doing when finding the integral is we are going
to split the curve under our function into small rectangles (the smaller
the rectangles, the more precise our graph is going to be), and then
calculate the area of those rectangles to find out the area under a
curve.

The formula for finding the area is called the riemann sum and is
denoted by,
$$\int_{a}^{b} f(x) \,dx = \lim_{n \Rightarrow \infty} \sum_{i=0}^{n-1} f(x_i) \Delta x$$

Explaining this a bit, the limit sign indicates that we are going to
split the area into an infinite number of rectangles. As we said before,
the more rectangles, the more accurate our result is going to be. The
sum is to add all of rectangles so we can get the area of the whole
curve instead of only one rectangle and finally, the arguments are the
positions of the rectangles. We denote the area with the integral sign,

$$\int f(x)\,dx$$

Indefinite Integral
-------------------

Lets talk more about integrals and how we can compute them.

Another name for integrals are anti-derivatives. What is nice about
integrals is that they undo derivatives thus the name anti-derivative.

This means we can define them as the following,

Assume we have a function $f(x)$, the derivative of the function is
denoted as $f^{\prime}(x)$.

Then the integral (or the anti-derivative of the function) of
$f^{\prime}(x)$ is denoted by the following,

$$\int f^{\prime}(x)=f(x)+c$$

This is called the indefinite integral.

The c at the end is any constant and you need it at the end of your
integration because if you think about it since the integral is the
anti-derivative, when you take the derivative of any constant, the
constant disappears so when taking the anti-derivative it's only right
that we use a constant to denote any number we can add to the end of our
integration.

Now lets take a look at some of the properties of integrals before we
look at solving some,

1.  $\int kf(x),dx = k\int f(x),dx \quad \quad \text{k is a constant}$

2.  $\int -f(x),dx = -\int f(x),dx$

3.  $\int f(x) \pm g(x),dx = \int f(x),dx \pm \int g(x),dx$

Finally lets work on some examples,

Compute the following indefinite integrals.

1.  $\int 10x^9 -12x^3-5,dx$

2.  $\int t^7+33t^2+8t,dt$

3.  $\int 6x^5-7x^3+12x^2-10,dx$

To solve these we just go backwards.

1.  $\int 10x^9 -12x^3-5,dx$\
    $$\begin{aligned}
    = x^10-3x^4-5x+c\end{aligned}$$

2.  $\int t^7+33t^2+8t,dt$\
    $$\begin{aligned}
    = \frac{1}{8}t^8+11t^3+4t^2+c\end{aligned}$$

3.  $\int 6x^5-7x^3+12x^2-10,dx$\
    $$\begin{aligned}
    =x^6-\frac{7}{4}x^4+4x^3-10x+c\end{aligned}$$

Finally we are going to look at some common integrals that we are going
to use a lot in this class and subsequent classes,

1.  $\int \sin(x),dx = -\cos(x)+c$

2.  $\int \sec^2(x),dx = \tan(x)+c$

3.  $\int \csc^2(x),dx = -\cot(x)+c$

4.  $\int \cos(x),dx = \sin(x)+c$

5.  $\int \sec(x) \tan(x),dx = \sec(x)+c$

6.  $\int \csc(x) \cot(x),dx = - \csc(x)+c$

7.  $\int e^x,dx = e^x+c$

8.  $\int a^x,dx = \frac{a^x}{ln(a)}+c$

9.  $\int \frac{1}{x}=ln|x|+c$

10. $\int \frac{1}{x^2+1},dx = \tan^{-1}(x)+c$

11. $\int \frac{1}{\sqrt{1-x^2}}=sin^{-1}(x)+c$

12. $\int \sinh(x),dx = cosh(x)+c$

13. $\int sech^2(x),dx = \tanh(x)+c$

14. $\int csch^2(x),dx= -\coth(x)+c$

15. $\int \cosh(x),dx = \sinh(x)+c$

16. $\int sech(x) tanh(x),dx = -sech(x)+c$

17. $\int csch(x) coth(x),dx = - csch(x)+c$

Lets work on some examples with these integrals,

Solve the following integrals from the common integrals we learnt about
above.

1.  $\int e^t + \frac{2}{t},dt$

2.  $\int \frac{14}{x}-\frac{3}{x^2},dx$

3.  $\int 6t^3+8t^{-6}+t^{-10},dt$

This is the same integration we did before.

1.  $\int e^t + \frac{2}{t},dt$\
    $$\begin{aligned}
    \int e^t, dt + \int \frac{2}{t},dt \\
    \int e^t, dt + 2\int \frac{1}{t},dt \\
    = e^t +2ln|t|+c\end{aligned}$$

2.  $\int \frac{14}{x}-\frac{3}{x^2},dx$\
    $$\begin{aligned}
    14 \int \frac{1}{x},dx - 3\int  \frac{1}{x^2},dx \\
    = 14ln|x| + \frac{3}{x}\end{aligned}$$

3.  $\int 6t^3+8t^{-6}+t^{-10},dt$\
    $$\begin{aligned}
    =\frac{6}{4}t^4-40t^{-5}-\frac{1}{9}t^{-9}\end{aligned}$$

Solving Indefinite Integrals By Substitution
--------------------------------------------

Ok, we go introduced to the idea of integrals and the area problem. Now
the method we used above works, but not for all integrals, what if we
have the following integral, $$\int \sqrt{9x+3},dx$$

Do we just give up and not do math again? Nope, we use a substitution to
solve the following integral.

Substitution Rule Identity of differentials, $$du = u^{\prime}dx$$ Note:
u is a function of x. Since we know this identity, we can write it as,
$$\int f(u)u^{\prime},dx=\int f(u),du$$ Finally this can be written as,
$$\int f(g(x))g^{\prime}(x),dx= \int f(u),du$$

This rule is best shown by example, lets look at a couple.

Solve the following indefinite integrals using substitution rule.

1.  $\int 12x(7+6x^2)^9,dx$

2.  $\int (4x^3-12x)(x^4-6x^2)^{-3},dx$

3.  $\int (\cos(x)+\sin(x))e^{\sin(x)-\cos(x)},dx$

4.  $\int \cos(7t),dt$

We just apply what we learnt.

1.  $\int 12x(7+6x^2)^9,dx$\
    $$\begin{aligned}
    u=7+6x^2 \\
    du = 12x (dx) \\
    \frac{du}{12x} = dx \\
    \int 12x(u)^9 \frac{du}{12x} \\
    \int u^9, du \\
    \frac{1}{10}u^10+c \\
    \frac{1}{10}(7+6x^2)^10 +c\end{aligned}$$

2.  $\int (4x^3-12x)(x^4-6x^2)^{-3},dx$\
    $$\begin{aligned}
    u = x^4-6x^2  \\
    du = 4x^3-12x dx \\
    \frac{du}{4x^3-12x} =dx \\
    \int (4x^3-12x)u^{-3} \frac{du}{4x^3-12x} \\
    \int u^{-3} \\
    -\frac{1}{2}u^{-2} +c \\
    -\frac{1}{2}(x^4-6x^2)^{-2} +c\end{aligned}$$

3.  $\int (\cos(x)+\sin(x))e^{\sin(x)-\cos(x)},dx$\
    $$\begin{aligned}
    u = sin(x)-cos(x) \\
    du = cos(x)+sin(x) dx \\
    \frac{du}{cos(x)+sin(x)} =dx \\
    \int \cos(x)+\sin(x)e^u \frac{du}{\cos(x)+\sin(x)} \\
    \int e^u \\
    e^{\cos(x)+\sin(x)} +c\end{aligned}$$

4.  $\int \cos(7t),dt$\
    $$\begin{aligned}
    u = 7t \\
    du = 7dt\\
    \frac{du}{7} = dt \\
    \frac{1}{7} \int cos(u), du \\
    \frac{1}{7} sin(u) +c \\
    \frac{1}{7} sin(7t)+c\end{aligned}$$

The most important thing to note from this section is that there are
still integral we cannot compute, a whole chapter in calculus 2 is
focused on more advanced methods of computing integrals.

Definite Integral
-----------------

Now that we have learnt how to compute some integrals, you might be
asking yourself how the area plays a role in this directly? The definite
integral is with the help of the Fundamental theorem of calculus, is
going to give us a solution to the area under a certain curve.

Definite Integral If a function f(x) is continuous on the interval
\[a,b\] then the definite integral of the function from a to b is,
$$\int_a^b f(x),dx = lim_{n \Rightarrow \infty} \Sigma^{n}_{i=0}f(x^{*}_{i})\Delta x$$

We are not going to look at any examples because solutions are better
found using the fundamental theorem of calculus. The next section is
going to dive deep in the properties and methods for solving definite
integrals. This section only introduces the idea of definite integrals.

Fundamental Theorem Of Calculus
-------------------------------

Now lets talk about the fundamental theorem of calculus,

Fundamental Theorem of Calculus If f is continuous on the interval
\[a,b\], and $F^{\prime}(x)=f(x)$, then
$$\int^{b}_{a} f(x),dx=F(b)-F(a)$$

The fundamental theorem of calculus is key here, in order to solve our
definite integrals, all we do is take the integral as if it were a
definite integral, then substitute a and b into the given function.
Finally, subtract the function with the a substitution from b.

Before we look at examples, lets look at some properties,

1.  $\int_{a}^{a}f(x),dx = 0$

2.  $\int_{a}^{b}kf(x),dx=k\int_{a}^{b}f(x),dx$

3.  $\int_{a}^{b} [f(x) \pm g(x)]dx=\int_{a}^{b}f(x)dx \pm \int_{a}^{b}g(x)dx$

4.  $\int_{a}^{b} f(x)dx = \int_{a}^{c} f(x),dx + \int_{c}^{b} f(x),dx \quad a<c<b$

5.  $\int_{a}^{b} f(x),dx = - \int_{b}^{a} f(x),dx \quad a<b$

Finally, lets look at some examples of indefinite integrals,

1.  $\int_{1}^{4} 5x-4,dx$

2.  $\int_{-3}^{4} \frac{8}{x^3},dx$

3.  $\int_{4}^{9} \sqrt{x},dx$

4.  $\int_{2}^{3} \frac{x^3-5x^2}{x},dx$

5.  $\int_{4}^{10} 7,dx$

```{=html}
<!-- -->
```
1.  $\int_{1}^{4} 5x-4,dx$\
    $$\begin{aligned}
    \frac{5}{2}x^2-4x]^{4}_{1} \\
    [\frac{5(4)^2}{2}-4(4)]-[\frac{5(1)^2}{2}-4(1)] \\
    40-16-\frac{5}{2}+4 \\
    \frac{51}{2}\end{aligned}$$

2.  $\int_{-3}^{4} \frac{8}{x^3},dx$\
    $$\begin{aligned}
    \int_{-3}^{4} 8x^{-3},dx \\
    -4x^{-2}]^{4}_{-3} \\
    (\frac{-4}{4^2})-(\frac{-4}{(-3)^2}) \\
    \frac{-1}{4} + \frac{4}{9} = \frac{7}{36}\end{aligned}$$

3.  $\int_{4}^{9} \sqrt{x},dx$ $$\begin{aligned}
    \frac{2x^{\frac{3}{2}}}{3}]^{9}_{4} \\
    (\frac{2(9)^{\frac{3}{2}}}{3})-(\frac{2(4)^{\frac{3}{2}}}{3}) \\
    \frac{2(27)}{3}-\frac{2(8)}{3}=\frac{54}{3}-\frac{16}{3} \\
    \frac{38}{3}\end{aligned}$$

4.  $\int_{2}^{3} \frac{x^3-5x^2}{x},dx$ $$\begin{aligned}
    \int_{2}^{3} x^2-5x,dx \\
    \frac{x^3}{3} - \frac{5x^2}{2}]^{3}_{2} \\
    (\frac{3^3}{3}-\frac{5(3)^2}{2})-(\frac{2^3}{3}-\frac{5(2)^2}{2}) \\
    9-\frac{45}{2}-(\frac{8}{3}-10) \\
    9-\frac{45}{2}-\frac{8}{3}+10 \\
    \frac{-37}{6}\end{aligned}$$

5.  $\int_{4}^{10} 7,dx$\
    $$\begin{aligned}
    7x]^{10}_{4} \\
    70-28=42\end{aligned}$$

Solving Definite Integrals By Substitution
------------------------------------------

This section, we are just going to jump to examples, we already know how
to use the substitution rule and we know have to compute definite
integrals, now we just combine the two ideas.

1.  $\int^{0}_{1} 10(1-2x^2)\sqrt[4]{7-3x+2x^3}dx$

2.  $\int^{1}_{0} x^2[x^3+5]^2,dx$

3.  $\int^{2}_{1} 4xe^{x^2},dx$

```{=html}
<!-- -->
```
1.  $\int^{0}_{1} 10(1-2x^2)\sqrt[4]{7-3x+2x^3}dx$\
    $$\begin{aligned}
    -\int^{1}_{0} 10(1-2x^2)\sqrt[4]{7-3x+2x^3}dx \\
    u = 7-3x+2x^3 \\
    du = 6x^2-3 (dx) \\
    \frac{du}{-3(-2x^2+1)} =dx
    -\int^{1}_{0} 10(1-2x^2)\sqrt[4]{u} \frac{du}{-3(-2x^2+1)} \\
    \frac{10}{3} \int^{1}_{0} \sqrt[4]{u} \\
    \frac{4}{5}u^{\frac{5}{4}}]^{1}_{0} \\
    \frac{4}{5}(7-3x+2x^3)^{\frac{5}{4}}]^{1}_{0} \\
    [\frac{4}{5}(6^{\frac{5}{4}})]-[\frac{4}{5}7^{\frac{5}{4}}] \\
    -1.596422\end{aligned}$$

2.  $\int^{1}_{0} x^2[x^3+5]^2,dx$\
    $$\begin{aligned}
    u= x^3 +5 \\
    du = 3x^2 dx \\
    \frac{du}{3x^2} = dx \\
    \int^{1}_{0} x^2[u]^2 \frac{du}{3x^2} \\
    \frac{1}{3} \int^{1}_{0} u^2 \\
    \frac{1}{9} u^3 +c\\
    \frac{1}{9} (x^3+5)^3 ]^{1}_{0} \\
    [\frac{1}{9} 6^3]-[\frac{1}{9} 5^3] \\
    \frac{91}{9}\end{aligned}$$

3.  $\int^{2}_{1} 4xe^{x^2},dx$\
    $$\begin{aligned}
    u = x^2 \\
    du = 2x dx \\
    \frac{du}{2x} = dx \\
    \int^{2}_{1} 4xe^{x^2} \frac{du}{2x} \\
    2 \int^{2}_{1} e^u \\
    2e^u +c \\
    2e^{x^2}]^{2}_{1} \\
    [2e^4]-[2e] \\
    103.7597364\end{aligned}$$
