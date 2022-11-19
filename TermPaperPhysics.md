# Physics Term Paper

#### Rowan Kelleher

##### November 13, 2022

Outline:

***Stuff to add/explain***

1. Explain cross sections before diving into the definition of the cross sections and their use in asymmetry calculations
   1. Make sure to figure out / explain the significance of asymmetries
2. Try to find original results to both get more diverse references and find what they were saying at time of publication to give more of a timeline
3. Where does theoretical value for g_1^n come from

**Notes:**

1. **Start from textbook, then introduce the field (QCD and scattering)**
2. **With heavy math - do it the way Glenn did it during class **
   1. **If needed, skip and leave a reference**
   2. **If doable, include the math**
   3. Supplement with a reference
   4. *Probably include asymmetries*
3. **Figures are valuable - make sure to include feynman diagram for SIDIS, quark model evolution, potentially plots**

1. Introduction: Outline the motivation, the purpose, and the content of the paper
   1. Over the past summer and throughout this semester I have had the opportunity to work on a particle physics research project. My project concerns the validity of TMD factorization in the Semi-Inclusive deep inelastic scattering  (SIDIS) at CLAS12, a detector at Jefferson Lab. Specifically, I have worked on calculating SIDIS kinematics from CLAS12 data (and simulation) that can be used to calculate a quantity called affinity that estimates how well certain factorization schemes describe the QCD physics occuring in SIDIS. My project is tiny part of the giant global effort to describe the dynamics and structure of nucleons: the proton and neutron. This effort was jump started in 1988 when the European Muon Collaboration published the first results of $g_1^p$, a quantity that describes how much of the proton's spin is made up from valence quark spin. The simplest quark model of the proton describes the nucleon as a collection of three quarks bound together by nuclear gluon, where the proton's 1/2 spin is the sum of the spins of the 1/2 spin quarks. SIDIS experiments have forced physicists to create more complex nucleon models where the three valence quarks orbit through a sea of quark-antiquark pairs. The proton spin can thus originate in parts from valence quark spin and angular momentum, sea quark spin and angular momentum, and even gluon spin and angular momentum. This paper aims to introduce the experiments that began and continued these efforts in proton spin studies, explain the impact of SIDIS studies on the field, and connect the physics back to the basics of spin taught in Modern Physics courses
   2. First the paper will provide an overview of spin for elementary particles and how the quantity can be used to describe (word for not elementary) particles. I will then discuss the Bjorken and Ellis-Jaffe sum rules and their relevence to nucleon spin, as well as the experiments that tested their validity. These experiments lead into the current advances concerning the proton spin puzzle where the paper concludes.
   3. **MAKE SURE TO PREFACE WITH EMC RESULTS THAT STARTED CRISIS**
   
1. Section 1: What is spin and why is it important
   1. Electron spin: recap of what we learned in class
   2. How does electron spin relate / differ from nucleon spin?
2. Section 2: Beginnings of nucleon spin theory
   1. Assumptions about the makeup of the nucleon's spin
   2. Bjorken Sum Rule (and Ellis Jaffe sum rule?)
   3. First EMC experiment testing the sum rules
   4. Further experiments with SLAC, CERN, SMC
3. Section 3: Proton spin puzzle from then on

Unplaced parts that I can explain now but need to place in a natural place later

1. Nucleon/QCD basics

   1. In order to understand the importance of the EMC results regarding the proton's spin makeup, we must first understand the basics of the nucleon and the forces that hold it together. Protons and neutrons, together nucleons, are subatomic particles that make up the nuclei of atoms. Nucleons are not elementary particles, however, and have constituents themselves. The first quark model of the nucleon called the Eightfold way was theorized by Gell-Mann and consisted of three static quarks that combined to make up all of the proton's spin. Quarks were categorized by three generations and size flavors, where each generation consists of two flavors of different charges (see Appendix I for a diagram of the standard model of particle physics). Later, theorists thought up relativistic quark models where quarks made up 60% of the proton's spin, with the other 40% coming from quark orbital angular momentum. Today data and theory point to a number of different contributions to the proton spin. Quantum Chromodynamics (QCD) explain the strong force binding colored quarks together through the exchange of gluons, force carriers which may contribute up to 50% of the protons spin. Furthermore, current quark models predict a sea of quark-antiquark pairs residing in the proton which contribute a small, but nonzero portion of the proton spin (Aidala et al. 2). Physicists have found that studying the quark-gluon model of the proton to be quite difficult as the proton is a bound state meaning the quarks and gluons cannot be separated into individual compenents. The strong force increases in magnitude with the distance between two interacting quarks, making it impossible to remove a quark or a gluon from the proton (Jaffe 24). Despite the difficulties QCD presents, physicists can still probe the nucleon through scattering experiments to learn more about the dynamics and structure of protons and neutrons. <u>(maybe here include a set of photos showing the progression of the proton makeup</u>)

2. What is SIDIS?

   1. The experiments conducted to learn more about the spin structure of the nucleon have typically been Inclusive and Semi-Inclusive Deep Inelastic Scattering experiments (DIS and SIDIS). Inelastic scattering refers to experiments where a particle (typically in a particle accelerator like the LHC or RHIC) collides with another particle and through its momentum transfer "breaks" the particle into different particles. Electrons and muons (leptons) are typically accelerated to high energies and directed at target nucleons to make them run into each other. Inelastic scattering differs from elastic scattering as the target particle remains whole in the latter experiments. These experiments are referred to as deep if the square of the momentum transfered from the lepton to to the nucleon, $Q^2$ is large (Jaffe). Thus we have Deep Inelastic Scattering, which describes the experiments performed by the EMC and SLAC at the beginning of the proton spin crisis. These experiments are described as inclusive as they detect the scattered lepton, but not the remnants of the target proton. Inclusive DIS kinematics depend solely on $Q^2$ and $\nu  = k_0 -  k_0'$ where $k_0$ represents the leptonic energy. Semi-inclusive deep inelastic scattering refers to experiments where the detectors capture the scattered lepton in addition to at least one high energy hadron. This introduces other kinematics that depend on the hadron's momentum, energy, angle with respect to virtual photon, etc. SIDIS and DIS experiments typically assume that contributions from the $Z_0$ and $W$ bosons are negligible, allowing physicists to describe the interactions as purely QED (virtual photon hits proton) (Windmolders 2).

3. Scaling and differential cross sections

   1. OUTLINE 

      1. Make sure to introduce the spin crisis in the intro - tell about EMC results a little
      2. Then explain DIS and SIDIS before going into the theory (DONE) that preceded the EMC results - mostly stuff from jaffe paper mixed with stuff from windmolders - windmolders  can supplement jaffe to further explain some of the math
      3. After this, we can lead into discussion of stuff after EMC

   2. In 1966, __FIRSTNAME__ Bjorken theorized that the operators mediating the electromagnetic interaction may obey the same rules as free-field operators leading him to create a sum rule for inelastic scattering of polarized leptons off polarized protons and neutrons. This rule, referred to as the Bjorken sum rule, describes the relationship between the structure functions $g_1^p$ (proton) and $g_1^n$ (neutron)  and DIS kinematics. 

      1. $$
         \int_0^{\infin} \frac{Q^2}{M \nu^2}d\nu \Bigl( g_1^p(Q^2,\nu) - g_1^n(Q^2,\nu)\Bigl ) = \frac{g_A}{3}
         $$

   3. The structure functions are proportional to the polarization asymmetry which is defined as the difference of the cross section where nucleon and lepton spins are parallel and the cross section of anti parallel nucleon and lepton spin. $g_1$ is one of four structure functions that together describe the proton composition. Bjorken's sum rule predicts that the cross sections contained $g_1$ do not depend on $Q^2$, shown by the lack of $Q^2$ on the right side of the equation (Jaffe 26). This prediction suggests that the size of the probed object doesn't affect the cross section, meaning that the quarks and gluons must be point-like objects. The Stanford Linear Accelerator (SLAC) tested Bjorken's hypothesis at large $Q^2$ and $\nu$ confirmed the sum rule meaning that the cross section depends only on a scaling variable called Bjorken x or $x_{Bj}$  (Windmolders 2).  

      1. $$
         x_{Bj} = \frac{Q^2}{2M\nu}
         $$

   4. In electron proton DIS experiments, $x_{Bj}$ can be thought of as the fraction of the target proton's momentum attributed to the quark about to be struck by the incident electron (viewed in a high proton momentum frame). This allows us to think of the structure functions as probability distributions in x for the quarks inside the nucleon (Jaffe 26). When labeled by flavor, we find:

   5. $$
      g_1^p(x) = \frac{4}{9}\Delta u (x) + \frac{4}{9}\Delta \bar u (x) + \frac{1}{9}\Delta d (x) + \frac{1}{9}\Delta \bar d (x) + \frac{1}{9}\Delta s (x) + \frac{1}{9}\Delta \bar s (x)
      $$

   6. where $\Delta u(x)$ represents the difference between up quark x distributions for quarks with spin parallel and antiparallel to the spin of the proton. We get the fractional coefficients in front of each term from the square of the quark's charge due to DIS utilizing the QED interaction. While we do not find $Q^2$ dependence for the structure function here, it is important to note that QCD radiative effects introduce $Q^2$ dependence at high momentum transfer. Radiative effects are when the target proton emit(s) gluon(s) that are unmeasured, altering the energy and momentum of the system. By integrating the structure function all $x_{Bj}$, we can write:

   7. $$
      \int _0 ^1 g^p _1 (x)dx = \frac{1}{2}\Bigl( \frac{4}{9} \Delta u + \frac{1}{9} \Delta d + \frac{1}{9} \Delta s \Bigl)
      $$

   8. QCD flavor symmetry shows that matrix elements F and D can be related to $\Delta u - \Delta s$ and $\Delta u - \Delta d$, allowing substitutions leading to:

   9. $$
      18 \int _0 ^1 g_1 ^p (x)dx = 3F + D + 2\Sigma \space \space \space (eq 4)
      $$

   10. (Jaffe 26) Here, $\Sigma$ corresponds to the sum $\Delta u + \Delta d + \Delta s$, or the contribution of all the light quarks to the proton's spin

   11. As mentioned earlier, the simplest quark model of the proton consists of two up quarks and one down quark, while more sophisticated models describe a sea of virtual quark-antiquark pairs residing in the proton. In 1973, ___ Jaffe and John Ellis theorized that unpolarized strange quarks may inhabit the nucleon. They thought that these quarks, which are much more massive than up and down quarks, may not contribute a significant amount to the proton's total spin, leading them to approximate the strange contribution as 0 in equation 4. They then calculated a value for the structure function $g_1^p$ using current experimental values for F and D as well as QCD radiative corrections:

   12. $$
       \int _0 ^\infin g_1 ^p (x,Q^2)dx = 0.176 \pm 0.006   \space \space \space (eq        \space 5)
       $$

   13. (Jaffe 27)

   14. This equation became known as the Ellis-Jaffe sum rule, and inspired experiments to test it

   15. 

   16. 1. **AT THIS POINT, A LOT OF THE THEORY HAS BEEN INTRODUCED, MOVE TO EXPERIMENTAL**

   Section 2: EMC Result

   **Give  topic sentence about this section**

   1.  The first DIS experiments began in the 1970s, starting at SLAC. However, the earliest polarized proton scattering was carried out at too low $x_{Bj}$ values to investigate the Bjorken sum rule and Ellis-Jaffe sum rule. By the end of the decade Vernon Hughes had begun an experiment capable of evaluating the sum rules. His group measured:

   2. $$
      \int _0 ^1 g^p _1 (x)dx = 0.17 \pm 0.05
      $$

   3. While this result agreed with the Ellis-Jaffe sum rule, the scattering events occurred at low $Q^2$, leaving ambiguity about phase space close to $x_{Bj}$ = 0. Following this experiment at SLAC, CERN produced the next results at the super Proton Synchrotron. This experiment was conducted by CERN's European Muon Collaboration (EMC). The EMC experiment scattering high energy muons off of unpolarized proton targets. Through decaying pions they achieved 80% polarization and energy levels as high as 100 GeV, much higher than previous experiments. Their results published in 1987 found the structure function to be much less than that measured by SLAC and the prediction from the Ellis-Jaffe sum rule:

   4. $$
      \int _0 ^1 g^p _1 (x)dx = 0.126 \pm 0.018
      $$

   5. (Jaffe 27)

   6. This measurement corresponds to $\Sigma = 0.120 \pm 0.16$, suggesting that, within error, none of the proton's spin comes from the spin of the light quarks' inside it. Additionally, the result suggested that a significant portion of the proton's spin comes from strange quark-antiquark pairs with a value of:

   7. $$
      \Delta s = -0.190 \pm 0.056
      $$

   8. (Jaffe 27)

   9. Ellis and Jaffe had conjectured this value to be zero and thus the EMC data shows a violation of their sum rule.

   10. The spin muon collaboration succeeded the EMC and set out to further their goals of describing the nucleon spin structure through measurements of the neutron structure function. SLAC followed suit and worked to measure the structure function as well, and both groups announced their first results in 1993. Assuming no contribution from the strange quark, the theoretical value is:

   11. $$
       \int _0 ^1 g^n _1 (x)dx = -0.002 \pm 0.005
       $$

   12. The SMC reported an inconsistent value of:

   13. $$
       \int _0 ^1 g^n _1 (x)dx = -0.08 \pm 0.04
       $$

   14. And lastly SLAC reported a closer to theoretical value:

   15. $$
       \int _0 ^1 g^n _1 (x)dx = -0.022 \pm 0.011
       $$

   16. (Jaffe 28)

   17. Recalling the Bjorken sum rule, we can write a new integral which is equal to $1/2$ the left side of equation 1:

   18. $$
       \int^1_0 (g(x)_1^p - g(x)_1^n)dx
       $$

   19. The new SLAC and SMC data produced results for this quantity, allowing for evaluation of the Bjorken sum rule. The results from both experiments proved consistent with expected values, acting as a confirmation of the sum rule. 

   1. **NEW SECTION KINDA  - TRANSITION FROM EMC RESULT TO FOLLOWING EXPERIMENTS**


#### Section 3: Experiments past the EMC/SMC

1. Following the results from the SMC and SLAC that cemented the Bjorken sum-rule in spin physics, many experiments continued the legacy of investigating the proton spin structure. The first of these experiments used inclusive DIS to study the nucleon, 

1. 

### Appendix

#### Appendix I

Standard model diagram (for showing generations and flavors of quarks)