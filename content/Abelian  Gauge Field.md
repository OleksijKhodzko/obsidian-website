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
$$
where $A_\mu$ is a ==gauge== field.
If we put that in $(2)$, we get:
$$
A_\mu' = A_\mu-\partial_{\mu}{\chi(x)}.
$$
