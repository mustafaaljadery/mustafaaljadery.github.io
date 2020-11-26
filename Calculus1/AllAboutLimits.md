All About Limits
================

In this chapter we are going to start talking about 1 of the 3
fundamental ideas behind calculus. The limit I would say is the most
important out of the 3 since the other two rely on the limit.

Introducing The Limit
---------------------

### Introduction

Before we get into the notation of the limit and how to solve limits, we
need to discuss what limits are. Limits deal with approach, as the
values of a function get larger and larger what happens to the function,
or as the values of a function get smaller and smaller what happens to a
function? Limits have many applications in calculus, the fundamental
idea of rate of change using limits is the derivative, while the idea of
infinitesimally small rectangles added together is the integral. Since
we are going to start talking about derivatives first, we are going to
work with Rates of Change, and in time we are going to be looking at
Integrals.

### Rate Of Change

Rate of Change is slope. In algebra everyone learned about slope,
$slope=\frac{rise}{run}$. Rate of change is the same exact idea, the
only difference between what we learned in algebra and what we are going
to be learning in calculus, is that in calculus we are going to be able
to find the slope of a curve at a point while in algebra slope was
always constant throughout the graph (the graphs were linear).

In order to find the rate of change, we use the same formula we used in
algebra.

$$slope=\frac{y_2-y_1}{x_2-x_1}$$

Now the question is how can we find the slope of an exact point on a
curve?

The best way to describe, our rate of change at an exact point, is to
look at it visually.

\*\*Visual Representation Available Only on the pdf\*\*

When looking at the slope of a curve, we can see that at each point
there is a different slope. All of the graphs of functions before this,
we saw that the slope is constant at every point, the slope never
change; however, the idea behind rates of change in calculus is that the
slope is different at each point. Again going back to the question, how
can we find the slope of an exact point on a nonlinear curve?

In order to find the slope of a point on a curve, you pick another point
that is really really close to that point and use the rate of change
formula.

For example, if we want to find the rate of change of a curve at
$f(4)=9$ we pick a value of a, that is really small say, 0.0001 and we
use the rate of change formula as follows
$$\frac{f(x+a)-f(x)}{x+a-x} \quad \Rightarrow \quad \frac{f(x+a)-f(x)}{a}$$

$f(x+a)$ is very close to $f(x)$, as we said \"a\" = a very small value.
This infinitesimally small change is going to be a the key to an
accurate slope at the point we are referring to.

### Limit Notation

To simplify our idea of rates of change we use limit notation.

Simple Definition Of Limit. A limit is the value that a function
\"approaches\" (y-values) as the domain approaches some other value
(x-values). Both sides of the function have to approach the same value
in order for the limit to exist.

Note that we only care about what happens when the values approach the
value, we don't care about what happens at the value.

Also note, this is not the precise definition of a limit, the precise
definition of a limit will be discussed later. However, this is the
common definition of a limit that is referred to when talking about
limits.

This is best looked at in some examples.

Solve each the following.

1.  $\displaystyle{\lim_{x \to -3}=\frac{x^2+6x+9}{x^2+3x}}$

2.  $\displaystyle{\lim_{x \to 1}=\frac{-x^2+10x-9}{x^2-1}}$

3.  $\displaystyle{\lim_{x \to 0}=\frac{2-\sqrt{4+2x}}{x}}$

In order to solve each of these examples, we use a table and plug in
values closer and closer to what the limit whats us to evaluate and see
if they match from both sides.

1.  $\displaystyle{\lim_{x \to -3} \frac{x^2+6x+9}{x^2+3x}}$\

      --------- ----------------- --------- ---------------
        **x**       **f(x)**        **x**      **f(x)**
        -2.5          -0.2          -3.5     0.1428571429
        -2.9     -0.03448275862     -3.1     0.03225806452
        -2.99    -0.003344481605    -3.01    0.0033222591
       -2.999     -0.0003334444    -3.001    0.0003332222
       -2.9999   -0.00003333444    -3.0001   0.00003333222
      --------- ----------------- --------- ---------------

    $$\displaystyle{\lim_{x \to -3} \frac{x^2+6x+9}{x^2+3x}}=0$$ As the
    values get closer and closer to -3, the output gets closer and
    closer to 0 .

2.  $\displaystyle{\lim_{x \to 1} \frac{-x^2+10x-9}{x^2-1}}$\

      -------- ------------- -------- --------------
       **x**     **f(x)**     **x**      **f(x)**
        1.5          3         0.5     0.1428571429
        1.1     3.761904762    0.9     4.263157895
        1.01    3.975124378    0.99    4.025125628
       1.001    3.997501249   0.999    4.002501251
       1.0001   3.999750012   0.9999   4.000250013
      -------- ------------- -------- --------------

    $$\displaystyle{\lim_{x \to 1} \frac{-x^2+10x-9}{x^2-1}}=4$$

3.  $\displaystyle{\lim_{x \to 0} \frac{2-\sqrt{4+2x}}{x}}$\

      -------- --------------- --------- ---------------
       **x**      **f(x)**       **x**      **f(x)**
        0.5     -0.472135955     -0.5     -0.5358983849
        0.1     -0.4939015319    -0.1     -0.5064113104
        0.01    -0.4993765576    -0.01    -0.5006265674
       0.001    -0.4999375156   -0.001    -0.5000625156
       0.0001   -0.4999937501   -0.0001   -0.5000062502
      -------- --------------- --------- ---------------

    $$\displaystyle{\lim_{x \to 0} \frac{2-\sqrt{4+2x}}{x}}=-0.5$$

Computing Limits
----------------

In the previous section, we introduced the limit and we saw one method
of computing limits, using a table. Two other common ways of computing
limits are direct substitution and graphing them.

In this section, we are going to focus on direct substitution. In order
to use our method of direct substitution, our function must be
continuous, we are going to define continuous in another section but for
know we are going to only being dealing with continuous functions. Later
on, we are going to look at both continuous functions and non continuous
functions.

Here are the properties of limits what will use to solve limits for now.

Here are common properties of limits.

1.  $\displaystyle{\lim_{x \to a} c=c}$

2.  $\displaystyle{\lim_{x \to a} x=a}$

3.  $\displaystyle{\lim_{x \to a} [f(x)+g(x)]=\lim_{x \to a} f(x) + \lim_{x \to a} g(x)}$

4.  $\displaystyle{\lim_{x \to a} [f(x)-g(x)]=\lim_{x \to a} f(x)-\lim_{x \to a} g(x)}$

5.  $\displaystyle{\lim_{x \to a} [cf(x)]=x\lim_{x \to a} f(x)}$

6.  $\displaystyle{\lim_{x \to a} [f(x)g(x)] = \lim_{x \to a} f(x) \lim_{x \to a} g(x)}$

7.  $\displaystyle{\lim_{x \to a} \frac{f(x)}{g(x)}=\frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}}$\
    Note that $\displaystyle{\lim_{x \to a}g(x)\neq 0}$.

8.  $\displaystyle{\lim_{x \to a} [f(x)]^n=(\lim_{x \to a} f(x))^n}$

Using these properties, lets look at some examples.

Compute each of the following.

1.  $\displaystyle{\lim_{x \to 4} (3x^2-9x+2)}$

2.  $\displaystyle{\lim_{x \to 0} (x^4-4x^2+12x-8)}$

3.  $\displaystyle{\lim_{x \to 2} \frac{10+x^2}{3-4x}}$

4.  $\displaystyle{\lim_{x \to -3} \frac{x^3-20x+4}{x^2+8x-1}}$

5.  $\displaystyle{\lim_{x \to -6} \sqrt[3]{7x+8}}$

Using our properties we can easily compute.

1.  $\displaystyle{\lim_{x \to 4} (3x^2-9x+2)}$\
    $$\begin{aligned}
    \lim_{x \to 4} 3x^2 -\lim_{x \to 4} 9x + \lim_{x \to 4} 2 \\
    3\lim_{x \to 4} x^2 - 9\lim_{x \to 4} x + 2 \\
    3(4)^2-9(4)+2 \\
    3(16)-36+2 \\
    48-36+2 \\
    \boxed{\lim_{x \to 4} (3x^2-9x+2)=14}\end{aligned}$$

2.  $\displaystyle{\lim_{x \to 0} (x^4-4x^2+12x-8)}$\
    $$\begin{aligned}
    \displaystyle{\lim_{x \to 0} x^4 - \lim_{x \to 0} 4x^2 + \lim_{x \to 0} 12x - \lim_{x \to 0} 8} \\
    \displaystyle{\lim_{x \to 0} x^4 -4\lim_{x \to 0} x^2 + 12\lim{x \to 0} t - 8} \\
    \displaystyle{(0)^4-4(0)^2+12(0)-8} \\
    \boxed{\displaystyle{\lim_{x \to 0} (x^4-4x^2+12x-8)=-8}}\end{aligned}$$

3.  $\displaystyle{\lim_{x \to 2} \frac{10+x^2}{3-4x}}$\
    $$\begin{aligned}
    \displaystyle{\frac{\lim_{x \to 2} 10+x^2}{\lim_{x \to 2} 3-4x}} \\
    \displaystyle{\lim_{x \to 2} 10+x^2 = 10+(2)^2} \\
    \displaystyle{\lim_{x \to 2} 10+x^2=14} \\
    \displaystyle{\lim_{x \to 2} 3-4x=3-4(2)} \\
    \displaystyle{\lim_{x \to 2}=5} \\
    \boxed{\displaystyle{\lim_{x \to 2} \frac{10+x^2}{3-4x}=\frac{14}{5}}}\end{aligned}$$

4.  $\displaystyle{\lim_{x \to -3} \frac{x^3-20x+4}{x^2+8x-1}}$\
    $$\begin{aligned}
    \displaystyle{\frac{\lim_{x \to -3} x^3-20x+4}{\lim_{x \to -3} x^2+8x-1}} \\
    \displaystyle{\lim_{x \to -3} x^3-20x+4 = \lim_{x \to -3} x^3 -20 \lim_{x \to -3 } x +4} \\
    \displaystyle{(-3)^3-20(-3)+4} \\
    -27+60+4 \\
    \displaystyle{\lim_{x \to -3} x^3-20x+4=37} \\
    \displaystyle{\lim_{x \to -3} x^2+8x-1=\lim_{x \to -3} x^2 +\lim_{x \to -3} 8x-1} \\
    (-3)^2+8(-3)-1 \\
    9-24-1 \\
    \displaystyle{\lim_{x \to -3} x^2+8x-1=-16} \\
    \boxed{\displaystyle{\lim_{x \to -3} \frac{x^3-20x+4}{x^2+8x-1}=\frac{37}{-16}}}\end{aligned}$$

5.  $\displaystyle{\lim_{x \to -6} \sqrt[3]{7x+8}}$\
    $$\begin{aligned}
    \displaystyle{\lim_{x \to -6} (7x+8)^{\frac{1}{3}}} \\
    \displaystyle{(\lim_{x \to -6} 7x+8)^{\frac{1}{3}}} \\
    \displaystyle{(7(-6)+8)^{\frac{1}{3}}}
    (-42+8)^\frac{1}{3} \\
    -34^\frac{1}{3}=-3.23961180 \\
    \displaystyle{\lim_{x \to -6} \sqrt[3]{7x+8}=-3.23961180}\end{aligned}$$

If you have been paying attention to these examples, you can see that
you can get the same answer if we just plug in whats in the limit to the
original equation; however, there are limitations to this that we are
going to discuss in the last section of this chapter.

One-Sided Limits
----------------

One sided limits are limits that approach a value from one side only.
For example, in the first section for this chapter, our computing method
was the table. When using the table we used values from both sided of
the limit (review if you are confused). In one-sided limits we use
values from only one side of the limit.

Right-Valued Limits. If x approaches a from the right side (values
greater than a) then the function is a right valued/handed limit.
$$\lim_{x \to a^{+}} f(x)=L$$

Left-Valued Limits. If x approaches a from the left side (values less
than a) then the function is a left valued/handed limit.
$$\lim_{x \to a^{-}} f(x)=L$$

1.  $\text{If } \displaystyle{\lim_{x \to a^{-}} f(x)=\lim_{x \to a^{+}} f(x)} \text{ then, } \displaystyle{\lim_{x \to a} f(x)} \text{ exists.}$

2.  $\text{If } \displaystyle{\lim_{x \to a} f(x) \text{ exists, then } \displaystyle{\lim_{x \to a^{+}} f(x)= \lim_{x \to a^{-}} f(x)}}$

Limits at Infinity
------------------

### Infinite Limits

Infinite limits are in the form of:

$$\lim_{x \to a} f(x)=\pm \infty$$

This also holds true for left/right valued limits.

Infinite Limits. If values of x increase without a bound then it is said
that we have an infinite limit.

Lets take a look at an important example.

Solve the following

1.  $\displaystyle{\lim_{x \to 0^{+}} \frac{1}{x}}$

2.  $\displaystyle{\lim_{x \to 0^{-}} \frac{1}{x}}$

3.  $\displaystyle{\lim_{x \to 0} \frac{1}{x}}$

We are going to have to use a table.

1.  $\displaystyle{\lim_{x \to 0^{+}} \frac{1}{x}}$\

      -------- ----------
       **x**    **f(x)**
         1         1
        0.1        10
        0.01      100
       0.001      1000
       0.0001    10000
      -------- ----------

    $$\lim_{x \to 0^{+} \frac{1}{x}= +\infty}$$

2.  $\displaystyle{\lim_{x \to 0^{-}} \frac{1}{x}}$\

      --------- --------
          x       f(x)
         -1        -1
        -0.1      -10
        -0.01     -100
       -0.001    -1000
       -0.0001   -10000
      --------- --------

    $$\lim_{x \to 0^{-}} \frac{1}{x}=-\infty$$

3.  $\displaystyle{\lim_{x \to 0} \frac{1}{x}}$\
    Since the right and left limits don't output the same value, the
    limit does not exist.

A really important thing to note is that if you look at the example
above, if we just plugged in 0 to our denominator then we would get
undefined, however when we used the table we got a value. In the next
section when we introduce continuity, we will talk about which functions
allow direct substitutions and which ones you have to graph or use a
table.

Infinite Limits have a vertical asymptote.

### Limits At Infinity

Limits at infinite take the form of\":

$$\lim_{x \to \infty} f(x) \quad \quad \lim_{x \to -\infty} f(x)$$

This is very different form what we learned before. Before this we
learned that as x approaches a certain values, our outputs get
infinitely bigger or infinitely smaller. Here it is different, we are
making x either as big as possible, or as small as possible.

Important:
$$\lim_{x \to \pm \infty} \frac{c}{x}=0 \quad \quad \lim_{x \to \pm \infty} \frac{x}{c}=\pm \infty$$
C = Any Constant.

Using this property lets look at some examples.

1.  $\displaystyle{\lim_{x \to \infty} -11x^5+9x^3+8x}$

2.  $\displaystyle{\lim_{x \to -\infty} \frac{10x^3-6x}{7x^3+9}}$

3.  $\displaystyle{\lim_{x ]to \infty} \frac{\sqrt{8+11x^2}}{-9-x}}$

```{=html}
<!-- -->
```
1.  $\displaystyle{\lim_{x \to \infty} -11x^5+9x^3+8x}$\
    $$\begin{aligned}
    \lim_{x \to \infty} x^5(-11+\frac{9}{x^2}+\frac{8}{x^4}) \\
    \infty(-11+0+0) \\
    \boxed{\lim_{x \to \infty} -11x^5+9x^3+8x=- \infty}\end{aligned}$$

2.  $\displaystyle{\lim_{x \to -\infty} \frac{10x^3-6x}{7x^3+9}}$\
    $$\begin{aligned}
    \frac{x^3(10-\frac{6}{x^2})}{x^3(7)+\frac{9}{x^3}} \\
    \frac{10}{7} \\
    \boxed{\lim_{x \to -\infty} \frac{10}{7} = \frac{10}{7}}\end{aligned}$$

3.  $\displaystyle{\lim_{x \to \infty} \frac{\sqrt{8+11x^2}}{-9-x}}$\
    $$\begin{aligned}
    \frac{\sqrt{x^2(11+\frac{8}{x^2})}}{-x(1+\frac{9}{x})} \\
    \frac{x(\sqrt{11+\frac{8}{x^2}})}{-x(1+\frac{9}{x})} \\
    \frac{-\sqrt{11+\frac{8}{x^2}}}{1+\frac{9}{x}} \\
    \boxed{\lim_{x \to \infty} \frac{-\sqrt{11+\frac{8}{x^2}}}{1+\frac{9}{x}}=\frac{-\sqrt{11}}{1}=-\sqrt{11}}\end{aligned}$$

Note that you couldn't just plug in infinity and add and subtract
infinite. Infinite is not a real number so doing such a thing is not
possible. In order to solve these types of equations you have to factor
and use the two properties listed above.

Continuity
----------

### Continuous Functions

Continuity is the biggest topic when discussing limits. If a function is
continuous on an interval, we just use direct substitution to solve. We
substitute the value of the value of x the limit is approaching to all
values of x in the function.

Continuity. A continuous function is a function that does hold any
abrupt changes in values. Those abrupt changes are also referred to as
discontinuities.

Graphically, a continuous function is a function that is never broken on
the graph. The graph has no holes or vertical asymptotes that affect the
interval in which the function is graphed.

As a result, if we know that a function is continuous on the interval we
are working on then, $$\lim_{x \to a} f(x)=f(a)$$

Finally, an important skill is finding where a certain function is
discontinuous. Functions are discontinuous when points are undefined.

Lets work on some examples,

Solve each of the following using our understanding of continuity and
direct substitutionm.

1.  $\displaystyle{\lim_{x \to 3} \frac{6+2x}{7x-14}}$

2.  $\displaystyle{\lim_{x \to -5} \frac{5x-20}{x^2-12x}}$

3.  $\displaystyle{\lim_{x \to -7} \frac{4x+1}{5\cos(\frac{x}{2})+1}}$

```{=html}
<!-- -->
```
1.  $\displaystyle{\lim_{x \to 3} \frac{6+2x}{7x-14}}$\
    $$\begin{aligned}
    \frac{6+2(3)}{7(3)-14} \\
    \lim_{x \to 3} \frac{6+2x}{7x-14} = \frac{12}{7}\end{aligned}$$

2.  $\displaystyle{\lim_{x \to -5} \frac{5x-20}{x^2-12x}}$\
    $$\begin{aligned}
    \frac{5(-5)-20}{(-5)^2-12(-5)} \\
    \lim_{x \to -5} \frac{5x-20}{x^2-12x}= \frac{-45}{75}=\frac{-3}{5}\end{aligned}$$

3.  $\displaystyle{\lim_{x \to -7} \frac{4x+1}{5\cos(\frac{x}{2})+1}}$\
    $$\begin{aligned}
    \frac{4(-7)+1}{5\cos(\frac{-7}{2})+1} \\
    \frac{-27}{5(-0.9364566873)+1} \\
    \lim_{x \to -7} \frac{4x+1}{5\cos(\frac{x}{2})+1}=7.33240677\end{aligned}$$

### Intermediate Value Theorem

Intermediate Value Theorem. If a function f(x) is continuous in an
interval \[a,b\], then there is a value of $f(c)$ where
$f(a) < f(c) < f(b)$ and $a<c<b$.

This theorem is best shown by example.

Show that at least one solution exists in the interval, using the
intermediate value theorem.

1.  $1+7x^3-x^4=0 \text{ on } [4,8]$

2.  $x^2+11x=3 \text{ on } [-15,5]$

```{=html}
<!-- -->
```
1.  $1+7x^3-x^4=0 \text{ on } [4,8]$\
    $$\begin{aligned}
    f(4)= 1+7(4)^3-(4)^4 \\
    f(4)=193 \\
    f(6)=6 \\
    f(8)=1+7(8)^3-(8)^4 \\
    f(8)=-511 \\
    -511<6<193 \\
    \text{proven, f(6) is a solution}\end{aligned}$$

2.  $x^2+11x=3 \text{ on } [-15,5]$\
    $$\begin{aligned}
    f(-15)=(-15)^2+11(-15)-3 \\
    f(-15)=720 \\
    f(0)=0 \\
    f(5)=(5)^2+11(5)-3 \\
    f(5)=-140 \\
    -140 <0<720 \\
    \text{proven, f(0) is a solution}\end{aligned}$$

### Precise Definition Of The Limit

In this particular book, we are not going to go in depth on the precise
definition of the limit for multiple reasons. 1. Proof of the limit is
impractical in this class. Most limits are going to be solved using
direct substitution and the ones that cant use direct substitution will
either be solved by looking at a graph or making a table. 2. Leaving the
proof to a higher math class (Introduction to Proofs, Real Analysis)
will really show the beauty of the proof.

However, I am going to definite it here.

Statement: $\displaystyle{\lim_{x \to a} f(x)=L}$. Given any real number
$\epsilon >0$, there exists another real number $\delta >0$ so that,
$$\text{if } 0>|x-a|<\delta,then |f(x)-L|<\epsilon$$