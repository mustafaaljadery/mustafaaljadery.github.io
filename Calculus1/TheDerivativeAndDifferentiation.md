The Derivative + Differentiation
================================

In this chapter we are going to introduce, define and look at how to
solve the derivative. The derivative is the second of the three major
concepts in calculus. Derivatives stem from our understand of limits and
rates of change.

Slope of Tangent Lines + Rate Of Change
---------------------------------------

In this section we are going to rehash what we learned in limits. Again,
limits are the fundamental idea of the derivative. Even though I said
that there are 3 main ideas in calculus 1 it doesn't mean they are not
connect. In fact, one builds on the other.

### Tangent Lines

A Tangent line is a line that touches the curve of our function once and
only once. The Tangent line highlights the rate of change of the
function at exactly that point.

In calculus, instead of looking at linear functions we are going to be
looking at curves. Curves different slopes depending where you are on
the domain. Thus the tangent line highlights the rate of change at only
that point.

As we have seen before, here are what tangent lines look like
graphically.

\*\*Graphic Only Available On the Pdf\*\*

The most important takeaway from tangent lines is that when dealing with
curves, the slopes of tangent lines different depending where we are in
the domain. The three blue lines in the example all have different
slope.

### Rates Of Change

Rate of change always relates back to this formula,
$$\frac{f(x)-f(a)}{x-a}$$

However, in the last chapter we connected this formula for rates of
change to your limit notation,

$$\lim_{x \to a} \frac{f(x)-f(a)}{x-a}$$

Both these equations state the exact same thing but with different
notation.

Rate of change measures how fast our outputs are changing.

In the next section we are going to introduce the derivative and relate
it to our rate of change.

What Is A Derivative?
---------------------

The derivative is exact the rate of change we discussed in the last
section. We note it as, $$\lim_{h \to 0} \frac{f(x+h)-f(x)}{h}$$

This limit is so important that we have a different name for it, the
derivative.

Using this notation for the derivative, lets work on an example.

Find the derivative of the following.

1.  $f(x)=x^2-8x+20$

Using our limit formula we can solve.

1.  $f(x)=x^2-8x+20$\
    $$\begin{aligned}
    \lim_{h \to 0} \frac{[(x+h)^2-8(x+h)+20]-[x^2-8x+20]}{h} \\
    \lim_{h \to 0} \frac{[x^2+2hx+h^2-8x-8h+20-x^2+8x-20]}{h} \\
    \lim_{h \to 0} \frac{2hx+h^2-8h}{h} \\
    \lim_{h \to 0} \frac{h(2x+h-8)}{h} \\
    \lim_{h \to 0} 2x+h-8 \\
    f^{\prime}(x)=2x-8 \end{aligned}$$

The derivative has many different notations, including:
$$f^{\prime}(x) \quad f^{\prime} \quad \frac{d}{dx}(f(x)) \quad \frac{dy}{dx} \quad \frac{d}{dx}(y)$$

Differentiable. When a function is called differentiable it means the
derivative must exists to even value of a functions domain.

If a function is differentiable then it is also continuous.

Techniques Of Differentiation
-----------------------------

The method of finding the derivative above can be very tedious. For
example, lets say we wanted to find the derivative of this following
function, $$f(x)=x^167-x^53+4x^7$$ Trying to find the derivative for
this function is going to be a real pain, it would take hours if you use
pascals triangle and probably days if you don't. Thus we have new and
more efficient ways to solve derivatives.

Before we look at our new techniques in solving derivatives we have to
look at the properties of derivatives.

1.  $\frac{d}{dx}(u+v)=\frac{du}{dx}+\frac{dv}{dx}$

2.  $\frac{d}{dx}(u-v)=\frac{du}{dx}-\frac{dv}{dx})$

3.  $\frac{d}{dx}(cu)=c\frac{du}{dx} \quad \text{"c" is defined as a constant}$

Now that we have our properties lets introduce the most essential
formula for taking derivatives.

Power Rule: $$\frac{d}{dx}[x^n]=nx^{n-1}$$

It's really that simple, lets work on a couple example to highlight its
importance.

1.  $f(x)=x^10-7x^5+2x^3-x^2$

2.  $g(x)=\frac{4}{x^2}+\frac{1}{7x^5}+\frac{1}{2x}$

3.  $h(x)=3x^{-6}-8x^{-3}+9x^{-1}$

4.  $i(x)=\sqrt[6]{x}-7\sqrt[4]{x}+3\sqrt{x}$

```{=html}
<!-- -->
```
1.  $f(x)=x^10-7x^5+2x^3-x^2$\
    $$\begin{aligned}
    10(x)^9-7(5)x^4+2(3)x^2-2x \\
    f^{\prime}(x)=10x^{9}-35x^4+6x^2-2x\end{aligned}$$

2.  $g(x)=\frac{4}{x^2}+\frac{1}{7x^5}+\frac{1}{2x}$\
    $$\begin{aligned}
    4x^{-2}+\frac{1}{7}x^{-5}+\frac{1}{2}x^{-1} \\
    -8x^{-3}+\frac{-5}{7}x^{-6}+\frac{-1}{2}x^{-2} \\
    g^{\prime}(x)=\frac{-8}{x^3}+\frac{-5}{7x^6}-\frac{1}{2x^2}\end{aligned}$$

3.  $h(x)=3x^{-6}-8x^{-3}+9x^{-1}$ $$\begin{aligned}
    -18x^{-7}+24x^{-4}-9x^{-2} \\
    h^{\prime}(x)=\frac{-18}{x^7}+\frac{24}{x^4}-\frac{9}{x^2}\end{aligned}$$

4.  $i(x)=\sqrt[6]{x}-7\sqrt[4]{x}+3\sqrt{x}$ $$\begin{aligned}
    i(x)=x^{\frac{1}{6}}-7x^{\frac{1}{4}}+3x^{\frac{1}{2}} \\
    \frac{1}{6}x^{\frac{-5}{6}}-\frac{7}{4}x^{\frac{-3}{4}}+\frac{3}{2}x^{\frac{-1}{2}} \\
    i^{\prime}(x)=\frac{1}{6\sqrt[6]{x^5}}-\frac{7}{4\sqrt[4]{x^3}}+\frac{3}{2\sqrt{x}}\end{aligned}$$

$f(x)=c \quad \Rightarrow \quad f^{\prime}(x)=0$ the derivative of any
constant is 0 and that makes intuitive sense because a constant can be
defined as $cx^0$ and when we use the power rule, the coefficient is
going to multiplied by 0 and anything multiplied by 0 is 0.

Solving derivatives using the power rule really simplifies the process
of finding our rate of change.

Product and Quotient Rules
--------------------------

A question may arise, what about other properties of derivatives? How
can we solve two derivatives multiplied or divided from each other? As
for the previous section, we only defined properties that allowed us to
solve for derivatives that are being added or subtracted. In this
section, we are going to look at multiplication and division.

Product Rule. When taking the derivative of the product of two functions
that are differentiable, the following property is used,
$$\frac{d}{dx}(f(x)*g(x))=\frac{d}{dx}f(x)*g(x)+f(x)*\frac{d}{dx}g(x)$$

This states that the derivative of of the product of two functions is
the derivative of the first functions times the second function plus the
first function times the derivative of the second function.

Quotient Rule. When taking the derivative of the quotient of two
functions that are differentiable, then the following property is used,
$$\frac{d}{dx}(\frac{f(x)}{g(x)})=\frac{[\frac{d}{dx}(f(x))*g(x)]-[f(x)*\frac{d}{dx}(g(x))]}{[g(x)]^2}$$

The quotient rule states that the derivative of a quotient is the
derivative of the numerator times the denominator minus the numerator
times the derivative of the denominator all over the square of the
denominator.

Mathematics students have to really pay attention to properties, you
cant just use any property. There are defined ones for the operation you
are performing, don't mix them up.

Lets take a look at a few examples utilizing the product and quotient
rules.

Find the derivatives the following using the product and quotient rules.

1.  $f(x)=(2-\sqrt{x})(3+8\sqrt[3]{x^2})$

2.  $g(x)=(x^2-5x+1)(12+2x-x^3)$

3.  $h(x)=\frac{4x-x^2}{6-x}$

4.  $i(x)=\frac{(1-4x)(2+x)}{3+9x}$

```{=html}
<!-- -->
```
1.  $f(x)=(2-\sqrt{x})(3+8\sqrt[3]{x^2})$\
    $$\begin{aligned}
    f^{\prime}(x)=[\frac{d}{dx}(2-\sqrt{x})*(3+8\sqrt[3]{x^2})]+[(2-\sqrt{x})*\frac{d}{dx}(3+8\sqrt[3]{x^2})] \\
    (\frac{-1}{2}x^{\frac{-1}{2}})(3+8x^{\frac{2}{3}})+(2-x^{\frac{1}{2}})(\frac{16}{3}x^{\frac{-1}{3}}) \\
    \frac{-3}{2}x^{-\frac{-1}{2}}-4x^{\frac{1}{6}}+\frac{32}{3}x^{\frac{-1}{3}}-\frac{16}{3}x^{\frac{1}{6}} \\
    f^{\prime}(x)=\frac{32}{3x^{\frac{1}{3}}}-\frac{28x^{\frac{1}{6}}}{3}-\frac{3()}{2x^{\frac{1}{2}}}\end{aligned}$$

2.  $g(x)=(x^2-5x+1)(12+2x-x^3)$\
    $$\begin{aligned}
    (2x-5)(12+2x-x^3)+(x^2-5x+1)(-3x^2+2) \\
    24x+4x^2-2x^4-60-10x+5x^3-3x^4+15x^3-3x^2+2x^2-10x+2 \\
    g^{\prime}(x)=-5x^4+20x^3+3x^2+4x-58\end{aligned}$$

3.  $h(x)=\frac{4x-x^2}{6-x}$\
    $$\begin{aligned}
    \frac{[\frac{d}{dx}(4x-x^2)*(6-x)]-[(4x-x^2*\frac{d}{dx}(6-x))]}{(6-x)^2} \\
    \frac{[(4-2x)(6-x)]-[(4x-x^2)(-1)]}{x^2-12x+36} \\
    \frac{24-4x-12x+2x^2+4x-x^2}{x^2-12x+36} \\
    \frac{x^2-12x+24}{x^2-12x+36}\end{aligned}$$

4.  $i(x)=\frac{(1-4x)(2+x)}{3+9x}$\
    $$\begin{aligned}
    \frac{[\frac{d}{dx}[(1-4x)(2+x)]*(3+9x)]-[(1-4x)(2+x)*\frac{d}{dx}[3+9x]]}{(9x+3)^2} \\
    \frac{(-8+1-4x-4x)(9x+3)-(1-4x)(2+x)(9)}{(9x+3)^2} \\
    \frac{-24x-72x^2-21-63x-18+63x+36x^2}{(9x+3)^2} \\
    i^{\prime}(x)=\frac{-36x^2-24x-39}{(9x+3)^2}\end{aligned}$$

Derivatives Of Various Functions
--------------------------------

This section is going to discuss the derivatives of important functions
that amplify our understanding of calculus.

### Trig Functions

Firstly, lets look at the derivatives of the trig functions. Before we
discuss the important trig functions we need to look at 2 limits that
are used to prove the derivatives of the trig functions,
$$\lim_{x \to 0} \frac{sin(x)}{x}=1 \quad \quad \lim_{x \to 0} \frac{cos(x)-1}{x}=0$$

These two limits are proven using the squeeze theorem.

Squeeze Theorem. The squeeze theorem or sometimes called the sandwich
theorem, states that if there exists a positive number $p$ who falls
under,$g(x) \leq f(x) \leq h(x)$ for all x that satisfies $0<|x-a|<p$
and if $\displaystyle{\lim_{x \to a} g(x)=\lim_{x \to a}h(x)=L}$, then
$\displaystyle{\lim_{x \to a} f(x)=L}$

We are not going to prove the two limits but it is good to know where
they are derived from (squeeze theorem).

Now simply, the derivative of the 6 trig functions are:

1.  $\frac{d}{dx}(sin(x))=cos(x)$

2.  $\frac{d}{dx}(cos(x))=-sin(x)$

3.  $\frac{d}{dx}(tan(x))=sec^{2}(x)$

4.  $\frac{d}{dx}(cot(x))=-csc^{2}(x)$

5.  $\frac{d}{dx} (sec(x))=sec(x)tan(x)$

6.  $\frac{d}{dx}(csc(x))=-csc(x)cot(x)$

Lets work on a couple of examples,

Differentiate all of the following functions.

1.  $f(x)=x^4-9sin(x)+2tan(x)$

2.  $g(x)=8sec(x)+cos(x)-4csc(x)$

3.  $h(x)=6\sqrt[5]{x^2}+8xsin(x)$

```{=html}
<!-- -->
```
1.  $f(x)=x^4-9sin(x)+2tan(x)$\
    $$\begin{aligned}
    4x^3-9cos(x)+2sec^{2}(x)\end{aligned}$$

2.  $g(x)=8sec(x)+cos(x)-4csc(x)$\
    $$\begin{aligned}
    8sec(x)tan(x)-sin(x)+4csc(x)cot(x)\end{aligned}$$

3.  $h(x)=6\sqrt[5]{x^2}+8xsin(x)$\
    $$\begin{aligned}
    6x^{\frac{2}{5}}+8xsin(x)
    \frac{12}{5}x^{\frac{-3}{5}} +8sin(x)+8xcos(x) \\
    \frac{12}{5\sqrt[5]{x^3}}+8sin(x)+8xcos(x)\end{aligned}$$

### Exponential and Logarithmic Functions

Now lets take a look at the derivatives of exponential and logarithmic
functions. Exponential functions are written in the form of,
$$f(x)=a^x$$

While logarithmic functions are written in the form of,

$$y=\log_a x$$

More about the basic exponential and logarithmic functions and operators
was discussed in the review chapter of this book, if you need a
refresher, a good idea is too look back there.

Lets take a look at the derivatives of these functions.

Derivative of Exponential Functions:

$$\frac{d}{dx} a^x = a^x\ln{a}$$

The Derivative of the natural number e: $$\frac{d}{dx} e^x = e^x$$

The derivatives of exponential functions in the form of $a^x$ is
$a^x\ln{a}$. While, the derivative of your natural number (or eulers
number) $e^x$ is the same $e^x$.

An important thing to note, and we are going to be talking about this in
the next section of the book is that, these functions may require the
use of the chain rule. Furthermore, chain rule is used to prove why the
derivatives are so.

Now when talking about the derivatives of logarithmic functions. The key
concept to understand is that exponential and logarithmic functions are
inverses of each other. Note: two functions are inverses if
$(f(x) \circ g(x))$ and $(g(x) \circ f(x))$ both equal x. If this is the
case then f(x) and g(x) are said to be inverses of each other.

We can take the derivatives of inverses by using this formula,
$$\frac{d}{dx}g(x)=\frac{1}{f^{\prime}(g(x))}$$

Now lets use this formula to find the derivative of $\ln{x}$, the
inverse of e.

$$\begin{aligned}
f(x)=e \quad \quad g(x)=\ln{x} \\
\frac{d}{dx} g(x)=\frac{1}{e^{\ln{x}}} \\
\frac{d}{dx} \ln{x}=\frac{1}{x}\end{aligned}$$

Finally lets take a look that the derivative of logarithmic functions in
the form of $\log_a x$.

$$\begin{aligned}
\log_a x = \frac{\ln{x}}{\ln{a}} \\
\frac{d}{dx} \log_a x = \frac{d}{dx} \frac{\ln{x}}{\ln{a}} \\
\frac{d}{dx} \frac{\ln{x}}{\ln{a}} = \frac{1}{\ln{a}} * \frac{d}{dx} \ln{x} \\
= \frac{1}{\ln{a}} * \frac{1}{x} \\
\frac{d}{dx} \log_a x = \frac{1}{x\ln{a}}\end{aligned}$$

Now lets take a look at some examples,

Differentiate the following.

1.  $f(x)= 10^x-7^x$

2.  $g(x)= 20\ln{x}+log_123 x$

3.  $h(x)= x+7^x*8^x$

4.  $i(x)=\frac{1+4\ln{x}}{5x^3}$

We just solve using the formulas derived from this subsection.

1.  $f(x)= 10^x-7^x$\
    $$\begin{aligned}
    \frac{d}{dx} a^x = a^x\ln{a} \\
    f^{\prime}(x)=10^x\ln{10}-7^x\ln{7} \\\end{aligned}$$

2.  $g(x)= 20\ln{x}+log_123 x$\
    $$\begin{aligned}
    g^{\prime}(x)= \frac{20}{x} + \frac{1}{x\ln{123}}\end{aligned}$$

3.  $h(x)= x+7^x*8^x$\
    $$\begin{aligned}
    h^{\prime}(x)=1+(\frac{d}{dx}7^x *8^x)+(7^x*\frac{d}{dx}8^x)\\
    1+((7^x\ln{7})*8^x)+(7^x*(8^x\ln{8})) \\
    h^{\prime}(x)=56^x\ln{56}+1\end{aligned}$$

4.  $i(x)=\frac{1+4\ln{x}}{5x^3}$\
    $$\begin{aligned}
    \frac{[(5x^3)*(\frac{4}{x})]-[(1+4\ln{x})*15x^2]}{(5x^3)^2} \\
    \frac{20x^2-15x^2+60x^2\ln{x}}{25x^6} \\
    \frac{5x^2+60x^2\ln{x}}{25x^6} \\
    i^{\prime}(x)=\frac{1-ln(x^12)}{5x^4}\end{aligned}$$

### Inverse + Hyperbolic Functions

In this subsection, we are going to look at the derivatives of inverse
trig functions + introduce hyperbolic functions and find the derivatives
of them.

When looking at the derivatives of inverse trig functions, an important
thing to remember is our inverse functions derivative formula,
$$g^{\prime}(x)=\frac{1}{f^{\prime}(g(x))}$$

Knowing this formula, we can find the derivative of the inverse of sine
($\arcsin(x)$)

When using the inverse formula,

$$\begin{aligned}
\frac{1}{\cos(\arcsin(x))} \\\end{aligned}$$ since $\arcsin(x)$ can be
looked at as $sin(y)$, we can substitute it into the equation
$$\begin{aligned}
\frac{1}{\cos(y)} \\
\cos{y}=\sqrt{1-\sin^2y} \\\end{aligned}$$ Note: This is derived from
the equation, $\cos^2y+\sin^2y=1$ $$\begin{aligned}
\frac{d}{dx} sin^{-1}(x)=\frac{1}{\sqrt{1-x^2}}\end{aligned}$$

This same process if followed for the rest of the trig function, below
are the derivatives to all of them.

1.  $\frac{d}{dx}\sin^{-1}x=\frac{1}{\sqrt{1-x^2}}$

2.  $\frac{d}{dx}\cos^{-1}x=\frac{-1}{\sqrt{1-x^2}}$

3.  $\frac{d}{dx}\tan^{-1}x=\frac{1}{1+x^2}$

4.  $\frac{d}{dx}\csc^{-1}x=\frac{-1}{|x|\sqrt{x^2-1}}$

5.  $\frac{d}{dx}\sec^{-1}x=\frac{1}{|x|\sqrt{x^2-1}}$

6.  $\frac{d}{dx}\cot^{-1}x=\frac{-1}{1+x^2}$

Now onto hyperbolic functions, hyperbolic trigonometric functions are
equations for a hyperbola. They utilize the natural logarithm $e^x$.
Hyperbolic functions deal with curves in real world applications.

1.  $sinh(x) = \frac{e^x-e^{-x}}{2}$

2.  $cosh(x) = \frac{e^x+e^{-x}}{2}$

3.  $tanh(x) = \frac{e^x-e^{-x}}{e^x+e^{-x}}$

4.  $coth(x) = \frac{e^x+e^{-x}}{e^x+e^{-x}}$

5.  $sech(x) = \frac{2}{e^x+e^{-x}}$

6.  $csch(x) = \frac{2}{e^x-e^{-x}}$

These hyperbolic functions are used to model hanging ropes, wires,
threads, sky-driving routes etc.

In order to find the rate of change of these functions, we take the
derivative. Below are the derivatives of the hyperbolic trig functions,

1.  $\frac{d}{dx} sinh(x) = cosh(x)$

2.  $\frac{d}{dx} cosh(x) = sinh(x)$

3.  $\frac{d}{dx} tanh(x) = sech(x) sech(x)$

4.  $\frac{d}{dx} csch(x) = -csch(x)coth(x)$

5.  $\frac{d}{dx} sech(x) = -sech(x)tanh(x)$

6.  $\frac{d}{dx} coth(x) = -csch^{2}(x)$

Now lets look at some examples,

Differentiate the following.

1.  $f(x)=5\sin^{-1}(x)-cos^{-1}(x)$

2.  $g(x)=\frac{x+1}{\tan^{-1}(x)}$

3.  $h(x)=e^x \cosh(x)$

4.  $i(x)=\tan(x)\tanh(x)$

Solve using the methods discussed in this subsection.

1.  $f(x)=5\sin^-1(x)-cos^{-1}(x)$\
    $$\begin{aligned}
    f^{\prime}(x) = \frac{5}{\sqrt{1-x^2}}+\frac{1}{\sqrt{1-x^2}}\end{aligned}$$

2.  $g(x)=\frac{x+1}{\tan^{-1}(x)}$\
    $$\begin{aligned}
    g^{\prime}(x)=\frac{[1*\tan^{-1}(x)]-[(x+1)*\frac{1+x^2}]}{(\tan^{-1}(x))^2} \\
    \frac{\frac{(1+x^2)(\tan^{-1}(x))-x+1}{1+x^2}}{(\tan^{-1}(x))^2} \\
    g^{\prime}(x)=\frac{x^2\tan^{-1}(x)-x+\tan^{-1}(x)-1}{\tan^{-1}(x)^2(1+x^2)}\end{aligned}$$

3.  $h(x)=e^x \cosh(x)$\
    $$\begin{aligned}
    h^{\prime}(x)=(e^x*\cosh(x))+(e^x*\sinh(x))\end{aligned}$$

4.  $i(x)=\tan(x) \tanh(x)$\
    $$\begin{aligned}
    i^{\prime}(x)=(\sec^2(x)\tanh(x))+(\tan(x)*sech^{2}(x)) \\\end{aligned}$$

Chain Rule
----------

Chain Rule is one of the most important and most used rules for
differentiating in calculus. In is really important, because most
functions, don't come with only a single variable, but multiple.

For example, as of the previous chapters we couldn't solve an equation
like,

$$(3x+1)^2$$

However, with the use of chain rule, we open ourselves to a plethora of
different equations we can solve.

Chain rule breaks down the function into a composition in the form of
$(f \circ g)$. When broken down into a composition,

Chain Rule If we have two functions compositions that are both
differentiable then,
$\frac{d}{dx} f(g(x))=f^{\prime}(g(x))g^{\prime}(x)$

This theorem is best look at by example.

Solve these examples using chain rule

1.  $a(x)=(9+2x-x^3)^6$

2.  $b(x)=(14x^2-3x)^-2$

3.  $c(x)=\sin(4x+7x^4)$

4.  $d(x)=\tan(1-2e^x)$

5.  $e(x)=e^{1-x^2}$

6.  $f(x)= \frac{sin^2{x}}{1+cos^{x^2}}$

We first define these functions as compositions then we solve using our
chain rule.

1.  $a(x)=(9+2x-x^3)^6$\
    $$\begin{aligned}
    a^{\prime}(x)=6(9+2x-x^3)^5*(2-3x^2) \end{aligned}$$

2.  $b(x)=(14x^2-3x)^-2$\
    $$\begin{aligned}
    b^{\prime}(x)=-2(14x^2-3x)^-3*(28x-3)= \frac{-56x+6}{(14x^2-3x)^3}\end{aligned}$$

3.  $c(x)=\sin(4x+7x^4)$\
    $$\begin{aligned}
    c^{\prime}(x) = \cos(4x+7x^4) *(4+28x^3)\end{aligned}$$

4.  $d(x)=\tan(1-2e^x)$\
    $$\begin{aligned}
    d^{\prime}(x)=\sec^2(1-2e^x)*-2e^x\end{aligned}$$

5.  $e(x)=e^{1-x^2}$\
    $$\begin{aligned}
    e^{\prime}(x)=e^{1-x^2}*-2x\end{aligned}$$

6.  $f(x)= \frac{\sin^2{x}}{1+\cos(x^2)}$\
    $$\begin{aligned}
    f^{\prime}(x)=\frac{[2\sin{x}*(1+\cos(x^2)]-[\sin^2{x}*cos(x^2)*2x]}{[1+\cos(x+2)]^2} \\
    f^{\prime}(x)= \frac{\cos(x^2)\sin(2x)+2x\sin^2(x)\sin(x^2)+\sin(2x)}{(1+\cos(x^2))^2}\end{aligned}$$

Implicit Differentiation
------------------------

Implicit differentiation, lets us solve for equations that are not
explicit functions of x. For example, the following function, is
explicitly written in x, $$y=3x^3+\cos(8x)$$ All of our y variables are
on one side and all of your x variables + the constants are on the other
side. However, equations aren't always this nice. Sometimes, we have
implicit functions of x, for example, $$x^2+y^2=25$$

Implicit differentiation, is basically a rewrite of chain rule. The
whole idea stems around,

Implicit Differentiation. $$\frac{d}{dx}(f(x))^2 = 2f(x)f^{\prime}(x)$$

It's literally the same fundamental idea of chain rule. Looking back at
our example,

$$\begin{aligned}
\frac{d}{dx} x^2+y^2=\frac{d}{dx}25 \\
\frac{d}{dx}x^2 + \frac{d}{dx} y^2 = \frac{d}{dx}25 \\
2x+2yy^{\prime}=0 \\
2yy^{\prime}=-2x \\
y^{\prime} = \frac{-2x}{2y} = \frac{-x}{y}\end{aligned}$$

Lets work on a couple of examples,

Solve using implicit differentiation.

1.  $4x-6y^2=xy^2$

2.  $y^2-12x^3=8y$

3.  $\sin(y)+cos(y)=e^{4y}$

4.  $tan(3x+7y = 6-4x^{-1})$

Just use the same chain rule.

1.  $4x-6y^2=xy^2$\
    $$\begin{aligned}
    4-12yy^{\prime} = y^2 +2xyy^{\prime} \\
    4-y^2 = 12yy^{\prime} +2xyy^{\prime} \\
    4-y^2 = y^{\prime} (12y+2xy) \\
    y^{\prime} = \frac{4-y^2}{12y+2xy}\end{aligned}$$

2.  $y^2-12x^3=8y$\
    $$\begin{aligned}
    2yy^{\prime}-36x^2=8 \\
    2yy^{\prime}= 8+36x^2 \\
    y^{\prime}= \frac{8+36x^2}{2y} \\
    y^{\prime}= \frac{4+18x^2}{y}\end{aligned}$$

3.  $\sin(x)+cos(y)=e^{4y}$\
    $$\begin{aligned}
    \cos(x)-sin(y)y^{\prime}=4y^{\prime}e^4y \\
    \cos(x)= 4y^{\prime}e^4y+sin(y)y^{\prime} \\
    \cos(x)= y^{\prime}(4e^4y+sin(y)) \\
    y^{\prime}=\frac{\cos(x)}{(4e^4y+sin(y))}\end{aligned}$$

4.  $tan(3x+7y) = 6-4x^{-1}$\
    $$\begin{aligned}
    \sec^{2}(3x+7y)(7y^{\prime} +3)=\frac{4}{x^2} \\
    7y^{\prime}+3 = \frac{4}{x^2\sec^2(3x+7y)} \\
    y^{\prime}= \frac{4}{7x^2\sec^2(3x+7y)}-\frac{-3}{7}\end{aligned}$$

Some of these problems could have been solved by just isolating the y
variable, this way is easier, if you can isolate the y variable, always
do that first. If not you have to use implicit differentiation.

Related Rates
-------------

This section is one out of the 2 that calculus students find the most
difficult. Related rates focuses on the applications of what we have
learnt until now in calculus. Attention is heavily needed in these
sections, try to work out all of the examples yourselves + follow the
tips presented in this section.

Related rates problems combine two things, chain rule and implicit
differentiation.

Here are the steps below to solve chain rule problems:

1.  Read the problem carefully

2.  Draw a sketch

3.  Write out what you are given in the problem

4.  Write what you are solving for

5.  Differentiate and solve appropriately

These types of problems are best looked at by example,

Solve these by chain rule and implicit differentiation.

1.  The radius of a circle is decreasing at a rate of 4cm/min. How fast
    is the area and circumference of the circle changing when the radius
    is 8cm?

2.  The surface area of a snowball decreases at a rate of $6ft^2/hr$.
    How fast is the diameter changing when the radius is 2ft?

3.  A street light is mounted on a pole 24 ft tall. A man 6ft tall walks
    away from the pole at a rate of 4ft/s. How fast is the tip of his
    shadow moving when he is 20ft from the pole? How fast is the length
    of his shadow changing at this instant?

4.  A trough is 12ft long, 4ft wide, and 2ft high. The ends of the
    trough are isosceles triangles. Water is poured into the trough at
    $36ft^3/min$. How fast is the water level changing when the water is
    1 feet deep ?

These may seem really hard at first, but they really are not.

1.  The radius of a circle is decreasing at a rate of 4cm/min. How fast
    is the area and circumference of the circle changing when the radius
    is 8cm? $$\begin{aligned}
    r=8 \\
    \frac{dR}{dt} = -4 \\
    \frac{dA}{dt} =? \\
    \frac{dC}{dt} = ? \\
    A =\pi r^2 \\
    \frac{dA}{dt} = 2\pi r \frac{dR}{dt} \\
    \frac{dA}{dt} = -64\pi \\
    C =2 \pi r \\
    \frac{dC}{dt} =2\pi \frac{dR}{dt} \\
    \frac{dC}{dt} = -8\pi\end{aligned}$$

2.  The surface area of a snowball decreases at a rate of $6ft^2/hr$.
    How fast is the diameter changing when the radius is 2ft?
    $$\begin{aligned}
    r =2 \\
    d =4 \\
    \frac{dD}{dt} = ? \\
    \frac{dSA}{dt} = -6 \\
    SA = 4 \pi r^2 \\
    \frac{d}{2} = r \\
    SA = \pi d^2 \\
    \frac{dSA}{dt} = 2 \pi d \frac{dD}{dt} \\
    \frac{dD}{dt} = \frac{-3}{4 \pi}\end{aligned}$$

3.  A street light is mounted on a pole 24 ft tall. A man 6ft tall walks
    away from the pole at a rate of 4ft/s. How fast is the tip of his
    shadow moving when he is 20ft from the pole? How fast is the length
    of his shadow changing at this instant? $$\begin{aligned}
    \tan(\theta) = \frac{24}{x+s} \\
    \tan(\theta) = \frac{6}{s} \\
    \frac{24}{x+s} = \frac{6}{s} \\
    24s =6x+6s \\
    18s=6x \\
    s = \frac{x}{3} \\
    \frac{ds}{dt} = \frac{1}{3} \frac{dx}{dt} \\
    \frac{ds}{dt} = \frac{4}{3} \\
    l=\frac{4}{3}x \\
    \frac{dL}{dt} = \frac{4}{3} \frac{dx}{dt}
    \frac{dL}{dt} = \frac{16}{3}\end{aligned}$$

4.  A trough is 12ft long, 4ft wide, and 2ft high. The ends of the
    trough are isosceles triangles. Water is poured into the trough at
    $36ft^3/min$. How fast is the water level changing when the water is
    1 feet deep ? $$\begin{aligned}
    h =1 \\
    v = \frac{1}{2}lwh \\
    v = \frac{1}{2}(12)(2h)h \\
    v = 12h^2 \\
    \frac{dv}{dt} =12(2h) \frac{dh}{dt} \\
    \frac{dh}{dt} = 1.5 ft/min\end{aligned}$$

Higher Order Derivatives
------------------------

Higher order derivatives basically take the derivative of the
derivative, for example, a second order derivative is just,
$$(f^{\prime})^{\prime}$$

Its the derivative of the derivative. Its written as,
$$f^{\prime \prime}$$

A third order derivative is, $$(f^{\prime \prime})^{\prime}$$

etc.. for even higher order derivatives.

These higher order derivatives have their applications, and we are going
to be talking about them in the next chapter. Lets look at some examples
of solving these higher order derivatives,

Solve the following functions for the second derivative.

1.  $f(x)= \cos(2-7x^2)$

2.  $g(x)=\tan(3x)$

3.  $h(x)=\frac{1}{\sqrt{6x+x^4}}$

We first solve for the first derivative, then take the derivative again.

1.  $f(x)= \cos(2-7x^2)$\
    $$\begin{aligned}
    -\sin(2-7x^2)-14x \\
    14x\sin(2-7x^2) \\
    14\sin(2-7x^2)+14x(\cos(2-7x^2)*-14x) \\
    -196x^2\cos(2-7x^2)+14sin(2-7x^2)\end{aligned}$$

2.  $g(x)=\tan(3x)$\
    $$\begin{aligned}
    3\sec^2(3x) \\
    3[\sec(3x)]^2 \\
    18\sec^2(3x)\tan(3x)\end{aligned}$$

3.  $h(x)=\frac{1}{\sqrt{6x+x^4}}$\
    $$\begin{aligned}
    f^{\prime} = \frac{6+4x^3}{6x+x^4} \\
    \frac{[\frac{d}{dx}(6+4x^3)*6x+x^4]-[6+4x^3*\frac{d}{dx}6x+x^4]}{(6x+x^4)^2} \\
    f^{\prime \prime} = \frac{-27-6x^6}{(6x+x^4)^\frac{5}{2}}\end{aligned}$$

L'Hopital's Rule
----------------

L'hopitals rules deals with functions that are in indeterminate form.
Indeterminate form are commonly written as,
$\frac{0}{0} or \frac{\pm \infty}{\pm \infty}$. We cannot solve
functions that evaluate to such forms, first because in the
$\frac{0}{0}$ case, we don't know which to divide first, and second in
the $\frac{\pm \infty}{\pm \infty}$ example, infinity is not a real
number so we cant treat it as one all of the time, infinity just keeps
growing so we essentially cannot divide it.

Now to l'hopitals theorem,

L'hopitals Rule. Suppose that
$\displaystyle{\lim_{x \Rightarrow a}f(x) =0 or \pm \infty, \lim_{x \Rightarrow a}g(x)=0 or \pm \infty }$and
that functions f and g are differentiable on the interval. Then,
$\displaystyle{\lim_{x \Rightarrow a} \frac{f(x)}{g(x)}=\lim_{x \Rightarrow a} \frac{f^{\prime}(x)}{g^{\prime}(x)}}$.

Lets look at examples,

Solve the following limits, use l'hopitals if necessary.

1.  $\displaystyle{\lim_{x \Rightarrow 1} \frac{x^2+8x-9}{x^3-2x^2-5x+6}}$

2.  $\displaystyle{\lim_{x \Rightarrow 6} \frac{\sin(\pi x)}{\ln(x-5)}}$

3.  $\displaystyle{\lim_{x \Rightarrow -\infty} x^2e^x}$

4.  $\displaystyle{\lim_{x \Rightarrow 0^+} x^\frac{1}{x}}$

```{=html}
<!-- -->
```
1.  $\displaystyle{\lim_{x \Rightarrow 1} \frac{x^2+8x-9}{x^3-2x^2-5x+6}}$\
    $$\begin{aligned}
    \displaystyle{\lim_{x \Rightarrow 1} \frac{2x+8}{3x^2-4x-5}} \\
    \displaystyle{\frac{10}{-6} = \frac{-5}{3}}\end{aligned}$$

2.  $\displaystyle{\lim_{x \Rightarrow 6} \frac{\sin(\pi x)}{\ln(x-5)}}$\
    $$\begin{aligned}
    \frac{\cos(\pi x) \pi}{\frac{1}{x-5}} \\
    \frac{1(\pi)}{\frac{1}{1}} \\
    \pi\end{aligned}$$

3.  $\displaystyle{\lim_{x \Rightarrow -\infty} x^2e^x}$\
    $$\begin{aligned}
    \frac{e^x}{\frac{1}{x^2}} \\
    \frac{e^x}{\frac{-2}{x}} \\
    \frac{xe^x}{-2} \\
    0\end{aligned}$$

4.  $\displaystyle{\lim_{x \Rightarrow 0^+} x^\frac{1}{x}}$\
    $$\begin{aligned}
    \ln(y) = \ln(x^\frac{1}{x}) \\
    \ln(y) = \frac{\ln(x)}{x} \\
    \ln(y) = \frac{1}{x} \\
    \lim_{x \Rightarrow 0^+} e^\frac{1}{x} = \infty\end{aligned}$$

Also know that when using l'hopitals rule, the limit you are solving for
has to be in the form of $\frac{f(x)}{g(x)}$. If it isn't in this form
that it is your job to put it in that form first, then proceed with
l'hopitals.
