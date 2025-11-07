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
\begin{gather}
x \to x'=f(x;\omega),\\
u_a(x)\to u'_{a}(x')=F_a(u_{b}(x);\omega).
\end{gather}
$$
Infinitesimal transformations:
$$
\begin{gather}
x\to x'=x+\omega^{a}\xi_{\alpha}(x)+\dots, \\
u_\alpha(x) \to u'_\alpha (x') = u'_\alpha(x) + \omega^{k}\xi_k \cdot \frac{ \partial u'_\alpha }{ \partial x } \Bigg|_{\omega=0}^{} +\dots\implies u_a(x')+\omega^{k}D_k u_a(x),
\end{gather}
$$
where
$$
\begin{gather}
\xi_\alpha=\frac{ \partial f(x;w) }{ \partial \omega^{\alpha} } \Bigg|_{\omega=0}^{},\\
D_{k}u_\alpha= \frac{ \partial  }{ \partial \omega^{k} } F_a(u_a(x);\omega)\Bigg|_{\omega=0}^{}-\xi^{\mu}_{k}\partial_{\mu}{u'_\alpha}\Bigg|_{\omega=0}^{}
\end{gather}
$$

$\xi_\alpha$ is called ==a Killing vector.== $D_ku_a(x)$ is called a ==Lie derivative== of field $u_a$ at point $x$ in direction $\xi_k$.

$S_\Omega[u]$ - action functional calculated in the time interval $[t', t'']$.
Transformation $(f, F)$ is a symmetry if new action that we get by applying it differs from the initial one only with a boundary term $\int_{\partial_{\Omega }} dS_{\mu}K^{\mu}(u;x;\omega)$.


