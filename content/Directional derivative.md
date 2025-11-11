---
tags:
  - differentail_geometry
  - GR
  - guage_theory
date: 2025-11-11
---
Directional derivative of a field $\phi$ in direction of unit vector $\vec{u}$ in point $x$ is defined as 
$$
D_{u}\phi(x)=\lim_{ \epsilon \to 0 } \frac{\phi(x+\epsilon \vec{u})-\phi(x)}{\epsilon}.
\tag{1} 
$$
It can be computed as scalar product of gradient of $\phi$ and unit vector $\vec{u}$:
$$
D_u\phi(x)=\nabla \phi \cdot \vec{u}
\tag{2} 
$$
# In GR or just general differential geometry 
Definition $(1)$ doesn't work anymore, because $\phi(x+\epsilon \vec{u})$ and $\phi (x)$ are in different [[tangent space|tangent spaces]], so we use analog of eq. $(2)$ as definition:
$$
\nabla _{X}Y=X^{\mu}\nabla_{\mu} Y,
$$
where $X$ is a vector field, $Y$ is a tensor field or a tensor.

# Parallel transport 
*Parallel transport of ==tensor== $Y(x_{0})$ defined in a [[tangent space]] at some point in space $x_{0}$ over some curve $\Lambda$*  ==is defined as a tensor field== $Y(x)$ such that it's directional derivative over [[tangent vector]] of $\Lambda$ stays 0.
$$
\nabla_{u_{\lambda}} Y(x)\equiv 0\implies u_\lambda^{\mu}\nabla_{\mu} Y(x)=0.
$$
$$
\frac{d\Lambda^{\mu}}{d\lambda}\nabla_{\mu} Y(x)\equiv 0.
$$
## Non-Abelian case 
In GR, for example, the connection of space-time is [[Levi-Civita connection]], components of which are [[Christoffel symbols]]. 