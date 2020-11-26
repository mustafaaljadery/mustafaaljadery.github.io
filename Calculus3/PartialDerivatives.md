Partial Derivatives
===================

In this section, we are going to add to our definition of derivatives so
that we can use them with functions of multiple variables.

Multivarible Functions
----------------------

A multivariable function is just a function that takes more than one
input. In our usualy f(x) = y functions, we have only one input, x. In
our multivariable functions, we can have an infinite number of inputs.
The most common multivariable functions we are going to look at are,
f(x,y) and f(x,y,z).

Limits
------

Here we have one theorem,

A multivariable function in the form of f(x,y) is continuous on the
point (a,b) if, $$\lim_{(x,y)\to (a,b)}f(x,y)=f(a,b)$$

Partial Derivatives
-------------------

When looking at a multivariable function in the form of f(x,y), we can
take the partial derivative with respect to x by,

$$f_x(a,b)= g^{\prime}(a) \quad where \quad g(x)=f(x,b)$$

Using limits we can definite the limits with respect to x and y as the
following,

$$f_x(a,b)= \lim_{h \to 0} \frac{f(a+h,b)-f(a,b)}{h}$$

$$f_y(a,b)= \lim_{h \to 0} \frac{f(a,b+h)-f(a,b)}{h}$$

Looking at the notations for partial derivatives,

$$f_x(x,y)= f_x= \frac{\partial f}{\partial x}= \frac{\partial}{\partial x}f(x,y)$$

$$f_y(x,y)=f_y=\frac{\partial f}{\partial y}= \frac{\partial}{\partial y}f(x,y)$$

To summarize,

1.  To find $f_x$, regard y as a constant and differentiate f(x,y) with
    respect to x.

2.  To find $f_y$, regard x as a constant and differentiate f(x,y) with
    respect to y.

Higher Order Partial Derivatives
$$(f_x)_x = f_{xx}= \frac{\partial}{\partial x}(\frac{\partial f}{\partial x})= \frac{\partial^2 f}{\partial x^2}$$
$$(f_x)_y= f_{xy}=\frac{\partial}{\partial y}(\frac{\partial f}{\partial x})= \frac{\partial^2 f}{\partial y \partial x}$$
$$(f_y)_x = f_{xy}= \frac{\partial}{\partial x} (\frac{\partial f}{\partial y})= \frac{\partial^2 f}{\partial x \partial y}$$
$$(f_y)_y= f_{yy}= \frac{\partial}{\partial y}(\frac{\partial f}{\partial y})= \frac{\partial^2 f}{\partial y^2}$$

Clairaut's Theorem If a function f is defined on a disk F that contains
the point (a,b). If the functions $f_{xy}$ and $f_{yx}$ are continuous
on the disk then, $$f_{xy}(a,b)=f_{yx}(a,b)$$

Chain Rule
----------

### Case 1

Suppose that z = f(x,y) is a function of x and y where x = g(t) and y =
h(t). Then z is a differentiable function of t and
$$\frac{dz}{dt}= \frac{\partial f}{\partial x} \frac{dx}{dt}+ \frac{\partial f}{\partial y} \frac{dy}{dt}$$

### Case 2

Suppose that z = f(x,y) is a function of x and y, where x = g(s,t) and
y=h(s,t). Then,
$$\frac{\partial z}{\partial s}=\frac{\partial z}{\partial x}\frac{\partial x}{\partial s}+\frac{\partial z}{\partial y}\frac{\partial y}{\partial s} \quad \quad \frac{\partial z}{\partial t}= \frac{\partial z}{\partial x} \frac{\partial x}{\partial t}+ \frac{\partial z}{\partial y}\frac{ \partial y}{\partial t}$$

### General Chain Rule

If u is s differential function of n variables and each of those
variables are a differential function of m variables. Then,
$$\frac{\partial u }{\partial t_i}= \frac{\partial u}{\partial x_1}\frac{\partial x_1}{\partial t_i}+\frac{\partial u}{\partial x_2}\frac{\partial x_2}{\partial t_i}+...+\frac{\partial u}{\partial x_n}\frac{\partial x_n}{\partial t_i}$$

Finally, we are going to talk about implicit differentiation,

Implicit Differentiation
$$\frac{dy}{dx}= - \frac{\frac{\partial F}{\partial x}}{\frac{\partial F}{\partial y}} = -\frac{F_x}{F_y}$$

Directional Derivatives
-----------------------

The directional derivative of the function f(x,y) at $(x_0,y_0)$ in the
direction of the unit vector, \<a,b\> is
$$D_u f(x_0,y_0)= \lim_{h \to 0} \frac{f(x_0+ha,y_0+hb)-f(x_0,y_0)}{h}$$

If f is a differential function, then f has a directional derivative in
the direction of any unit vector, $$D_u f(x,y)= f_x (x,y)a+f_y(x,y)b$$

Furthermore, we can define the gradient

$$\nabla f(x,y)=<f_x(x,y),f_y(x,y)>$$

$$D_u f(x,y)= \nabla f(x,y)* u$$

U is the unit vector

The maximum value of the directional derivative $D_u f(x)$ is
$||\nabla f(x)||$ and then the unit vector will have the same direction
as the gradient vector.

Finally, the gradient vector is perpendicular to the level curve/level
surface.

Finding Maxima and Minima
-------------------------

### Relative

The relative minimum is a point where on an interval, to the left all
values are higher than that point and to the left all the values are
higher than that point. The relative maximum is a point where on an
interval, to the left all values are lower than the point and to the
right all the values are lower than that point.

To find the critical point of a multivariable function, either of the
following has to be true,

1.  $\nabla f(a,b)= 0^{\rightarrow}$

2.  $f_x (a,b)$ and/of $f_y (a,b)$ does not exist.

Second Derivatives Test If the second partial derivative of a function f
is continuous on a disk with a center of (a,b), and $f_x(a,b)=0$ and
$f_y(a,b)=0$, $$D=D(a,b)=f_{xx}(a,b)f_{yy}(a,b)-[f_{xy}(a,b)]^2$$

1.  If D\>0 and $f_{xx}(a,b)>0$, then f(a,b) is a local minimum.

2.  If D\>0 and $f_{xx}(a,b)<0$, then f(a,b) is a local maximum.

3.  If D\<0, the f(a,b) is not a local maximum or minimum.

### Absolute

Extreme Value Theorem If f(x) is continuous on a closed interval, then
f(x) has both a maximum and a minimum in that closed interval. If f(x)
has an extreme on an open interal, then that extreme occurs at a
critical point.

How to find Absolute Extrema

Find all of the critical points of a function.

Find all the extrema at the boundary of the function

The higher and lowest values are the absolute maximum and minimum

Constraints and Lagrange Multipliers
------------------------------------

Optimization using Lagrange Multipliers,

1.  Solve the following system of equations,
    $$\nabla f(x,y,z)= \lambda \nabla g(x,y,z)$$ $$g(x,y,z)=k$$

2.  Plug in all the solutions to the original function to find the
    minimum and maximum.

Finally, when looking at functions of 3 variables:

$$\nabla f(x_0,y_0,z_0)= \lambda \nabla g(x_0,y_0,z_0)+ \mu \nabla h(x_0,y_0,z_0)$$