---
tags:
date: 2025-03-10
---
![[GR_problem_set_2025_03.pdf]]
# 16. Geodesic equation
First, the distance between 2 points in spacetime:
$$
S = \int _{A}^{B} ds,
$$
$$
ds^{2}= d x_{\mu} d x^{\mu}=g^{\mu \nu} d x_{\nu} d x_{\mu}
$$
$$
S = \int _{A}^{B}\sqrt{ g^{\mu \nu}d x_{\mu}d x_{\nu} }
$$
Now to find the geodesic equation we have to minimize the distance:
$$
\delta S=\delta \int _{A}^{B}\sqrt{ g^{\mu \nu}d x_{\mu}d x_{\nu} } = 0
$$
And we also introduce the parametrization:
$$
x = x(\lambda), \ \dot{x}_{\mu}=\frac{dx_{\mu}}{d\lambda}
$$

$$
ds=\sqrt{ g^{\mu \nu}dx_{\mu}dx_{\nu} } = \sqrt{ g^{\mu\nu}\dot{x}_{\mu}\dot{x}_{\nu}  }d\lambda 
$$
$$
\begin{gather}

\delta\sqrt{ g^{\mu\nu}\dot{x}_{\mu}\dot{x}_{\nu}  } = \frac{1}{2}\frac{1}{\sqrt{ g^{\mu\nu}\dot{x}_{\mu}\dot{x}_{\nu}  }} [\partial_{\sigma}{g^{\mu\nu}}\dot{x}_{\mu}\dot{x}_{\nu}\delta x_\sigma+g^{\mu\nu}(\underbrace{ \dot{x}_{\nu}\delta\dot{x}_{\mu}+\dot{x}_{\mu}\delta\dot{x}_{\nu}}_{ 2g^{\mu\nu}\dot{x}_{\nu}\partial_{\sigma}\dot{x}_{\mu} })] = \dots 
\end{gather}
$$
I mean, ![[geodezyjna.pdf]]



# 17. Properties of Riemann tensor with Levi-Civita connection
$$ 
R^{\rho }{}_{\sigma \mu \nu }=\partial _{\mu }\Gamma ^{\rho }{}_{\nu \sigma }-\partial _{\nu }\Gamma ^{\rho }{}_{\mu \sigma }+\Gamma ^{\rho }{}_{\mu \lambda }\Gamma ^{\lambda }{}_{\nu \sigma }-\Gamma ^{\rho }{}_{\nu \lambda }\Gamma ^{\lambda }{}_{\mu \sigma }
$$
