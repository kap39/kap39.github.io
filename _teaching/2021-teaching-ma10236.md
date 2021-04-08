---
title: "MA10236: Methods and Applications 1B"
collection: teaching
type: "Undergraduate course"
permalink: /teaching/ma10236
venue: "University of Bath, Online"
date: 2021-01-29
location: "Bath, UK"
---

This page is for the 2020/21 Semester 2 module MA10236:Methods and Applications 1B. The notes provided on this page are provided exclusively for educational purposes at the University of Bath  to supplement the module MA10236, and are to be used for private study only. 


Deadlines and Tutorial Info
======

Please submit your homework to me via moodle, weekly before Wednesday at 9AM (GMT). The tutorials are held weekly on zoom at the times described below. Please email me if you are going to miss a tutorial or can't make this homework deadline if you require an extension. 
- A2: Fridays 12:15
- A3: Fridays 13:15


Week 1
======

* Vectors
    * Magnitude and direction \$\mathbf{a}\$.
    * Directed line segment characterized by two ordered points. \$\overrightarrow{PQ}\$.
    * Norm: \$ \Vert \mathbf{a}\Vert = \sqrt{\sum a_i^2} \$ OR length of the line segment. 
        * This is a scalar quantity (just magnitude, no direction)
    * If \$\mathbf{a} = \overrightarrow{PQ}\$, then \$-\mathbf{a} = \overrightarrow{QP}\$. 


Week 2
======
* Vector addition and vector-scalar multiplication 
    * \$ \mathbf{a} + \mathbf{b} = \mathbf{b} + \mathbf{a} \$ 
    * \$ (\mathbf{a} + \mathbf{b}) + \mathbf{c} = \mathbf{a} + (\mathbf{b} + \mathbf{c}) \$ 
    * \$ \mathbf{a} + \mathbf{0} = \mathbf{0} + \mathbf{a} = \mathbf{a} \$
    * \$ \mathbf{a} + (-\mathbf{a}) = \mathbf{0} \$
    * \$ \lambda( \mu \mathbf{a}) = (\lambda \mu \mathbf{a})\$
    * \$\lambda( \mathbf{a} + \mathbf{b}) = \lambda\mathbf{a} + \lambda \mathbf{b} \$
    * \$ (\lambda + \mu) \mathbf{a} = \lambda \mathbf{a} + \mu \mathbf{a} \$
* Unit vector \$\hat{\mathbf{a}} = \frac{\mathbf{a}}{\Vert\mathbf{a}\Vert}\$
* Projection
    * For two vectors \$ \mathbf{a}, \mathbf{b}\$, \$\mathbf{b}\$ can be described as a projection on \$\mathbf{a}\$, which we can denote \$ \mathbf{b}\_{\Vert}\$ (  the part of \$\mathbf{b}\$ parallel to \$\mathbf{a}\$) and a perpendicular component denoted \$ \mathbf{b}\_{\perp}\$. )
    * \$ \mathbf{b}_{\Vert} = \Vert\mathbf{b}\Vert \cos(\theta)\$ where \$ \theta\$ is the angle between \$\mathbf{a}\$ and \$\mathbf{b}\$. 
* Dot product
    * \$ \mathbf{a} \cdot \mathbf{b} = \sum a_i b_i = \Vert\mathbf{a}\Vert \Vert\mathbf{b} \Vert \cos(\theta)\$. 
    * equal to zero when the vectors are perpendicular. 
    * \$ \mathbf{a} \cdot \mathbf{a} = \Vert\mathbf{a}\Vert^2 \$
    * returns a scalar value. 
* Cross product
    * \$ \mathbf{a} \times \mathbf{b}\$ returns a vector which is orthogonal to both \$ \mathbf{a} \$ and \$ \mathbf{b}\$. 
    * a vector cross producted with itself returns the zero vector. 
    * \$ \Vert \mathbf{a} \times \mathbf{b} \Vert \$ gives the area of the parallelogram spanned by \$ \mathbf{a}\$ and \$\mathbf{b}\$.
    * \$ \Vert \mathbf{a} \times \mathbf{b} \Vert = \Vert\mathbf{a} \Vert \Vert \mathbf{b}\Vert \sin(\theta)\$ 
    * If equal to zero, the two vectors are parallel. 
    * Is the determinant of the matrix whose rows are the cartesian spanning vectors, \$ \mathbf{a}\$, and \$\mathbf{b}\$ respectively.

Week 3
======

* Scalar triple product 
    * \$\[\mathbf{a},\mathbf{b},\mathbf{c}\] = \mathbf{a}\cdot( \mathbf{b}\times \mathbf{c})\$
    * The scalar triple product calculates the volume of the parallelepiped spanned by the three vectors. 
    * When it's \$0\$ the three vectors are coplanar. 
        * Note: Three vectors are coplanar if there exists three scalars \$  \lambda, \mu, \nu \$ with \$\lambda^2 + \mu^2 + \nu^2 >0\$ such that \$ \lambda \mathbf{a} + \mu \mathbf{b} + \nu \mathbf{c} = \mathbf{0}$. 
    * It's the same up to cyclic permutations, but swaps sign when only two swap places. 
    * If any two of the vectors in the scalar triple products are the same, it's equal to zero (see coplanar). 
    * \$\lambda \[\mathbf{a},\mathbf{b},\mathbf{c}\] = \[\lambda \mathbf{a},\mathbf{b},\mathbf{c}\] \$
* vector triple product
    * \$ \mathbf{a}\times(\mathbf{b}\times \mathbf{c}) = (\mathbf{c}\cdot \mathbf{a}) \mathbf{b} - (\mathbf{b}\cdot \mathbf{a})\mathbf{c}\$.
    * \$ \mathbf{a}\times(\mathbf{b}\times \mathbf{c}) \ne  (\mathbf{a}\times\mathbf{b})\times \mathbf{c} \$ (Not associative!!).
* Equation of a straight line 
    * If a line is defined with \$\mathbf{r} = \mathbf{a} + \lambda \mathbf{l}\$ then it can be throught of as the line passing through \$\mathbf{a}\$ in the direction given by $\mathbf{l}\$, then each point on the line is given by a different value of the scale parameter \$\lambda\$. 
    * Alternate form: \$ (\mathbf{r} - \mathbf{a}) \times \mathbf{l} = \mathbf{0}$. (Implies that \$\overrightarrow{AR} \Vert \mathbf{l}\$).
    * Two lines ( $\mathbf{r} = \mathbf{a}+\lambda \mathbf{l}\$, \$\mathbf{r} = \mathbf{b} + \mu \mathbf{m}\$) intersect iff \$\[\mathbf{a},\mathbf{l},\mathbf{m}\]  = \[\mathbf{b},\mathbf{l},\mathbf{m}\] \$. 
        * This can be used to find common perpendiculars to two lines. 
        * means that \$ \mathbf{a}-\mathbf{b}, \mathbf{l}, \mathbf{m}\$ are coplanar. 
    

Week 4
======

* Common perpendicular of two lines \$\mathbf{r} = \mathbf{a} + \lambda\mathbf{l}\$ and $\mathbf{r} = \mathbf{b} + \mu \mathbf{m}\$. 
    * This is the shortest distance between the two lines. 
    * Has the form \$\mathbf{r} = \mathbf{c} + \nu \mathbf{n}\$, where $\mathbf{n} = \mathbf{l}\times\mathbf{m}\$, and $\mathbf{c}\$ is a point on one of the lines. 
* Equation of a plane \$\Pi\$.
    * parametric form: \$ \mathbf{r} = \mathbf{a} + \lambda \mathbf{l} + \mu\mathbf{m}$, for $\mathbf{l}, \mathbf{m}\$ parallel to \$\Pi\$, and unique scalars \$\lambda, \mu\$. 
    * Normal and a point: \$ (\mathbf{r}-\mathbf{a}).\mathbf{N}=0 \$ . Or \$ \mathbf{r}\cdot \mathbf{N} = \mathbf{a}\cdot \mathbf{N}\$. 

Week 5
======
Given a position vector \$ \mathbf{r} = \mathbf{r}(t) = x(t)\mathbf{i} + y(t)\mathbf{j} + z(t)\mathbf{k}\$.
* The equation of a straight line can be described as \$ \mathbf{r} = \mathbf{a} + \lambda \mathbf{l}\$. 
* The derivative \$\mathbf{r}^\prime(t) = x^\prime(t)\mathbf{i} + y^\prime(t)\mathbf{j} + z^\prime(t)\mathbf{k}\$.
* \$ \frac{d}{dt}(\Vert\mathbf{r}\Vert) = \frac{1}{\Vert \mathbf{r}\Vert}\mathbf{r}\cdot \mathbf{r}^\prime \$. 
* If \$\mathbf{r} = \mathbf{r}(t)\$ and \$t = t(s)\$, then:
    * arc length: \$ s(t) = \int_{t_0}^t \Vert \mathbf{r}^\prime (\tau)\Vert d\tau \$. 
    * \$ \frac{ds}{dt} = \Vert \mathbf{r}^\prime(t) \Vert \$.
    * \$ \frac{d\mathbf{r}}{ds} = \frac{d\mathbf{r}}{dt} \frac{dt}{ds} \$ .
* The Unit Vector Tangent:
    *  \$ \hat{\mathbf{T}}(t) = \frac{\mathbf{r}^\prime(t)}{\Vert \mathbf{r}^\prime (t) \Vert} =  \frac{d\mathbf{r}}{ds} \$. 
    * \$ \Vert \hat{\mathbf{T}} \Vert = 1 = \hat{\mathbf{T}}\cdot \hat{\mathbf{T}}\$. 
    * \$ \hat{\mathbf{T}}\cdot \frac{d\hat{\mathbf{T}}}{dt} = 0 \$.
* Principal Unit Normal: 
    * \$ \hat{\mathbf{N}} = \frac{\hat{\mathbf{T}}^\prime}{\Vert\hat{\mathbf{T}}^\prime\Vert} \$. 
* Curvature: 
    * \$ \kappa = \Vert \frac{d\hat{\mathbf{T}}}{ds} \Vert  = \Vert \frac{d^2\hat{\mathbf{r}}}{ds^2} \Vert = \frac{\Vert\hat{\mathbf{T}}^\prime \Vert}{\Vert \mathbf{r}^\prime\Vert} \$. 
* Radius of curvature: \$ a = 1/\kappa\$. 
* Vector line integral of vector function \$ \mathbf{F}(\mathbf{r}(t))\$ for \$ a \le t \le b\$ is given by \$ I  = \int_a^b \mathbf{F}(\mathbf{r}(t))\cdot \mathbf{r}^\prime(t) dt \$.
* Scalar line integral of scalar function \$ \rho(\mathbf{r})\$ for \$ a \le t \le b\$  given by \$ I = \int_C \rho(\mathbf{r}) ds = \int_a^b \rho(\mathbf{r}) \Vert \mathbf{r}^\prime \Vert dt \$. 
* Derivative
    * Nabla : $\nabla = \partial_x \mathbf{i} + \partial_y \mathbf{j} + \partial_z \mathbf{k} \$. 
    * Gradient of scalar function: \$ \nabla f = f_x \mathbf{i} + f_y \mathbf{j} + f_z \mathbf{k} \$. 
    * Directional derivative: \$ D_{\mathbf{u}} f = \mathbf{u} \cdot \nabla f \$. 

* Worked Example: For a curve given by \$ \mathbf{r}(t) = 3t^2\mathbf{i} + 2t\mathbf{j} + \mathbf{k}\$. Find:
    * Unit tangent vector: 
        * First: \$ \mathbf{r}^\prime = 6t \mathbf{i} + 2 \mathbf{j}\$. 
        * Then we have \$ \Vert \mathbf{r}^\prime \Vert = \sqrt{ (6t)^2 + 2^4} =\sqrt{36t^2 + 4} = 2 \sqrt{9t^2 + 1}\$. 
        * Finally \$\hat{\mathbf{T}} = \frac{\mathbf{r}^\prime}{\Vert \mathbf{r}^\prime \Vert} = \frac{3t\mathbf{i} + \mathbf{j}}{\sqrt{9t^2 + 1}} \$.
    * Arc length measured from the point \$ A= (12, 4, 1 ) \$. 
        * Need to find \$ t_0\$ at \$ A = (12, 4, 1) \$. which has \$ x = 3t^2 = 12\$, \$ y = 2t = 4\$ and $z= 1 = 1\$. Hence \$t_0 = 2\$.
        * \$ s(t) = \int_2^t \Vert \mathbf{r}(\tau) \Vert d\tau = t\sqrt{9t^2+1}  + \frac{1}{3}\sinh^{-1}(3t) -(2\sqrt{37}+\frac{1}{3}\sinh^{-1}(6))\$. 
    * Principal unit normal: 
        * First: \$ \hat{\mathbf{T}}^\prime = \frac{3}{(9t^2+1)^{3/2}}\mathbf{i} - \frac{9t}{(9t^2+1)^{3/2}}\mathbf{j}\$. 
        * Then we have \$ \Vert \hat{\mathbf{T}}^\prime \Vert =\sqrt{\frac{18t^2 + 9}{(9t^2+1)^3}} = \frac{3}{9t^2+1}\$. 
        * Finally \$\hat{\mathbf{T}} = \frac{\mathbf{r}^\prime}{\Vert \mathbf{r}^\prime \Vert} = \frac{3t\mathbf{i} + \mathbf{j}}{\sqrt{9t^2 + 1}} \$.
    * Curvature:
        * \$ \kappa = \frac{\Vert \hat{\mathbf{T}}^\prime\Vert}{\Vert\mathbf{r}^\prime \Vert} = \frac{3}{2\sqrt{9t^2+1}} \$.
    * Where the vector function is \$ \mathbf{F}(\mathbf{r}) = (x+y)\mathbf{i} + z\mathbf{j} \$ for \$ 0 \le t \le 1\$, the vector line integral:
        * In terms of \$t\$, \$ \mathbf{F}(\mathbf{r}(t)) = (3t^2 + 2t)\mathbf{i} + \mathbf{j} \$. 
        * \$ \mathbf{F}(\mathbf{r}(t)) \cdot \mathbf{r}^\prime = (3t^2 + 2t)6t + 2 = 18t^3 + 12t^2 + 2 \$. 
        * \$ I = \int_0^1 \mathbf{F}(\mathbf{r}(t)) \cdot \mathbf{r}^\prime dt = 19/2 \$.
    * Where the scalar function is \$ \rho(\mathbf{r}) = x-2z \$ for \$ 0 \le t \le 1\$, the scalar line integral:
        * In terms of \$ t\$, \$ \rho(\mathbf{r}(t)) = 3t^2- 4 \$. 
        * \$ I = \int_0^1 2(3t^2-4)\sqrt{9t^2+1} dt \approx 32 \$.

Week 6
=====
* Differentiating vectors: 
    * \$ \frac{d}{dt} ( \mathbf{c}) = \mathbf{0} \$. 
    * \$ \frac{d}{dt} ( \mathbf{r}_1(t) + \mathbf{r}_2(t)) = \frac{d}{dt}(\mathbf{r}_1(t)) + \frac{d}{dt}(\mathbf{r}_2(t))\$. 
    * \$ \frac{d}{dt}(\mathbf{r}_1(t) \cdot \mathbf{r}_2(t)) = \frac{d\mathbf{r}_1}{dt} \cdot \mathbf{r}_2 +  \mathbf{r}_1\cdot \frac{d\mathbf{r}_2}{dt} \$.
    * \$  \frac{d}{dt}(\mathbf{r}_1(t) \times \mathbf{r}_2(t)) \frac{d\mathbf{r}_1}{dt} \times \mathbf{r}_2 +  \mathbf{r}_1\times\frac{d\mathbf{r}_2}{dt} \$. Order matters.
* Position vector of a particle \$ P\$ is given by \$ \mathbf{x}(t)\$.
    * \$ r(t) = \Vert \mathbf{x}(t) \Vert \$. 
    * The velocity of the particle \$ \mathbf{v}(t) = \dot{\mathbf{x}} = \frac{d\mathbf{x}}{dt}\$. 
    * The speed of the particle: \$ v = \Vert \mathbf{v} \Vert \$. 
    * The acceleration of the particle: \$ \mathbf{a} = \dot{\mathbf{v}} = \frac{d\mathbf{v}}{dt} =  \ddot{\mathbf{x}} =  \frac{d^2\mathbf{x}}{dt^2} \$. 
* Identities: 
    * \$ r\dot{r} = \mathbf{x} \cdot \dot{\mathbf{x}}\$. 
    * \$ v \dot{v} = \dot{\mathbf{x}} \cdot \ddot{\mathbf{x}} = \mathbf{v} \cdot \dot{\mathbf{v}} \$. 
* Remember how to solve second order ODE's
    * General soltion = Complimentary function + Particular integral.
    * Integrating Factor.
    * Integrate out.
* Cartesian to cylindrical polar basis vectors: 
    * \$ \mathbf{e}_r = \cos\theta \mathbf{i} + \sin \theta \mathbf{j} \$.
    * \$ \mathbf{e}_\theta = -\sin \theta \mathbf{i} + \cos \theta \mathbf{j} \$. 
    * \$ \mathbf{e}_z = \mathbf{k} \$. 

Week 7
====
* Harmonic equation : \$ \ddot{\mathbf{x}} + \omega \mathbf{x} = 0\$, \$\omega = \$ constant. 
    * General solution of the form \$ \mathbf{x}(t) = \mathbf{a}\cos(\omega t) + \mathbf{b}\sin(\omega t)\$. 
    * Periodic solution with period \$T= 2\pi /\omega\$. 
* Orbits
    * Work in Polar coordinates \$ \mathbf{e}\_r, \mathbf{e}\_\theta\$
    * Following a moving point \$\dot{\mathbf{e}}_r=\dot{\theta}\mathbf{e}\_\theta\$, and \$\dot{\mathbf{e}}\_\theta=-\dot{\theta}\mathbf{e}\_r\$
    * Position vector \$ \mathbf{x}(t) = r(t) \mathbf{e}_r(\theta(t))\$. 
    * \$ \ddot{\mathbf{x}} = (\ddot{r}-r\dot{\theta}^2)\mathbf{e}\_r + (r\ddot{\theta} + 2\dot{r}\dot{\theta})\mathbf{e}_\theta\$.
    * \$ \dot{\theta} \$ is the angular momentum (denoted \$ \omega \$).
* Keplers Laws 
    * *K1* Each planet moves in an ellipse with the Sun as its focus. 
    * *K2* Areas swept out by a line segment connecting the orbit and a planet in equal times are equal.
    * *K3* The perido of revolution squared is proportional to the semi major axis cubed: \$T^2 = ca^3\$. 
* Newtons Laws
    * *N1* Bodies have constant velocity unless acted upon by external forces (inertia)
    * *N2* A particle of mass \$m\$ acted upon by a force \$\mathbf{F}\$  has an acceleration determined by \$\mathbf{F} = m \mathbf{a}\$. 
    * *N3* Two bodies exert forces on eachother which are: equal in magnitude, in opposite direction to eachother, and parallel to the straight line joining the two bodies.
* Forces
    * Constant forces e.g gravity close to the earths surface,  are described by a constant vector. 
    * Resistive forces e.g friction, viscosity, and drag. These forces act to oppose motion of a particle. 
    * Central forces e.g gravity between a body and a satellite. This force acts towards or away from the center of force.
    * The force between two bodies is often given by an inverse square law, . For bodies \$ \mathbf{x}_1, \mathbf{x}_2\$ we have
    \$\$ \mathbf{F} =K \frac{\mathbf{x}_1 - \mathbf{x}_2}{\Vert \mathbf{x_1} - \mathbf{x}_2\Vert^3} \nonumber \$\$
        which is either attractive or repulsive based on the sign of \$K\$.
    * The weight of a particle close to the surface of the earth is \$ \mathbf{F} = m \mathbf{g}\$. 
* Projectiles 
    * Under gravity with no air resistance
        * Equation of motion \$ \ddot{\mathbf{x}} = \mathbf{g} \$.
        * Motion governed by \$ \matahbf{x}(t) = \mathbf{x}_0 + \mathbf{v}_0 t + \frac{1}{2} \mathbf{g}t^2 \$. 
        * Initial position \$ \mathbf{x}(0) = \mathbf{x}_0\$, launched at angle \$\alpha\$ from the horizontal with  initial velocity\$ \mathbf{v}(0) = \dot{\mathbf{x}}(0) = \mathbf{v}_0\$. 
        * Horizontal distange (range) given by \$ X = \frac{v_0^2 \sin(2\alpha)}{g}\$ maximum at \$\alpha = \frac{\pi}{4}, X = \frac{v_0^2}{g}\$. 
    * Under gravity with air resistance
        * Now equation of motion has drag forces: \$ \ddot{\mathbf{x}} + \frac{\mu}{m} \dot{\mathbf{x}} = \mathbf{g}\$.
        * Trajectory is now different and range equation is also different. 
<!--
Week 8 
====

* A Simple Pendulum: A Particle \$P\$ suspended from a fixed point \$O\$ by an inextensible length of sting of length \$l\$. Subject to uniform gravity and moves in the vertical plane containing \$O\$. 
    * Define angle \$\theta\$ to the vertical and work in polar coordinates. The position of the particle given by \$ \mathbf{x} = r\mathbf{e}_r\$.
    * Tension \$\mathbf{T}\$ in the string acts in the direction \$-\mathbf{e}_r\$.
    * The weight of the particle is given by \$ -mg\mathbf{k}\$. 
    * Resolving forves gives the equation of motion \$ m\ddot{\mathbf{x}} = m\mathbf{g} + \mathbf{T} \$.

-->