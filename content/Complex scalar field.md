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
$$
Vacuum manifold $\mathcal{V}$ (which is called [[Mexican hat potential]]) is $\phi=a\exp\left\{i\beta\right\}$.
$$
\phi ^{*}\phi=a^{2}\implies a=\sqrt{ \frac{12|m^{2}|}{\lambda} },
$$
$$
\beta \in \left[0, 2\pi \right) .
$$
Any vacuum states from $\mathcal{V}$ are invariant under $U(1)$, which means [[Spontaneous symmetry breaking and Goldstone bosons|SSB]]. 

Lets introduce new parametrization of $\phi$:
$$
\phi(x)=(a+\chi(x))e^{ i\Theta (x) }
$$



# Transforms of [[Complex scalar field]] under [[Poincare transforms]] 
$$\phi'(x)=\phi(x).$$


