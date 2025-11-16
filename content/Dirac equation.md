Dirac equation governs evolution of the wave function of a relativistic 1/2-spin quantum particle.  
*The role of wave function in [[Dirac equation]] plays $\psi$, which is a [[Dirac bispinor]]*.
$$
i\gamma^{\mu}\partial_{\mu}{\psi}-m\psi=0
$$
# Dirac gamma matrices
$$

$$
$$
\Big\{\gamma ^{\mu}, \gamma^{\nu} \Big\}=2\eta^{\mu \nu}I_{4},
$$
where $\eta^{\mu \nu}$ is Minkovski metric.

$$
\gamma^{0}=\gamma_{0}=\begin{pmatrix}
1 & 0 \\
0 & -1
\end{pmatrix}
$$
$$
\gamma^{i}=-\gamma _{i}=\begin{pmatrix}
0 & \sigma^{i} \\
-\sigma^{i} & 0
\end{pmatrix}
$$
$$
\sigma_{\mu \nu}\equiv \frac{i}{2}\Big[\gamma_{\mu}, \gamma_{\nu} \Big]
$$
$$
\gamma_{5}=i\gamma^{0}\gamma^{1}\gamma^{2}\gamma^{3}\gamma^{4}
$$
$$
\gamma_{5}^{2}=1
$$
![[Pasted image 20251113194016.png]]

*When we say $\gamma_{\mu}$* transforms like a 4-vector, we mean like a operator 4-vector.
# Scalar product
We define $\psi$ to be Lorentz-invariant. But if we calculate the transformation of $\psi^{\dagger}$, we will find out that it is not Lorentz-invariant (because $\sigma_{\mu \nu}$ is not). So we invent **Dirac adjoint** $\bar{\psi}=\psi ^{\dagger}\gamma_{0}$, which is.
The scalar product then is 
$$
\braket{ \psi_{1} | \psi_{2} } =    \int d^{4}3\ \psi \bar{\psi}
$$