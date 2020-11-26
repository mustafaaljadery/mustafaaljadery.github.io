Review of Algebra and Trigonometry
==================================

In this chapter, we are going to review concepts from algebra and
trigonometry that are heavily used in calculus. It is really important
that you have all of these concepts down before starting calculus.

Review of Functions
-------------------

### Functions

Function A function is a relationship between the set of inputs and
outputs, where every input has exactly one output.

Functions can be represented in multiple forms, from sets to graphs to
equations; The more common representation of functions in calculus are
equations and graphs. Any of the above forms of representation can be
functions, if and only if for every input there is only one unique
output. This is best shown by example.

Determine whether the following equations are functions or not. Explain
why.

1.  $y=x^2$

2.  $3+y^2=12x$

3.  $y=2x^5-5x+13$

In order to tell whether the equations are functions or not, we solve
for y. If for every unique input of x we get only one output of y then
it is a function.

1.  $y=x^2$ $$y=x^2 \quad \Rightarrow \quad f(x)=x^2$$ We can see that
    for every input of x, we get exactly one output of y. So from your
    definition we know that this equation is a function.

2.  $3+y^2=12x$ $$\begin{aligned}
    y^2=12x-3 \\
    \boxed{y= \pm \sqrt{12x-3}}\end{aligned}$$ A we can see here, this
    equation is not a function. For every input of x, we get 2 outputs
    of y (a positive value and a negative value).

3.  $y=2x^5-5x+13$
    $$y=2x^5-5x+13 \quad \Rightarrow \quad f(x)=2x^5-5x+13$$ As we can
    see, for every unique input of x we are going to get exactly one
    output y. Thus making this equation a function.

### Domain and Range

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

For the second domain restriction, its not only for $\sqrt{x} \quad x<0$
but for all even roots. For example,$\sqrt[4]{x} \quad x <0$ does NOT
output a real value (domain restriction). It is the same for
$\sqrt[6]{x} \quad x<0$\...

Lets look at some examples.

Find the domain of all the following equations.

1.  $y=3x^2+9x-2$

2.  $x^2+2x$

3.  $\frac{1}{x-7}$

4.  $\frac{1}{\sqrt[4]{2x+8}}$

Here we just try to find a possible domain restriction.\

1.  $y=3x^2+9x-2$ Not of the domain restriction we listed above are
    valid for this equation so the domain is $\mathbb{R}$ (\"all real
    numbers\").

2.  $x^2+2x$ Again, none of the domain restrictions listed above are
    valid for this problem since we are not dealing with fractions, we
    don't have an even root and no logarithmic functions are present.
    The answer is $\mathbb{R}$.

3.  $\frac{1}{x-7}$ In this problem we have a domain restriction, we
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

### Function Notation

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

### Graphs

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

### The Vertical Line Test

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

### Piece-wise Defined Functions

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

### Function Compositions

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

Review of Trigonometry
----------------------

This section is going to review all of the trigonometry we are going to
be using in calculus. Most students usually struggle in calculus for 2
main reasons:

1.  They aren't very comfortable with their algebra.

2.  They don't know their trigonometry

Know both your Algebra and your Trigonometry.

### Basic Trig Functions

Here are all the common basic trig functions: $$\begin{aligned}
\sin(x)=\frac{\text{Opposite}}{\text{Hypotenuse}} \quad \quad \cos(x)=\frac{\text{Adjacent}}{\text{Hypotenuse}} \quad \quad tan(x)=\frac{\text{Opposite}}{\text{Adjacent}} \\\end{aligned}$$
Furthermore, all 3 of these functions have reciprocals:
$$\begin{aligned}
\csc(x)=\frac{\text{Hypotenuse}}{\text{Opposite}} \quad \Rightarrow \quad \csc(x)=\frac{1}{\sin(x)} \\
\sec(x)=\frac{\text{Hypotenuse}}{\text{Adjacent}} \quad \Rightarrow \quad \sec(x)=\frac{1}{\cos(x)} \\
\cot(x)=\frac{Adjacent}{Opposite} \quad \Rightarrow \quad \cot(x)=\frac{1}{\tan(x)}\end{aligned}$$

An important thing to note is that the reciprocals are NOT the same as
the inverses. For example, the reciprocal of $\sin(x)$ is $\csc(x)$
while the inverse of $\sin(x)$ is $\sin^{-1}(x)$. $\sin^{-1}(x)$ and
$\csc(x)$ are completely different DON'T mistake them for each other.

### Degrees v. Radians

In calculus, nearly all of our calculations are going to be in Radians.
Radians is just more applicable. However, usually have a hard time
grasping radians because all their work before was done in degrees. They
can visualize degrees perfectly, while radians not so much. In this
section we are going to review Radians.

Here are the important conversions between degrees and radians:

  ------------- --- ----------------- ----------------- ----------------- ----------------- ------- ------------------ --------
   **Degrees**   0         30                45                60                90           180          270           360
   **Radians**   0   $\frac{\pi}{6}$   $\frac{\pi}{4}$   $\frac{\pi}{3}$   $\frac{\pi}{2}$   $\pi$   $\frac{3\pi}{2}$   $2\pi$
  ------------- --- ----------------- ----------------- ----------------- ----------------- ------- ------------------ --------

A very handy tool to have around when converting between degrees and
radians and vice versa is the unit circle:

An important think to remember is that when we are talking about that
$\cos(x)$ refers to the **x-axis** while $\sin(x)$ refers to the
**y-axis**.

Finally, one thing to note before we look at examples is that any radian
value $\pm 2\pi$ is the same value. For example, $\frac{\pi}{6}$ is the
same as $\frac{13\pi}{6}$. In fact it isn't only $2\pi$ but any multiple
of $\pm2\pi$. $\pm4\pi$, $\pm6\pi$\...

Lets take a look at some examples:

Solve each of the following.

1.  $\sin(\frac{5\pi}{6})$

2.  $\cos(\frac{5\pi}{6})$

3.  $\tan(\frac{5\pi}{6})$

4.  $\cos(\frac{19\pi}{6})$

5.  $\sec(\frac{11\pi}{3})$

6.  $\cot(\frac{7\pi}{4})$

With the help of our unit circle and we can solve each of the trig
functions.

1.  $\sin(\frac{5\pi}{6})$\
    If we look at our unit circle, we can see that the at the point
    $\frac{5\pi}{6}$ we get the coordinates,
    $(\frac{-\sqrt{3}}{2},\frac{1}{2})$. Since we know that sine is our
    y value, our answer is $\boxed{\frac{1}{2}}$.

2.  $\cos(\frac{5\pi}{6})$\
    Similar to the last problem, our coordinates are
    $(\frac{-\sqrt{3}}{2},\frac{1}{2})$. We know that cosine is our x
    value, so the answer is $\boxed{\frac{-\sqrt{3}}{2}}$.

3.  $\tan(\frac{5\pi}{6})$\
    This one is a little different. We have to recall the identity of
    tangent, $\tan(x)=\frac{\sin(x)}{\cos(x)}$. We know the value of
    $\sin(x)$ and we know the value of $\cos(x)$ from our previous 2
    examples. $$\begin{aligned}
    \sin(\frac{5\pi}{6})=\frac{1}{2} \\
    \cos(\frac{5\pi}{6})=\frac{-\sqrt{3}}{2} \\
    \tan({\frac{5\pi}{6}}) = \frac{\frac{1}{2}}{\frac{-\sqrt{3}}{2}} \\
    \frac{1}{2} * \frac{2}{-\sqrt{3}} \\
    \frac{-1}{\sqrt{3}} \\
    \boxed{\frac{-\sqrt{3}}{3}}\end{aligned}$$

4.  $\cos(\frac{19\pi}{6})$\
    In this example, $\cos(\frac{19\pi}{6})$ is equivalent to
    $\cos(\frac{5\pi}{6})$. As we said above $\pm 2\pi$ yields the same
    result. $\boxed{\cos(\frac{5\pi}{6})=\frac{-\sqrt{3}}{2}}$

5.  $\sec(\frac{11\pi}{3})$\
    As we can recall from above, $\sec(x)=\frac{1}{\cos(x)}$.
    $$\begin{aligned}
    \cos(\frac{11\pi}{3})=\frac{\sqrt{3}}{2} \\
    \frac{1}{\frac{\sqrt{3}}{2}} \\
    \frac{1}{1} * \frac{2}{\sqrt{3}} \\
    \frac{2}{\sqrt{3}} \\
    \boxed{\frac{2\sqrt{3}}{3}}\end{aligned}$$

6.  $\cot(\frac{7\pi}{4})$ $$\begin{aligned}
    \cot(x)=\frac{\cos(x)}{\sin(x)} \\
    \cos(\frac{7\pi}{4})= \frac{\sqrt{2}}{2}, \quad \quad \sin(\frac{7\pi}{4})=\frac{-\sqrt{2}}{2} \\
    \frac{\frac{\sqrt{2}}{2}}{\frac{-\sqrt{2}}{2}} \\
    \frac{\sqrt{2}}{2} * \frac{2}{-\sqrt{2}} \\
    \boxed{\cot(\frac{7\pi}{4})=-1}\end{aligned}$$

### Solving Trig Functions

In order to solve trig functions, we have to introduce the idea of
inverse functions. We are going to introduce the idea here, but we are
going to go in depth in the next section. The fundamental idea of an
inverse function is a function that reverses another function. This is
best explained with an example.

$$\sin^{-1}(\sin(x))=x$$

A good way to think about this is that, the inverse function undoes the
original function and vice-versa.

Here are the inverses of our trig functions $$\begin{aligned}
\sin(x) \quad \quad \sin^{-1}(x) \\
\cos(x) \quad \quad \cos^{-1}(x) \\
\tan(x) \quad \quad \tan^{-1}(x) \\
\csc(x) \quad \quad \csc^{-1}(x) \\
\sec(x) \quad \quad \sec^{-1}(x) \\
\cot(x) \quad \quad \cot^{-1}(x) \end{aligned}$$

Most trig problems are going to require a calculator that is in radian
mode. Before attempting to solve any of the examples, make sure you have
a calculator in radian mode.

That being said lets look at how we can solve some examples

Solve each of the following for x.

1.  $4\sin(x)=2$

2.  $6\tan(x)=5$

3.  $-5\cos(\frac{x}{9})=4$

4.  $4\sec(\frac{x}{2})=1$

5.  $2\cot(x)=2$

Solve each of the following for x.

1.  $4\sin(x)=2$\
    $$\begin{aligned}
    \sin(x)= \frac{1}{2} \\
    x=\sin^{-1}(\frac{1}{2}) \\
    x= 0.5235987756 +2\pi n \\
    x= 2.617993878 +2\pi n\end{aligned}$$ We added the $+2\pi n$ to the
    end of both of the answers because again, $2\pi$ is just a full
    circle and we will end up at the same place wether we add it or not.
    Furthermore, we got the second answer by looking at our unit circle,
    we know that sine is the y-axis, so we have to find the other angle
    where sine is positive.

2.  $6\tan(x)=5$\
    $$\begin{aligned}
    \tan(x)=\frac{5}{6} \\
    x=\tan^{-1}(\frac{5}{6}) \\
    x= 0.6947382762 +2\pi n \\
    x= 3.83633093 + 2\pi n \end{aligned}$$

3.  $-5\cos(\frac{x}{9})=4$\
    $$\begin{aligned}
    \cos(\frac{x}{9})=\frac{-4}{5} \\
    \frac{x}{9} = \cos^{-1}(\frac{-4}{5}) \\
    \frac{x}{9} = 2.5498091545 + 2\pi n \\
    \frac{x}{9} = 3.785093762 +2 \pi n \\
    x = 22.94828779 + 18 \pi n \\
    x = 34.06584386 + 18 \pi n\end{aligned}$$

4.  $4\sec(\frac{x}{2})=1$ $$\begin{aligned}
    \sec(\frac{x}{2})=\frac{1}{4} \\
    \frac{1}{\cos(\frac{x}{2})}=\frac{1}{4} \\
    1= \frac{1}{4}*\cos(\frac{x}{2}) \\
    \cos(\frac{x}{2})=4 \\
    \frac{x}{2}=\cos^{-1}(4) \\
    \frac{x}{2}=1.823476582 +2 \pi n \\
    \frac{x}{2}= 4.459708725 + 2\pi n \\
    x=3.646953164 + 4 \pi n \\
    x=8.91941745 + 4 \pi n\end{aligned}$$

5.  $2\cot(x)=2$ $$\begin{aligned}
    \cot(x)=1 \\
    \frac{1}{\tan(x)}=1 \\
    \tan(x)=1 \\
    x= \tan^{-1}(1) \\
    x=0.7853981634 + 2\pi n \\
    x=3.926990817+ 2\pi n \end{aligned}$$

Sometimes, we are asked to solve trig functions on an interval. Solving
trig functions on an interval is basically limiting the number of
outputs we can get. Right now, we get an infinite number of outputs, for
each of the answers above we can just keep adding or subtracting $2\pi$
for ever. Lets look at couple of examples involving a restricted
interval.

1.  $31=1+40\cos(\frac{x}{8}) in [-10,30]$

2.  $15\csc(15x)+14=20-12\csc(15x) in [1,2]$

```{=html}
<!-- -->
```
1.  $31=1+40\cos(\frac{x}{8}) in [-10,30]$\
    $$\begin{aligned}
    40\cos(\frac{x}{8})=30 \\
    \cos(\frac{x}{8})=\frac{3}{4} \\
    \frac{x}{8} = \cos^{-1}(\frac{3}{4}) \\
    \frac{x}{8}=0.7227342478 + 2\pi n \\
    \frac{x}{8}=5.560451059 + 2 \pi n \\
    x=5.781873982 + 16 \pi n \\
    x=44.48360847 + 16 \pi n \\
    \boxed{-5.78187398,5.78187398}\end{aligned}$$

2.  $15\csc(15x)+14=20-12\csc(15x) in [1,2]$\
    $$\begin{aligned}
    27\csc(15x)=6 \\
    \csc(15x)=\frac{2}{9} \\
    \frac{1}{\sin(15x)}=\frac{2}{9} \\
    \sin(15x)=\frac{9}{2} \\
    15x=\sin^{-1}(\frac{9}{2}) \\
    No solutions\end{aligned}$$

Review of Inverse Functions
---------------------------

Inverse functions are fundamental in mathematics, thus I decided to make
a whole section on them. The idea of inverse functions stems on
canceling or undoing a certain function. As we learnt form the previous
section: $$\begin{aligned}
f^{-1}(f(x))=x \\
f(f^{-1}(x))=x\end{aligned}$$

Not all functions have inverses!

In order to tell whether a curve is a function on the graph we use the
vertical line test and in order to tell whether the curve has an inverse
we use the horizontal line test. A curve can only have an inverse if and
only it passes the horizontal line test.

Horizontal Line Test. If a horizontal line intersects a function's graph
once and only once then it is said that that function has an inverse. If
at any point on the curve a horizontal line intersects at more than one
point then the function does NOT have an inverse.

Moreover, when graphing the inverse of a function, the inverse is always
going to reflect the function on the line $y=x$. An example of this is
the function $f(x)=2x$ (red), its inverse is $f(x)=\frac{x}{2}$ (blue).

┬á

Finally, before some examples, in order to solve for the inverse of a
function algebraically, you follow the following steps:

1.  Write down the original equation

2.  Replace every instance of y with x and every instance of x with y

3.  Solve for y

4.  The result will the the inverse of the original

Again never forget, not all functions have inverses. Let's look at some
examples:

Find the inverse for each of the following

1.  $f(x)=x^3+6$

2.  $f(x)=\frac{1+9x}{4-x}$

3.  $f(x)=2x^7-9$

4.  $f(x)=\sqrt[3]{6-18x}$

```{=html}
<!-- -->
```
1.  $f(x)=x^3+6$\
    $$\begin{aligned}
    y=x^3+6 \\
    x=y^3+6 \\
    x-6=y^3 \\
    \sqrt[3]{x-6} =y \\
    \boxed{f^{-1}(x)=\sqrt[3]{x-6}}\end{aligned}$$

2.  $f(x)=\frac{1+9x}{4-x}$\
    $$\begin{aligned}
    y=\frac{1+9x}{4-x} \\
    x=\frac{1+9y}{4-y} \\
    x(4-y)=1+9y \\
    4x-xy=1+9y \\
    -9y-xy=1-4x \\
    y(-9-x)=1-4x \\
    y=\frac{1-4x}{-9-x} \\
    \boxed{f^{-1}(x)=\frac{4x-1}{9+x}}\end{aligned}$$

3.  $f(x)=2x^7-9$\
    $$\begin{aligned}
    y=2x^7-9 \\
    x=2y^7-9 \\
    x+9=2y^7 \\
    \frac{x+9}{2} = y^7 \\
    \sqrt[7]{\frac{x+9}{2}}=y\\
    \boxed{f^{-1}(x)=\sqrt[7]{\frac{x+9}{2}}}\end{aligned}$$

4.  $f(x)=\sqrt[3]{6-18x}$\
    $$\begin{aligned}
    y=\sqrt[3]{6-18x} \\
    x=\sqrt[3]{6-18y} \\
    x^3=6-18y \\
    x^3-6=-18y \\
    \frac{-x^3+6}{18} =y \\
    \boxed{f^{-1}(x)=\frac{-x^3+6}{18}}\end{aligned}$$

Review of Exponential and Logarithmic Functions
-----------------------------------------------

### Exponentials

Exponential and Logarithmic functions are essential in calculus and
other higher mathematical classes. Lets starting by looking at an
exponential function: $$f(x)=a^x$$

This exponential functions is just like others we have seen before.

Exponential Functions. Here are the properties of exponential functions:

1.  $\sqrt[a]{x}=x^\frac{1}{a}$

2.  $\frac{1}{x^a}=x^{-a}$

3.  $x^a*x^b=x^{a+b}$

4.  $\frac{x^a}{x^b}=x^{a-b}$

5.  $(x^a)^b=x^{ab}$

6.  $(xy)^a=x^a*y^a$

7.  $\sqrt[b]{x^a}=x^{\frac{a}{b}}$

### Logarithms

Logarithms are basically a different way of expressing the exponential
functions we learned. Exponentials and Logarithms are interchangeable as
follows: $$\log_b (a)=c \quad \leftrightarrow \quad b^c=a$$

Lets look at some examples solving logarithms.

Solve each of the following

1.  $\log_2 8$

2.  $\log_3 9$

3.  $\log_6 7776$

4.  $\log_\frac{1}{6} 1296$

5.  $log_\frac{1}{5} \frac{1}{125}$

In order to solve these types of problems, the easiest way is to just
convert them to the exponential form.

1.  $\log_2 8$\
    $$\begin{aligned}
    8=2^x \\
    \boxed{x=3}\end{aligned}$$

2.  $\log_3 9$\
    $$\begin{aligned}
    9=3^x \\
    \boxed{x=2}\end{aligned}$$

3.  $\log_6 7776$\
    $$\begin{aligned}
    7776=6^x \\
    \boxed{x=5}\end{aligned}$$

4.  $\log_\frac{1}{6} 1296$\
    $$\begin{aligned}
    1296=\frac{1}{6}^x \\
    \boxed{x=-4}\end{aligned}$$

5.  $log_\frac{1}{5} \frac{1}{125}$\
    $$\begin{aligned}
    \frac{1}{125}=\frac{1}{5}^x \\
    \boxed{x=3}\end{aligned}$$

A quite common logarithmic function is the natural logarithm, $\ln{x}$.
$$\log_e x \quad \leftrightarrow \quad \ln{x}$$

The natural number, $e$, is an irrational (a number that never ends just
like $\pi$). Its often called Euler's number named after Euler and its
value, $e=2.718281828...$.

Now let's take a look at the properties of Logarithmic Functions.

Logarithmic Functions.

1.  $\log_b (x*y)=\log_b (x) +\log_b (y)$

2.  $\log_b (\frac{x}{y})=\log_b (x)-\log_b (y)$

3.  $\log_b (x^y)=y*\log_b (x)$

4.  $\log_b (c)=\frac{1}{\log_c (b)}$

5.  $\log_b (x)=\frac{\log_c (x)}{\log_c (b)}$

6.  $b^{\log_b (x)}=x$

7.  $\log_b (0)= undefined$

8.  $\log_b (1)=0$

9.  $\log_b (b)=1$

Finally, lets look at some examples involving the properties.

Solving using the properties of Logarithms.

1.  $8+3e^{4-9z}=1$

2.  $\ln{3x+1}-\ln{x}=-2$

3.  $16+4\ln{x+2}=7$

Find the necessary properties for the equation and plug in the values.

1.  $8+3e^{4-9x}=1$\
    $$\begin{aligned}
    3e^{4-9x}=-7 \\
    e^{4-9x}=\frac{-7}{3} \\
    4-9x=\ln{\frac{-7}{3}} \\
    4-9x=undefined \\
    \boxed{\text{No Solution}}\end{aligned}$$

2.  $\ln{3x+1}-\ln{x}=-2$\
    $$\begin{aligned}
    3x+1-x=e^{-2} \\
    2x+1=e^{-2} \\
    2x=e^{-2}-1 \\
    x= \frac{e^{-2}-1}{2} \\
    x= -0.4323323584 \\
    \boxed{\text{No solution}}\end{aligned}$$ We can never have a
    negative in a natural logarithm.

3.  $16+4\ln{x+2}=7$\
    $$\begin{aligned}
    4\ln{x+2}=-9\
    \ln{x+2}=\frac{-9}{4} \\
    x+2=e^{\frac{-9}{4}} \\
    x= e^{\frac{-9}{4}}-2 \\
    \boxed{x= -1.894600775}\end{aligned}$$ Note that this answer is
    fine, but the answer from the previous question is not because after
    you solve you have to plug x back into the logarithm. If the
    logarithm argument is positive then its totally fine if x is
    negative.
