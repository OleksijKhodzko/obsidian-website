[[Configuration space]] of [[Complex scalar field]] is space of functions $\phi:\mathbb{R}^{3}\to \mathbb{C}.$ 
[[Trajectories]] are defined by functions $\phi(x)$ which are defined on $(ct, \vec{x})$ spacetime.

The most typical form of Lagrangian is
$$
\mathcal{L}=\partial_{\mu}{\phi}\partial^{\mu}{\phi}^{*}-\frac{1}{2}m^{2}\phi \phi ^{*}-V(\phi \phi ^{*}).
$$
# $U(1)$ symmetry
$$
\begin{gather*}
\phi'(x)=\exp\left\{iq\alpha\right\}\phi(x),\
q\in \mathbb{Z}\setminus \left\{ 0 \right\}  
\end{gather*}
$$
$\alpha$ here is the parametrization.

Lets calculate corresponding conserved current. 
The Lie derivative:
$$
\mathcal{D}\phi(x)=iq\phi(x).
$$
Using [[Noether's theorem#^857747|current density]] formula ($u_{1}=\phi,u_{2}=\phi ^{*}$) we get 
$$
j_{\mu}=iq(\phi ^{*}\partial_{\mu}{\phi}-\phi \partial_{\mu}{\phi ^{*}}).
$$
# Free scalar field 
$$
V\equiv 0
$$
# Goldstone model 
$$
V = U -m^{2}\phi ^{*}\phi,\ m^{2}<0
$$
$$
U(\phi \phi ^{*})=\frac{\lambda}{4!}\left( \phi ^{*}\phi-\frac{12|m^{2}|}{\lambda} \right)^{2}
$$
We get the Lagrangian:
$$
\mathcal{L}=\partial_{\mu}{\phi ^{*}}\partial^{\mu}{\phi}-U(\phi ^{*}\phi)
\tag{3.48}
$$
Vacuum manifold $\mathcal{V}$ (which is called [[Mexican hat potential]]) is 
$$
\phi=a\exp\left\{i\beta\right\},
\tag{3.53}
$$

$$
\phi ^{*}\phi=a^{2}\implies a=\sqrt{ \frac{12|m^{2}|}{\lambda} },
$$
$$
\beta \in \left[0, 2\pi \right) .
$$
Any vacuum states from $\mathcal{V}$ are invariant under $U(1)$, which means [[Spontaneous symmetry breaking and Goldstone bosons|SSB]]. 

Lets introduce new parametrization of $\phi$:
$$
\begin{gather*}
\phi(x)=(a+\chi(x))e^{ i\Theta (x) },\\
\Theta\in \left[0, 2\pi \right).
\end{gather*}
$$
$\chi=0$ and $\Theta=\beta$ corresponds to vacuum manifold $(3.53)$.
By writing  down the definition of [[functional derivative]] we can find out that if we derive equations of motions from a Lagrangian that we would obtain by substitution of any [[non-singular transformation]] in the initial Lagrangian. 
So our new legit [[Lagrangian]] is 
$$
\mathcal{L}(\chi,\Theta)=\partial_{\mu}{\chi}\partial^{\mu}{\chi}+(a+\chi)^{2}\partial_{\mu}{\Theta}\partial^{\mu}{\Theta}-\frac{\lambda}{4!}\chi^{2} (2a+\chi)^{2}
\tag{3.55}
$$
$\Theta$ field is called ==Goldstone field==. [[Euler-Lagrange equation]] for $\Theta$ is
$$
\partial_{\mu}{(a+\chi)^{2}\partial^{\mu}{\Theta(x)}}=0
\tag{3.58}
$$

## Vortexes ([[Real Scalar Field#Planar domain walls]] analog) 
To construct a vortex we take an approach analogous to [[Real Scalar Field#"Topological" way of constructing planar domain walls]]:
1. Our vacuum manifold is circle (in $(\phi, \phi ^{*},U(\phi \phi ^{*}))$ or $(\chi,\Theta,U(\chi,\Theta))$ phase space) $C_{\phi}:\ \phi=a\exp\left\{i\beta\right\}$. 
2. We choose a circle $C$ in 3-d space such that $\phi(t_{0},\theta)=a\exp\left\{i\theta\right\}$ for any $\theta$ for all points on that circle.
3. Without problems, we extend that circle to a cylinder $C\times R_{1}$.
4. Then we try to extend that cylinder to the whole 3-d space by assigning the same values for each point in the beams going from infinity towards $0$.  
5. There is an infinite amount of mathematical proofs with [[homotopies]] and [[winding number]] that  $\phi$ must vanish in the vicinity of $R=0$ for it to be continuous.
6. So we take a step back, leave $\phi$ equal to corresponding "vacuum values" outside of the cylinder and replace it with a continuous distribution inside the cylinder which vanishes at some points inside some tube.
7. The tube can be closed, then we get a 
8. Energy is the bigger the more vanishing points there are inside , so we leave just one.



# Transforms of [[Complex scalar field]] under [[Poincare transforms]] 
$$\phi'(x)=\phi(x).$$



