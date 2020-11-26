Parametric and Polar Curves
===========================

In this section we are going to divert from our normal f(x)=y functions
and take a look at pairs of functions (parametric equations). Then we
are going to look at polar coordinates, which are coordinates that are
used rather than the usual Cartesian coordinates.

Parametric Equations
--------------------

A parametric equation is just an equation that includes a pair of
functions. Parametric equations usually denote another change of
variable (usually t for time) and they are written as the following,
$$x = f(t) \quad \quad y = g(t) \quad \quad (x,y)=(f(t),g(t))$$

With this introduction to parametric equations, in those course we are
interested in the calculus behind them.

### Derivatives of Parametric Equations

Finding the first derivatives:

$$\frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}}, \quad \quad \frac{dx}{dt} \neq 0$$

$$\frac{dx}{dy}=\frac{\frac{dx}{dt}}{\frac{dy}{dt}}, \quad \quad \frac{dy}{dt} \neq 0$$

Finding the Tangents:

Horizontal Tangent,
$$\frac{dy}{dt}=0, \quad \quad \frac{dx}{dt} \neq 0$$ Vertical Tangent,
$$\frac{dx}{dt}=0, \quad \quad \frac{dy}{dt} \neq 0$$

Finding the second derivative:

$$\frac{d^2y}{dx^2}=\frac{d}{dx}(\frac{dy}{dx})=\frac{\frac{d}{dt}(\frac{dy}{dx})}{\frac{dx}{dt}}$$

### Area of Parametric Equations

$$A= \int^{b}_{a}g(t) f^{\prime}(t)dt$$

### Arc Length of Parametric Equations

$$L= \int^{b}_{a} \sqrt{(\frac{dx}{dt})^2+(\frac{dy}{dt})^2}dt$$

### Surface Area of Parametric Equations

$$s = \int 2 \pi y, dx \quad \quad around x-axis$$

$$s = \int 2 \pi x, ds \quad \quad around y-axis$$

$$ds = \sqrt{(\frac{dx}{dt})^2+(\frac{dy}{dt})^2}dt$$

Polar Coordinates and Polar Equations
-------------------------------------

Now lets talk about polar coordinates. Polar coordinates instead of
going up and down like the x and y coordinate system start at the origin
and go diagonal to the point. The length of that diagonal arc is denoted
by R and the angle that is created by the direction is $\theta$. That
being said our points are denoted as, (R,$\theta$). Furthermore, because
we are using $\theta$ there is an infinite number of angles that produce
the same line (This is not true for our normal x-y coordinate system).

How to convert from polar to Cartesian Coordinate:
$$x = r \cos(\theta) \quad \quad y = r \sin(\theta)$$

Cartesian to Polar Coordinate:
$$r^2=x^2+y^2 \quad \quad r = \sqrt{x^2+y^2} \quad \quad \theta = tan^{-1}(\frac{y}{x})$$

Just like the last section, we are going to look at the calculus behind
polar coordinates,

### Derivatives with Polar Coordinate

$$\frac{dy}{dx}=\frac{\frac{dr}{d \theta} sin \theta + rcos \theta}{\frac{dr}{d \theta}cos \theta-rsin\theta}$$

### Area with Polar Coordinate

$$A = \int^{b}_{a}\frac{1}{2}r^2 d\theta$$

Area of the difference of two curves:

$$A = \int^{b}_{a} \frac{1}{2}(r_o^2-r_i^2)d \theta$$

o stands for the outer one of the curves and i is the inside curve.

### Arc Length with Polar Coordinate

$$L = \int ds$$

$$ds = \sqrt{r^2+(\frac{dr}{d \theta})^2}d \theta$$

### Surface Area with Polar Coordinate

$$S = \int 2 \pi y ,ds \quad \quad \text{about the x-axis}$$

$$S = \int 2 \pi x, ds \quad \quad \text{about the y-axis}$$

$$ds = \sqrt{r^2+(\frac{dr}{d\theta})^2}d\theta$$

C:\Users\malja>pandoc -f latex -t markdown

\chapter{Parametric and Polar Curves}

In this section we are going to divert from our normal f(x)=y functions and take a look at pairs of functions (parametric equations). Then we are going to look at polar coordinates, which are coordinates that are used rather than the usual Cartesian coordinates.

\section{Parametric Equations}

A parametric equation is just an equation that includes a pair of functions. Parametric equations usually denote another change of variable (usually t for time) and they are written as the following,
$$x = f(t) \quad \quad y = g(t) \quad \quad (x,y)=(f(t),g(t))$$

With this introduction to parametric equations, in those course we are interested in the calculus behind them.

\subsection{Derivatives of Parametric Equations}

Finding the first derivatives:

$$\frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}}, \quad \quad \frac{dx}{dt} \neq 0$$

$$\frac{dx}{dy}=\frac{\frac{dx}{dt}}{\frac{dy}{dt}}, \quad \quad \frac{dy}{dt} \neq 0$$

Finding the Tangents:

Horizontal Tangent,
$$\frac{dy}{dt}=0, \quad \quad \frac{dx}{dt} \neq 0$$
Vertical Tangent,
$$\frac{dx}{dt}=0, \quad \quad \frac{dy}{dt} \neq 0$$

Finding the second derivative:

$$\frac{d^2y}{dx^2}=\frac{d}{dx}(\frac{dy}{dx})=\frac{\frac{d}{dt}(\frac{dy}{dx})}{\frac{dx}{dt}}$$

\subsection{Area of Parametric Equations}

$$A= \int^{b}_{a}g(t) f^{\prime}(t)dt$$

\subsection{Arc Length of Parametric Equations}

$$L= \int^{b}_{a} \sqrt{(\frac{dx}{dt})^2+(\frac{dy}{dt})^2}dt$$

\subsection{Surface Area of Parametric Equations}

$$s = \int 2 \pi y, dx \quad \quad around x-axis$$

$$s = \int 2 \pi x, ds \quad \quad around y-axis$$

$$ds = \sqrt{(\frac{dx}{dt})^2+(\frac{dy}{dt})^2}dt$$


\section{Polar Coordinates and Polar Equations}

Now lets talk about polar coordinates. Polar coordinates instead of going up and down like the x and y coordinate system start at the origin and go diagonal to the point. The length of that diagonal arc is denoted by R and the angle that is created by the direction is $\theta$. That being said our points are denoted as, (R,$\theta$). Furthermore, because we are using $\theta$ there is an infinite number of angles that produce the same line (This is not true for our normal x-y coordinate system).

How to convert from polar to Cartesian Coordinate:
$$x = r \cos(\theta) \quad \quad y = r \sin(\theta)$$

Cartesian to Polar Coordinate:
$$r^2=x^2+y^2 \quad \quad r = \sqrt{x^2+y^2} \quad \quad \theta = tan^{-1}(\frac{y}{x})$$

Just like the last section, we are going to look at the calculus behind polar coordinates,

\subsection{Derivatives with Polar Coordinate}
$$\frac{dy}{dx}=\frac{\frac{dr}{d \theta} sin \theta + rcos \theta}{\frac{dr}{d \theta}cos \theta-rsin\theta}$$


\subsection{Area with Polar Coordinate}

$$A = \int^{b}_{a}\frac{1}{2}r^2 d\theta$$

Area of the difference of two curves:

$$A = \int^{b}_{a} \frac{1}{2}(r_o^2-r_i^2)d \theta$$

\begin{remark}
o stands for the outer one of the curves and i is the inside curve.
\end{remark}

\subsection{Arc Length with Polar Coordinate}

$$L = \int ds$$

$$ds = \sqrt{r^2+(\frac{dr}{d \theta})^2}d \theta$$

\subsection{Surface Area with Polar Coordinate}

$$S = \int 2 \pi y ,ds \quad \quad \text{about the x-axis}$$

$$S = \int 2 \pi x, ds \quad \quad \text{about the y-axis}$$

$$ds = \sqrt{r^2+(\frac{dr}{d\theta})^2}d\theta$$
^Z
Parametric and Polar Curves
===========================

In this section we are going to divert from our normal f(x)=y functions
and take a look at pairs of functions (parametric equations). Then we
are going to look at polar coordinates, which are coordinates that are
used rather than the usual Cartesian coordinates.

Parametric Equations
--------------------

A parametric equation is just an equation that includes a pair of
functions. Parametric equations usually denote another change of
variable (usually t for time) and they are written as the following,
$$x = f(t) \quad \quad y = g(t) \quad \quad (x,y)=(f(t),g(t))$$

With this introduction to parametric equations, in those course we are
interested in the calculus behind them.

### Derivatives of Parametric Equations

Finding the first derivatives:

$$\frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}}, \quad \quad \frac{dx}{dt} \neq 0$$

$$\frac{dx}{dy}=\frac{\frac{dx}{dt}}{\frac{dy}{dt}}, \quad \quad \frac{dy}{dt} \neq 0$$

Finding the Tangents:

Horizontal Tangent,
$$\frac{dy}{dt}=0, \quad \quad \frac{dx}{dt} \neq 0$$ Vertical Tangent,
$$\frac{dx}{dt}=0, \quad \quad \frac{dy}{dt} \neq 0$$

Finding the second derivative:

$$\frac{d^2y}{dx^2}=\frac{d}{dx}(\frac{dy}{dx})=\frac{\frac{d}{dt}(\frac{dy}{dx})}{\frac{dx}{dt}}$$

### Area of Parametric Equations

$$A= \int^{b}_{a}g(t) f^{\prime}(t)dt$$

### Arc Length of Parametric Equations

$$L= \int^{b}_{a} \sqrt{(\frac{dx}{dt})^2+(\frac{dy}{dt})^2}dt$$

### Surface Area of Parametric Equations

$$s = \int 2 \pi y, dx \quad \quad around x-axis$$

$$s = \int 2 \pi x, ds \quad \quad around y-axis$$

$$ds = \sqrt{(\frac{dx}{dt})^2+(\frac{dy}{dt})^2}dt$$

Polar Coordinates and Polar Equations
-------------------------------------

Now lets talk about polar coordinates. Polar coordinates instead of
going up and down like the x and y coordinate system start at the origin
and go diagonal to the point. The length of that diagonal arc is denoted
by R and the angle that is created by the direction is $\theta$. That
being said our points are denoted as, (R,$\theta$). Furthermore, because
we are using $\theta$ there is an infinite number of angles that produce
the same line (This is not true for our normal x-y coordinate system).

How to convert from polar to Cartesian Coordinate:
$$x = r \cos(\theta) \quad \quad y = r \sin(\theta)$$

Cartesian to Polar Coordinate:
$$r^2=x^2+y^2 \quad \quad r = \sqrt{x^2+y^2} \quad \quad \theta = tan^{-1}(\frac{y}{x})$$

Just like the last section, we are going to look at the calculus behind
polar coordinates,

### Derivatives with Polar Coordinate

$$\frac{dy}{dx}=\frac{\frac{dr}{d \theta} sin \theta + rcos \theta}{\frac{dr}{d \theta}cos \theta-rsin\theta}$$

### Area with Polar Coordinate

$$A = \int^{b}_{a}\frac{1}{2}r^2 d\theta$$

Area of the difference of two curves:

$$A = \int^{b}_{a} \frac{1}{2}(r_o^2-r_i^2)d \theta$$

o stands for the outer one of the curves and i is the inside curve.

### Arc Length with Polar Coordinate

$$L = \int ds$$

$$ds = \sqrt{r^2+(\frac{dr}{d \theta})^2}d \theta$$

### Surface Area with Polar Coordinate

$$S = \int 2 \pi y ,ds \quad \quad \text{about the x-axis}$$

$$S = \int 2 \pi x, ds \quad \quad \text{about the y-axis}$$

$$ds = \sqrt{r^2+(\frac{dr}{d\theta})^2}d\theta$$