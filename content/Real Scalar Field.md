[[Configuration space]] of [[Real Scalar Field]] is space of functions $\phi: \mathbb{R}^{3}\to \mathbb{R}$.
[[Trajectories]] are defined in $(ct, \vec{x})$ spacetime.

# Transforms of [[Real Scalar Field]] under [[Poincare transforms]] 
By definition, scalar field is invariant under [[Poincare transforms]] :
$$
\phi'(x')=\phi(x).
$$
Lie derivative:
$$
\mathcal{D}\phi(x)=-\xi^{\rho}\partial_{\rho}{\phi(x)}.
$$
Killing vector is either for translations in Minkovski space or for [[Lorentz transform]].
Lets demand local invariance without external fields and also assume vanishing of the surface term.
$$
\mathcal{L}(\phi(x), \partial_{\mu}{\phi(x)}) =\mathcal{L}(\phi'(x'), \partial'_{\mu}{\phi'(x')}) \tag{3}
$$

^7a0c17

From this equality we see that and invariance of scalar field we see that Lagrangian can have any dependence on $\phi(x)$ but the derivatives must be present only in invariant combinations.

The most popular form of the Lagrangian is:
$$
\mathcal{L}=\frac{1}{2} \eta^{\mu \nu}\partial_{\mu}{\phi(x)}\partial_{\nu}{\phi(x)}-\frac{1}{2}m^{2}\phi(x)^{2}-V(\phi(x)).
$$
The pertinent motion equations are:
$$
\Box\ \phi+m^{2}\phi+V'=0.
$$
# Quadratic potential 
For quadratic potential the equation $(5)$ is a [[Klein-Gordon equation]].

# Cubic potential 
Cubic potential is not of physical interest because the corresponding energy is not bounded from the bottom.
To show that, lets write down the [[Noether's theorem#^857747|current density]] for translation symmetry  (energy corresponds to time translation symmetry):
$$
j^{\mu}_{\alpha}=-\mathcal{L}\delta^{\mu}_{\alpha}-\partial^{\mu}{\phi(x)}\partial_{\alpha}{\phi(x)}. 
$$
#### Energy-momentum tensor 
$$
j_\alpha^{\mu}= T^{\mu}_{\ \ \ \nu}\xi^{\nu}_{\alpha}.
$$
For scalar field $j^{\mu}_{\nu}=T^{\mu}_{\ \ \ \nu}.$

==Now if we calculate the energy-momentum tensor, we get that the energy is arbitrary, consequently not bounded from below.==


# Quartic potential 
Potential:
$$
V(\phi)=\frac{\lambda}{4!}\phi^{4}(x)
$$
Equations of motion:
$$
\partial_{\mu}{\partial^{\mu}{\phi}}+m^{2}\phi+\frac{\lambda}{3!}\phi^{3}=0 \tag{9}
$$

^350772

Energy and momentum:
$$

$$
$$
E = \int d^{3}x j^{0}_{0}, \ P^{i}=-\int d^{3}xj_{i}^{0}.
$$
Minus is here because of the metric used to rise index.
We take $0-th$ space-time coordinate part of current density because it is conserved if we assume that other coordinates vanish on infinity

# Vacuum manifolds and [[Spontaneous symmetry breaking and Goldstone bosons|SSB]]
$$
\begin{align*}
\mathcal{L}=\frac{1}{2} \eta^{\mu \nu}\partial_{\mu}{\phi(x)}\partial_{\nu}{\phi(x)}-\frac{1}{2}m^{2}\phi(x)^{2}-\frac{\lambda}{4!}\phi(x)^{4} = \\
=\frac{1}{2} \eta^{\mu \nu}\partial_{\mu}{\phi(x)}\partial_{\nu}{\phi(x)}-U(\phi(x)) + \frac{3m^{4}}{2\lambda},
\end{align*}
$$
$$
U=\frac{\lambda}{4!}\left( \phi^{2}\pm \frac{6|m^{2}|}{\lambda} \right)^{2}
$$
## $m^{2}>0$
$$
U=\frac{\lambda}{4!}\left( \phi^{2}+ \frac{6|m^{2}|}{\lambda} \right)^{2}
$$
Minimal energy is 0 ($\psi\equiv 0$). Nothing interesting.
## $m^{2}<0$
$$
U=\frac{\lambda}{4!}\left( \phi^{2}- \frac{6|m^{2}|}{\lambda} \right)^{2}
$$
In this case the we have 3 extremums:
```handwritten-ink
{
	"versionAtEmbed": "0.3.4",
	"filepath": "Ink/Writing/2025.11.8 - 13.21pm.writing"
}
```
$$
\phi_{\pm }=\pm \sqrt{ \frac{6|m^{2}|}{\lambda} }, \ \phi_{0}=0
$$
 Vacuum manifold is invariant under $S: \phi\to-\phi$ transformation. But the individual vacuum states are not.

### Small perturbations around the $\psi_{\pm}$ vacua
$$
\phi=\phi_{\pm }+\epsilon(x).
$$
Putting it into [[#^350772|(9)]] we get just a [[Klein-Gordon equation]]:
$$
(\partial_{\mu}{\partial^{\mu}{}}+2|m^{2}|)\epsilon(x)=0.
$$
Which gives $\omega (\vec{k})=c\sqrt{ \vec{k}^{2}-2|m^{2}| }$. It is imaginary for small $\vec{k}$.
If we put imaginary $\omega(\vec{k})$ into [[Klein-Gordon equation#Expansion for homogeneous solution]] we see that  ==$\psi_{+}$ is stable== (the condition here is the opposite to the condition in [[Klein-Gordon equation]] note, as it is derived for equation with positive sign near the mass term, and here we have minus).
### Small perturbations around $\psi_{0}$ vacua
$$
\phi=\epsilon(x).
$$
Putting it into [[#^350772|(9)]] we get another [[Klein-Gordon equation]]:
$$
(\partial_{\mu}{\partial^{\mu}{ }}-|m^{2}|)^{2}\epsilon(x)=0.
$$
$\omega(\vec{k})=c\sqrt{ \vec{k}^{2}+|m^{2}| }$, so $\psi_{0}$ is unstable.


### Planar domain walls 


