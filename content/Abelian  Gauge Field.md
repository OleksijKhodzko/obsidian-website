Lets say we have Lagrangian for [[Complex scalar field]]:
$$
\mathcal{L}=\partial_{\mu}{\phi}\partial^{\mu}{\phi ^{*}}-m^{2}\phi \phi ^{*}.
\tag{1} 
$$
It has have a global $U(1)$ symmetry:
$$
\phi'(x)=\exp\left\{iq\alpha \right\}\phi(x).
$$
We introduce a ==local gauge symmetry==:
$$
\phi'(x)=\exp\left\{iq\chi(x)\right\}\phi(x).
$$
$\chi(x)$ is smooth and vanishes on infinity.
The [[Lagrangian]] (1) is not invariant under local symmetry, so we invent a ==covariant derivative==, which transforms in the same way as a field: 
$$
\mathcal{D}_{\mu}'\phi'(x)=\exp\left\{iq\chi(x)\right\}\mathcal{D}_{\mu}\phi(x).
\tag{2} 
$$
We look for the expression in the form:
$$
\mathcal{D}_{\mu}\phi=\partial_{\mu}{\phi}+iqA_{\mu}(x)\phi,
\tag{3} 
$$
where $A_\mu$ is a ==gauge== field.
If we put that in $(2)$, we get:
$$
A_\mu' = A_\mu-\partial_{\mu}{\chi(x)}.
\tag{4.7} 
$$

^35d749

# Parallel transport

![[Directional derivative#Abelian case]]

Using $(3)$ we can find
$$
W[x,x_{0},\Lambda,A]=\exp\left\{-iq\int dx^{\mu}A_{\mu}\right\}.
$$

# [[Lagrangian]] invariant under [[Gauge transform]]
## Way numer uno
To get a [[Lagrangian]] invariant under [[Gauge transform]] we can just replace partial derivatives with covariant in $(1)$:
$$
\mathcal{L}_{1}=\mathcal{D}_{\mu}(A)\phi ^{*}\mathcal{D}^{\mu}(A)\phi-m^{2}\phi ^{*}\phi. 
\tag{4} 
$$
After applying [[Euler-Lagrange equation|Euler-Lagrange equations]], we  can notice that for this model field $A$ is not independent:
$$
A_{\mu}=\frac{i}{2q}\left( \frac{\partial_{\mu}{\phi}}{\phi} -\frac{\partial_{\mu}{\phi ^{*}}}{\phi ^{*}}\right).
$$
Also, the model is not defined if $\phi=0$ for some $x$.

## Way numer duo 
We can also add some additional  term $\mathcal{L}_A$ to $(4)$, but it has to be gauge- and Lorentz-invariant.
### Gauge invariance 
According to [[#^35d749|(4.7)]], $A_{\mu}$ can't be gauge-invariant and the only invariant combination for the partial derivatives is when there is a difference of them $F_{\mu \nu}=\partial_{\mu}{A_\nu}-\partial_{\nu}{A_\nu}$.
### Lorentz invariance 
There are 2 possible Lorentz-invariants:
1. Just a contraction $F^{\mu \nu}F_{\mu \nu}$
2. One that utilities the fact that proper Lorentz group has $\det L=1$: $\epsilon_{\mu \nu\lambda \rho}F_{\mu \nu}F_{\lambda \rho}$.
The second one is lame, not useful.

We can get a [[Klein-Gordon equation]] with a [[Lagrangian]] of form 
$$
\mathcal{L}=\mathcal{D}_{\mu}(A)\phi ^{*}\mathcal{D}^{\mu}(A)\phi-m^{2}\phi ^{*}\phi-\frac{1}{4e^{2}}F^{\mu \nu}F_{\mu \nu}. 
\tag{5} 
$$
