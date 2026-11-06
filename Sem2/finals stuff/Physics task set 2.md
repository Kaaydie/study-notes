# Task 1. 
An airplane rises up with a constant velocity v = 700 km/h. After a time interval t = 4
min, the airplane reaches height h = 4 km. What is the velocity vx of a plane shadow on the
Earth surface?
![[Pasted image 20260829140526.png]] 
$v=700km/h=194.4m/s$

$4km/4min=1km/min=16.6m/s$

$v_{x}^{2}=194.4^{2}-16.6^2$ 
$v_{x}\approx 193.7288m/s\approx 697.42km/h$

# task 2.
A body falling downward gets a velocity v1 = 29 m/s at point A and v2 = 49 m/s at
point B. What is the distance AB and time for passing this distance?
![[Pasted image 20260829140555.png]]
asuming $g\approx 10m/s^{2}$
$t=2s$

$d=v_{1}·t+\frac{1}{2}·g·t^{2}$
$d=58+20=78m$
# task 3.
What is the initial velocity v0 in the vertical motion of a ball down if after the
reflection from the ground the ball jumped on height h = 15 m above the throwing level?
Neglect the air friction and consider the ball as perfectly elastic. 
$h=15m$
$v=\sqrt{ 2gh }=\sqrt{ 2·9.8·15 }=\sqrt{294}\approx17.2m/s$

# task 4.
Motion of a body is described by the following set of parametric equations:
x = r sinωt and y = r cosωt, where r(t) = const and ω(t) = const. (A) Determine the
components of the velocity and acceleration vectors. (B) Prove that the trajectory of motion is
a circle with the radius r. (C) Find the absolute value of the velocity and acceleration.

$v_{x}=\frac{dx}{dt}=r\omega \cos\omega t$
$v_{y}=\frac{dy}{dt}=-r\omega \sin\omega t$
$\vec{v}=(r\omega \cos\omega t,-r\omega \sin\omega t)$

$a_{x}=\frac{dv}{dt}=-rw^{2}\sin\omega t$
$a_{y}=\frac{dy}{dt}=-r\omega^{2}\cos\omega t$
$\vec{a}=(-w^{2}x,-w^{2}y)$

B)
$x^{2}+y^{2}=r^{2}\overbrace{ (\sin ^{2}\omega t+\cos ^{2}\omega t) }^{ 1 }$

$x^{2}+y^{2}=r^{2}$
C)
$|v|=\sqrt{ v^{2}_{x}+v^{2}_{y} }=\sqrt{ r^{2}\omega^{2}(\cos ^{2}\omega t+\sin ^{2}\omega t) }=|r\omega|=r |\omega|$
$|a|=\sqrt{ a^{2}_{x}+a^{2}_{y} }=\sqrt{ \omega^{4}(x^{2}+y^{2}) }=\omega^{2}r$
# task 5.
Motion of a material point is described by the following set of parametric equations:
x = ct, and y = a + bt2, where a, b and c are constans. (A) Find the components of velocity and
acceleration. (B) Determine the vectors of tangent and normal accelerations (with respect to
the trajectory). (C) Find the trajectory using a = 0, b = g/2, c = v0.
$x=ct,y=a+bt^{2}$
$v_{x}=\frac{dx}{dt}=c$
$v_{y}=\frac{dy}{dt}=2bt$
$v=c\mathbb{i}+2bt\mathbb{j}=(c,2bt)$
$|v|=\sqrt{ c^{2}+4b^{2}t^{2} }$
$a_{x}=\frac{dv}{dt}=0$
$a_{y}=\frac{dv}{dt}=2b$
$a=2b\mathbb{j}=(0,2b)$
$|a|=2b$

(b)
$v·a=4b^{2}t$
$a_{\tan}=\frac{v·a}{|V|}=\frac{4b^{2}t}{\sqrt{ c^{2}+4b^{2}t^{2} }}$
$|v\times a|=b$
$a_{norm}=\frac{|v\times a|}{|v|}=\frac{|2bc|}{\sqrt{ c^{2}+4b^{2}t^{2} }}$
(c)
$x=v_{0}t\to t=\frac{x}{v_{0}}$
$y=\frac{g}{2}t^{2}$
$y=\frac{g}{2} \left( \frac{x}{v_{0}} \right)^{2}$
# task 6.
A projectile thrown with an initial velocity v0 at an angle α. Find the equation of
trajectory of this motion y(x). Derive the relationships for the maximum height and range.
Discuss the obtained results as a function of α. Find the final velocity and the tangential and
normal accelerations at the moment when the projectile hits the ground.
$v_{x0}=v_{0}\cos\alpha$
$v_{y0}=v_{0}\sin\alpha$


$\vec{s}=\vec{v}_{0}t+\frac{1}{2}\vec{a}t^{2}$
$s_{x}=v_{x0}·t$
$s_{y}=v_{y0}t+\frac{1}{2}(-g)t^{2}$


$v_{y}=v_{y0}-gt$
$v_{x}=v_{x0}$

maximum height is at half time
$0=v_{0}\sin\alpha-gt_{1/2}$
$t_{1/2}=\frac{v_{0}\sin\alpha}{g}=\frac{v_{y0}}{g}$
$s_{y}=v_{y0} · \frac{v_{y0}}{g}-\frac{1}{2}·g· (\frac{v_{y0}}{g})^{2}$
$h_{max}=\frac{v_{y0}^{2}}{2g}$
$h_{max}(\alpha)=\frac{v_{0}^{2}\sin ^{2}\alpha}{2g}$
range max
$r_{max}=\frac{v_{x_{0}}·2v_{y0}}{g}$
$r_{max}(\alpha)=\frac{(v_{0}\cos\alpha)·2(vo\sin\alpha)}{g}$
$r_{max}(\alpha)=\frac{v_{0}^{2}\sin2\alpha}{g}$

final velocity
$v_{xf}=v_{x_{0}}=v_{0}\cos\alpha$
$v_{yf}=v_{y0}-g·2· \frac{v_{y0}}{g}=-v_{y_{0}}=-v_{0}\sin\alpha$
$v_{f}=\sqrt{ (v_{0}\cos\alpha)^{2}+(-v_{0}\sin\alpha)^{2} }=\sqrt{ v_{0}^{2}\underbrace{ (\cos ^{2}\alpha+\sin ^{2}\alpha) }_{ 1 } }$
$\vec{v}_{f}=\vec{v_{0}}$

$a_{t}=\frac{\vec{v}·\vec{a}}{v}=\frac{(v_{0}\cos\alpha,-v_{0}\sin\alpha)·(0,-g)}{v_{0}}=g\sin\alpha$

$a_{n}=\sqrt{ a^{2}-a_{t}^{2} }$
$a_{n}=\sqrt{ g^{2}-(g\sin\alpha)^{2} }$
$a_{n}=g\cos\alpha$
# task 7.
A stone thrown horizontally from the height h = 2 m fell at a distance s = 7 m from
the starting point. Find the initial (v0) and the final (vk) velocity of this stone. 
$h=\frac{1}{2}gt^{2}$
$t=\sqrt{ \frac{2h}{g} }=\sqrt{ \frac{4}{10} }\approx0.633s$
$s=v_{0}·t$
$7=v_{0}·0.633$
$v_{0}=11m/s$
# task 8.
A train is moving along a horizontal arc track with a radius of curvature R = 400 m.
The tangential acceleration of the train at = 0.2 m/s2. Calculate the normal acceleration (an)
and the total linear acceleration of the train (a) at a moment when its velocity is v = 10 m /s.
$a_{t}=0.2m/s^{2}$
$a_{n}=\frac{v^{2}}{r}=\frac{10^{2}}{400}=0.25m/s^{2}$
$a=\sqrt{ a_{t}^{2}+a_{n}^{2} }=\sqrt{ 0.2^{2}+0.25^{2} }=0.32m/s^{2}$

