Multiple Integrals
==================

In calculus 1 and 2 we dealt with only one integral because we only
dealt with single variable functions. However, in calculus 3 we are
going to talk about multiple integrals as we deal with mulivariable
functions.

Double Integrals
----------------

The double integral over a rectangle R,
$$\int_R \int f(x,y) dA= \lim_{m,n \to \infty} \Sigma^{m}_{i=1} \Sigma^{n}_{j=1} f(x_{ij}^{*},y_{ij}^{*}) \nabla A$$

If $f(x,y) \geq 0$then the volume if found by the following,
$$V= \int_R \int f(x,y)dA$$

Fubini's Theorem If f(x,y) is continuous on $R = [a,b] \times [c,d]$
then,
$$\int_R \int f(x,y)dA= \int^{b}_{a} \int^{d}_{c} f(x,y) dy,dx= \int^{d}_{c} \int^{b}_{a} f(x,y) dx,dy$$

If $f(x,y)=g(x)h(y)$,
$$\int_R \int f(x,y)dA= \int_R \int g(x)h(y)dA= (\int^{b}_{a} g(x) dx)(\int_{c}^{d} h(y) dy)$$

Now lets talk about properties of double integrals over general regions,

1.  $\int_D \int f(x,y) + g(x,y) dA= \int_D \int f(x,y)dA+ \int_D \int g(x,y)dA$

2.  $\int_D \int c f(x,y) dA = c \int_D \int f(x,y)dA$

3.  $\int_D \int f(x,y) dA = \int_{D_1} \int f(x,y)dA+ \int_{D_2} \int f(x,y)dA$

Double Integral Over Polar Regions
----------------------------------

When looking at double integrals over polar regions,
$$dA=r dr d \theta$$

Is the key differential.

A little reminder about polar coordinates,
$$x =r cos \theta \quad \quad y = rsin \theta \quad \quad r^2=x^2+y^2$$

Knowing these conversions, we can convert our double integral formula
over general regions to polar regions,
$$\int_D \int d(x,y) dA = \int^{\beta}_{\alpha} \int^{h_2(\theta)}_{h_1(\theta)}f(r cos \theta, r sin \theta)r,dr,d \theta$$

Triple Integrals
----------------

When integration over a three dimensional region, the following is used,

$$\int \int_E \int f(x,y,z) dV$$

This is our triple integral

The volume of the three-dimensional region E,
$$V = \int \int_E \int dV$$

Triple Integrals Over Cylindrical and Spherical Coordinates
-----------------------------------------------------------

### Cylindrical

Just like our polar coordinate, our spherical coordinates have different
conversion factors than our usual general plane.

Lets begin with the basic conversions,
$$x = r cos \theta \quad \quad y=r sin \theta \quad \quad z =z$$

And the differential: $$dV = r dz dr d\theta$$

Defining the conversions all together,

$$\int \int_E \int f(x,y,z)dV=\int^{\beta}_{\alpha} \int^{h_2(\theta)}_{h_1(\theta) \int^{u_2(r cos \theta, r sin \theta)}_{u_1(r cos \theta, r sin \theta)} rf(r cos \theta, r sin \theta, z) dz dr d \theta}$$

### Spherical

Again lets remind ourselves the spherical coordinate conversions,
$$x = \rho sin \phi cos \theta \quad \quad y = \rho sin \phi sin \theta \quad \quad z = \rho cos \phi \quad \quad x^2+y^2+z^2=\rho^2$$

Our differential is conversed to,
$$dV= \rho^2 sin \phi d \rho d \theta d \phi$$

Finally, the integral will become,

$$\int \int_E \int f(x,y,z)dV= \int^{\gamma}_{\sigma} \int^{\beta}_{\alpha} \int^{b}_{a} \rho^2 sin \phi f(\rho sin \phi cos \theta, \rho sin \phi sin \theta, \rho cos \phi)d\rho d \theta d \phi$$

Changing Variables
------------------

In this section we are going to refer back to an important technique in
Calculus 1, the u substitution. However, when dealing with multiple
integrals we cant just use a u substitution, we have to use something
called the jacobian.

The jacobian of x = g(u,v), y = h(u,v) is,
$$\frac{\partial (x,y)}{\partial (u,v))}= |\frac{\frac{\partial x}{\partial u}}{\frac{\partial y}{\partial u}} \frac{\frac{\partial x}{\partial v}}{\frac{\partial y}{\partial v}}|$$

Change of Variable for double integrals, When using the transformation,
$x = g(u,v) and y = h(u,v)$,
$$\int_R \int f(x,y)dA = \int_S \int f(g(u,v),h(u,v))|\frac{\partial (x,y)}{\partial (u,v)}| dA^{-}$$