---
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

UPDATE: I have included all previous weeks quizzes, including solutions after each question in <p style="color:#557786;"> teal </p>, no graphs provided for the moment until I can think of a low effort way to do it.

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

<!--
### Tutorial Quiz 

1. For the continuous function \$ f(x) \$: 
    * What is the notation for derivative with respect to \$ x\$ (list as many as possible) ?
    * What is the notation for the indefinite integral?
    * What is the notation for definite integral over \$ [a,b]\$
2. State the Fundamental Theorem of Calculus. 
3. What is the relation between \$ \int_a^b f(x) dx \$ and \$ \int_b^a f(x) dx\$. 
4. For a continuous function \$ f(x)\$ over an interval \$[a,b]\$
    * What is the equation of Arc Length \$S\$?
    * What is the equation of Surface Area of Revolution, \$A \$? 
5. Sketch the following functions 
    * \$ y = \cosh(x) \$
    * \$ y = \sinh(x) \$
    * \$ y = \tanh(x) \$
-->


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

<!-- 
### Tutorial Quiz 

 1. What is the relationship between 2D cartesian \$(x,y) \$ and polar coordinates \$(r,\theta) \$ ?
 2. What shape is given by \$ r= 3 \$ in cylindrical polar coordinates?
 3. For constants \$ a,b,c\$ describe the shape of \$ r=a, \theta=b, \phi = c\$ in spherical coordinates.
 4. True or False
    * The equations \$ r = 2\$ and \$ x^2 + y^2 + z^2 = 2\$ represent the same surface.
    * The coordinates of a point in cylindrical coordinates are unique
    * The coordinates of a point in cartesian coordinates are unique. 
    * The equation of a cardoid is \$ r = 1-cos(\theta) \$.
    * The equation \$ r = \theta/2\pi \$ in polar coordinates is the Fibonnaci spiral. 
 5. What shape is given by \$\phi = \frac{\pi}{4} \$ in spherical coordinates?
-->


## Week 3 - Partial Differentials

* Partial Differentiation
* Chain, Product and Quotient Partial Differentials 
* Critical Points of 2D Functions
* Partial Differential Equations


<!--
### Tutorial Quiz

1. For a function \$f(x)\$ what does it mean when \$ f'(x)\$ and \$f''(x)\$ both equal zero? 
2. List as many notations as you can for partial derivative with respect to: 
    * x
    * y
    * xx
    * xy
    * yy
3. What is the relationship between \$ \partial_{xy}\$ and \$ \partial_{yx}\$. 
4. Name and define the types of critical points. 
    * What does it mean for a point to be a critical point?
5. State the second derivative test. 
    * What assumptions can be made based on the different possible results of the second derivative test? 
    * When is the second derivative test inconclusive? 
6. What is the Hessian of a function? 
    * How does it relate to the second derivative test?
7. Write cartesian coordinates in terms of cylindrical polar coordinates
8. Write spherical polar coordinates in terms of cartesian coordinates. 

-->
## Week 4 - Cartesian Double Integrals

* Order of Integration
* Averaging using integration

<!--
### Tutorial Quiz

1. For the functions given, state the type of rule that needs to be used and how to solve the following derivatives:
    * \$\frac{\partial}{\partial x} f(g(x,y))\$
    * \$ \frac{d}{d t} f(x(t),y(t)) \$ 
    * \$ \frac{\partial}{\partial y} f(x,y)\cdot g(x,y)\$
    * \$ \frac{\partial}{\partial x} \left(\frac{f(x,y)}{g(x,y)}\right)\$
2. Name and write  the \$\nabla\$ operator in terms of \$\partial_x, \; \partial_y\$. 
3. What is: 
    * Laplace's equation for \$f(x,y)\$ 
    * The 1D wave equation for \$ f(x,t)\$ 
    * The 2D wave equation for \$ f(x,y,t)\$ 
4. What is the graphical interpretation of a double integral? 
5. How do we evaluate double integrals? 
6. State Fubini's theorem for \$ \iint f(x,y)dA \$ where \$ a \le x \le b\$ and \$ c\le y \le d\$.
7. What is the Jacobian of a coordinate system? 
    * How many different notations can you think of? 
    * What is the Jacobian of cylindrical polar (from cartesian)?
    * What is the Jacobian of cartesian (from cartesian)?
    * What is the Jacobian of spherical polar (from cartesian)?
-->


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

<!--
## Week 6 - Polar coordinates

* More double integrals I guess

## Week 7 - Triple Integrals

* Seriously? 

## Week 8 - Differential Equations
## Week 9
## Week 10
## Week 11
 -->

