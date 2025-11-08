---
title:
draft: false
tags:
  - Group_theory
---
# Physics definition
Lie Group is a group elements of which are characterized by continuous parameters.

# Math definition
In [mathematics](https://en.wikipedia.org/wiki/Mathematics "Mathematics"), a **Lie group** is a [[Group|group]] that is also a [differentiable manifold](https://en.wikipedia.org/wiki/Differentiable_manifold "Differentiable manifold"), such that group multiplication and taking inverses are both differentiable.

# Generators
For Lie groups with unitary representations:
$$
a(\theta) = \exp \{i\theta\cdot \mathbf{X}\}
$$
with generators
$$
X_{k}=-i \frac{ \partial a }{ \partial \theta_{k} } \Bigg|_{\theta=0}.
$$
## Lie Algebras
Definition of Lie [[Алгебра|algebra]]:
$$
\left[ X_{j},X_{k} \right] =iC^{l}_{jk}X_{l},
$$
where $C^{l}_{jk}$ is called a structure constants.

Generator of Lie groups in unitary representations form a Lie algebra, which can be shown equating the Taylor series for commutator of Lie group elements and expansion for small $\xi$:
$$
a(\xi) = a(\phi) a(\theta)a^{-1}(\phi)a^{-1}(\theta)
$$
$$
\exp\left\{i\xi \mathbf{X}\right\} = 1 + i\xi_{l}X_{l} + \dots=1+\theta_{j}\phi_{k} \Big[X_{j}, X_{k} \Big]+\dots
$$
Expanding $\xi$ with $\phi$ and $\theta$ and using boundary conditions
$$
\xi_{i} = g_{i}(\theta, \phi), \ g(0, \phi) = g(\theta, \phi) = 0,
$$
which we get from definition of commutator, we get
$$
\xi_{l} = C^{l}_{jk} \theta_{j}\phi_{k}+\dots\ .
$$
$$
1+\theta_{j}\phi_{k} \Big[X_{j}, X_{k} \Big]+\dots = 1 + i\xi_{l}X_{l} + \dots
\implies \left[ X_{j},X_{k} \right] =iC^{l}_{jk}X_{l},
$$
### Adjoin representation
Matrices $X_{j}$ can have any number of dimensions.
Adjoin $(T_{j})^{m}_{k} = -i C^{m}_{jk}$ representation has the exact number of dimensions as the minimal amount of real parameters needed to define a transformation (algebra element).

