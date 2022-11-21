# Physics Paper Planning

### Notes

#### Pop-style articles that may be helpful:

1. 2015 short article : "Are scientists finally on the brink of understanding where proton spin comes from?" - phys.org
   1. https://phys.org/news/2015-06-scientists-brink-proton.html
2. Jaffe - "Where does the proton's spin really come from"
   1. https://web.archive.org/web/20160416035309/http://inpp.ohiou.edu/nuclear_lunch/archive/2007/jaffe-1995.pdf
   2. **This seems to be actually quite readable and helpful, explains the bjorken sum real, parton distributions**
3. Look at all of references here:
   1. https://en.wikipedia.org/wiki/Proton_spin_crisis

#### Jaffe "Where does the Proton really get its spin"

***Introduction***

<u>Proton spin doesn't come from quarks?</u>

1. European Muon Collaboration (EMC) Announcement started the crisis
   1. ~*page 24 left column*~ 
   2. said that little or none of the proton's spin can be attributed to the spins of its valence quarks
   3. More experiments (EMC, CERN, Stanford) show that 24-30% of spin comes from valence quarks
   4. Corollary - sea quarks is strongly polarized in the direction opposite to the nucleon's net spin
      1. also, many polarized strange quarks

<u>Confirmation of QCD</u>

1. Validates the Bjorken sum rule
2. given urgency to understand the nucleon structure

<u>Beginnings of QCD and proton structure</u>

1. 1970 -experiments began to probe nucleon's spin structure
2. ~*Page 24 right column*~ - 
3. took until 1987 for first results of EMC data, then to 1995 for CERN to arrive at a consensus

***Tribulations of quantum chromodynamics***

<u>Nucleon/QCD Basics</u>

1. Nucleon is a highly relativistic bound state of quarks and gluons
   1. The quarks (and gluons) cannot (even in principle) be separated into individual components
2. QCD is nonlinear - gluons attract each other through strong force
   1. at long distances the force is too strong to remove a quark or gluon from a nucleon
   2. Hence, its hard to match the theory with observable consequences
3. Despite these difficulties, the QCD lagrangian is very simple
   1. Quark masses must be put in by hand, but otherwise the lagrangian is completely determined by a natural generalization of electormagnetic invariance to a set of noncommuting "charges", the three colors introduced to evade pauli exclusion principle
4. *~Page 25 left column~*
5.  If the nucleon were a non-relativistic bound system, the spin of the ground state, in which all orbital angular momenta are zero, would be merely the spin of its constituents added up according to addition rules
   1. This is why it is easier to add systems with heavy quarks (charm, bottom, and top) as they are massive and not relativistic
   2. Since the nucleon has a relatively large total mass compared to the quark mass, the answer is unclear
   3. Orbital angular momentum, polarized q-qbar pairs and spin-1 gluons can contribute to the total angular momentum of ground state

<u>Probing Nucleon</u>

1. *~Page 25 right column~*
2. hadronic phenomena is accessible but hadron-hadron interactions do not inform nucleon structure
   1. It is difficult to draw conclusions from hadron hadron scattering experiments as you are scattering a complex system off of another complex system and you only measure complex systems in your experiment
3. ~*Page 26 left column*~
4. We do know the electric charges and magnetic moments of the proton and neutron, as well as their charge radius and the vector and axial "weak charges" as measured in beta decay
   1. However, this isn't super useful anyways as relativistic systems behave differently from non-relativistic counterparts
5. Recent (for the time, 1990s) QCD at large Q^2 has provided a new set of probes
   1. SOmewhat like probing electrons in atomic shells - a problem in nonperturbative QED - by using inelastic electron scattering in the perturbative born approximation

***Bjorken's Sum Rule***

1. Bjorken (1966) theorized that the current operators mediating the weak and electromagnetic interactions may obey the same commutation relations as free-field operators (endnote 3) - no idea what this means

2. Sum rule for inelastic scattering of polarized electrons (or muons) off polarized protons and neutrons

   1. Deep inelastic at high $Q^2$

3. Structure function $g_1$ 

   1. proportional to polarization asymmetry
   2. defined as **cross section measured with the spins** of the incident lepton and target nucleon **parallel** (to each other and beam direction) **minus** cross section with **antiparallel** spins

4. The proton composition is summarized in four structure functions

5. Relativistic invariance tells us they can be written as functions of $Q^2$ and $\nu$

   1. $Q^2$ is momentum transfer, $\nu$ is energy lost by lepton in target rest frame

6. ~*Page 26 Left Column*~

7. Bjorken sum rule:
   $$
   \int_0^{\infin} \frac{Q^2}{M \nu^2}d\nu \Bigl( g_1^p(Q^2,\nu) - g_1^n(Q^2,\nu)\Bigl ) = \frac{g_A}{3}
   $$
   

   1. $g_1^p$ and $g_1^n$ are the proton and neutron structure functions respectively

   2. $g_A$ is the weak axial charge constant measured in beta decay

   3. When created, most striking feature was the fact that the right side was independent of $Q^2$

      1. Physicists believed that the nucleon was a soft object and couldn't absorb significant momentum transfer

      2. if this assumption were true, then we would also expect that the structure functions $g_1$ would fall off at high $Q^2$ - but what we actually see is that the integral over $\nu$ results in a independence of $Q^2$

      3. SLAC experiments confirmed the bjorken sum rule, and we saw large cross sections at large $Q^2$

      4. At large $Q^2$, the structure functions appeared to depend only on the ratio that became Bjorken's scaling variable
         $$
         x = \frac{Q^2}{2M\nu}
         $$
         

         1. This variable can be seen as the integral of at the front of the sum rule, and hence the structure functions depend on it??? (confused)

   4. Because of this scaling phenomena, Bjorken and others recognized that the behavior reflected free-field dynamics at short distances inside the nucleon

      1. This supported the idea that the nucleon was composed of confined, weakly interacting pointlike quarks

***Parton Distributions***

<u>Quark Gluon Model</u>

1. In this model, $x_{Bj}$ is the fracation of the target proton's momentum (viewed in a frame with high target momentum) attributed to the quark about to be struck by the electron.
   1. this makes the structure functions probability distributions in x for the quarks inside the nucleon 
2. The structure functions are important for describing DIS interactions
   1. The functions themselves are sums of the probability distributions labeled by the flavor and spin of the constituent quarks
   2. Isotopic symmetry relates the quark distributions in the neutron and proton
      1. This says that up quark distribution in the proton must be equal to the distribution of down quarks in the neutron

~*Page 27 Left Column*~

3. Spin dependent proton structure function is written as:
   $$
   g_1^p(x) = \frac{4}{9}\Delta u (x) + \frac{4}{9}\Delta \bar u (x) + \frac{1}{9}\Delta d (x) + \frac{1}{9}\Delta \bar d (x) + \frac{1}{9}\Delta s (x) + \frac{1}{9}\Delta \bar s (x)
   $$

   3. Here, $\Delta u (x)$ is shorthand for the difference between up x distributions for quarks with spins parallel and anti-parallel to the spin of the proton
   4. Each quark's contributing term is proportional to it's electric charge as this is QED scattering with an electron
   5. only x dependence is shown, but at high $Q^2$ we see QCD radiative effects and hence $Q^2$ dependence

4. We can integrate the structure function as well as the right hand side and combine quarks of the same flavor:

$$
\int _0 ^1 g^p _1 (x)dx = \frac{1}{2}\Bigl( \frac{4}{9} \Delta u + \frac{1}{9} \Delta d + \frac{1}{9} \Delta s \Bigl)
$$

5. $\Delta u$ represents the fraction of the protons spin carried by the up and anti-up quarks, and similar things for down and strange quarks

6. Theorists can solve the right hand side of the equation by looking at beta decay data (look at footnote 5: https://reader.elsevier.com/reader/sd/pii/0550321372903185?token=7BEFBE1982BD0999A29EF8F95A6E613130212520D8E12905F3260D19846F10CE29D7F06EB1C6B8BE1D88C2EFCA997EB8&originRegion=us-east-1&originCreation=20221110034508)

7. Flavor symmetry of strong interactions shows that Matrix elements F and D are related to differences in $\Delta u - \Delta s$ and $ \Delta u - \Delta d$ .

   1. This does not tell us the total fraction of spin carried by all the light quarks (u s and d) which would be the sum $\Delta u + \Delta d + \Delta s$

   2. However, we can rewrite the integral:

   3. $$
      18 \int _0 ^1 g_1 ^p (x)dx = 3F + D + 2\Sigma \space \space \space (eq 4)
      $$

~*Page 27 right column*~

<u>More complex nucleon models  (beyond 3 valence quarks)</u>

1. The typical, simple proton model has 2 up quarks and 1 down quark

2. Jaffe and John Ellis in 1973 suggested that there may be unpolarized strange quarks in the nucleon (endnote 6)

   1. More sophisticated models of the nucleon argue that relativistic effects generate a sea of virtual quark-anti-quark pairs

   2. Jaffe and Ellis conjectured that those virtual pairs may not be spin correlated with the proton as  a whole (total spin)

   3. Since the strange quark is very massive, they reasoned that the strange-antistrange pairs would make up much less of the sea as compared to up and down pairs

   4. This leads to the approximation where the sea component is 0 in equation 4

   5. Using current (for the paper) values for F and D, and QCD radiative corrections, the Ellis-Jaffe sum rule:

      1. $$
         \int _0 ^\infin g_1 ^p (x,Q^2)dx = 0.176 \pm 0.006   \space \space \space (eq        \space 5)
         $$

         1. This is for $Q^2$ around 10GeV^2

      2. QCD corrections have advanced, and there are a number of corrections for different kinematics

   6. 

1. Lalit Sehgal pointed out in 1974 that equation 4 could be rewritten to solve for the sum, and that the sum appeared to be about 0.6 - this suggests that a significant portion of the proton spin does not come from the quarks

***An Experimental Science***

Endnote 2 is the paper of the first published results fo DIS

1. SLAC carried out the first experiment

   1. Early polarized proton data was a crude test of bjorken scaling, but there wasn't enough precision nor power (x range) to test the sum rules

   2. by late 1970s Hughes had started a more powerful experiment and provided the first evaluation of the proton sum rule integral

      1. They measured:

      2. $$
         \int _0 ^1 g^p _1 (x)dx = 0.17 \pm 0.05
         $$

      3. This is in good agreement with the theory assuming the strange contribution is approximately 0.
      
      4. However, the electron beam at SLAC was pretty low energy and hence had pretty low $Q^2$. The physicists could not draw much conclusion about the phase space close to x = 0 as $Q^2$ was nowhere near asymptotic there.

2. The super Proton Synchrotron at CERN produced the next results

   1. There the EMC ran muon DIS off of unpolarized targets in an effort to measure $g_1^p$

   2. They utilized pion decay to harness high energy muons up to 100 GeV and polarization of 80%

      1. This higher energy reached into higher $Q^2$ regimes and lower x than SLAC could have achieved. 

   3. This experiment produced the first EMC results in 1987 using SLAC and CERN data

   4. $$
      \int _0 ^1 g^p _1 (x)dx = 0.126 \pm 0.018
      $$

   5. This corresponds to a sigma value of $\Sigma  = 0.120 \pm 0.16$

   6. This sigma value suggested that none of the proton's spin comes from the spin of the constituent quarks

   7. Furthermore, the data showed that $\Delta s$ was nonzero, and actually made up a significant contribution to the proton spin (strange quark-anti quark pairs)

      1. $\Delta s = -0.190 \pm 0.056$


~*Page 28 Right column*~

1. The spin muon collaboration succeeded the EMC and set out to measure the neutron structure function
2. SLAC also continued studies

***Father and son***

1. Emlyn Hughes worked as the spokesperson for the SLAC experiment while Vernon spoke for the SMC, allowing them a friendly competition

2. The two groups announced their first data on the neutron structure function and spin sum rule early in 1993 at the same time

   1. Theoretical value:

      1. $$
         \int _0 ^1 g^n _1 (x)dx = -0.002 \pm 0.005
         $$

         

   2. The SMC reported :

      1. $$
         \int _0 ^1 g^n _1 (x)dx = -0.08 \pm 0.04
         $$

   3. SLAC reported:

      1. $$
         \int _0 ^1 g^n _1 (x)dx = -0.022 \pm 0.011
         $$

      2. SLAC reported higher precision due to helium target - see physics today june, page 17

3. These results allowed physicists to test the accuracy of bjorken's sum rule, and it held up pretty well. The Ellis-Jaffe sum rule, however, seemed to fail by 2 standard deviations

***Responses to the crisis***

~*Page 29, left column*~

1. There are many theories for why the discrepency between quark spin and hadron spin exists:
   1. SU(3) flavor-symmetry violation may have made the estimate of the $\Delta u - \Delta s$ inaccurate
   2. Unexpected phenomena at low x may have been overlooked





**<u>*Need to Research after:*</u>**

1. Relativistic nucleon
   1. How does the fact that the nucleon is relativistic complicate the proton spin puzzle?
      1. Quarks are very light, so they can have high velocity at low momentum compared to a charm or bottom quark
2. "connection between electron scattering form factors and the fourier transforms of charge and magnetization densities, well known from atomic and nuclear physics, fails for intrinsically relativistic systems like the proton"
3. nonlinear systems - why does this make QCD difficult to work with
4. Perturbative born approximation and Inelastic scattering

**<u>Questions:</u>**

1. Structure functions:
   1. What exactly are they? do they just describe the distribution of quarks in proton?
2. Spin:



#### The Spin Structure of the Nucleon

**Introduction**

*Page 2*

1. Activity inspired by EMC data
   1. quark intrinsic spin makes up small portion of proton spin
2. Transverse spin asymmetries up to 40%
   1. Suggests spin orbit coupling in nucleon associated with transverse momentum
3. Transverse momentum studies have spawned new programs to map 3d structure of proton
4. Development of quark models
   1. eightfold way picture of Gell-Mann
      1. no inclusion of quark motion, quark spin contributes 100% of protons spin
   2. Relativistic quark models without gluonic or pion cloud degrees of freedom
      1. Predicts 60% of proton spin comes from quarks, and 40% is quark orbital angular momentum
   3. Today: data and theory point to proton spin puzzle being a valence quark effect
      1. valence quark contributions
      2. polarized glue contributes a significant portion of proton's spin (up to 50%)
         1. sea quark and QCD gluon corrections are small and within expectations of quark model
5. Organization of paper:
   1. Part 1: sections II-III
      1. Brief introduciton to nucleon spin physics and experiments that have been performed
   2. Part 2: Section IV
      1. Discussion of proton spin puzzle and small value of $g_A^{(0)}$ extracted from polarized DIS.
   3. Section V
      1. Overview of present global program aimed at disentangling the spin-flavor structure of proton
   4. Section VI
      1. Theoretical interp of longitudinal spin data and understanding the proton spin puzzle
   5. Section VII
      1. Transverse structure of the nucleon and manifestations of orbital angular momentum
      2. Introduces generalized parton distributions and TMDs, which describe spin-momentum correlations and spin-orbit couplings in the nucleon
         1. TMDs are manifest in high energy single-spin and azimuthal asymmetries
   6. Sections VIII-IX
      1. Summary of key issues and challenges for next generation of experiments

**II Spin structure functions and parton distributions** 

*Page 3*

1. DIS and polarized DIS experiments have informed the high energy spin structure of nucleon
   1. pDIS involve scattering a longitudinally polarized high energy lepton beam from a longitudinally or transversly polairzed nucleon at high $Q^2$
   2. pDIS has only been fixed target so far, but the EIC will have colliding pDIS
   3. Inclusive DIS - only the scattered lepton is observed in the final state
   4. Semi-Inclusive DIS - SIDIS - at least on hadron is tagged
   5. Experiments performed at SLAC, JLAB, DESY and CERN
   
2. info on the proton's spin structure has in the past come from measuring $g_1$ and $g_2$ in DIS, and recently in SIDIS

3. pDIS experiments tell us about helicity distributions of quarks and gluons
   1. helicity: at leading order this is thought of as the probability of finding a parton with longitudinal polarization parallel or antiparallel to that of the nucleon
   
4. In photon nucleon scattering, the structure functions are defined through the imaginary part of the forward compton scattering amplitude
   1. the structure function contains all the target-dependent info in the DIS process
   
   2. Differential cross sections for longitudinal polarized target
   
      1. Polarized differential cross section:
   
      2. $$
         \frac{d^2\sigma \uparrow \downarrow}{dxdy} + \frac{d^2\sigma \uparrow \uparrow}{dxdy} = \\
         \frac{2 \pi \alpha ^2}{M E x^2 y^2}\left[\left(1 - y - \frac{M x y}{2 E}\right)F_2(x,Q^2) + xy^2F_1(x,Q^2) \right]
         $$
   
      3. and
   
      4. $$
         \frac{d^2\sigma \uparrow \downarrow}{dxdy} + \frac{d^2\sigma \uparrow \uparrow}{dxdy} = \\
         \frac{4 \alpha ^2}{M E x^2 y^2}\left[\left(2 - y - \frac{M x y}{ E}\right)g_1(x,Q^2) + \frac{2 M x}{E}g_2(x,Q^2) \right]
         $$
   
         
   
      5. The first arrow represents the longitudinal polarization of the lepton beam, second arrow represents the spin.
   
      6. These cross sections are derived in many textbooks, for example Roberts 1990
   
   3. Asymmetries:
   
      1. $$
         A_1 = \frac{\sigma_{\frac{1}{2}} - \sigma_{\frac{3}{2}}}{\sigma_{\frac{1}{2}} + \sigma_{\frac{3}{2}}} = \frac{g_1 - \frac{Q^2}{\nu^2} g_2}{F_1}\rightarrow \frac{g_1}{F_1}
         $$
   
      2. Here, $\sigma _{\frac{3}{2}}$ and $\sigma _{\frac{1}{2}}$ are the cross sections for the absorption of a transversly polarized photo with spin polarized parallel and antiparallel to the spin of the longitudinally polarized nucleon
   
      3. For longitudinally polarized targets, the  approximation to $\frac{g_1}{F_1}$ is made as the $g_2$ contribution to the cross section and asymmetry is suppressed by the factor $\frac{M}{E} << 1$
   
      4. For transverse polarized targets this suppression factor for $g_2$ is missing, which implies that transverse polarization is vital to measure $g_2$
   
         1. **I think this means that the suppression makes it difficult to measure $g_2$, but using transverse polarization we can measure**
   
      5. Referencese Roberts 1990 and Windmolders 2002 are given for procedure on extracting the structure functions from the asymmetries
   
         1. Windmolders 2002 - https://arxiv.org/pdf/hep-ph/0211350.pdf

**Section 3: Experiments**

<u>*From this section see what we can learn from each experiment rather than just give summaries - try to bring together a story*</u>

1. SLAC experiments
   1. Polarized DIS measurements, set many standards in polarized beam and target tech
   2. There were 6 experiments performed utilizing polarized electrons from laser photoemission:
      1. E80, E130, E142, E143, E154, E155
   3. Here physicists figured out that cycling the beam and/or target polarization reduced systematic uncertainties in the measured spin asymmetries related to the stability of experimental setup (6)
   4. Used solid state butanol and ammonia for the proton and D-butonol, ND_3 and LiD for the deutron.
   5. polarized the targets using dynamic nuclear polarization
      1. Requires temps of 1K and strong magnetic fields.
      2. Since the targets contains a considerable amount of  non-polarized nucleons, a dillution factor was introduced
   6. Information on the neutron structure was obtained from combinations of measurements with proton and deuteron targets or by using polarized He targets which are dominated by the neutron as the two propon spins are anti-aligned
   7. Polarization was obtained from pumping and adiabatic spin exchange
   8. target polarization was measured through NMR
   9. Scattered electrons were detected with magnetic spectrometers optimized for high-momentum-resolution and good electron ID (all page 6)
2. Page 7: CERN Experiments
   1. EMC and SMC
      1. First polarized DIS measurements at x < 0.1 down to x = 0.01
      2. Used a muon beam with momenta up to 200 GeV, and solid state irradiated ammonia target
      3. Low x measurements suggested the breakdown of the naive parton picture that all spin comes from quarks (as discussed in previous section)
      4. EMC inspired the SMC experiments (1992-6) and COMPASS experiments (2002 on)
      5. After 1987 the focus shifted to measurements of the flavor singlet axial charge (Ellis-Jaff sum-rule) in events with x < 0.1
      6. Large acceptance of the SMC spectrometer in the forward direction allowed them to present the first determination of individual quark distributions for different flavors (Adeva et al 1996, 1998a) from SIDIS
   2. COMPASS
      1. COMPASS uses an advanced polarized target system that cools the targets to 60 mK in frozen spin mode, and then are polarized by dynamic nuclear polarization. This allows them to reach polarization of 85% for protons and 50% for deuterons
      1. COMPASS reconstructs one final state hadron which provides information about the struck quark flavor.
3. HERMES at DESY
   1. HERMES uses a unique technique for the polarized target where they used has targets of pure nuclear-polarized targets. This way, they can avoid dilution of the signal from unpolarized nucleons in the target
   2. The targets were highly longitudinally polarized (~85%) or transversly polarized (75%), and physicists could flip the direcction of the spin within milliseconds (8).
   3. HERMES also used a novel storage cell design that allowed for the target gas to be 100x more dense than previously would've been possible
4. JLAB experiments - page 9
   1. JLAB had highest polarization electron beams (85%) with 0.8-6 GeV energy
      1. Tech follows the tech developed at SLAC

5. Hadronic Scattering Experiments
   1. RHIC




***Section 4: Proton Spin Puzzle***

1. First moment of $g_1$ is related to the scale-invariant axial charges of the target nuclei:

2. $$
   \int _0 ^1 dx \space g_1 ^p (x,Q^2) = \left( \frac{1}{12}g_A^{(3)} + \frac{1}{36}g_A^{(8)} \right) \left\{ 1 + \sum \limits_{l \geq 1}c_{NSl} \alpha_s^l(Q)\right\} \\
   + \frac{1}{9}g_A^{(0)}|_{inv}\left\{ 1 + \sum \limits_{l \geq 1}c_{Sl} \alpha_s^l(Q) \right\} + O(\frac{1}{Q^2}) + \beta_{\infin}
   $$

3. Here, $g_A^{(3)}$, $g_A^{(8)}$, and $g_A^{(0)}$ are the isovector, SU(3) octet and scale-invariant flavor-singlet axial charges respectively. Once can calculate the flavor non-singlet $c_{NSl}$ and singlet $c_{Sl}$ Wilson coefficients in l-loop perturbative QCD. We know these values to a precision of O($\alpha _s ^3$). For DIS at $\alpha _s = 0.3$, one finds:

4. $$
   \left\{1 + \sum_{l = 1}^3 c_{NSl} \alpha_s ^l(Q)\right\} = 0.85
   $$

5. and

6. $$
   \left\{1 + \sum_{l = 1}^3 c_{Sl} \alpha_s ^l(Q)\right\} = 0.96
   $$

7. $\beta_{\infin}$ represents a possible leading twist subtraction constant from the circle at infinity when one closes the contour in the complex plane  in the dispersion relation. This constant affects just the first moment and corresponds to a contribution at $x_{Bj} = 0$. 

8. In terms of flavor-dependent axial charges:

9. $$
   2Ms_\mu \Delta q = \langle p, s|\overline{q} \gamma_{\mu} \gamma_5 q| p, s \rangle
   $$

10. We find the isovector, octet and singlet axial charges are:

11. $$
    g_A ^{(3)} = \Delta u - \Delta d \\
    g_A ^{(8)} = \Delta u + \Delta d - 2\Delta s \\
    g_A ^{(0)}|_{inv} / E(\alpha _s) \equiv g_A ^{(0)} = \Delta u + \Delta d + \Delta s
    $$

    1. $g_A^{(0)}$ is the same as $\Sigma$ before, and shows the total contribution from light quark spin, and this is the same as $g_1(x)$ in the short paper

12. The term $g_A ^{(0)}|_{inv} / E(\alpha _s)$ is explained in reference (this long paper) ___ on pages 12-13, and is out of the scope of this paper

13. $g_A^{(0)}$ is obtained through measuring the structure function $g_1$ and combining the first moment integral in eq 12 with knowledge of $g_A^{(3)}$ and $g_A^{(8)}$ from other processes and pQCD

14. $g_A^{(3)}$ is obtained from measuring neutral $\beta$ decays and the octet axial charge is commonly taken to be ...

15. DIS measurements of $g_1$ have been made at CERN, DESY, JLAB, and SLAC



***A. Spin sum rules*** 









##### Windmolders 2002: "An Introduction to the Evalution of Spin Structure Functions from Experimental Data"

*Page 1*

1. Abstract

*Page 2*

***I Introduction***

2. General introduction to the formalism of nucleon spin structure functions and their interpretation in terms of constituents can be found in recent textbooks (Ref 1)

   1. Maybe look at laterhttps://archive.org/details/electroweakinter0000rent/page/318/mode/2up

3. The present paper is to define the kinematic variables and introduce the relevant physics parameters

4. Spin structure functions are measured in experiments performed with incident electron or muon beams

5. Inclusive: measure only scattered lepton

6. Inclusive scattering kinematics depend only on the momentum transfer $Q^2$ and the energy transfered from the lepton to the virtual photon $\nu$

7. $$
   \nu = k_0 - k_0' \space \space \space \space and \space \space \space \space Q^2 = -q^2 = (k - k')^2 - (k_0 - k_0')^2
   $$

8. These lectures cove the region of DIS where the mass of the final state (X) is much larger than the target proton's mass.

   1. We could equivolently say that we only cover phase space where $Q^2$ and $\nu$ are large.

9. The paper also assumes that the QED interaction regarding the virtual photon and proton is the only interaction, and that interactions through the $Z_0$ and W bosons are negligible

**Scaling and differential cross sections**

1. At large $Q^2$ and $\nu$, we find that the cross section depends only on Bjorken scaling x:

2. $$
   x_{Bj} = \frac{Q^2}{2M \nu}
   $$

   1. Here, M represents the mass of the target nucleon

3. Scaling refers to the fact that at a given fixed x, the cross section does not dependent on the value of $Q^2$

   1. This means that the size of the probed object doesn't affect the cross section
   2. Furthermore, scaling means that the constituents of the proton, the quarks and gluons, must be point-like objects

4. x can be thought of as the fraction of nucleon momentum carried by the quark struck by the virtual photon in the quark gluon model

*Page 3* - nice diagram on this page

**Spin effects, cross sections, and asymmetries**

1. Spin effects create a difference between the cross sections for parallel and antiparallel orientations of the beam and target spins $\sigma ^{\leftarrow \leftarrow}$ and $\sigma ^{\leftarrow \rightarrow}$ 

2. We can utilize an spin averaged cross section to discuss the spin effects

   1. $$
      \overline{\sigma} = \frac{1}{2}(\sigma^{\leftarrow \rightarrow} + \sigma^{\leftarrow \leftarrow})
      $$

3. The averaged cross section is measured in unpolarized experiments, whereas the spin dependent cross section can be measured in experiments with polarized target and beam:

   1. $$
      \Delta = (\sigma^{\leftarrow \rightarrow} - \sigma^{\leftarrow \leftarrow})
      $$

4. DIS experiments aim to measure differential cross sections expressed in terms of two structure functions

   1. $$
      \frac{d^2 \overline{\sigma}}{dxdQ^2} = aF_1(x, Q^2) + bF_2(x, Q^2) \\
      \frac{d^2 \Delta \sigma}{dxdQ^2} = cg_1(x, Q^2) + dg_2(x, Q^2) \space \space \space 
      $$

   2. These structure functions mostly depend on x, and partially on $Q^2$ as scaling is only approximate\

5. $F_1$ and $F_2$ are the unpolarized structure functions related in the quark-parton model by the Callan-Gross relation:

   1. $$
      2xF_1(x) = F_2(x)
      $$

*Page 4*

1. More generally:

   1. $$
      F_1(x,Q^2)\cong \frac{F_2(x, Q^2)}{2x(1+R(x,Q^2))}
      $$

   2. where $R(x,Q^2)$ is small

2. Although scaling tells us that there should be no dependence on $Q^2$ in these structure functions, scaling is violated by interactions between quarks and gluons

   1. QCD describes these effects

3. The second structure function $g_2(x,Q^2)$ has been found to be small.

   1. For a longitudinal spin configuration, the coefficient d is small, suppressing the contribution of $g_2$ even further, and thus we neglect it

4. We can thus write the **cross section asymmetry** as:

   1. $$
      A_{\parallel} = \frac{\Delta \sigma}{2 \overline{\sigma}}\\
      A_{\parallel} \cong D \frac{g_1(x,Q^2)}{F_1(x,Q^2)}
      $$

   2. where D is calculable from the coefficients a, b and c in the structure functio cross sections

   3. Most experiments aim to evalute $A_{\parallel}$ in order to gain access to the spin structure function $g_1$ using the spin averaged functions $F_1$ or $F_2$

      1. We can measured these functions from unpolarized experiments

5. The rest of the lecture is dedicated to deriving the parallel asymmetry from experimental data

6. **Spin effects in DIS can be intuitively understood by the fact that a quark having its spin projection along the  reference axis (+OZ) can absorb a virtual photon whose spin is projected along (-OZ) and flip its sign. However, no absorption can occur when the two spins are initially oriented in the same direction**

7. We can define quark distributions $q_i^+(x)$ to represent the quarks of flavor i whose spin is along the nucleon spin, and $q_i^-(x)$ to represent spin opposite the nucleon spin

   1. From these distributions we define the cross sections where the nucleon spin is opposite the virtual photon spin ($\frac{1}{2}$) and parallel to virtual photon spin ($\frac{3}{2}$).

   2. When the spins are opposite, the cross section is proportional to $q_i^+$ and when they are parallel they are proportional to $q_i^-$

   3. The **virtual photon asymmetry** is obtained by summing over the quark flavors i and multiplying each term by the square of the quark charge expressed in units of electric charge ($e_i^2 = \frac{4}{9}$ or $ \frac{1}{9}$)

      1. $$
         A_1 = \frac{\sigma_{\frac{1}{2}} - \sigma_{\frac{3}{2}}}{\sigma_{\frac{1}{2}} + \sigma_{\frac{3}{2}}}
         \cong
         \frac{\Sigma e_i^2(q_i^+(x) - q_i^-(x))}{\Sigma e_i^2(q_i^+(x) + q_i^-(x))}
         $$

      2. The denominator shows the decomposition of $F_1$  in terms of quark flavors, while the numerator shows decomposition of $g_1$ in terms of quark spin distributions

***2 Polarized DIS Experiments***

*page 5*

**General characteristics of electron and muon experiments**

1. 



#### Notes from Textbook

<u>**Chapter 9: Atomic Structure**</u>

***9.2 The Spinning Electron***

1. Spectral lines are doubled as compared to what we would expect

2. Orbital motion of electron gives rise to magnetic effects, but here we find a different phenomena.

3. In addition to the electorn orbit, it can be helpful to think of the electron as a charged ball spinning on it's axis.

   1. This is a not the case, however

4. The magnetic effects of the electron "spinning" can be described by a spin magnetic moment $\mu_s$. 

   1. If we think of the electron as a collection of charged objects with mass m all rotating about a fixed axis, then we can calculate the magnetic moment from the angular momentum $L = r \times p$ 

5. I will forgoe any further calculations involving the spinning electron as this is not actually accurate to the electron spin moment. If we calculate the necessary velocity for the outermost layer of the electron that corresponds to the measured value for the electrons magnetic moment then we find that the outside of the electron must move much faster than the speed of light. Einstein's special  theory of relativity forbids this, however, and thus we must reconcile the magnetic moment of the electron as an intrinsic characteristic of the particle, like electric charge, not a result of any actual spinning.

6. The Stern-Gerlach experiment demonstrated the existence of the electron spin magnetic moment in 1921.

   1. In the experiment a beam of silver atoms were sent through a magnetic field and deposited onto a glass plate. Stern and Gerlach utilized a non-uniform magnetic field that would exert a force on an particle with a magnetic moment. This magnetic deflection depends on the the angle between the particle's magnetic moment and the z axis (designated by experimental design). Stern and Gerlach intended for the experiment to show the quantization of space due to quantized orbital momentum. They had expected to see many discrete deposits of silver atoms according to quantization of orbital moments, $(2l+1)$, which contrasts the continuous span of silver expected from a classical perspective where the electron orbital moment can exist anywhere. 

   2. When viewing the results, the physicists were shocked to find two discrete components, not the odd number given by $(2l  + 1)$, nor a continuous span described in classical mechanics. Furthermore, the silver atoms used in this experiment have no orbital angular momentum in their ground state where the valence electron resides in the s state ($l = 0$).

   3. T.E. Phipps and J.B. Taylor confirmed the results of Stern and Gerlach in 1927. To reduce the complexity of the system they opted to use hydrogen atoms in their experiment. After finding the same result, physicists concluded that orbital momentum must not account for the total atomic magnetic moment.

   4. Graduate students at the University of Leiden theorized that this unknown effect may result from the spinning motion of the outermost electron which cemented the name of the phenomena, despite its inaccuracy. 

   5. Furthermore, the students conjectured that the moment obeyed the same quantization rules as orbital angular momentum, producing a formula for number of components of spin angular momentum: $(2s + 1)$. Both the Stern-Gerlach experiment and Phipps-Taylor experiment showed two distinct components, indicating the value for the spin quantum number $s = \frac{1}{2}$.

   6. Now applying space quantization rules for angular momentum to spin, we introduce:

      1. $$
         S_z = m_s \hbar
         $$

      2. where $m_s = \pm \frac{1}{2}$

      3. The values for $m_s$ are often represented by an up arrow or plus sign for $m_s = +\frac{1}{2}$, and a down arrow or negative sign for $m_s = -\frac{1}{2}$

      4. Taking the magnitude of spin angular momentum we find:

         1. $$
            |S| = \sqrt{s(s+1)\hbar} = \frac{\sqrt{3}}{2} \hbar
            $$

         2. This value is a constant, showing that the spin angular momentum for an electron is an intrinsic property of the electron

   ##### Connection from textbook to paper

   (connect talking about how an experiment showed that the naive picture was wrong)

   In 1967 (fix date), the EMC experiment produced an unexpected result suggesting that not all of the proton's spin comes from the spin of the constituent quarks. The result of this experiment is reminiscent of the Stern-Gerlach result, as both found that the current models of the atom and the proton were oversimplified, and missing essential phenomena that accounts for part of the total phenomena. In a sense, the proton spin puzzle could be thought of as a repeat (change word) of the Stern-Gerlach result at the next level lower, from the atom to the nucleon. Hence, this paper serves to give a brief introduction to the more recent expansion on spin studies that occurred after the content taught in modern physics

**Questions**

1. Why 2 structure functions each?

#### SIDIS stuff

1. Transverse spin and momentum
   1. https://arxiv.org/pdf/2001.05415v2.pdf
2. Proton spin puzzle
   1. https://arxiv.org/pdf/1209.2803.pdf
   2. Paper producing the measurements leading to this:
      1. https://reader.elsevier.com/reader/sd/pii/0370269388915237?token=7FC1A05FDCA95B7A36181ECC3C50B755D70077F4D389CBCB9DE2A7D32515C5D0C107523D3822F60511B4CB20FEE2C1D0&originRegion=us-east-1&originCreation=20220901161448
3. Spin asymmetry leading to determination of structure function g1
   1. https://www.sciencedirect.com/science/article/pii/0370269388915237

4. DIS of e-p collisions
   1. https://journals.aps.org/prl/pdf/10.1103/PhysRevLett.37.1261 - PRL


#### Quark model / valence and sea quarks

#### Particles

1. Positron discovery
   1. https://journals.aps.org/pr/pdf/10.1103/PhysRev.43.491
2. Strange discovery

## Notes:

### Proton Spin Puzzle:

#### Section 1

1. EMC data suggested that quark intrinsic spin contributes little to the spin of the proton (1988).
   1. Longitudinal spin is understood, but transverse spin is not
2. Article compiles the developments of QCD spin physics
3. Big questions:
   1. Are the results from the EMC correct?
   2. How is psin distributed among the valence and sea quarks and gluons
   3. What about orbital angular momentum in the nucleon

#### Section 2: Spin Structure Functions and Parton Distributions

Brief introduction to nucleon spin physics and the experiments that have been performed to investigate it

1. Polarized deep inelastic scattering - pDIS - experiments where longitundinally polarized leptons are scattered off a longitudinal or transversly polarized nucleon at large momentum transfer ($Q^2$)
   1. Inclusive measurements are where only the scattered lepton is measured in the final state
   2. Semi-Inclusive measurements are where at least one high energy final state hadron is measured.
   3. *Question: What is the difference between transversely and longitudinally polarized particles*
   4. Measurements with longitudinally polarized targets and beams give info about the helicity distributions of quarks and glons in the nucleon
      1. At leading order, they can be though of as the difference in probability of finding a parton with longitudinal polarization parallel or anti-parallel to that of the nucleon

Start by describing concept in book, then take ten page story through the paper. Convey that you understand what they did and why they did it. Convey your excitement about the paper. 



### Connection to textbook:

1. Chapter 9 begins a discussion about electron spin - can use this to lead into the spin of proton
2. Chapter 15 discusses quarks, QCD, etc. - good place to find some starting points that connect to stuff.
3. Try to find anything about particle accelerators
   1. Nuclear reactions go into this with nuclei collisions
   2. Radiation detectors are used for detectors like CLAS12
   3. "How to find a top quark" essay - particle accelerators and detectors



### Cross Sections

1. When a quantum particle approaches another particle, there is a non-zero probability that it doesn't interact with the potential	
   1. The number of scattering events is probabilistic, so this means that the cross section is the probability of a certain process happening
   2. for particle collisions, the total cross section is the probability of measuring a specific endstate given a collision (or interaction)
      1. For example: when you collide 2 protons, whats the probability of measuring 4 leptons in the final state?
   3. the differential cross section is the probability of measuring the endstate within a range of a kinematic variable
      1. For example: when colliding 2 protons, whats the probability of measuring 4 leptons within a certain bjorken x range, or a specific
   4. A peak in a differential cross section is called a resonance, and these are very interesting
   5. *Question: So if we plot a histogram of the counts of a particle with specific Q2 values, is that its differential cross section?*



DI-HADRON STUDIES AT CLAS12