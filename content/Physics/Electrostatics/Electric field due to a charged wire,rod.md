## At General Point 
![](https://i.imgur.com/dPDu0Rz.jpg)

The electric field _dE_ due to the elemental charge _dq_ at point _P_ can be given as:
$$dE=\frac{Kdq}{(x^{2}+r^{2})}$$

Resolve the electric field _dE_ in rectangular components.

![](https://i.imgur.com/kB3as3f.jpg)

The electric field strength in x-direction will be given by integrating the component _dE sin$\theta$_ as.
$$E_x=\int{dE_x}=\int{dE \sin{\theta}}$$
$$\Rightarrow E_{x}=\int{\frac{kdq}{(r^{2}+x^{2})}\times \frac{x}{\sqrt{r^2+x^2}}}$$
$$\Rightarrow E_x=\int{\frac{k \lambda x dx}{(r^{2}+x^{2})^\frac{3}{2}}}$$
For [[Integration]] we use substitution,
$x=r \tan{\theta}$
and, $dx=r \sec^2{\theta} d \theta$
After substitution in above integrand, we get 
$$dE_{x}=\int{\frac{kQ}{L}\frac{r \tan{\theta}\cdot r \sec^{2}{\theta}d{\theta}}{r^{3}\sec^{2}{\theta}}}$$
$$\Rightarrow dE_x=\int{\frac{kQ}{Lr}\sin{\theta}d \theta}$$

Putting the limits:
$$E_{x}=\frac{kQ}{Lr}\int_{-\theta_{2}}^{+\theta_{1}}\sin{\theta}d \theta$$
$$\Rightarrow E_{x}=\frac{kQ}{Lr}[-\cos{\theta}]_{-\theta_{2}}^{+\theta_{1}}$$
$$\Rightarrow \boxed{E_{x}=\frac{kQ}{Lr}[\cos{\theta_2}-\cos{\theta_1}]}$$

Similarly, electric field strength at point _P_ due to _dq_ in y-direction is given as:

$$E_{y}=\int{dE_y}=\int{dE \cos{\theta}}$$
$$\Rightarrow E_{y}=\int{kQ\,\frac{dx}{L(r^{2}+x^{2})}\times \cos{\theta}}$$

Again, for integration we use substitution,
$x=r \tan{\theta}$
and, $dx=r \sec^{2}{\theta}d \theta$


