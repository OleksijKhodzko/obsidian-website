### 1. The Experiment: Deep Inelastic Scattering (DIS)

First, the lecture introduces the main experimental tool, **Deep Inelastic Scattering (DIS)**.

- **What it is:** Firing a high-energy, simple particle (like an electron, with 4-momentum $k$) at a complex target (like a proton, with 4-momentum $p$).
    
- **The "Probe":** The electron scatters by exchanging a "virtual photon" (a packet of force, with 4-momentum $q$). The electron flies off with a new 4-momentum $k'$.
    
- **The Two Outcomes (Page 2-3):**
    
    1. **Elastic Scattering:** The proton absorbs the photon but stays intact. The final state is just an electron and a proton ($e + p \to e + p$).
        
    2. **Inelastic Scattering:** The photon has so much energy it _shatters_ the proton. The proton breaks apart into a spray of new, unmeasured particles, labeled "X" ($e + p \to e + X$).
        
- **Key Variables (Page 3 & 18):**
    
    - $q = k - k'$: The 4-momentum of the virtual photon that probes the proton.
        
    - $Q^2 = -q^2$: A measure of the photon's "virtuality" or "resolving power." A higher $Q^2$ means you are probing the proton with a shorter wavelength, seeing smaller details.
        
    - $\nu = \omega - \omega'$: The amount of energy lost by the electron, which is transferred to the proton to break it apart.
        

### 2. The Formalism: Structure Functions ($W_1, W_2$)

The lecture then explains how physicists describe this process. They measure a "cross-section" ($\sigma$), which is just the probability of the scattering happening.

- **For a Simple, Pointy Particle (Page 4):** If the proton were a simple, elementary particle (an "elementary fermion"), we could calculate the _elastic_ cross-section exactly. The formula is known.
    
- **For a Complex, "Blob-like" Particle (Page 4 & 29):** Because the proton is _not_ simple, we can't calculate the _inelastic_ cross-section. Instead, we write a general formula that contains all the unknown information about the proton's internal "blob" in two functions:
    
    - $W_1(Q^2, \nu)$
        
    - $W_2(Q^2, \nu)$
        
- These are called **"structure functions."** The whole goal of the experiment (at places like SLAC, shown on Page 5) is to measure the cross-section to figure out what these two functions are. They are the "fingerprint" of the proton's internal structure.
    

### 3. The Experimental Clue: Bjorken Scaling

This is the "Aha!" moment from the experiments.

- **The Limit (Page 7):** James Bjorken suggested looking at the "Bjorken limit," where you crank up the energy to infinity ($Q^2 \to \infty$ and $\nu \to \infty$) but keep their ratio fixed.
    
- **The Scaling Variable:** This special ratio is defined as $x = \frac{Q^2}{2M\nu}$ (where $M$ is the proton's mass).
    
- **The Discovery (Page 7 & 30):** The experiments found something amazing. The structure functions (rewritten as $F_1$ and $F_2$) _stopped_ depending on $Q^2$. As you hit the proton harder (higher $Q^2$), its "fingerprint" didn't change!
    
    - $F_1(Q^2, \nu) \to F_1(x)$
        
    - $F_2(Q^2, \nu) \to F_2(x)$
        
- This "scaling" strongly implied that inside the "blob" of the proton, there were tiny, point-like, scale-invariant objects.
    

### 4. The Theory: The Feynman Parton Model

Richard Feynman provided the explanation for Bjorken Scaling.

- **The Idea (Page 8 & 31):** The proton is not a single "blob." It's a "bag" containing several point-like, elementary constituents called **"partons."**
    
- **The Model:** In this model, the "deep inelastic" scattering on the proton is just a simple _elastic_ scattering off one of these partons.
    
- **The Key Connection (Page 8):** The model assumes a parton carries a fraction $\xi$ of the proton's total momentum. The lecture shows that for the math to work (for the parton to be "on-shell" after being hit), this momentum fraction $\xi$ must be:
    
    - $\xi = \frac{Q^2}{2M\nu}$
        
- This is the _exact same formula_ as Bjorken's $x$. This is the central revelation:
    
    - $x = \xi$
        
    - The measurable quantity $x$ is physically interpreted as **the momentum fraction of the parton that was struck by the photon.**
        

### 5. Connecting Theory to Data (The Climax)

Pages 32-35 show how this model _predicts_ the structure functions.

1. The total inelastic cross-section on the proton is the _sum_ (integral) of all the elastic scatterings on its partons.
    
2. You have to weight this sum by the probability of finding a parton $i$ with momentum fraction $x$. This probability is the **Parton Distribution Function (PDF)**, $f_i(x)$.
    
3. By comparing the formula from the Parton Model with the general formula (from Step 2), the lecture _derives_ what the structure functions must be (Page 35):
    
    - $F_2(x) = \nu W_2 = x \sum_i e_i^2 f_i(x)$
        
    - $F_1(x) = MW_1 = \frac{1}{2} \sum_i e_i^2 f_i(x)$
        
    - ($e_i$ is the electric charge of parton $i$).
        

This beautifully explains Bjorken Scaling: the structure functions only depend on $x$ because the parton probabilities $f_i(x)$ only depend on $x$.

### 6. Proof & Identification: Quarks and Gluons

The lecture concludes by testing this model and identifying the partons.

- **The Callan-Gross Relation (Page 36):** The model makes a concrete prediction. If you look at the two formulas for $F_1$ and $F_2$ above, you find a fixed relationship: $F_2(x) = 2xF_1(x)$.
    
    - This specific relation is a smoking gun that the partons have spin-1/2 (i.e., they are fermions, like electrons).
        
    - The plot on Page 36 shows experimental data, where the ratio $2xF_1/F_2$ is indeed very close to 1, **proving the partons are spin-1/2 fermions.**
        
- **Partons = Quarks (Page 37):** We already have a theory of spin-1/2 fermions inside the proton: **quarks**. The lecture identifies the partons as the **up, down, and strange quarks (**$u, d, s$**)**.
    
    - The $F_2$ formula is rewritten using the quark charges (e.g., $e_u = 2/3$, $e_d = -1/3$): $F_2^p(x) = x \left[ \frac{4}{9}(u(x)+\bar{u}(x)) + \frac{1}{9}(d(x)+\bar{d}(x)) + ... \right]$
        
- **The Missing Momentum & Gluons (Page 38):**
    
    - We can use measurements of the proton's charge to create "sum rules." For example, a proton has 2 "valence" up quarks and 1 "valence" down quark. This means $\int (u(x)-\bar{u}(x))dx = 2$ and $\int (d(x)-\bar{d}(x))dx = 1$.
        
    - **The final puzzle:** If you add up all the momentum carried by all the quarks (valence and "sea" quarks), you only get about 50-55% of the proton's total momentum.
        
    - **Conclusion:** The other ~45% of the proton's momentum must be carried by other partons that the photon _cannot see_ (because they have no electric charge). These are the **gluons**.
        

**Appendix: The Math (Pages 9-27)** A large middle section of the lecture (Pages 9-27) is a formal, field-theory derivation of the cross-section formulas. It shows the rigorous math behind the equations used in the main argument. It covers:

- **S-Matrix Theory (Page 9-13):** The formal theory of how to calculate transition probabilities from an initial state $|i\rangle$ to a final state $\langle f|$.
    
- **Cross-Section Definition (Page 14-16):** How to get from a transition probability to a measurable cross-section $\sigma$, including the "flux factor."
    
- **Amplitude Calculation (Page 22-27):** How to calculate the "amplitude" $\mathcal{M}_{fi}$ using Feynman rules. This involves "Feynman traces" and "tensors" (like the leptonic tensor $L^{\mu\nu}$ and the hadronic tensor $W^{\mu\nu}$) to arrive at the final, measurable formulas for the cross-section.