Vector Calculus
===============

Vector calculus focuses on the calculus of vector fields. This section
will introduce a new kind of integral.

Vector Fields
-------------

A vector field in $R^2$ assigns a two-dimensional vector to each point
(x,y) of the subset D of $R^2$.

A vector filed in $R^3$ assigns a three-dimensional vector to each point
(x,y,z) of a subset F of $R^3$.

Gradient Vector Field $\nabla f = <f_x,f_y,f_z>$

Line Integrals
--------------

Line integrals are integrals that integral over a curve. They are
sometimes called curve integrals. This is different from the general
definition of the integral we have looked at before as they are used to
integrate over an area or interval.

Line Integral The line integral of f(x,y) along C,
$$\int_C f(x,y) ds = \int^{b}_{a} f(h(t),g(t))\sqrt{(\frac{dx}{dt})^2+(\frac{dy}{dt})^2}dt$$

Also to simplify we can note,
$$\sqrt{(\frac{dx}{dt})^2+(\frac{dy}{dt})^2}= ||r^{\rightarrow \prime}(t)||$$

Furthermore, going to three variables,
$$\int_C f(x,y,z) ds = \int^{b}_{a} f(x(t),y(t),z(t))\sqrt{(\frac{dx}{dt})^2+(\frac{dy}{dt})^2+(\frac{dz}{dt})^2}dt$$

A fact, $$\int_C f(x,y)ds = \int_{-C} f(x,y) ds$$

Now when we want to look at line integrals we have to define if we want
to look at the integral with respect to y or with respect to x or both.

Respect to x
$$\int_C f(x,y)dx = \int^{b}_{a} f(x(t),y(t))x^{\prime}(t)dt$$

Respect to y
$$\int_C f(x,y) dy = \int^{b}_{a} f(x(t),y(t))y^{\prime}(t)dt$$

Looking at the two integrals together,
$$\int_C Pdx + Q dy = \int_C P(x,y)dx + \int_C Q(x,y)dy$$

Another fact,

$$\int_{-C}f(x,y)dx = - \int_C f(x,y)dx \quad \quad \text{and} \quad \quad \int_{-C} f(x,y)dy = - \int_C f(x,y)dy$$

$$\int_{-C} Pdx+ Q dy =-\int_C Pdx+Qdy$$

All of the following goes on to more variables.

Moreover, when talking about line integrals of vector functions,

If $F^{\rightarrow}$ is a continuous vector field defined on a smooth
curve C given by a vector function r(t). Then the line integral is,
$$\int_C F^{\rightarrow}*dr=\int^{b}_{a} F^{\rightarrow}(r(t))* r^{\prime}(t)dt = \int_C F^{\rightarrow}*T^{\rightarrow}ds$$

Fundamental Theorem of Line Integrals If c is a smooth curve given by
the vector function r(t) and f is a differentiable function of two or
three variables whose gradient is continuous on the curve. Then,
$$\int_C \nabla f *dr = f(r(b))- f(r(a))$$

Green's Theorem
---------------

Greens Theorem If C is positively oriented, piecewise-smooth, and is a
simple closed curve and let D be a region bounded by C. If P and Q have
continuous partial derivatives on the open region that contains D, then
$$\int_C Pdx+Qdy = \int_D \int (\frac{\partial Q}{\partial x}-\frac{\partial P}{\partial y})dA$$

Greens Theorem is simplified to,
$$A = \oint_C x dy = - \oint_C y dx = \frac{1}{2} \oint_C x dy -ydx$$

Surface and Flux Integrals
--------------------------

### Surface Integrals

A surface integral is an integral in the form of,
$$\int_S \int f(x,y,z) dS= \int_D \int f(x,y,g(x,y))\sqrt{(\frac{\partial g}{\partial x})^2+(\frac{\partial g}{\partial y})^2+1}dA$$

When the surface integral is given for surfaces after parameterization,
$$\int_S \int f(x,y,z)dS = \int_D \int f(r^{\rightarrow}(u,v))||r^{\rightarrow}_{u} \times r^{\rightarrow}_v||dA$$

### Flux Integrals

The flux of $F^{\rightarrow}$ across S,

$$\int_S \int F^{\rightarrow} \cdot dS^{\rightarrow}=\int_S \int F^{\rightarrow} \cdot n^{\rightarrow}dS$$

Divergence Theorem
------------------

Divergence Theorem

Let E be a simple solid region and S is the boundary surface of E with
positive orientation. Let $F^{\rightarrow}$ be a vector field whose
components have continuous first order partial derivatives. Then,
$$\int_S \int F^{\rightarrow} \cdot ds^{\rightarrow}= \int \int_E \int div F^{\rightarrow}dV$$

Stokes' Theorem
---------------

Let S be an oriented smooth surface that is bounded by a simple, close
,smooth boundary curve C with positive orientation. $F^{\rightarrow}$,
$$\int_C F^{\rightarrow} \cdot dr^{\rightarrow} = \int_S \int curlF^{\rightarrow} \cdot dS^{\rightarrow}$$