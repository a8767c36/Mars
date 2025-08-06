
so, in this paper we want to discuss how big planets can be at a maximum sothat rockets can still lift off of them with reasonable amounts of fuel.

we'll first do some rough calculations and then some examples.

to simplify things a bit, we assume the planet's interior has a density between 1 g/cm^3 and 10 g/cm^3.

a rocket wants to achieve a circular trajectory very closely above the surface of the planet. so we'll have to calculate the first orbital velocity \(v_1\).

this can be done by comparing to equations, the first one to describe the circular motion and the second one to describe the effects of gravity on the rocket.

First equation:

$$x(t) = r\cdot cos(\omega t)$$

Second equations:

$$\ddot x = g$$

where \(g\) is the local gravity acceleration.

----

The local gravity acceleration \(g\) is connected to \(GM\) and \(r\) via:

$$g = - GM/r^2$$

Differentiating \(x\) and plugging \(g\) in:

$$\ddot x(t) = -r\omega^2\cdot cos(\omega t) = g = -GM/r^2$$

At \(t = 0\), \(cos(\omega t) = 1\) and \(r^2 \omega^2 = GM/r\). Considering that \(r\cdot \omega = v_1\), we get that

$$v_1^2 = GM/r$$

which is the well-known formula for \(v_1\).

----

Since fuel use goes up exponentially with \(\Delta v\), and \(\Delta v \geq v_1 - v_0\), where \(v_0\) is the speed at which the planet's surface rotates, we can assume that \(\Delta v/v_e\) shouldn't exceed around \(6.9\) or so, where \(v_e\) is the effective exhaust velocity. At this point, \(m_0/m_1\), which is the ratio of liftoff mass to dry mass, exceeds around \(1000\), which is deemed unacceptable. Assuming an effective exhaust velocity of 3 km/s, that makes for a maximum \(\Delta v\) of around 20 km/s. Assuming \(v_0 << v_1\), i.e. the planet's rotation is small compared to the first orbital velocity, we can assume that \(\Delta v \approx v_1 =\) 20 km/s.

Now, to calculate what a maximum mass a planet may have such that a rocket is still able to lift off from it, we have to calculate at which total mass (or rather, gravitational parameter \(GM\)) the orbital velocity \(v_1\) reaches 20 km/s.

We do this once for a denser planet as the first extreme and a less-dense planet as the other extreme.

Assuming a maximum density of \(\rho_{max}\) = 10 g/cm^3, we get \(v_1^2 = GM/r = G\rho_{max}V/r = G\rho_{max}\cdot 4/3\pi r^3/r = G\rho_{max}\cdot 4/3\pi r^2\) and thus

* \(M\) = 10^26 kg at \(\rho_{max}\) = 10 g/cm^3

And assuming a minimum density of \(\rho_{min}\) = 1 g/cm^3, as is the case when the planet is made entirely of ice, then we get

* \(M\) = 3*10^26 kg at \(\rho_{min}\) = 1 g/cm^3










