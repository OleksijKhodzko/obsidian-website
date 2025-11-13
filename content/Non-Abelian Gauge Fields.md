Let's say we have a generalized [[Lagrangian]] build from the [[Lagrangian]] of a [[Complex scalar field]]:
$$
\mathcal{L}=\partial_{\mu}{\vec{\phi}^{\dagger}}\partial^{\mu}{\vec{\phi}}-m^{2}\vec{\phi}^{\dagger} \vec{\phi}.
\tag{1} 
$$
Let's consider transformation of $SU(N)$ group, which almost excludes the $U(1)$ transformations, except for the [[Center of SU(N)]].[^1] But $Z_N$ is discrete subgroup of $U(1)$, which means that $\chi(x)$ in $\phi'(x)=\exp\left\{iq\chi(x)\right\}\phi(x)$ isn't continuous and formula [[Abelian  Gauge Field#^35d749|(4.7)]] cannot be applied because of the derivative. So, essentially we are excluding the $U(1)$ transforms and are left with Non-Abelian $SU(2)$ group. 

Let's denote the $SU(n)$ transformation 
$$
\vec{\phi}'=\omega(x)\vec{\phi}(x).
\tag{1} 
$$ 
![[SU(N) groups]]
$$
D_{\mu}\phi(x)= \partial_{\mu}{\phi} + i\varepsilon_\mu \hat{A}_{\mu}\phi, (2)
$$
where $\hat{A}_\mu$ are hermitian traceless matrices, which transform under the rules:
# [[Directional derivative#Parallel transport]]
$$
W[y,x,S,A]=P\exp\left\{-\int_{S}dx^{\mu}\hat{A}_{\mu}\right\}
$$

# Lagrangian term for non-Abelian gauge field
$$
\mathcal{L}=-\frac{1}{2g^{2}}\mathrm{Tr}\ (\hat{F}_{\mu \nu}\hat{F}^{\mu \nu})=-\frac{1}{4g^{2}}F^{a}_{\mu \nu}F^{a\mu \nu}
\tag{2} .
$$

#TODO: write the definition of strength $F$

Here we used that $\mathrm{Tr}\ (\hat{T}_a\hat{T}_b)=\frac{1}{2}\delta_{ab}$, where $\hat{T}$-s are generators of [[Lie Groups and Algebras|Lie Algebra]] of the $SU(n)$ group[^2].
[^1]: #question What is $SU(n)$ in relation to $U(n)$ ?
[^2]: #question How exactly we do this calculation?

