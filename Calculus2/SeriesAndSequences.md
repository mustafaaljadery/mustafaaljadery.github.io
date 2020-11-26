Series and Sequences
====================

In this chapter we are going to look at series and sequences. We first
got introduced to series and sequences back in our intermediate algebra
class, now we are going to introduce calculus topics with applications
to the series and sequences that we got introduced to in our algebra
class.

Sequences
---------

A sequence is just a set of terms, numbers, items. It is just a list. If
the sequence goes on forever then the sequence is called an infinite
sequence. If the sequence converges then the sequence is finite.

When looking at an infinite sequence, there are many notations,
$${a_1,a_2,...,a_n,a_{n+1},...} \quad \quad {a_n} \quad \quad {a_n}^{\infty}_{n=1}$$

That being said, we can think of $a_n$ as a function. Lets look at some
theorem with sequences,

Given the sequence ${a_n}$ if we have a function f(x) such that
$f(n)=a_n$ and $\lim_{x \to \infty} f(x)=L$ then
$\lim_{n \to \infty} a_n = L.$

Suppose that $a_n \leq b_n \leq c_n$ for all $n>N$, for some N. If
$\lim_{n \to \infty} a_n= \lim_{n \to \infty} c_n=L, then \lim_{n \to \infty} b_n=L.$

$\lim_{n \to \infty} |a_n|=0$ if and only if $\lim_{n \to \infty} a_n=0$

If a sequence is bounded and monotonic then it converges.

The same properties for limits that define convergence are the same as
the ones for sequences. So when looking at convergence, use the same
properties for limits.

Lets work on some examples,

Find wether the following sequences converge.

1.  $a_n=cos(\frac{1}{n})$

2.  $a_n=\frac{sin(n)}{n}$

```{=html}
<!-- -->
```
1.  $a_n=cos(\frac{1}{n})$\
    $$\begin{aligned}
    \lim_{n \to \infty} cos[\frac{1}{n}]= cos(0)=1 \\
    Converges\end{aligned}$$

2.  $a_n=\frac{sin(n)}{n}$ $$\begin{aligned}
    \frac{-1+0}{n} = \frac{-1}{n}=0 \\
    \text{we have to use the squeeze theorem} \\
    g(x) \leq f(x) \leq h(x) \\
    \lim_{x \to \infty} g(x)=L \quad \quad \lim_{x \to \infty} h(x)=L \\
    -1 \leq sin(n) \leq 1 \\
    \frac{-1}{n} \leq \frac{sin(n)}{n} \leq \frac{1}{n} \\
    0 \leq 0 \leq 0 \\
    \text{Converges}\end{aligned}$$

Series
------

A series is the sum of a sequence. This concept was introduced in
intermediate algebra. The series for our infinite sequence is the
following,

$${a_n}^{\infty}_{n=0} \quad \Rightarrow \quad \Sigma^{\infty}_{i=0} a_n= a_0+a_1+a_2+...$$

If the sequence ${s_n}$ is convergent and $\lim_{n \to \infty} s_n=s$
exists as a real number, then the series $\Sigma a_n$ is convergent. If
the sequence ${s_n}$ is divergent, then the series is called divergent.

One of the most important infinite series that were are going to look at
is the geometric series,
$$\Sigma^{\infty}_{n=1} ar^{n-1} \quad \quad a \neq 0$$

A geometric series is convergent if $|r|<1$ and the sum of the series is
equal to $\frac{a}{1-r}$. If $|r|\geq 1$, then the series is divergent.

This section was just meant to rehash information from intermediate
algebra, there are no practice problems for this section.

Testing Convergence/Divergence
------------------------------

We are going to dedicate a whole section for testing whether a series
converges or diverges because it is essential to the following tests
that we are going to learn.

If $\Sigma a_n$ converges then $\lim_{n \to \infty} a_n=0$.

Knowing this, we can talk about the divergence test. The divergence test
revolves around the same idea and the theorem above.

Divergence Test If $\lim_{n \to \infty} a_n \neq 0$ then $\Sigma a_n$
will diverge.

Now talking about absolute vs conditional convergence. A series is
absolutely convergent if both $\Sigma a_n$ and $\Sigma |a_n|$ are
convergent. A series is conditionally convergent is $\Sigma a_n$ is
convergent and $\Sigma |a_n|$ diverges. Lets look at some properties of
convergence,

1.  If the series $\Sigma a_n$ is absolutely convergent then the value
    of s will be obtained with any arrangement of $\Sigma a_n$.

2.  If the series $\Sigma a_n$ is conditionally convergent then there is
    a rearrangement of $\Sigma a_n$ that will hold for any real number.

Lets work on two examples,

Determine if the following series are convergent or divergent.

1.  $s_n=\frac{5+8n^2}{2-7n^2}$

2.  $s_n=\frac{n^2}{5+2n}$

Using the following theorem that we learned we can solve the following.

1.  $s_n=\frac{5+8n^2}{2-7n^2}$\
    $$\begin{aligned}
    \lim_{n \to \infty} s_n= \lim_{n \to \infty}o \frac{5+8n^2}{2-7n^2}=-\frac{8}{7} \\
    \text{The series converges at } -\frac{8}{7}\end{aligned}$$

2.  $s_n=\frac{n^2}{5+2n}$\
    $$\begin{aligned}
    \lim_{n \to \infty} s_n= \lim_{n \to \infty} \frac{n^2}{5+2n}= \infty \\
    \text{The series diverges.}\end{aligned}$$

Integral Test+Comparison Test
-----------------------------

### Integral Test

The integral test states the following,

Integral Test If a function f(x) is continuous, positive and decreasing
on an interval then,

1.  If $\int^{\infty}_{k} f(x) dx$ is convergent, the so is the series
    $\Sigma^{\infty}_{n=k} a_n.$

2.  If $\int^{\infty}_{k} f(x) dx$ is divergent, then the series
    $\Sigma^{\infty}_{n=k} a_n$ is the same.

Furthermore, we can talk about the p-series test which is defined as the
following,

p-series Test If $h>0$ then $\Sigma^{\infty}_{n=h} \frac{1}{n^p}$
converges if p\>1 and diverges if $p \leq 1$.

Now lets work on some examples with the integral test.

Solve the following using the integral test for convergence/divergence.

1.  $\Sigma^{\infty}_{n=1} ne^{-n^2}$

2.  $\Sigma^{\infty}_{n=2} \frac{1}{n ln(n)}$

```{=html}
<!-- -->
```
1.  $\Sigma^{\infty}_{n=1} ne^{-n^2}$\
    $$\begin{aligned}
    \int^{\infty}_{1} xe^{-x^2}dx \\
    \lim_{b \to \infty} \int^{b}_{1} xe^{-x^2}dx \\
    \frac{1}{2}\lim_{b \to \infty} [-e^{-b^2}-(-e^{-1})]=\frac{1}{2e}\end{aligned}$$

2.  $\Sigma^{\infty}_{n=2} \frac{1}{n ln(n)}$\
    $$\begin{aligned}
    \int^{\infty}_{2} \frac{1}{xln(x)}dx \\
    \lim_{b \to \infty} \int^{b}_{2}\frac{1}{xln(x)}dx \\
    \lim_{b \to \infty} ln(ln(x))]^{b}_{2} \\
    \lim_{b \to \infty}ln(ln(b))-ln(ln(2))=\infty\end{aligned}$$

### Comparison Test

Following the name, the comparison test work to compare two series to
each other.

Comparison Test Suppose that we have a second series $\Sigma b_n$,
$$a_n,b_n > 0 \quad \text{for all n}$$
$$\Sigma^{\infty}_{n=1}b_n \quad \text{converges,} \quad a_n \leq b_n \quad \text{for all} \quad n \Rightarrow \Sigma^{\infty}_{n=1}a_n \quad \text{Converges}$$
$$\Sigma^{\infty}_{n=1} b_n \quad \text{diverges,} \quad a_b \geq b_n \quad \text{for all n } \quad \Rightarrow \Sigma^{\infty}_{n=1}a_n \quad \text{diverges}$$

Limit Comparison Test Assuming we have the same property,
$a_n,b_n > 0 \quad \text{for all n}$, for our two series,
$$c = \lim_{n \to \infty} \frac{a_n}{b_n}$$ If c is positive and is
finite, the both series either converge or both series diverge.

1.  $\Sigma^{\infty}_{n=1} \frac{1}{n^2+1}$

2.  $\Sigma^{\infty}_{n=1} \frac{2^{\frac{1}{n}}}{n}$

```{=html}
<!-- -->
```
1.  $\Sigma^{\infty}_{n=1} \frac{1}{n^2+1}$\
    $$\begin{aligned}
    n^2+1>n^2 \quad \quad n \geq 1 \\
    \frac{1}{n^2+1}<\frac{1}{n^2} \quad \quad n>1 \\
    \Sigma^{\infty}_{n=1} \frac{1}{n^2} \quad \quad \text{This series converges} \\
    \text{Thus, } \quad \Sigma^{\infty}_{n=1} \frac{1}{n^2+1} \leq \Sigma^{\infty}_{n=1} \frac{1}{n^2}\end{aligned}$$

2.  $\Sigma^{\infty}_{n=1} \frac{2^{\frac{1}{n}}}{n}$\
    $$\begin{aligned}
    2^{\frac{1}{n}}= \sqrt[n]{2} >1 \quad \text{for all n that is greater than 1} \\
    \frac{2^{\frac{1}{n}}}{n}>\frac{1}{n} \\
    \Sigma^{\infty}_{n=1} \frac{1}{n} \quad \quad \text{Diverges} \\
    \Sigma^{\infty}_{n=1} \frac{2^{\frac{1}{n}}}{n}\end{aligned}$$

Alternating Series Test
-----------------------

In all of the following tests, we are going to test for convergence. One
of the tests we are going to talk about is the alternating series test.
The alternating series test states the following,

Alternating Series Test If we have a series in the form of
$a_n=(-1)^{n+1}*b_n, b_n>0$ for all n and $b_n$ is decreasing.

If $\lim_{n \to \infty} b_n=0 \Rightarrow \Sigma^{\infty}_{n=1} a_n$
converges.

That being said, lets work on some examples with the alternating series
test.

1.  $\Sigma^{\infty}_{n=1} (-1)^{n+1}*(\frac{5n+3}{2n-7})$

2.  $\Sigma^{(-1)^{n+1}}_{5^n}$

3.  $\Sigma^{\infty}_{n=1} (-1)^n*\frac{n}{ln(n)}$

```{=html}
<!-- -->
```
1.  $\Sigma^{\infty}_{n=1} (-1)^{n+1}*(\frac{5n+3}{2n-7})$\
    $$\begin{aligned}
    \lim_{n \to \infty} \frac{5n+3}{2n-7} \\
    \lim_{n \to \infty} \frac{5}{2} = \frac{5}{2} \\
    \lim_{n \to \infty} b_n \neq 0 \\
    \text{This series Diverges}\end{aligned}$$

2.  $\Sigma^{(-1)^{n+1}}_{5^n}$\
    $$\begin{aligned}
    \Sigma^{\infty}_{n=1} (-1)^{n+1}*\frac{1}{5^n} \\
    \lim_{n \to \infty} \frac{1}{5^n} = \frac{1}{\infty} =0 \\
    a_{n+1} \leq a_n \quad \quad \frac{1}{5^{n+1}} \leq \frac{1}{5^n} \\
    \text{Converges}\end{aligned}$$

3.  $\Sigma^{\infty}_{n=1} (-1)^n*\frac{n}{ln(n)}$\
    $$\begin{aligned}
    \lim_{n \to \infty} \frac{n}{ln(n)} = \lim_{n \to \infty} \frac{1}{\frac{1}{n}} \\
    \lim_{n \to \infty} n = \infty\\
    \text{The series Diverges}\end{aligned}$$

Root and Ratio Test
-------------------

### Root Test

The ratio test tests for absolute convergence. It states the following,

Root Test Suppose that $\lim_{n \to \infty} \sqrt[n]{|a_n|}=L$

1.  If L\<1, then $\Sigma a_n$ converges absolutely.

2.  If L\>1, or the limit goes to $\infty$, then $\Sigma a_n$ diverges.

3.  If L=1, or L does not exist, then the test is inconclusive and we
    say the Ratio test is inconclusive. More work has to be done to find
    and answer.

Furthermore, we have the following fact,

$$\lim_{n \to \infty} n^{\frac{1}{n}}=1$$

Now lets work on some examples,

1.  $\Sigma^{\infty}_{n=1} [\frac{3+5n}{2+3n}]^n$

2.  $\Sigma^{\infty}_{n=1} [\frac{1}{n^2}+\frac{1}{n}]^n$

```{=html}
<!-- -->
```
1.  $\Sigma^{\infty}_{n=1} [\frac{3+5n}{2+3n}]^n$\
    $$\begin{aligned}
    \lim_{n \to \infty} |a_n|^\frac{1}{n} \\
    \lim_{n \to \infty} [[\frac{3+5n}{2+3n}]^n]^{\frac{1}{4}} \\
    \lim_{n \to \infty} \frac{3+5n}{2+3n} \\
    \lim_{n \to \infty} \frac{5}{3} \\
    \frac{5}{3}>1 \quad \quad \text{Diverges}\end{aligned}$$

2.  $\Sigma^{\infty}_{n=1} [\frac{1}{n^2}+\frac{1}{n}]^n$\
    $$\begin{aligned}
    \lim_{n \to \infty} ([\frac{1}{n^2}+\frac{1}{n}]^n)^{\frac{1}{n}} \\
    \lim_{n \to \infty} [\frac{1}{n^2}+\frac{1}{n}]=0+0 \\
    0<1 \quad \quad \text{converges}\end{aligned}$$

### Ratio Test

Another test that tests for absolute convergence is the ratio test and
it is defined as the following.

Ratio Test When dealing with the series $\Sigma a_n$,
$$L=\lim_{n \to \infty} |\frac{a_{n+1}}{a_n}|$$

1.  If L\<1 then the series is absolutely convergent.

2.  If L\>1 then the series is divergent.

3.  If L=1 then the ratio test is inconclusive.

Using this definition, lets work on some examples,

1.  $\Sigma^{\infty}_{n=1} \frac{3^n}{n!}$

2.  $\Sigma^{\infty}_{n=1} \frac{3^{n+2}*n^2}{4^n}$

```{=html}
<!-- -->
```
1.  $\Sigma^{\infty}_{n=1} \frac{3^n}{n!}$\
    $$\begin{aligned}
    a_n=\frac{3^n}{n!} \\
    a_{n+1}= \frac{3^{n+1}}{(n+1)!} \\
    \lim_{n \to \infty} |\frac{a_n+1}{1}*\frac{1}{a_n}| \\
    \lim_{n \to \infty} |\frac{3^{n+1}}{(n+1)!}*\frac{n!}{3^n}| \\
    \lim_{n \to \infty} |\frac{3}{n+1}|=0 <1 \\
    \text{This series converges.}\end{aligned}$$

2.  $\Sigma^{\infty}_{n=1} \frac{3^{n+2}*n^2}{4^n}$\
    $$\begin{aligned}
    \lim_{n \to \infty} |\frac{a_n+1}{1}*\frac{1}{a_n}| \\
    \lim_{n \to \infty} |\frac{3^{n+3}*(n+1)^2}{4^{n+1}}*\frac{4^n}{3^{n+2}*n^2}| \\
    \lim_{n \to \infty}|\frac{3^{n+2}*3^1}{4^n*4^1}*\frac{(n+1)^2}{n^2}*\frac{4^n}{3^{n+2}}| \\
    \frac{3}{4} \lim_{n \to \infty} |\frac{(n+1)^2}{n^2}| \\
    \frac{3}{4} \lim_{n \to \infty} |1+2*\frac{1}{n}+\frac{1}{n^2}| \\
    \frac{3}{4}(1) \\
    \frac{3}{4}<1 \quad \quad \text{Converges}\end{aligned}$$

Power Series
------------

A power series is a series that is written in the form of,

$$\Sigma^{\infty}_{n=0} c_n(x-a)^n$$

Important things about the power series that we are going to note are
the radius and the interval of convergence.

Radius of Convergence There is a number R that our power series will
converge for, \|x-a\|\<R and will diverge for \|x-a\|\>R

Interval Of Convergence The interval of convergence of an interval is
a-R\<x\<a+R

Interval of convergence is closely tied to the radius of convergence.

Determine the radius and interval of convergence of the following
series.

1.  $\Sigma^{\infty}_{n=0} \frac{x^n}{n!}$

2.  $\Sigma^{\infty}_{n=0} n!x^n$

```{=html}
<!-- -->
```
1.  $\Sigma^{\infty}_{n=0} \frac{x^n}{n!}$\
    $$\begin{aligned}
    \lim_{n \to \infty} |\frac{U_n+1}{U_n}|< 1 \\
    U_{n + 1} = \frac{x^{n+1}}{(n+1)!} \quad \quad U_n= \frac{x^n}{n!} \\
    \lim_{n \to \infty} |\frac{x^n*x}{(n+1)n!}*\frac{n!}{x^n}| \\
    \lim_{n \to \infty} |\frac{1}{n+1}||x| \\
    0|x|= 0 \\
    R = \infty \quad \quad I(-\infty,\infty) \end{aligned}$$

2.  $\Sigma^{\infty}_{n=0} n!x^n$\
    $$\begin{aligned}
    \lim_{n \to \infty} |\frac{(n+1)!x^{n+1}}{n!x^n}| \\
    \lim_{n \to \infty} |n+1|*|x|=|x|* \lim_{n \to \infty} |n+1| \\
    \infty \\
    R=0 \quad \quad I(0)\end{aligned}$$

Taylor and Maclaurin Series
---------------------------

A taylor series is a series that is defined as the following,

Taylor Series f(x)= $\Sigma^{\infty}_{n=0} \frac{f^{(n)}(a)}{n!}(x-a)^n$

Maclaurin Series f(x)= $\Sigma^{\infty}_{n=0} \frac{f^{(n)}(0)}{n!}x^n$

Furthermore, we can define the remainder to be the error of the taylor
series and it is defined as the following,

$$R_n(x)=f(x)-T_n(x)$$

What stems from this is this theorem,

If $f(x)=T_n(x)+R_n(x)$ then,
$$\lim_{n \to \infty} R_n(x)=0 \quad \quad |x-a|<R$$
$$f(x)=\Sigma^{\infty}_{n=0}\frac{f^{(n)}(a)}{n!}(x-a)^n \quad \quad |x-a|<R$$

Lets work on some example,

Find the taylor/maclaurin series for the functions.

1.  $f(x)=e^x \quad \quad c=3$

2.  $f(x)=\sin(x) \quad \quad c=0$

3.  $f(x)=cos(x) \quad \quad c=0$

```{=html}
<!-- -->
```
1.  $f(x)=e^x \quad \quad c=3$\
    $$\begin{aligned}
    f^{\prime}(x)=e^x=f^{\prime \prime}=f^{\prime \prime \prime}= f^{4}(x) \\
    f(3)=e^3=f^{\prime}(3)=f^{\prime \prime}(3) \\
    f(x)=f(c)+f^{\prime}(c)(x-c)+\frac{f^{\prime \prime}(x-c)^2}{2!}+\frac{f^{\prime \prime \prime}(c)(x-c)^3}{3!}+... \\
    e^x=e^3+e^3(x-3)+\frac{e^3(x-3)^2}{2!}+\frac{e^3(x-3)^3}{3!}+... \\
    e^x = \Sigma^{\infty}_{n=0}\frac{e^3(x-3)^n}{n!}\end{aligned}$$

2.  $f(x)=\sin(x) \quad \quad c=0$\
    $$\begin{aligned}
    f^{\prime}=\cos(x)=f^{5} \\
    f^{\prime \prime}=- \sin(x)=f^{6} \\
    f^{\prime \prime \prime} - \cos(x)=f^{7} \\
    f^{4}=\sin(x)=f^{8} \\
    f(0)=0 \\
    f^{\prime}(0)=1=f^5 \\
    f^{\prime \prime}(0)=0=f^6 \\
    f^{\prime \prime \prime}(0)=-1=f^7 \\
    f^4(0)=0=f^8 \\
    f(x)=f(0)+f^{\prime}(0)(x)+\frac{f^{\prime \prime}(0)x^2}{2!}+\frac{f^{\prime \prime \prime}x^3}{3!}+... \\
    f(x)=0+x+0+\frac{-x^3}{3!}+0+\frac{x^5}{5!}+0-\frac{x^7}{7} \\
    \Sigma^{\infty}_{n=0} \frac{x^{2n+1}}{(2n+1)!}(-1)^n\end{aligned}$$

3.  $f(x)=cos(x) \quad \quad c=0$\
    $$\begin{aligned}
    \frac{d}{dx}[sin(x)]=\frac{d}{dx}[x-\frac{x^3}{3!}+\frac{x^5}{5!}-\frac{x^7}{7!}+...] \\
    cos(x)=[1-\frac{x^2}{2!}+\frac{x^4}{4!}-\frac{x^6}{6!}+...] \\
    \Sigma^{\infty}_{n=0} \frac{x^{2n}}{(2n)!}(-1)^n\end{aligned}$$