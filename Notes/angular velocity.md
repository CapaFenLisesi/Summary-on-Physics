# Angular velocity

Suppose there are two coordinate frames. The frame 2 is rotating relatively to frame 1. If the coordinates of the particles in frame 2 is
$$r_2=(x_2,y_2,z_2)$$
The coordinates of the particle in frame 1 is
$$r_1 = O(t)r_2$$
and
$$O^TO=I$$
So, we can derive that
$$\Omega + \Omega^T= 0 \quad \Omega = O^T\frac{dO}{dt}$$
Then we have
$$\frac{dr_1}{dt} = \frac{dO}{dt}r_2 + O\frac{dr_2}{dt} = OO^T \frac{dO}{dt}r_2 + Ov_2  = O (\Omega r_2 + v_2)$$
Suppose
$$\Omega = \left[ \begin{matrix} 0& -\omega_{2z}& \omega_{2y}\\ \omega_{2z}& 0& -\omega_{2x}\\ -\omega_{2y}& \omega_{2x}& 0\end{matrix} \right] $$
So, we have
$$v_1 = O(\omega_2 \times r_2 + v_2) $$
Now, we define
$$\omega_1 = O\omega_2$$
We can derive that
$$O \Omega O^T = \left[ \begin{matrix} 0& -\omega_{1z}& \omega_{1y}\\ \omega_{1z}& 0& -\omega_{1x}\\ -\omega_{1y}& \omega_{1x}& 0\end{matrix} \right] $$
So, we have
$$v_1 = \omega_1 \times r_1 + Ov_2$$
$\omega$ is the so-called angular velocity.

**Note**
1. $\omega_1$ is independent of the way we choose frame 2.
2. If we choose frame 1 differently, $\omega_1$ will transform like an vector.