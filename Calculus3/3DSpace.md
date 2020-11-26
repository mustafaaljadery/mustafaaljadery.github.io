3D Space
========

Calculus 1 and 2 have been focused on functions of only one variable.
However, in calculus 3 we are going to stretch our knowledge to
functions of many variables. That being said, functions of multiple
variable are defined in higher dimentions than our normal 2D space. In
this section we are going to get introduced ot our 3D space then in the
following sections we are going to do calculus with our multiple
variables.

Introduction to Vectors
-----------------------

A vector is just a quantity (for example a displacement) that has a
direction and a magnitude.

When talking about vector functions, they are denoted as the following,
$$r^{\rightarrow}(t)=<t,1>$$

Vector Addition When two vectors are added, the resulting vector is from
the initial point of the first vector to the end point of the second
vector.

Scalar Multiplication Scalar multiplication is when a c (constant) is
multiplied to every value of a vector. This multiplication either
stretches the vector or shrinks the vector.

Now to finding the the vector from two points we use the following,

Finding the Vector Suppose we have the two points $A(x_1,y_1,z_1)$ and
$B(x_2,y_2,z_2)$. The vector representation of the following
$AB^{\rightarrow} = <x_2-x_1,y_2-y_1,z_2-z_1>$

Finding the magnitude or the length of a vector is denoted as the
following, \|v\| or \|\|v\|\|,

magnitude Finding the magnitude in two dimensions,
$$|v|= \sqrt{x^2_1+y^2_1}$$ Finding the magnitude in three dimensions,
$$|v|= \sqrt{x^2_1+y^2_1+z^2_1}$$

This follows to as many dimensions as needed.

Vectors can be defined in multiples ways, one of the definitions we can
use to define vectors are the use of the standard basis vectors, the
standard basis vectors are defined as the following,

$$i=<1,0,0> \quad \quad j=<0,1,0> \quad \quad k =<0,0,1>$$

Finally we have the following properties of vectors,

1.  $a+b=b+a$

2.  $a+(b+c)=(a+b)+c$

3.  $a+0=a$

4.  $a+(-a)=0$

5.  $c(a+b)=ca+ba$

6.  $(c+d)a=ca+da$

7.  $(cd)a=c(da)$

8.  $1a=a$

Dot Product
-----------

The dot product of two vector tells use how much of one vector goes in
the direction of the other vector.

The dot-product is defined mathematically as the following,

$$a^{\rightarrow}\cdot b^{\rightarrow}=a_1b_1+a_2b_2+a_3b_3$$

As the formula above shows, the result of a scalar it is not a vector
quantity.

Now onto the properties of dot products,

1.  $u^{\rightarrow} \cdot (v^{\rightarrow}+w^{\rightarrow})=u^{\rightarrow}\cdot v^{\rightarrow}+u^{\rightarrow} \cdot w^{\rightarrow}$

2.  $v^{\rightarrow} \cdot w^{\rightarrow}= w^{\rightarrow} \cdot v^{\rightarrow}$

3.  $v^{\rightarrow} \cdot v^{\rightarrow}=||v^{\rightarrow}||^2$

4.  $(cv^{\rightarrow})\cdot w^{\rightarrow}=v^{\rightarrow} \cdot (cw^{\rightarrow})=c(v^{\rightarrow} \cdot w^{\rightarrow})$

5.  $v^{\rightarrow} \cdot 0^{\rightarrow}=0$

Given these, there are a couple of theorems with dot product,

Assuming there is an angle $\theta$ that is in between the two vectors a
and b then, $$a \cdot b=|a||b|cos \theta$$

Furthermore, another important property of vectors is orthogonality,

orthogonality 2 Vectors are orthogonal to each other if they are
perpendicular to each other. Orthogonality is found when the dot product
of two vector is equal to 0. $$a \cdot b = 0$$

Direction cosines are direction angles are the angels that the vector
makes the positive x,y, and z-axes. Direction cosines are defined as the
following,

$$cos \alpha = \frac{a}{\sqrt{a^2+b^2+c^2}}$$
$$cos \beta = \frac{b}{\sqrt{a^2+b^2+c^2}}$$
$$cos \gamma = \frac{c}{\sqrt{a^2+b^2+c^2}}$$
$$cos^2\alpha+cos^2\beta + cos^2 \gamma$$

Finally we are going to look at Projections. Projections are new vectors
that are going in the direction of the other. One vector is resolved
into two omponent vectors, one is parallel and the second is
perpendicular.

Projections The projection of vector $b^{\rightarrow}$ onto
$a^{\rightarrow}$,
$$proj_{a^{\rightarrow}}b^{\rightarrow}= \frac{a^{\rightarrow} \cdot b^{\rightarrow}}{||a^{\rightarrow}||}a^{\rightarrow}$$

Cross Product
-------------

The cross product is a vector that is perpendicular to both vectors that
the cross product is taken.

Cross Product If we define two vectors, $a = <a_1,a_2,a_3>$ and
$b = <b_1,b_2,b_3>$ the cross product of the two vectors is
$a \times b = <a_2b_3-a_3b_2,a_3b_1-a_1b_3,a_1b_2-a_2b_1>$

Remember that the cross product is orthogonal with means that it is
perpendicular to both of the vectors.

The magnitude of the cross product is equal to the area of the
parallelogram determined by a and b.

1.  $a \times b = -b \times a$

2.  $(ca) \times b = c(a \times b )= a \times (cb)$

3.  $a \times (b+c)=a \times b + a \times c$

4.  $(a+b) \times c = a \times c + b \times c$

5.  $a \cdot (b \times c)=(a \times b) \cdot c$

6.  $a \times (b \times c )=(a \cdot c)b-(a \cdot b )c$

Furthermore, the magnitude of the cross product of 3 vectors is the
volume of the parallelepiped.

Lines and Planes
----------------

The vector equation of a line is defined as the following,
$r = r_0 +tv$. This can be defined as the following,
$$r^{\rightarrow}=r_0^{\rightarrow}+tv^{\rightarrow}=<x_0,y_0,z_0> + t<a,b,c>$$

The parametric equations for lines,
$$x = x_0+at \quad \quad y=y_0+bt \quad \quad z = z_0+ct$$

Finally, the symmetric equations of a line are,

$$\frac{x-x_0}{a}=\frac{y-y_0}{b}=\frac{z-z_0}{c}$$

Now onto planes, vector equations of the plane are defined are,
$$n^{\rightarrow} \cdot r^{\rightarrow}=n^{\rightarrow} \cdot r_0^{\rightarrow}$$
$$<a,b,c> \cdot <x-x_0,y-y_0, z-z_0>$$ $$a(x-x_0)+b(y-y_0)+c(z-z_0)=0$$

Quadric Surfaces
----------------

In this section, we are going to define the equations of multiple
3d-shapes,

Ellipsoid $$\frac{x^2}{a^2}+\frac{y^2}{b^2}+\frac{z^2}{c^2}=1$$

Cone $$\frac{x^2}{a^2}+\frac{y^2}{b^2}=\frac{z^2}{c^2}$$

Cylinder $$\frac{x^2}{a^2}+\frac{y^2}{b^2}=1$$

Hyperboloid of One Sheet
$$\frac{x^2}{a^2}+\frac{y^2}{b^2}-\frac{z^2}{c^2}=1$$

Hyperboloid of Two Sheets
$$-\frac{x^2}{a^2}-\frac{y^2}{b^2}+\frac{z^2}{c^2}=1$$

Elliptic Paraboloid $$\frac{x^2}{a^2}+\frac{y^2}{b^2}=\frac{z}{c}$$

Hyperbolic Paraboloid $$\frac{x^2}{a^2}-\frac{y^2}{b^2}=\frac{z}{c}$$

Cylindrical and Spherical Coordinates
-------------------------------------

### Cylindrical Coordinates

Cylindrical coordinates are no other than polar coordinates into three
dimensions. Cylindrical coordinates is shown as the following,
$(r, \theta,z)$.

Conversions,

Cylindrical to Cartesian

$$x = r cos \theta$$ $$y = r sin\theta$$ $$z =z$$

Cartesian to Cylindrical

$$r = \sqrt{x^2+y^2}$$ $$\theta = tan^{-1}(\frac{y}{x})$$ $$z=z$$

### Spherical Coordinates

The spherical coordinate system is another three dimensional space where
again different form the Cartesian coordinates, the spherical
coordinates include a distance from a fixed point, and polar angle and
orthogonal projection.

Spherical to Cylindrical coordinates

$$r = \rho sin \varphi$$ $$\theta = \theta$$ $$z = \rho cos \varphi$$

Now to find the Cartesian coordinates,

$$x = \rho sin \varphi cos \theta$$ $$y = \rho sin \varphi sin \theta$$
$$z = \rho cos \varphi$$ $