## 0.1 Functions

### Introduction To Functions {docsify-ignore}

Mathematicians and Scientists use functions to describe the relationship between variables and quantities.

**Definition:**
If a variable y depends on a variable x in such a way that each value of x determines exactly one value of y, then we say that *y is a function of x.*

Another way to define a function is to think of it as a machine. The machine takes in an input and produces and output.

![Computer Function Example](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/Computer_Function.PNG?raw=true)

Here we can see that the machine itself is an object so we can define it as say f. Thus giving us a new definition for a function:

A function f is a rule that associates a unique output with each input. If the input is denoted by x, then the output is denoted by f(x). ( The word "unique" means exactly one)

### Independent and Dependent Variables {docsify-ignore}
For any input of x, the output of a function is the value of f at x. Sometimes the output of functions are denoted by a single letter, say y:

"Insert Picture"

The x variable above is the Independent Variable and the y is the Dependent Variable, this makes sense because  doesn't depend on anything, you definite it yourself, while the y depends on what you give in for x.

**Example: Functional Relationships**

#### $f(0)=3$ {docsify-ignore}
f associates y=3 with x=0.
#### $f(1)=4$ {docsify-ignore}
f associates y=4 with x=1.
#### $f(2)=-1$ {docsify-ignore}
f associates y=-1 with x=2.
#### $f(3)=6$ {docsify-ignore}
f associates y=6 with x=3.

**Example:**

### $\hspace{2cm}y=3x^2-4x+2 \\\\ \hspace{1.6cm}f(x)=3x^2-4x+2$ {docsify-ignore}

#### $f(0)=3(0)^2-4(0)+2=2$ {docsify-ignore}
f associates y=2 with x=0.
#### $f(-1.7)=3(-1.7)^2-4(-1.7)+2=17.47$ {docsify-ignore}
f associates y=17.47 with x=-1.7.
#### $f(\sqrt{2})=3(\sqrt{2})^2-4(\sqrt{2})+2=8-4\sqrt{2}$ {docsify-ignore}
f associates $y=8-4\sqrt{2}$ with $x=\sqrt{2}$.

### Graphs of Functions: {docsify-ignore}

If a function f is real valued then the graph of the function in the xy-plane is defined as the graph of the equation.


**Graphs of Common Functions:**

### $f(x)=x$ {docsify-ignore}
![Graph of y=x](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/y%3Dx.png?raw=true)
### $f(x)=x^2$ {docsify-ignore}
![Graph of y=x^2](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/y%3Dx%5E2.png?raw=true)
### $f(x)=x^3$ {docsify-ignore}
![Graph of y=x^3](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/y%3Dx%5E3.png?raw=true)
### $f(x)=\frac{1}{x}$ {docsify-ignore}
![Graph of y=1/x](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/y%3Dx%5E-1.png?raw=true)
### $f(x)=\sqrt{x}$ {docsify-ignore}
![Graph of y=x^(1/2)](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/y%3Dsqrtx.png?raw=true)
### $f(x)=\sqrt[3]{x}$ {docsify-ignore}
![Graph of y=x^(1/3)](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/y%3Dcuberootx.png?raw=true)

Graphs can help provide visual information about a function.

### The Vertical Line Test {docsify-ignore}
The Vertical Line Test is best described by example:

![The Vertical Line Test Example](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/Vertical_Line_Test_Example.PNG?raw=true)

The curve in this example can't be a function. From our knowledge of the xy-plane, we know that each point on the graph can we written as (x,y) or (x, f(x)). Now lets take a look at the curve, we have two different points, (a,b) and (a,c). "a", our independent variable outputs two different points "b" and "c", thus making it not a function.

**The Formal Definition of The Vertical Line Test:**
A curve in the xy-plane is the graph of some function f if and only if no vertical line intersects the curve more than once.

**Example:**
### $x^2+y^2=25$ {docsify-ignore}
![x^2+y^2=25](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/x%5E2%2By%5E2%3D25.png?raw=true)

This certainly is not a function as there are many vertical lines that touch the curve of the graph at more than one point.

### The Absolute Value Function {docsify-ignore}
$
\left|x\right| = \left\{
        \begin{array}{ll}
            -x & \quad x < 0 \\
            x & \quad x \geq 0
        \end{array}
    \right.
$

The absolute value function strips out the minus sign if the input is less than 0 and leaves the input alone of its more than or equal to zero.

**Examples**

$$|5|=5 \hspace{1cm}|0|=0 \hspace{1cm}   |-7|=-7$$

Properties of The Absolute Value Function:

"insert"
 A number and its negative have the same absolute value.
 The absolute value of a product is the product of the absolute values.
 The absolute value of a ratio is the ratio of the absolute values.
 The triangle inequality.

### Piece-wise Defined Functions {docsify-ignore}
**Definition:**
A piece-wise function is a function built from pieces of different functions over different intervals.

$
f(x) = \left\{
        \begin{array}{ll}
            0 & \quad x \leq -1 \\
            \sqrt{1-x^2} & \quad -1<x<1 \\
            x & \quad x \geq 1
        \end{array}
    \right.
$

![Piece-wise Function Graph](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/0.0_Picewise.png?raw=true)

The formula above changes at the points x=-1 and x=1(The breakpoints of the formula). To graph piece-wise functions, you graph each equations on its respective domain.

### Domain and Range {docsify-ignore}
**Domain:**
The allowable inputs in an equation(x-values).

**Range:**
The set of outputs as x varies over the domain(y-values).


The domain can sometimes have restrictions: physical, geometrical, or by the formula itself. For example. when defining the length of the sides of a certain shape, your domain can't have negative values. However, the most common form of domain restrictions we are going to see throughout calculus are mrestrictions by mathematical formula. For example, in the formula $\frac{1}{x}$, xcan't be negative, otherwise the formula isn't defined. Furthermore, in the formula $\sqrt{x}$, x cannot be a negative as the result wouldn't be a real number.

**Definition**

If a real valued function of a real variable is defined by a formula, and if no domain is stated explicitly,, then it is to be understood that the domain consists of all real vnumbers for which the formula yeilds a real value. This is called the **natural domain** of a function.

**Examples** 

Find the natural domain of the following formulas:

##### **(a) $f(x)=x^3$** {docsify-ignore}

If we plug in any real value of x, we wouldn't get a problem. So our natural domain is the interval $(-\infty,+\infty)$.

##### **(b) $f(x)=\frac{\displaystyle 1}{\displaystyle [(x-1)(x-3)]}$** {docsify-ignore}

The function f, is defined on all of the domain except when $x=1$ & $x=3$. When $x=1$ or $3$, the denominator would equal 0, which is undefined. Our natural domain therefore is $(-\infty,1)\cup(1,3)\cup(3,+\infty)$.

> Note: $\cup$(Union): The collection of sets in a set of all elements. It connects sets of terms together.

##### **(c) $f(x)=\tan x$** {docsify-ignore}
$f(x)=\frac{\sin x}{\cos x}$

The natural domain is the set of all real numbers except when $\cos x=0$. $\cos x=0$ at $\pm\frac{\pi}{2},\pm\frac{3\pi}{2},\pm\frac{5\pi}{2}...$ 

##### **(d) $\sqrt{x^2-5x-6}$** {docsify-ignore}
$\sqrt{(x-2)(x-3)}$

The natural domain of this formula is all real values except when $(x-2)(x-3)$ are negative:

$$(-\infty,2]\cup[3,+\infty)$$

> Note: "[]" vs. "()": You use the big brackets when the set includes that term and the small brackets when the set doesn't include that term.

### The Effect Of Algebraic Operations On Domain

This concept is best describe by example:

$$f(x)=\frac{x^2-4}{x-2}$$

The natural domain of this function is pretty easy to find, the denominator can't equal zero, so x can't be 2.

Natural Domain: $(-\infty,2)\cup(2,+\infty)$

However, what if we simply the expression?

$$\frac{(x-2)(x+2)}{(x-2)} \rightarrow (x+2)$$

The (x-2)'s cancel out leaving us with (x+2). (x+2) has no domain restrictions, however we always have to keep in mind the domain restrictions from the original function.

$$(x+2), \R \thinspace except \thinspace x=2$$

**Examples**

Find the domain and range of:

##### **(a) $f(x)=2+\sqrt{x-1}$** {docsify-ignore}
**Domain:**

$\sqrt{x-1}$ can't be negative.
$$[1,+\infty)$$


**Range:**

![Graph of Function](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/2%2Bsqrt(x-1).png?raw=true)

$$[2,+\infty)$$

##### **(b) $f(x)=\frac{x+1}{x-1}$** {docsify-ignore}
**Domain:**

$$(x-1)\neq0 \rightarrow x\neq1 \\ (-\infty,1)\cup(1,+\infty)$$

**Range:**

In order to get the range we solve for x:

$
\begin{aligned}
y=\frac{x+1}{x-1} \\
(x-1)y=x+1 \\
yx-y=x+1 \\
yx-y-x=1 \\
yx-x=y+1 \\
x(y-1)=y+1 \\
x=\frac{y+1}{y-1} \rightarrow y\neq1
\end{aligned}
$
$$(-\infty,1)\cup(1,+\infty)$$

### Exercises {docsify-ignore}
#### 1) Let $\thinspace f(x)=\sqrt{x+1}+4$.

##### a) The natural domain of f is _______? {docsify-ignore}

$\sqrt{x+1}$ can't be negative
$[-1,+\infty)$

##### b) $f(3)=$_______? {docsify-ignore}

$
\begin{aligned}
\sqrt{(3)+1}+4 \\
\sqrt{4}+4 \\ 
2+4 \\
6
\end{aligned}
$

##### c) $f(t^2-1)=$ _______? {docsify-ignore}

$
\begin{aligned}
\sqrt{(t^2-1)+1}+4 \\
\sqrt{t^2}+4 \\
\left|t\right|+4
\end{aligned}
$

##### d) $f(x)=7$ if $x=$ _______? {docsify-ignore}

$
\begin{aligned}
\sqrt{x+1}+4=7 \\
\sqrt{x+1}=3 \\
(\sqrt{x+1})^2=(3)^2 \\
x+1=9 \\
x=8
\end{aligned}
$

##### e) The range of f is _______? {docsify-ignore}

The easiest way to find the range of this function is to graph it:

![Graph Of The Function](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/4%2Bsqrt(x%2B1).png?raw=true)

$[4,+\infty)$

#### 2. Line segments in an xy-plane form "letters" as depicted: {docsify-ignore}

![LIMITS Example](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/Limits.PNG?raw=true)

##### a) If the y-axis is parallel to the letter I, which of the letters represent the graph of $y=f(x)$ for some function f?{docsify-ignore}

Here we would use the Vertical Line Test.
The only letter that passes the vertical line test is the letter M.

##### b) What if the y-axis was perpendicular to the letter I?{docsify-ignore}
If the y-axis was perpendicular to the letter I, we would use the horizontal line test. The two I's are the only ones that pass the test.

#### 3. The accompanying figure shows the complete graph of $y=f(x)$. {docsify-ignore}

![Graph of f(x)](https://github.com/mustafaaljadery/mustafaaljadery.github.io/blob/master/Images/0.0_question_4.PNG?raw=true)

##### a) The domain of f is _____? {docsify-ignore}

$[-3,3)$

##### b) The range of f is _____? {docsify-ignore}

$[-2,2]$

##### c) $f(-3)=$ _____? {docsify-ignore}

At $x=-3$, $y=1$
$f(-3)=1$

##### d) $f(\frac{1}{2})$ _____? {docsify-ignore}

At $x=\frac{1}{2}$, $y=1$

##### e) The solutions to $f(x)=\frac{-3}{2}$ are x= _____ ?and x = _____? {docsify-ignore}

At $y=\frac{-3}{2}$, $x=\frac{-3}{4}$ & $\frac{-3}{2}$

#### 4.The accompanying table gives a 5-day forecast of high and low temperatures in degrees Fahrenheit {docsify-ignore}

##### a) Suppose that x and y denote the respective high and low temperature predictions for each of the 5 days. Is y a function of x? If so, give the domain and range of this function. {docsify-ignore}

For every unique input (high) there is an output (low), so it is a function.


Domain: {$65,70,71,73,75$}


Range: {$48,50,52,56$}

##### b) Suppose that x and y denote the respective low and high temperature predictions for each of the 5 days. Is y a function of x? If so, give the domain and range of this function. {docsify-ignore}

No, y is not a function of x because the input "52" has 2 different outputs.

### 5. Let l, w, and A denote the length, width and area of a rectangle, respectively, and suppose that the width of the rectangle is half the length. {docsify-ignore}

#### a) If l is expressed as a function of w, then l=_____? {docsify-ignore}

$2w$

#### b) If A is expressed as a function of l, then A=_____? {docsify-ignore}

$
\begin{aligned}
L=2w \\
\frac{L}{2}=w\\
A=L*w \\
A=\frac{L}{1}*\frac{L}{2} \\
A=\frac{L^2}{2}
\end{aligned}
$

#### c) If w is expressed as a function of A, then w=_____? {docsify-ignore}

$
\begin{aligned}
A=\frac{L^2}{2} \\
A=\frac{2w^2}{2} \\
2A=2w^2 \\
\frac{A}{2}=w^2 \\
w=\sqrt{\frac{A}{2}}
\end{aligned}
$



## 0.2 New Functions From Old
Coming Soon


## 0.3 Families of Functions
Coming Soon


## 0.4 Inverse Functions
Coming Soon 


## 0.5 Exponential and Logarithmic Functions
Coming Soon 