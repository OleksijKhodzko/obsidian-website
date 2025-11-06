---
tags:
  - Field_theory
  - Problem_sets
date: 2025-06-11
---
![[set_3.pdf]]
# 1. Derrick's theorem
$${\mathcal{L}}={\frac{1}{2}}\sum_{j=1}^{N}\partial_{\mu}\phi_{j}\partial^{\mu}\phi_{j}-V(\phi_{j}).$$
Each static solution can be derived from minimizing the energy, because the equations of motion are
$$
\delta \int dtL=0.
$$
And for static solutions
$$
H = \pi_0 \dot{\phi_0}-L=-L.
$$
So we get $\delta H=0$.

$$
H = \underbrace{ \frac{1}{2}\int d^{d}x\partial_{k}{\phi^{0}_{j}}\partial_{k}{\phi_{j}^{0}} }_{ G } + \underbrace{ \int d^{d}xV(\phi^{0}_{j}) }_{ W }
$$
$\phi^{0}_{j}$ here is the static solution. We want to show that for $d>1$ there are no static solutions with finite energy. For that we need to show there are no finite minimums of energy for $d>1$. For that let's generate from $\phi^{0}_{j}$ a family of fields 
$$
\phi'^{0}_{j}(x)=\phi^{0}_{j}(\lambda x).
$$ 
$$
G(\lambda)=G(\phi'^{0}_{j}(x)) = \frac{1}{2}\lambda^{-d} \int d^{d}x\partial_{k}{\phi'^{0}_{j}}\partial_{k}{\phi'^{0}_{j}}=\lambda^{2-d}G(1)
$$
$$
W(\lambda)=\int d^{d}xV(\phi'^{0}_{j})=\lambda^{-d}W(1)
$$
$$
H(\lambda)=G(\lambda)+W(\lambda)=\lambda^{2-d}G+\lambda^{-d}W
$$
For $\phi^{0}_{j}$ to be the solution it should be the minimum of this family (but not only):
$$
\frac{d}{d\lambda}H(\lambda)\Bigg|_{\lambda=1}^{}=0.
$$
$$
(2-d)G-Wd=0 \implies d =\frac{2G}{G+W},
$$
We know that $W>0$ as $V(\phi)>0$; $W>0$ from definition:
$$G\equiv\frac{1}{2}\int d^{d}x\partial_{k}\phi_{j}^{0}\partial_{k}\phi_{j}^{0}.$$
So we have $d < 2$ for non-zero potential.

