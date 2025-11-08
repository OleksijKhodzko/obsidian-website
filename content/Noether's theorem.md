---
tags:
  - Field_theory
date:
---
# Noether's Theorem
Invariance of a field theoretical model (action) under a continuous group of transformations $G$ implies the existence of integrals of motion which are functionals of fields and their derivatives  which are constant in time provided that the fields obey the equations of motions derived from the principle of least action.

Lets denote elements of $G(\omega)=(f(\omega), F(\omega))$,  $\omega=(\omega^{1},\dots,\omega^{s})=\omega^{\alpha}_{\alpha=1,\dots, s}$, where $\omega$ are continuous real parameters. $f(\omega)$ acts on spacetime points and $F(\omega)$ acts on fields.
$G(0)\equiv I$. All the transforms are smooth.
$$
\begin{gather*}
x \to x'=f(x;\omega),\\
u_a(x)\to u'_{a}(x')=F_a(u_{b}(x);\omega).
\end{gather*}
$$
Infinitesimal transformations:
$$
\begin{gather*}
x\to x'=x+\omega^{a}\xi_{\alpha}(x)+\dots, \\
u_\alpha(x) \to u'_\alpha (x') = u'_\alpha(x) + \omega^{k}\xi_k \cdot \frac{ \partial u'_\alpha (x)}{ \partial x } \Bigg|_{\omega=0}^{} +\dots\implies u_{a}'(x) = \underbrace{ u_a(x) }_{ F(0) }+\omega^{k}D_k u_a(x),
\end{gather*}
$$
where
$$
\begin{gather*}
\xi_\alpha=\frac{ \partial f(x;w) }{ \partial \omega^{\alpha} } \Bigg|_{\omega=0}^{},\\
D_{k}u_\alpha= \frac{ \partial  }{ \partial \omega^{k} } F_a(u_b(x);\omega)\Bigg|_{\omega=0}^{}-\xi^{\mu}_{k}\partial_{\mu}\underbrace{ {u_\alpha(x)} }_{ u'_\alpha (x)\approx u_a'(x') \text{ for } \omega=0}\Bigg|_{\omega=0}^{}
\end{gather*}
$$

^0109e9

$\xi_\alpha$ is called ==a Killing vector.== $D_ku_a(x)$ is called a ==Lie derivative== of field $u_a$ at point $x$ in direction $\xi_k$.

$S_\Omega[u]$ - action functional calculated in the time interval $[t', t'']$.
*Transformation $(f, F)$ is a symmetry if new action that we get by applying it differs from the initial one only with a boundary term $\int_{\partial_{\Omega }} dS_{\mu}K^{\mu}(u;x;\omega)$.*
It can be shown by taking functional derivative of both sides of this equality.

## Noether's identity
The identity is
$$
\int_\Omega d^{4}x \frac{dj^{\mu}_{\alpha}}{dx^{\mu}}=\int_\Omega d^{4}x D_\alpha u_a(x) \frac{\delta S}{\delta u_a}
$$
where density current is defined as
$$
j^{\mu}_{\alpha}=K^{\mu}_{\alpha}(u_a;x)-\mathcal{L}\xi^{\mu}_{\alpha}-\frac{ \partial \mathcal{L} }{ \partial (u_{a,\mu}(x)) }D_\alpha u_a(x), 
$$

^857747

^3ce7c5
where $K^{\mu}_{\alpha}$ is a coefficient in first-order term in expansion of $K^{\mu}$ by $\omega^{\alpha}$.
For $\omega=0$ $K\equiv 0$, so $K^{\mu}=\omega^{\alpha}K^{\mu}_{\alpha} + \dots$.
==The fact of its existence is called Noether's theorem.==
It is derived by expanding l.h.s of $S_{\Omega'}[u']=S_\Omega[u]+\int_{\partial_{\Omega }} dS_{\mu}K^{\mu}(u;x;\omega)$ to the first 2 orders and then putting $\omega=0$.

If the fields are "on-shell", r.h.s of identity vanishes and we get 
$$
Q_\alpha(t)=\int d^{3}xj^{0}_{\alpha}(t,\vec{x})=const.
$$
### Local symmetry
One can also pose local symmetry condition, which is equality between Lagrangians up to a full derivative. Then he will obtain $\nabla_{4} \cdot j_{\alpha}=0$.
