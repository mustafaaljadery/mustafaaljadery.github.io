Function A function is a relationship between the set of inputs and
outputs, where every input has exactly one output.

Functions can be represented in multiple forms, from sets to graphs to
equations; The more common representation of functions in calculus are
equations and graphs. Any of the above forms of representation can be
functions, if and only if for every input there is only one unique
output. This is best shown by example.

Determine whether the following equations are functions or not. Explain
why.

1.  $$y=x^2$$

2.  $$3+y^2=12x$$

3.  $$y=2x^5-5x+13$$

In order to tell whether the equations are functions or not, we solve
for y. If for every unique input of x we get only one output of y then
it is a function.

1.  $$y=x^2$$ $$y=x^2 \quad \Rightarrow \quad f(x)=x^2$$ We can see that
    for every input of x, we get exactly one output of y. So from your
    definition we know that this equation is a function.

2.  $$3+y^2=12x$$ $$\begin{aligned}
    y^2=12x-3 \\
    \boxed{y= \pm \sqrt{12x-3}}\end{aligned}$$ A we can see here, this
    equation is not a function. For every input of x, we get 2 outputs
    of y (a positive value and a negative value).

3.  $$y=2x^5-5x+13$$
    $$y=2x^5-5x+13 \quad \Rightarrow \quad f(x)=2x^5-5x+13$$ As we can
    see, for every unique input of x we are going to get exactly one
    output y. Thus making this equation a function.

Domain and Range
----------------

The domain and range of a function correlate directly with the x input
and y output. Your domain is all of the possible *real inputs* for a
certain function, while the range is the set of all the outputs of a
function.

Real Inputs. We we talk about the domain of a function in calculus it is
implied that we are talking about the real domain. The real domain is is
the set of all real numbers (not imaginary or other forms of numbers).

Domain. The domain of a function is the set of all possible inputs in a
function; the set of inputs which the function is defined.

Range. The range of a function is the set of all possible outputs
achieved when all possible inputs are plugged into the function.

Our focus when dealing with domain and range should be the domain in
particular. The range is just the output after we specify our domain, so
the domain is what we should be playing attention to.

Domain Restriction. Domain restrictions are values the we plug into our
function that will either output a value that is not real or will output
undefined.

Here are the most common domain restrictions you will face in calculus:
$$\begin{aligned}
f(x) & =\frac{1}{x} \quad x \neq 0 \\
f(x) & =\sqrt{x} \quad x \geq 0 \\
f(x) & =\ln{x} \quad x \neq 0 \\
f(x) & = \log{x} \quad x \neq 0\end{aligned}$$

For the second domain restriction, its not only for $$\sqrt{x} \quad x<0$$
but for all even roots. For example,$$\sqrt[4]{x} \quad x <0$$ does NOT
output a real value (domain restriction). It is the same for
$$\sqrt[6]{x} \quad x<0$$\...

Lets look at some examples.

Find the domain of all the following equations.

1.  $$y=3x^2+9x-2$$

2.  $$x^2+2x$$

3.  $$\frac{1}{x-7}$$

4.  $$\frac{1}{\sqrt[4]{2x+8}}$$

Here we just try to find a possible domain restriction.\

1.  $$y=3x^2+9x-2$$ Not of the domain restriction we listed above are
    valid for this equation so the domain is $\mathbb{R}$ (\"all real
    numbers\").

2.  $$x^2+2x$$ Again, none of the domain restrictions listed above are
    valid for this problem since we are not dealing with fractions, we
    don't have an even root and no logarithmic functions are present.
    The answer is $\mathbb{R}$.

3.  $$\frac{1}{x-7}$$ In this problem we have a domain restriction, we
    cant have zero in the denominator. We set the denominator not equal
    to $0$ and we solve. $$\begin{aligned}
    x-7  & \neq 0 \\
    x  & \neq 7\end{aligned}$$ We can plug in any value of x into the
    function except for 7. In interval notation we label this as
    $\boxed{(-\infty,7)\cup(7,+\infty)}$.

4.  $\frac{1}{\sqrt[4]{2x+8}}$ For this last one, we have two domain
    restrictions in one. Our denominator can't be zero and our 4th root
    cant be negative. $$\begin{aligned}
    2x+8 & >0 \\
    2x & >-8 \\
    x & >-4\end{aligned}$$ Our function is defined for every x greater
    than negative 4. In interval notation: $\boxed{(-4,+\infty)}$.

Domain and Range is really important in calculus. If the examples above
don't seem trivial, then I would defiantly recommend reviewing topics
from Intermediate Algebra and Pre-calculus.

Function Notation
-----------------

Functions can be written in a variety of ways, all possibly denoting the
same function. For example, $$y=x^2-4x+4$$ This function can be written
in many different froms: $$\begin{aligned}
f(x) & =x^2-4x+4 \quad \quad g(x)=x^2-4x+4 \\
M(x) & =x^2-4x+4 \quad \quad d(x)=x^2-4x+4 \\
u(x) & =x^2-4x+4 \quad \quad a(x)=x^2-4x+4 \end{aligned}$$ All of those
represent the same function $y=x^2-4x+4$. We use different notation
because different notation might give us more detail.

Given the function $f(x)=x^2-4x+4$, solve each of the following:

1.  $f(3)$

2.  $f(4)$

3.  $f(x)$

4.  $f(x^2)$

5.  $f(3x+2)$

In this example, we plug in the value that is given to us everywhere we
see an x in the function $f(x)=x^2-4x+4$.

1.  $f(3)$ $$\begin{aligned}
    f(3) & =(3)^2-4(3)+4 \\
    f(3) & =9-12+4 \\
    f(3) & =1\end{aligned}$$

2.  $f(4)$ $$\begin{aligned}
    f(4) & =(4)^2-4(4)+4 \\
    f(4) & =16-16+4 \\
    f(4) & =4\end{aligned}$$

3.  $f(x)$ $$\begin{aligned}
    f(x) & =x^2-4x+4\end{aligned}$$ The function stays the same.

4.  $f(x^2)$ $$\begin{aligned}
    f(x^2) & =(x^2)^2-4(x^2)+4 \\
    f(x^2) & =x^4-4x^2+4\end{aligned}$$

5.  $f(3x+2)$ $$\begin{aligned}
    f(3x+2) & =(3x+2)^2-4(3x+2)+4 \\
    f(3x+2) & =(3x+2)(3x+2)-12x-8+4 \\
    f(3x+2) & =9x^2+6x+6x+4-12x-8+4 \\
    f(3x+2) & =9x^2\end{aligned}$$

Again this should be review.

Roots Of A Function. The roots of a function are the x-intercepts of a
function (where the function crosses the x-axis).

In order to find the roots of a function we just set the function equal
to 0.

Find the roots of the following functions:

1.  $f(x)=x^2+7x-18$

2.  $f(x)=x^2-6x-91$

3.  $f(x)=x^2-2x$

4.  $f(x)=3x-9$

We just set f(x) = 0\

1.  $f(x)=x^2+7x-18$ $$\begin{aligned}
    0 & =x^2+7x-18 \\
    0 & =(x+9)(x-2)\\
    x & =-9 \quad x=2\end{aligned}$$

2.  $f(x)=x^2-6x-91$ $$\begin{aligned}
    0 & =x^2-6x-91 \\
    0 & =(x+7)(x-13) \\
    x & =-7 \quad x=13\end{aligned}$$

3.  $f(x)=x^2-2x$ $$\begin{aligned}
    0 & =x^2-2x \\
    0 & =x(x-2) \\
    x & =0 \quad x=2\end{aligned}$$

4.  $f(x)=3x-9$ $$\begin{aligned}
    0 & =3x-9 \\
    0 & =3(x-3) \\
    x & =3\end{aligned}$$

Graphs
------

Graphs of functions can provide us really helpful visual details. Before
we get into calculus, there are some graphs that we should know.

┬á

┬á

┬á

┬á

┬á

┬á

┬á

┬á

┬á

┬á

The Vertical Line Test
----------------------

The Vertical Line Test line test is a really handy took that can be used
to determine if a certain curve is a function or not.

The Vertical Line Test In order for a curve to be a function, a vertical
line intersects the graph of the curve in all places at exactly one
point.

Basically, when looking at the graph of a curve visualize vertical lines
going through each point of that curve. If any of those vertical lines
touches the curve more than once then it is NOT a function. Let's take a
look at an example.

Determine if each of the following curves are functions.

1.  ┬á

2.  ┬á

3.  ┬á

4.  ┬á

To tell if the curves are functions or not, we just add a vertical line
and move it around the graph, if the vertical line at any point touches
the graph more than once then it is not a function.

1.  ┬á\
    In this example, we can see that the blue vertical line we inserted
    no matter where it is moved on the domain, it is going to touch the
    graph once and only once.

2.  ┬á\
    Again, we can see that no matter where on the domain we are, we are
    never going to touch the vertical line more than once.

3.  ┬á\
    This example is different from the two we saw before. There are
    certain values of x that if we draw a vertical line through, they
    are going to touch the curve more than once. Thus, this curve is NOT
    a function.

4.  ┬á\
    It is a function!

Piece-wise Defined Functions
----------------------------

Piece-wise Functions Piece-wise functions are the collection of various
functions and each of those functions are defined at a certain interval

The best way to understand piece-wise functions is to look at one:

$$f(x) =
  \begin{cases}
                                   2x & \text{if $x\leq 0$} \\
                                   \frac{1}{x} & \text{if $x>0$}
  \end{cases}$$

Here we can see that our function $f(x)$ has two functions inside of it:
$2x$ and $\frac{1}{x}$. Depending where we are on the domain, we either
use the first one ($2x$) or the second one ($\frac{1}{x}$).

Function Compositions
---------------------

Composition of functions are the combination of two functions.
Compositions of two functions $f(x)$ and $g(x)$ is denoted as
$(f \circ g)$ or in more intuitive terms $f(g(x))$.Lets look at
evaluating some function compositions.

Solve the following compositions with the given data.
$$f(x)=2x^2+2x-4, \quad \quad g(x)=\frac{1}{x}, \quad \quad h(x)=4$$

1.  $(f \circ g)$

2.  $(g \circ f)$

3.  $(h \circ f)$

4.  $(f \circ g \circ h)$

In order to solve, we just plug in the necessary function(s) and
evaluate.

1.  $(f \circ g)$

    $$\begin{aligned}
    (f \circ g)\quad \Rightarrow \quad f(g(x)) \\
    f(x)=2x^2+2x-4 , \quad  g(x)=\frac{1}{x} \\
    f(\frac{1}{x})= 2(\frac{1}{x})^2+2{\frac{1}{x}}-4\\
    \boxed{f(\frac{1}{x})= \frac{2}{x^2}+\frac{2}{x}-4}\end{aligned}$$

2.  $(g \circ f)$ $$\begin{aligned}
    (g \circ f) \quad \Rightarrow \quad g(f(x)) \\
    g(x)=\frac{1}{x}, \quad  f(x)=2x^2+2x-4 \\
    \boxed{g(2x^2+2x-4)=\frac{1}{2x^2+2x-4}}\end{aligned}$$

3.  $(h \circ f)$ $$\begin{aligned}
    (h \circ f) \quad \Rightarrow \quad h(f(x)) \\
    h(x)=4, \quad f(x)=2x^2+2x-4 \\
    \boxed{h(2x^2+2x-4)=4}\end{aligned}$$

4.  $(f \circ g \circ h)$ $$\begin{aligned}
    (f \circ g \circ h) \quad \Rightarrow \quad f(g(h(x))) \\
    f(x)=2x^2+2x-4,  \quad g(x)=\frac{1}{x}, \quad h(x)=4 \\
    (g \circ h) \quad \Rightarrow \quad g(4)=\frac{1}{4} \\
    f(\frac{1}{4})=2(\frac{1}{4})^2+2(\frac{1}{4})-4 \\
    f(\frac{1}{4})=2(\frac{1}{16})+\frac{1}{2}-4 \\
    f(\frac{1}{4})=\frac{1}{8}+\frac{1}{2}-4 \\
    \boxed{f(\frac{1}{4})=\frac{-27}{8}}\end{aligned}$$

C:\Users\malja>




































