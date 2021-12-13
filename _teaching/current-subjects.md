---
layout: archive
title: "Current Subjects"
collection: teaching
type: "Undergraduate courses"
permalink: /teaching/current
venue: "University of Bath"
date: 2021-06-01
location: "Bath, UK"
---

This section contains structural information about the running of my current modules. There are also condensed notes meant to supplement the running of the courses.  


# MA10230: Multivariable Calculus and Differential Equations

This is the section for the semester 1 module, MA10230, for the academic year 21/22. The notes provided below are in no means a replacement for lecture notes and only meant to supplement the learning for students already enrolled in this course at the University of Bath. _The notes provided on this page are provided exclusively for educational purposes at the University of Bath to supplement the module MA10230, and are to be used for private study only. They are not for resale._<br/>

UPDATE: I have included all previous weeks quizzes, including solutions after each question in <span style="color:#557786;"> teal </span>, no graphs provided for the moment until I can think of a low effort way to do it.

## Deadlines and Tutorial information

Please submit your homework to the correct pigeonhole by no later than Tuesday at 5pm. Tutorials will be held weekly in person in the later half of the week. Please email me if you are going to miss a tutorial or can't make this homework deadline if you require an extension. 
<!-- B3: Thursday 16:15 6E 3.11
    A2: Friday 13:15 10W 2.01 -->


## Week 1 - Integrals, Lengths and Areas
For a function \$ y=f(x) \$ defined over an interval \$[a,b]\$
* Arc length \$ S(a,b) = \int_a^b \sqrt{1+\left(\frac{dy}{dx}\right)^2}dx \$
* Surface Area of Revolution \$ A(a,b) = \int_a^b 2\pi y\sqrt{1+\left(\frac{dy}{dx}\right)^2} dx \$
* Sketches and Classic Shapes. When you're going to sketch a graph you need to keep track of a few behaviours of the graph
    * What happens to the graph at \$ \pm \infty\$ . 
    * Are there any asymptotes? 
    * What is the behaviour of the of the gradient? Is it increasing, decreasing?
    * Where are the max/min stationary points?
    * Where does it cross the axes? 


### Tutorial Quiz 

1. For the continuous function \$ f(x) \$: 
    * What is the notation for derivative with respect to \$ x\$ (list as many as possible) ?
    * What is the notation for the indefinite integral?
    * What is the notation for definite integral over \$ [a,b]\$
    <ul style="color:#557786;">
        <li> $\partial_x \; \frac{\partial f}{\partial x}\; f^\prime\; Df\; \dot{f} $  </li>
        <li>$\int f(x) dx $</li>
        <li> $\int_a^b f(x) dx $</li>
    </ul>
2. State the Fundamental Theorem of Calculus. 
    <ul style="color:#557786;">
        <li> For a continuous function $f(x)$ over the interval $[a,b]\subset \mathcal{R}$, $f$ has antiderivative $g(x)$ $\forall x\in [a,b]$ such that $g(x) = \int_a^x f(\chi) d\chi $ </li>
        <li> Furthermore, for any antiderivative $h(x)$, and for $a \le \alpha \le \beta \le b\$ we have $\int_\alpha^\beta f(u) du = h(\beta) - h(\alpha) $</li>
    </ul>
3. What is the relation between \$ \int_a^b f(x) dx \$ and \$ \int_b^a f(x) dx\$. 
    <ul style="color:#557786;">
        <li> $ \int_a^b f(x) dx = -\int_b^a f(x) dx $ </li>
    </ul>
4. For a continuous function \$ f(x)\$ over an interval \$[a,b]\$
    * What is the equation of Arc Length \$S\$?
    * What is the equation of Surface Area of Revolution, \$A \$? 
    <ul style="color:#557786;">
        <li> $S(a,b) = \int_a^b \sqrt{1 + \left(\frac{dy}{dx}\right)^2} dx $ </li>
        <li>$A(a,b) = 2\pi \int_a^b y \sqrt{1 + \left(\frac{dy}{dx}\right)^2}dx  $</li>
    </ul>
5. Sketch the following functions 
    * \$ y = \cosh(x) \$
    * \$ y = \sinh(x) \$
    * \$ y = \tanh(x) \$
    <ul style="color:#557786;">
        <li> google it</li>
    </ul>



## Week 2 - Coordinate Systems

 *  Cartesian Coordinates \$ (x,y,z)\$ - uniquely define a singluar point. Independent coordinates. 
 *  Cylindrical Polar Coordinates \$(r,\theta, z)\$ - are unique up to \$\theta \in [0,2\pi]\$. \$z\$ behaves as the cartesian plane, and \$r\$ is defined radially outwards from the origin, \$ \theta\$ is anticlockise round from the positive \$x\$ axis. 
    * \$x=r\cos(\theta)\$
    * \$y = r\sin(\theta)\$
    * \$ z=z\$
 *  Spherical Polar Coordinates - \$(r,\theta,\varphi)\$ - first two the same as cylindrical polar coordinates, now \$ \varphi\$ is the polar angle defined between 0 and \$\pi\$. 
    * \$ x=rcos(\theta)\sin(\varphi)\$
    * \$ y = rsin(\theta)\sin(\varphi)\$
    * \$ z = r\cos(\varphi)\$
 
### Tutorial Quiz 

 1. What is the relationship between 2D cartesian \$(x,y) \$ and polar coordinates \$(r,\theta) \$ ?
     <ul style="color:#557786;">
        <li>  $x = r\cos(\theta)$, $y=r\sin(\theta)$, or backwards $r = x^2+ y^2$ and $\theta = \arctan(y/x) $ </li>
    </ul>
 2. What shape is given by \$ r= 3 \$ in cylindrical polar coordinates?
     <ul style="color:#557786;">
        <li> a cylinder generated by projecting a circle centred at the origin with radius $3$ along the $z$ axis.</li>
    </ul>
 3. For constants \$ a,b,c\$ describe the shape of \$ r=a, \theta=b, \phi = c\$ in spherical coordinates.
     <ul style="color:#557786;">
        <li> a sphere of radius $a$ </li>
        <li> a half plane aligned with $\theta=b$ around from the positive $x$ axis (i.e the plane is perpendicular to the xy plane and contains the $z$ axis.</li>
        <li> a cone with the tip at the origin projecting outwards in the positive $z$ direction with the slope at an angle $\phi=c$ to the z axis. </li>
    </ul>
 4. True or False
    * The equations \$ r = 2\$ and \$ x^2 + y^2 + z^2 = 2\$ represent the same surface. <span style="color:#557786;"> False </span>
    * The coordinates of a point in cylindrical coordinates are unique <span style="color:#557786;"> False </span>
    * The coordinates of a point in cartesian coordinates are unique. <span style="color:#557786;"> True </span>
    * The equation of a cardoid is \$ r = 1-cos(\theta) \$. <span style="color:#557786;"> True </span>
    * The equation \$ r = \theta/2\pi \$ in polar coordinates is the Fibonnaci spiral.  <span style="color:#557786;"> False, it's an Archimedes spiral </span>

 5. What shape is given by \$\phi = \frac{\pi}{4} \$ in spherical coordinates?
     <ul style="color:#557786;">
        <li> a cone with the tip at the origin projecting outwards in the positive $z$ direction with the slope at an angle $\phi=\pi/2$ to the z axis. </li>
    </ul>


## Week 3 - Partial Differentials

* Partial Differentiation
* Chain, Product and Quotient Partial Differentials 
* Critical Points of 2D Functions
* Partial Differential Equations



### Tutorial Quiz

1. For a function \$f(x)\$ what does it mean when \$ f'(x)\$ and \$f''(x)\$ both equal zero? 
    <ul style="color:#557786;">
        <li> $f(x)$ has a critical point at $x$ which is a maximum</li>
    </ul>
2. List as many notations as you can for partial derivative with respect to: 
    * x
    * y
    * xx
    * xy
    * yy
    <ul style="color:#557786;">
    <li> $\frac{\partial}{\partial_x},\; \partial_x \; \cdot_x, $</li>
    <li> $\frac{\partial^2}{\partial_x^2},\; \frac{\partial}{\partial x}\left(\frac{\partial}{\partial_x}\right), \; \cdot_x^2, \; \cdot_{xx} $</li>
    </ul>
3. What is the relationship between \$ \partial_{xy}\$ and \$ \partial_{yx}\$.
    <ul style="color:#557786;">
        <li> For well behaved functions $ \partial_{xy} = \partial_{yx} $ </li>
    </ul>
4. Name and define the types of critical points. 
    * What does it mean for a point to be a critical point?
    <ul style="color:#557786;">
        <li> a critical point is a point $(x_0,y_0)$ where the gradient of the function is zero, i.e the partial derivatives of $f$ at $(x_0,y_0)$ are both equal to zero. </li>
        <li>
        <table>
            <tr>
                <th> Critical Point </th>
                <th> Type</th>
                <th> Local Definition </th>
                <th> Global Definition </th>
            </tr>
            <tr>
                <th> Maximum </th>
                <th> Extrema </th>
                <th> $f(x_0,y_0) \ge f(x,y)$ within a disc $B$ centred at $(x_0,y_0)$ </th>
                <th> $f(x_0,y_0) \ge f(x,y) \forall (x,y)$ </th>
            </tr>
            <tr>
                <th>Minimum </th>
                <th> Extrema</th>
                <th> $f(x_0,y_0) \le f(x,y)$ within a disc $B$ centred at $(x_0,y_0)$ </th>
                <th> $f(x_0,y_0) \le f(x,y) \forall (x,y)$ </th>
            </tr>
            <tr>
                <th> Saddle Point </th>
                <th> not extrema </th>
                <th> - </th>
                <th> - </th>
            </tr>
        </table>
        </li>
    </ul>
5. State the second derivative test. 
    * What assumptions can be made based on the different possible results of the second derivative test? 
    * When is the second derivative test inconclusive? 
    <ul style="color:#557786;">
    <li> For a critical point $(x_0,y_0)$ of a function $f(x,y)$ with continuous second order derivatives, let the determinant be given by
    $$D = f_{xx}f_{yy} - f_{xy}^2 $$
    Then: 
        <ul>
            <li> If $D>0$ and $f_{xx} > 0$ then $(x_0,y_0)$ is a local minimum </li>
            <li> If $D>0$ and $f_{xx} < 0$ then $(x_0,y_0)$ is a local maximum </li>
            <li> If $D<0$ then $(x_0,y_0)$ is a saddle point </li>
            <li> If $D=0$ the test is inconclusive </li>
        </ul>
    <li> The second partials test is inconclusive when the first and second order derivatives are both equal to zero, or the second derivative doesn't exist at the critical point. In this case we need higher derivatives (or other types of information about the function) to give indication of the behaviour of the critical point. </li>
    </ul>
6. What is the Hessian of a function? 
    * How does it relate to the second derivative test?
    <ul style="color:#557786;">
    <li> The Hessian
    $$ H(x,y) = \begin{bmatrix} f_{xx} & f_{xy} \\ f_{yx} & f_{yy} \end{bmatrix} $$ is a matrix containing all second order partial derivatives of the function. The determinant in the second partials test is the determinant of this matrix. (Check for yourself). 
    </li>
    </ul>
7. Write Cartesian coordinates in terms of cylindrical polar coordinates
    <ul style="color:#557786;">
    <li> $x = r\cos(\theta)$</li>
    <li> $y = r\sin(\theta)$ </li>
    <li> $z=z$ </li>
    </ul>
8. Write spherical polar coordinates in terms of Cartesian coordinates. 
    <ul style="color:#557786;">
    <li> $r= \sqrt{x^2+y^2+z^2} $</li>
    <li> $ \theta = \tan^{-1}(y/x) $ </li>
    <li> $ \phi=\cos^{-1}\left(\frac{z}{\sqrt{x^2+y^2+z^2}}\right) $ </li>
    </ul>

## Week 4 - Cartesian Double Integrals

* Order of Integration
* Averaging using integration

### Tutorial Quiz

1. For the functions given, state the type of rule that needs to be used and how to solve the following derivatives:
    * \$\frac{\partial}{\partial x} f(g(x,y))\$
    * \$ \frac{d}{d t} f(x(t),y(t)) \$ 
    * \$ \frac{\partial}{\partial y} f(x,y)\cdot g(x,y)\$
    * \$ \frac{\partial}{\partial x} \left(\frac{f(x,y)}{g(x,y)}\right)\$
    <ul style="color:#557786;">
        <li> Chain Rule </li>
        <li> Multivariate Chain Rule </li>
        <li> Product Rule </li>
        <li> Quotient Rule </li>
    </ul>
2. Name and write  the \$\nabla\$ operator in terms of \$\partial_x, \; \partial_y\$. 
    <ul style="color:#557786;">
        <li> $\nabla = \partial_x + \partial_y $</li>
    </ul>
3. What is: 
    * Laplace's equation for \$f(x,y)\$ 
    * The 1D wave equation for \$ f(x,t)\$ 
    * The 2D wave equation for \$ f(x,y,t)\$ 
    <ul style="color:#557786;">
        <li> $\nabla^2 f = \partial_x^2 f + \partial_y^2 = 0 $</li>
        <li> $ \partial_t f = c^2 \partial_x^2 f $ </li>
        <li> $ \partial_t^2 f = c^2 \partial_x^2 f $ </li>
    </ul>
4. What is the graphical interpretation of a double integral? 
    <ul style="color:#557786;">
        <li> Volume under the surface </li>
    </ul>
5. How do we evaluate double integrals? 
    <ul style="color:#557786;">
        <li> evaluate inside integral first, then outside integral </li>
    </ul>
6. State Fubini's theorem for \$ \iint f(x,y)dA \$ where \$ a \le x \le b\$ and \$ c\le y \le d\$.
    <ul style="color:#557786;">
        <li> $\iint_R f(x,y) dA = \int_c^d \int_a^b f(x,y) dxdy = \int_a^b \int_c^d f(x,y) dydx$</li>
    </ul>
7. What is the Jacobian of a coordinate system? 
    * How many different notations can you think of? 
    * What is the Jacobian of cylindrical polar (from cartesian)?
    * What is the Jacobian of cartesian (from cartesian)?
    * What is the Jacobian of spherical polar (from cartesian)?
    <ul style="color:#557786;">
        <li> The determinant of the Jacobian matrix is an indication of how much an area is deformed over a certain transformation - think similar to scale factors</li>
        <li> Notation: $J_{u,v},\; \frac{\partial(x,y)}{\partial(u,v)},\; \det(J)$ </li>
        <li> $J(r,\theta,z) = r $ </li>
        <li> $ J(r,\theta,\rho) = r^2\sin(\rho) $ </li>
    </ul>


## Week 5 - Double Integrals 2: Here's the remix 

* Jacobian 
* Change of coordinates
* Why when and how

### Tutorial Quiz

1. What is the Jacobian of a transform \$ (x,y) \to (u,v) \$?
    * What is the Jacobian of cartesian to cylindrical polar coordinates?
    * What is the Jacobian of cartesian to Spherical polar coordiantes?  <br/>
     <ul style="color:#557786;">
        <li> The Jacobian of a transform $ J(u,v) = \big| \frac{\partial(u,v)}{\partial(x,y)}\big| $, is given to be the modulus determinant of the matrix of first order partial derivatives. It can be thought of almost like a scale factor, in that it helps map the transform from the xy plan to the uv plane.  </li>
        <li>$J(r, \theta)  = \begin{vmatrix} \cos(\theta) & \sin(\theta) \\ -r\sin(\theta) & r\cos(\theta) \end{vmatrix}  = r$</li>
        <li> $J(r, \theta, \psi)  = \begin{vmatrix} \cos(\theta)\sin(\phi) & \sin(\theta)\sin(\phi) & \cos(\phi)  \\ -r\sin(\theta)\sin(\phi) & r\cos(\theta)\sin(\phi) & 0 \\ r\cos(\theta)\cos(\phi) & r\sin(\theta)\cos(\phi) & -r\sin(\phi) \end{vmatrix}  = r^2 \sin(\phi)$</li>
    </ul>
      
2. For a region \$ R\$ in the positive quadrant bound by: \$ x=y, xy=1,x=\sqrt{2}\$:
    * Sketch \$R\$ in the \$ xy\$ plane. 
    * Introduce \$ u = x/y\$, \$ v = xy\$. 
        * Rewrite the three bounding equations in \$u\$ and \$v\$. 
        * Sketch S, the transformed region R in the \$uv\$ plane. 
        * Work out the Jacobian of this transformation  
    <ul style="color:#557786;">
    <li> $u=1$, $v=1$, $uv = 2$</li>
    <li> Since $x = \sqrt{uv}$, $y= \sqrt{v/u}$, we have $ J(u,v) = \begin{vmatrix} \frac{1}{2}\sqrt{v/u} & \frac{-1}{2}\sqrt{\frac{v}{u^3}}  \\ \frac{1}{2}\sqrt{\frac{u}{v}} & \frac{1}{2}\sqrt{uv} \end{vmatrix} = \frac{1}{4(u+\sqrt{u})} $ </li>
    </ul>
3.  For a region \$ R\$ bound by: \$ x-2y=0, x-2y=4,3x-y=1, 3x-y=8\$:
    * Sketch \$R\$ in the \$ xy\$ plane. 
    * Introduce \$ u = x-2y\$, \$ v = 3x-y\$. 
        * Rewrite the three bounding equations in \$u\$ and \$v\$. 
        * Sketch S, the transformed region R in the \$uv\$ plane. 
        * Work out the Jacobian of this transformation
    <ul style="color:#557786;">
    <li> $u=0$, $u=4$, $v=1$, $v=8$</li>
    <li> Since $x = \frac{u-2v}{6}$, $y= \frac{v-3u}{5}$, we have $ J(u,v) = \begin{vmatrix} \frac{1}{6} & \frac{-1}{3} \\ \frac{-3}{5} & \frac{1}{5} \end{vmatrix} = \frac{-1}{6} $ </li>
    </ul>
4.  For a region \$ R\$ in the positive quadrant bound by: \$xy=1, xy=4, y=1, y=2\$:
    * Sketch \$R\$ in the \$ xy\$ plane. 
    * Introduce \$ x=u/v\$, \$ y=v\$. 
        * Rewrite the three bounding equations in \$u\$ and \$v\$. 
        * Sketch S, the transformed region R in the \$uv\$ plane. 
        * Work out the Jacobian of this transformation
    <ul style="color:#557786;">
    <li> $u=1$, $u=4$, $v=1$, $v=2$</li>
    <li> We have $ J(u,v) = \begin{vmatrix}\frac{1}{v} & \frac{-u}{v^2}\\ 1 & 0 \end{vmatrix} = \frac{1}{v} $ </li>
    </ul>
5. Find the Jacobian of the transformation \$x=u\$, \$ y=2uv\$. 
    * Sketch S, the region: \$ 1 \le u \le 2\$, \$ 2 \le 2uv \le 4\$ in the uv plane 
    <ul style="color:#557786;">
    <li> We have $ J(u,v) = \begin{vmatrix}1 & 0 \\ 2v & 2u \end{vmatrix} = 2u $ </li>
    </ul>
6. HARD: Consider the region R  bound by \$ x^2 \le y \le 1+x^2 \$, \$ \sqrt{1-x^2} \le y \le \sqrt{4-x^2}\$. 
    * Sketch R in the \$ xy \$ plane
    * Let \$ u = x^2+ y^2 \$, \$ v = y-x^2 \$. Sketch S in the \$ uv \$ plane
    * Determine the Jacobian of the change
    <ul style="color:#557786;">
    <li> This is easier to solve for (x,y) and invert.  we have $ J(x,y) = \begin{vmatrix} 2x &2y \\  -2x *1\end{vmatrix} =4xy + 2x $. Hence $J(u,v) = \frac{1}{4xy+2x} = \frac{1}{4xy + 2x}$ ( we really should convert to $(u,v)$ here but it's a bit disgusting to do it so it's left as an exercise.) </li>
    </ul>


## Week 6 - Polar coordinates

* Changing integral limits from cartesian to polar coordinates. 
    * Remember that \$(r,\theta)\$ means the point is a distance \$r\$ away from the origin, at an angle \$\theta\$ anticlockwise from the positive x axis. To describe the plane UNIQUELY by this system restrict \$r \ge 0\$ and \$ 0 \le \theta 2\pi\$.
    * When integrating over polar coordinates you need to include the Jacobian, so \$ dxdy \to rdrd\theta\$. 
* What shapes and surfaces are better described with polar coordinates?
    * Circles are the obvious choice, but anything sinusoidal or curved may do better in polar coordinates. 
* Evaluating integrals using order of integration or mixing integrals
    * Remember when changing order of integration the limits will also need to be changed, and if one of your boundaries is a function of the other axis, this will have to be on the inside integral. 

### Tutorial Quiz
This week break up into 5 teams and each team work on a question, explain the solution to the rest of the class. The questions are broken down into smaller parts as a guide. [SOLUTIONS](https://kap39.github.io/files/Week6.pdf "Solutions")

1. Regions when transformation given: For the following Sketch the original region and the new region mapped by the transform, state the new bounding equations. 
    * For a region \$R\$ bound by the ellipse \$ x^2 + \frac{y^2}{36} = 1\$, and transform \$x=u/2\$ and \$ y= 3v\$
    * For the region \$ R \$ bound by the lines \$ y=-x+4\$, \$ y=x+1 \$ and \$ y=x/3 - 4/3 \$, with transformation \$x=\frac{u+v}{2} \$, \$ y = \frac{u-v}{2}\$.
    * For the trapezoidal region \$ R \$ with vertices given by \$(0,0)\$, \$(5,0)\$, \$(2.5,2.5)\$ and \$(2.5,-2.5)\$, using the transformation \$ x=2u+3v\$ and \$ y = 2u-3v\$. Solve the integral \$\iint x+y dA\$ using the transformation

2. Transformations when region given: For the following give the transform that maps one region to the other, and draw both regions. 
    * \$R\$ is the triangle with vertices (3,2), (-1,2), (-3,-2), and \$S\$ is the triangle with vertices (1,0), (0,1), (-1,0).
    * \$R\$ is the parallelogram with vertices (0,0),  (4,2), (3,4) and (-1,2). \$S\$ is the region defined by \$ 0 \le u \le 10\$, \$ 0 \le v \le 5 \$. 
    * \$ R\$ is the region bound by the equations \$ y = \sqrt{1-x^2}\$ and \$y=\sqrt{4-x^2}\$. \$S\$ is the region defined by \$1\le u \le 2\$, \$ 0 \le v \le \pi\$. 
    * \$ R \$ is the unit circle centered at the origin, \$S\$ is a unit square with vertices (0,0), (0,1) (1,0), (1,1). 

3.  Revising Chain rule and Polar Coordinates: 
    * What are cartesian coordinates in terms of polar coordinates. 
    * What is the chain rule for \$\frac{d f(g(x))}{dx}\$.
    * What is the multivariate chain rule for \$ \frac{df(x(t),y(t))}{dt} \$
    * What is the multivariate chain rule for \$ \frac{\partial f(x(t,s),y(t,s)}{\partial s} \$. 
    * What is the integral over an area in a general coordinate system? e.g in cartesian \$ \iint 1 dxdy\$. 
    * what is the equation of the Jacobian of a transform \$ (x,y) \to (u,v)\$
    * What is the equation of the Jacobian of a transform \$ (u,v) \to (x,y) \$
    * What is the Jacobian of cartesian to polar coordinates? Show workings.

4. Cartesian to Polar Limits: Rewrite the following integral limits into 2d polar coordinates.
    *  \$\int_0^\infty \int_0^\infty\ldots dydx = \iint\ldots rdrd\theta \$
    *  \$ \int_{-\infty}^\infty \int_{-\infty}^\infty\ldots dxdy = \iint \ldots rdrd\theta \$
    * \$ \int_0^1 \int_0^1 \ldots dxdy = \iint \ldots rdrd\theta \$  
    * \$ \int_0^1 \int_y^{y^2} \ldots dxdy = \iint \ldots rdrd \theta \$ 
    * \$ \int_0^\sqrt{2} \int_y^{\sqrt{4-y^2}} \ldots dxdy = \iint \ldots rdrd\theta \$.

5. Polar integration: Evaluate the area enclosed by the circle \$r=3cos(\theta)\$ and $r=1+cos(\theta)\$. 
    * Sketch the regions
    * Calculate the points of intersection
    * What symmetries or separations of the region can you use to simplify the integral
    * Write down the limits of integration \$ \iint rdrd\theta + \iint rdrd\theta\$. 
    * Evaluate the integral. 



## Week 7 - Triple Integrals
Solutions can be found [here](https://kap39.github.io/files/week7.pdf "Solutions")

* What does it mean?
    * For single integrals - area under a curve
    * Double integrals  - volume under a surface
    * Triple integrals - something 4D? Not super obvious what it represents geometrically. BUT it can be an alternate way to show volume under a surface - when the integrand is 1
* Triple integrals generally behave the same way as double  - integrate inside first, ensuring the limits of integration describe the region uniquely.
* Jacobian still works the same, but now is a 3x3 matrix - remember how to calculate the determinant of a 3x3 matrix!




### Tutorial Quiz
1. Calculate the line element, area element and volume element of integration in polar, cylindrical polar, and spherical polar coordinates, respectively. i.e what is?
    * dL in terms of r
    * dA in terms of \$(r,\theta)\$
    * dV in terms of \$(r,\theta,\phi)\$
2. Change the order of integration from \$dxdydz\$ to \$dzdydx\$  of the following
    * \$ \int_0^5 \int_0^2 \int_0^\sqrt{4-y^2} dxdydz \$
    * \$  \int_0^4 \int_0^{4-y} \int_0^{\sqrt{z}} dxdzdy\$ 
3. Use double integrals in polar coordinates to find the volume of the oblate spheroid \$ \frac{x^2}{a} + \frac{y^2}{a} + \frac{z^2}{c} = 1\$ where \$0 < c < a\$
4. Sketch the regions and express them as limits of a triple integral of volume:
    * \$ 0 \le z \le y^2,\quad 0\le y \le 1,\quad 0 \le x \le \pi/4\$
    * \$ x \ge 0, \quad y \ge 0, \quad 0 \le z \le 1-y-x\$
    * \$ x^2 + y^2 =1, \quad z=0,\quad z=y\$
5. Evaluate \$ \iiint_R 3-4x dV \$ where \$R\$ is the region below \$ z=1-xy\$ and above the region in the xy plane defined by \$ 0 \le x \le 1, 0 \le y \le 1\$.
    * Sketch the region
    * Determine limits and order of integration
    * Evaluate integral





## Week 8 - Differential Equations

This week we shift track and start looking at differential equations. We start with linear and separable differential equations. 
*  Separable Equations
    * These ODE's can be written in the form \$\frac{dy}{dx} = f(x)g(y)\$
    * As long as \$g(y) \ne 0\$ we can write \$\int \frac{1}{g(y)}dy = \int f(x)dx\$ and solve.
* Linear ODEs
    * Can be written in the form \frac{dy}{dx} + a(x) y = b(x) \$ 
    * Solve using Integrating Factor Method
    * \$IF = e^{\int a(x) dx}\$
    * the general solution then takes the form \$y(x) = \frac{1}{IF}\int IF b(x) dx\$. 

## Week 9 - More first order differential equations

Now looking at some more general types of first order ODE's

* Bernoulli Equations
* Homogeneous Equations
* Exact Equations

## Week 10 - Second order differential equations

Second order differential equations now require different methods to solve. In general the ones we consider take the form \$ a\frac{d^2y}{dx^2} + b\frac{dy}{dx} + cy = d(x)\$, with \$a\$ nonzero (else it would be first order - think about it). We call \$d(x)\$ the forcing term, so if \$d(x)=0\$ the equation is called "homogeneous", of "free". 
* Homogeneous/Free:
    * Have \$d(x) = 0\$
    * Solve using auxillary equation (take order of differential and replace with powers of \$\lambda\$) \$a\frac{d^2y}{dx^2} + b\frac{dy}{dx} + cy \to a\lambda^2 + b\lambda + c = 0\$
        * Two real, distinct roots \$\lambda_1, \lambda_2\$: \$ y = Ae^{\lambda_1 x} + Be^{\lambda_2 x}\$.
        * Real, repeated root \$\lambda\$ : \$y = Ae^{\lambda x} + Bxe^{\lambda x}\$
        * Complex Conjugate roots \$\lambda = \alpha \pm \beta i\$: \$ y = e^{\alpha x}(A\cos(\beta x) + B\sin(\beta x))\$.
* Inhomogeneous/Forced:
    * \$d(x) \ne 0\$
    * General Solution: Sum over the complementary function and particular integral
        * Find general solution to corresponding free ODE, this is called the complementary function (see above)
        * Find particular integral that satisfies forced ODE - particular solution will be of the same form as \$d(x)\$ and will need substitution into equation to find coefficients. e.g.
            * \$a e^{bx}\$
            * \$ ax^2 + bx + c\$ 
            * \$a\cos(bx) + c\sin(dx)\$



## Week 11 - Mechanics


 -->

