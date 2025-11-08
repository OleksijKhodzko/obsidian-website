$$
\Box\ \phi-m^{2}\phi=\eta(t,x)
$$
We can make a [[Fourier transform]] of that equation:
$$
\begin{gather*}
\tilde{\phi}(k)=\int d^{4}x\ e^{ ikx }\phi(x),\\
\phi(x)=\frac{1}{(2\pi)^{4}}\int d^{4}k\ e^{ -ikx }\tilde{\phi}(k).
\end{gather*}
$$
And we get 
$$
(k_{\mu}k^{\mu}-m^{2})\tilde{\phi}=\tilde{\eta}
$$

^9a8e2e

# Homogeneous [[Klein-Gordon equation]] 
$$
(k_{\mu}k^{\mu}-m^{2})\tilde{\phi}=0.
$$
The solution to such equation is 
$$
\tilde{\phi}_0(k)=C(k_{0},\vec{k})\delta(k^{2}-m^{2}).
$$
Backwards transform gives
$$
\phi_{0}(x)=\frac{1}{(2\pi)^{4}}\int d^{4}k\ e^{ -ikx }C(k_{0}, \vec{k})\delta(k^{2}-m^{2}).
$$
We can do shenanigans with it:
$$
\delta(a^{2}-b^{2})=\frac{1}{2}(\delta (a-b)+\delta(a+b))
$$
##### Expansion for homogeneous solution 
$$
\phi_{0}(x)=\int \frac{d^{3}k}{\sqrt{ 2(2\pi)^{3} \omega(\vec{k})}}\ (a_{+}(\vec{k})e^{ -ikx }+a_{-}(\vec{k})e^{ ikx })\Bigg|_{k_{0}=\frac{w(\vec{k})}{c}}^{} 
$$
Analysis: for real $k_{0}$ we get oscillating behavior. For imaginary $k_{0}$ we get exponential growth of values of the field in time. 

# Inhomogeneous [[Klein-Gordon equation]]  
The solution to [[#^9a8e2e|inhomogeneous equation]] is 
$$
\tilde{\phi}(k)=\text{"} \frac{\tilde{\eta}}{k^{2}-m^{2}}\text{"}+\tilde{\phi}_0(k).
$$
To find $\tilde{\phi}_g=\text{"} \frac{\tilde{\eta}}{k^{2}-m^{2}}\text{"}$ we use [[Green's function]]: 
$$
(k^{2}-m^{2})\tilde{G}(k)=1
$$
$$
\implies\underbrace{ (k^{2}-m^{2})\tilde{G}(k) }_{ 1 }\tilde{\phi}=\tilde{G}\tilde{\eta}.
$$
