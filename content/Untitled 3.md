![[Pasted image 20251104144742.png]]
$$\left\{I,I^{m}\right\}=i\int_{0}^{1}d x\int\frac{d^{d}\vec{k}}{(2\pi)^{d}}\frac{1}{\left(-\vec{k}^{2}-M^{2}\right)^{2}}\left\{1,k^{m}-x p^{m}\right\}\qquad\qquad(10)$$
where 
$$\LaTeX \text{ is being generated... } \vphantom{3}$$

	$$\LaTeX \text{ is being generated... } \vphantom{5}$$
The integration using 
$$\int d\Omega_{d}=\frac{2\pi^{d/2}}{\Gamma(d/2)}.$$
:

After going to polar coordinates:
$$\{I,I^{\mu}\}=\frac{i}{\Gamma(2-\varepsilon)}\frac{2\pi^{2-\varepsilon}}{(2\pi)^{4-2\varepsilon}}\int_{0}^{1}d x\left\{1,-x p^{\mu}\right\}\int_{0}^{\infty}d k\frac{k^{d-1}}{\left(\,k^{2}+M^{2}\right)^{2}}.$$
$$
r = \frac{k}{ M}:
$$
$$
\begin{align}

\{I,I^{\mu}\}=\frac{i}{\Gamma(2-\varepsilon)}\frac{2\pi^{2-\varepsilon}}{(2\pi)^{4-2\varepsilon}}\int_{0}^{1}d x\left\{1,-x p^{\mu}\right\}\int_{0}^{\infty} Mdr\frac{(Mr)^{d-1}}{\left(\,r^{2}+1\right)^{2} M^{4}} = \\
=\frac{i}{\Gamma(2-\varepsilon)}\frac{2\pi^{2-\varepsilon}}{(2\pi)^{4-2\varepsilon}}\int_{0}^{1}d x\left\{1,-x p^{\mu}\right\}\int_{0}^{\infty} Mdr\frac{(Mr)^{d-1}}{\left(\,r^{2}+1\right)^{2} M^{4}} =

\end{align}
$$

with $r^{2} = t$ we get:

$$
\{I, I^{\mu}\}=\frac{i}{\Gamma(2-\varepsilon)}\frac{2\pi^{2-\varepsilon}}{(2\pi)^{4-2\varepsilon}}\int_{0}^{1}d x\left\{1,-x p^{\mu}\right\}\int_{0}^{\infty} Mdr\frac{(Mr)^{d-1}}{\left(\,r^{2}+1\right)^{2} M^{4}} =
$$
$$
\begin{align}
\int ^{\infty}_{0}dx \frac{x^{d-1}}{(1+x^{2})^{2}} = \int ^{\infty}_{0}\frac{dt}{2\sqrt{ t }} \frac{t^{(d-1) / 2}}{(1+t)^{2}} =  \\
= \dots = \Gamma(2-\varepsilon)\Gamma(\varepsilon)
\end{align}

$$


We used that 
$$
\frac{\Gamma(x)\Gamma(y)}{\Gamma(x+y)} = B(x,y) = \int ^{\infty}_{0}dt \frac{t^{x-y}}{(1+t)^{x+y}}
$$
$$
\Big[I, I^{\mu} \Big] = i \frac{2\pi^{d/2}}{\Gamma\left( \frac{d}{2} \right)} \frac{\frac{1}{(2\pi)^{d}}1}{(-p^{2})^{\varepsilon}} [B(1-\varepsilon, 1 -\varepsilon), -p^{\mu}B(2-\varepsilon, 1-\varepsilon)] \frac{1}{2}\Gamma(2-\varepsilon)\Gamma(\varepsilon)
$$

$$
\Big[I, I^{\mu} \Big]=\frac{i}{(-p^{2})^{\varepsilon}} \frac{2}{2} \frac{\pi^{2-\varepsilon}}{\Gamma(2-\varepsilon)} \frac{1}{2^{4-2\varepsilon}} () = \frac{i}{2^{4}\pi^{2}}\left( \frac{4\pi}{-p^{2}} \right)^\varepsilon \times \Big[B(1-\varepsilon, 1-\varepsilon), -p^{\mu} B(2-\varepsilon, 1-\varepsilon) \Big]\Gamma(\varepsilon)
$$
We used $\Gamma(2-\varepsilon)=(4\pi)^{\varepsilon}$.

