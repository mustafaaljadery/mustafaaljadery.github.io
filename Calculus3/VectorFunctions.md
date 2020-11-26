Vector Functions
================

In this section we are going to talk about vector functions, unlike real
valued functions, vector functions are functions that are based around
vectors.

Intro to Vector Functions
-------------------------

A vector function is a function whose domain and range are a set of
vectors. These vector functions can have component functions inside of
them as the following,

$$r^{\rightarrow}(t)=<f(t),g(t),h(t)>$$

If $r(t)=<f(t),g(t),h(t)>$, then
$$\lim_{t \to a}r(t)=<\lim_{t \to a}f(t),\lim_{t \to a}g(t),\lim_{t \to a}h(t)>$$

Here we just introduced vector functions, the the following sections, we
are going to talk about the calculus behind these vector functions.

Vector Functions Calculus
-------------------------

In this section, we are going to talk about the derivatives and
integrals of vector functions.

### Derivative

Again the derivative is just the rate of change, and the derivative of
vector functions is the following,

$$r^{\rightarrow \prime}(t) = <f^{\prime}(t),g^{\prime}(t),h^{\prime}(t)>$$

1.  $\frac{d}{dt} (u^{\prime}+v^{\prime})=u^{\rightarrow \prime}+v^{\rightarrow \prime}$

2.  $(cu^{\rightarrow})^{\prime}=cu^{\rightarrow \prime}$

3.  $\frac{d}{dt} (f(t)u^{\rightarrow}(t))=f^{\prime}(t)u^{\rightarrow}(t)+f(t)u^{\rightarrow \prime}(t)$

4.  $\frac{d}{dt} (u^{\rightarrow} \cdot v^{\rightarrow})= u^{\rightarrow \prime} \cdot v^{\rightarrow}+ u^{\rightarrow} \cdot v^{\rightarrow \prime}$

5.  $\frac{d}{dt} (u^{\rightarrow} \times v^{\rightarrow})=u^{\rightarrow \prime} \times v^{\rightarrow}+ u^{\rightarrow} \times v^{\rightarrow \prime}$

6.  $\frac{d}{dt} (u^{\rightarrow}(f(t)))=f^{\prime}(t)u^{\rightarrow \prime}(f(t))$

### Integral

Now the integrals of vector functions,

$$\int r^{\rightarrow}(t)dt = <\int f(t)dt, \int g(t) dt, \int h(t)dt>+c^{\rightarrow}$$

and the same goes for definite integrals,
$$\int^{b}_{a} r^{\rightarrow}(t)dt=<\int^{b}_{a}f(t)dt,\int^{b}_{a} g(t)dt,\int^{b}_{a}h(t)dt>$$

Arc Length/ Parametization
--------------------------

The length of a curve is defined as the following,

$$L= \int^{b}_{a} \sqrt{[f^{\prime}(t)]^2+[g^{\prime}(t)]^2+[h^{\prime}(t)]^2}dt$$

This can be shortened to the following,

$$L=\int^{b}_{a} ||r^{\rightarrow \prime}(t)||dt$$

Finally, we can define the arc length function as,

$$s(t)=\int^{t}_{0} ||r^{\rightarrow \prime}(u)||du$$

Curvature
---------

Curvature is how fast a curve is changing direction at whatever
direction is measured.

Curvature
$$\kappa = \frac{||T^{\rightarrow}(t)||}{||r^{\rightarrow \prime}(t)||}$$

The formula is the magnitude of the derivative of the unit tangent
divided by the arc length.

Motion of Vector Functions
--------------------------

### Velocity

$$v^{\rightarrow}(t)=r^{\rightarrow \prime}(t)$$

### Acceleration

$$a^{\rightarrow}(t)=r^{\rightarrow \prime \prime}(t)$$

When talking about the motion we can talk about the tangential component
and the normal component,

tangent
$$A_T= \frac{r^{\rightarrow \prime}(t) \cdot r^{\rightarrow \prime \prime}(t)}{||r^{\prime}(t)||}$$

normal
$$A_N= \frac{||r^{\rightarrow \prime}(t) \times r^{\rightarrow \prime \prime}(t)||}{||r^{\prime}(t)||}$$