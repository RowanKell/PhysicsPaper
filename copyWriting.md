# A Brief Introduction to the Proton Spin Puzzle

##### Rowan Kelleher

###### November 22, 2022

### I. Introduction

​	Particle physics aims to describe the fundamental building blocks that make up every part of the universe. Physicist have developed our understanding of particles tremendously over the past few centuries, from models of the atom to now models of the protons and neutrons. One program in this field concerns the spin structure of the proton, and aims to describe how elementary particles, quarks and gluons (also referred to collectively as partons), make up the nucleons. The quark model of the proton began as a simple collection of static quarks, and has evolved into a complicated sea of quark anti-quark pairs orbiting at high speeds inside the nucleon. The first indication that the initial quark model was incorrect came in 1988 when the European Muon Collaboration (EMC) published results that disagreed with the assumptions underlying this model (EMC, 1988). The three valence quarks of the quark model appeared to not contribute much of the total spin of the proton. This result spurred a global effort to describe the dynamics and structure of the proton.

​	First the paper intends to provide an overview of spin for elementary particles and how the quantity can be used to describe (word for not elementary) particles. I will then discuss the Bjorken and Ellis-Jaffe sum rules and their relevance to nucleon spin, as well as the experiments that tested their validity. These experiments lead into the current topics in proton spin studies where the paper concludes.

### II. What is spin? From Electrons to Protons

​	Before the discovery of electron spin, physicists knew the electron had orbital angular momentum resulting from its orbit around the nucleus. Then, in 1921 Otto Stern devised an experiment that Walther Gerlach tested in 1922 (The Stern-Gerlach experiment) that produced evidence of another source of angular momentum. In this experiment, a beam of silver atoms are sent through a non-uniform magnetic field and deposited onto a glass plate for observation. The physicists used a non-uniform field to exert a force on any particle with magnetic moment. During flight, the atoms are deflected by the non-uniform field depending on the alignment of the particle's magnetic moment, and thus the physicists intended to show the quantization of space due to discrete levels of alignment creating discrete collections on the observation plate. Under the assumption that the electron's magnetic moment depends solely on the orbital angular momentum, they expected to see $(2l + 1)$ deposits on the plate. This expectation differs from the classical expectation, as classically there is no restriction on number of deposits, meaning that a result showing discrete deposits according to the formula would provide evidence of space quantization. The results did not follow either theory, however, and instead two distinct components showed on the plate. Because the silver atoms used in the experiment had no angular momentum in their ground state, corresponding to $l = 0$, the result clearly differed from the quantum expectation. The present theory of quantized orbital angular momentum had no explanation for the two components, suggesting the electron may have another contribution to its magnetic moment (Serway et al. 304).

​	Data from a 1927 recreation of the Stern-Gerlach experiment performed by T. E. Phipps and J. B. Taylor using hydrogen atoms produced the same result. This confirmed that there was another source of the electron's magnetic moment. Graduate students at the University of Lieden developed a theory to explain the phenomena and suggested the magnetic moment was a result of the electron spinning on its axis (Serway et al. 304). Although they were incorrect about the electron spinning, the name stuck and they created a theory of spin angular momentum. The students conjectured that the moment obeyed the same space quantization rules as orbital angular momentum, producing a formula for the number of components of spin angular momentum for a particle: $(2s + 1)$. In both the previously mentioned experiments, the results showed two discrete components which indicates the value for the spin quantum number: $s = \frac{1}{2}$. Furthermore, they gave formulas for the z-component and magnitude of spin angular momentum:
$$
S_z = m_s \hbar \\

\vert S \vert = \sqrt{s(s+1)\hbar} = \frac{\sqrt{3}}{2} \hbar
$$
Here, $m_s = \pm \frac{1}{2}$. Because the magnitude of the spin angular momentum depends only only constants, the spin magnetic moment must be an intrinsic property of the electron (Serway et al. 305-6).

​	Decades after the Stern-Gerlach experiment, the European Muon Collaboration (EMC) created an experiment to investigate the spin makeup of the proton

[^1]: Note that proton and nucleon are often used interchangeably in this paper. It seems that the proton was the main focus of these studies (hence proton spin puzzle), but the neutron plays an important role in measuring the observables necessary to understand the proton. In discussion of specific experiments and their results, care is taken to identify protons and neutrons appropriately.

. The quark models of the time predicted that the three valence quarks' spin accounted for all of the proton's spin angular momentum. However, the EMC results showed that only a small portion of proton spin can be attributed to the valence quarks. Just as in the Stern-Gerlach experiment physicists found that the current models did not account for the total angular momentum of the electron, the simple quark model of the proton did not account for the total spin. In a sense, the proton spin puzzle can be thought of as a repeat of the Stern-Gerlach result at a more elementary level. 

#### Section III. Beginnings of the Proton Spin Crisis

​	In order to discuss the theory and experiments that caused the spin crisis, one must develop a basic understanding of key concepts in scattering experiments. The 1988 EMC experiment, physicists employed deep inelastic scattering to probe the proton. Inelastic scattering refers to experiments where a particle  collides with another particle and through the transfer of momentum "breaks" the particle into different particles. In these experiments physicists accelerate leptons (electrons and muons) to high energies and "shoot" them at a target (often a proton). When the two particles collide, the lepton transfers part of its momentum to a virtual photon which the proton absorbs. The details of this interaction are the subject of quantum electrodynamics. At sufficiently high energies the virtual photon resolves an individual quark and can knock the quark out of the nucleon. However, quarks cannot exist alone and instead must be part of a hadron, or a group of two (mesons) or three (baryons) quarks, due to the strength of the strong nuclear force. Because of this, the scattered quark hadronizes into a new particle. This phenomenon is described by quantum chromodynamics, or QCD. We refer to scattering experiments as deep if the square of the momentum transferred from the lepton to the hadron, $Q^2$, is large. When only the incident and scattered lepton are measured in the experiment, the process is called inclusive; if at least one high energy hadron is measured in the final state (such as the hadron created by the struck quark), then the experiment is semi-inclusive. Thus we describe experiments such as that at conducted by the EMC as inclusive deep inelastic scattering, or DIS, and studies at COMPASS, HERMES, and JLab as semi-inclusive DIS, or SIDIS. All of the kinematics of DIS experiments are contained in the momentum transfer $Q^2$ as well as the energy transferred between the lepton and the target $\nu$. SIDIS experiments utilize more complex kinematics due to the introduction of hadronic variables. Furthermore, a cross section (in particle physics) refers to the probability of a certain event happening. When one quantum particle approaches another, there is a non-zero probability that the two do not interact. Hence, the total cross section for a particle collision describes the probability of measuring a specific endstate given an interaction. For example, we could find a cross section that describes the probability of measuring four leptons in the final state of a proton-proton collision. The differential cross section describes the probability of measuring an endstate within a range of a kinematic variable (Dotson, 2020)

​	The next step in our story of proton spin physics occrus in 1966, when James Bjorken theorized that the operators mediating the electromagnetic interaction may obey the same rules as free-field operators. This theory led to a sum rule for DIS of polarized leptons off polarized protons and neutrons. This rule, called the Bjorken sum rule, describes the relationship between the structure functions $g_1^p$ (proton) and $g_1^n$ (neutron)  and DIS kinematics:
$$
\int_0^{\infin} \frac{Q^2}{M \nu^2}d\nu \Bigl( g_1^p(Q^2,\nu) - g_1^n(Q^2,\nu)\Bigl ) = \frac{g_A}{3} \space \space \space \space (eq\space  1)
$$
There are four total structure functions that together summarize the composition of the proton. Here, $g_1$ is proportional to the polarization asymmetry, which is defined as the difference of the cross sections where nucleon and lepton spins are parallel and antiparallel. Bjorken's sum rule predicts that the cross sections contained $g_1$ do not depend on $Q^2$, shown by the lack of $Q^2$ on the right side of the equation (Jaffe 26). This prediction suggests that the size of the probed object doesn't affect the cross section, meaning that the quarks and gluons must behave as point-like objects. The cross section then depends only on the scaling variable $x_{Bj}$ where:
$$
x_{Bj} = \frac{Q^2}{2M\nu}
$$
In electron proton DIS experiments, $x_{Bj}$ can be thought of as the fraction of the target proton's momentum attributed to the quark about to be struck by the incident electron (viewed in a frame where the proton has high momentum). Bjorken scaling allows us to think of the structure functions as probability distributions in $x_{Bj}$ for the quarks inside the nucleon (Jaffe 26). When labeled by flavor (see appendix I for a diagram showing quark flavors), we find:
$$
g_1^p(x) = \frac{4}{9}\Delta u (x) + \frac{4}{9}\Delta \bar u (x) + \frac{1}{9}\Delta d (x) + \frac{1}{9}\Delta \bar d (x) + \frac{1}{9}\Delta s (x) + \frac{1}{9}\Delta \bar s (x) \space \space \space \space (eq\space  2)
$$
where $\Delta u(x)$ (and each term for the other flavors) represents the difference between up quark $x_{Bj}$ distributions for quarks with spin parallel and antiparallel to the spin of the proton. Given the interaction is described by QED, each term is multiplied by the square of its charge. While we do not find $Q^2$ dependence for the structure function here, it is important to note that QCD radiative effects introduce $Q^2$ dependence at high momentum transfer. Radiative effects occur when the target proton emit(s) gluon(s) that are unmeasured, altering the energy and momentum of the system. By integrating the structure function over all $x_{Bj}$ we find:
$$
\int _0 ^1 g^p _1 (x)dx = \frac{1}{2}\Bigl( \frac{4}{9} \Delta u + \frac{1}{9} \Delta d + \frac{1}{9} \Delta s \Bigl)\space \space \space \space (eq\space  3)
$$
QCD flavor symmetry shows that matrix elements F and D can be related to $\Delta u - \Delta s$ and $\Delta u - \Delta d$, allowing substitutions leading to:
$$
18 \int _0 ^1 g_1 ^p (x)dx = 3F + D + 2\Sigma \space \space \space (eq 4)
$$
(Jaffe 26). Here, $\Sigma$ corresponds to the sum $\Delta u + \Delta d + \Delta s$, the contribution of all the light quarks to the proton's spin. 

​	As mentioned earlier, the simplest quark model of the proton consists of two up quarks and one down quark. In 1973, Arthur Jaffe and John Ellis theorized that unpolarized strange quarks may inhabit the nucleon. They thought that these quarks, which are much more massive than up and down quarks, may not contribute a significant amount to the proton's total spin, leading them to approximate the strange contribution as 0 in equation 4. They then calculated a value for the structure function $g_1^p$ using current experimental values for F and D as well as QCD radiative corrections:
$$
\int _0 ^\infin g_1 ^p (x,Q^2)dx = 0.176 \pm 0.006   \space \space \space (eq        \space 5)
$$
(Jaffe 27). This sum rule became known as the Ellis-Jaffe sum rule, and was tested by DIS experiments conducted by the EMC and SLAC.

​	The first DIS experiments began in the 1970s, but they could not produce measurements in low enough $x_{Bj}$ to investigate the Bjorken and Ellis-Jaffe sum rules. By the end of the decade, Vernon Hughes had begun an experiment capable of evaluating the sum rules. His group measured:
$$
\int _0 ^1 g^p _1 (x)dx = 0.17 \pm 0.05
$$
While this result agreed with the Ellis-Jaffe sum rule, the scattering events occurred at low $Q^2$, leaving ambiguity about phase space close to $x_{Bj}$ = 0. Following this experiment at SLAC, CERN produced the next results at the super Proton Synchrotron. This experiment was conducted by CERN's European Muon Collaboration (EMC). The EMC experiment scattering high energy muons off of unpolarized proton targets. Through decaying pions they achieved 80% polarization and energy levels as high as 100 GeV, much higher than previous experiments. Their results published in 1987 found the structure function to be much less than that measured by SLAC and the prediction from the Ellis-Jaffe sum rule:
$$
\int _0 ^1 g^p _1 (x)dx = 0.126 \pm 0.018
$$
(Jaffe 27). This measurement corresponds to $\Sigma = 0.120 \pm 0.16$, suggesting that, within error, none of the proton's spin comes from the spin of the light quarks' inside it. Additionally, the result suggested that a significant portion of the proton's spin comes from strange quark-antiquark pairs with a value of:
$$
\Delta s = -0.190 \pm 0.056
$$
(Jaffe 27). Ellis and Jaffe had conjectured this value to be zero and thus the EMC data shows a violation of their sum rule.

​	The spin muon collaboration succeeded the EMC and set out to further their goals of describing the nucleon spin structure through measurements of the neutron structure function. SLAC followed suit and worked to measure the structure function as well, and both groups announced their first results in 1993. Assuming no contribution from the strange quark, the theoretical value is $\int _0 ^1 g^n _1 (x)dx = -0.002 \pm 0.005$. The SMC reported an inconsistent value of $\int _0 ^1 g^n _1 (x)dx = -0.08 \pm 0.04$. SLAC reported a value of $\int _0 ^1 g^n _1 (x)dx = -0.022 \pm 0.011$ (Jaffe 28). Recalling the Bjorken sum rule, we can write a new integral which is equal to $1/2$ the left side of equation 1:
$$
\int^1_0 (g(x)_1^p - g(x)_1^n)dx \space \space \space \space (eq\space  6)
$$
The results from both experiments proved consistent with expected values, confirming Bjorken's rule

#### IV. Current Solutions and Problems

This section is devoted to recent developments regarding the proton's spin structure. The structure function $g_A^{(0)}$ represents the same quantity as $\Sigma$ in equation four, and differs only by convention. We can attempt to explain its small experimental value through theoretical QCD, accounting now for other effects.:
$$
g_A^{(0)} = \left( \sum_q \Delta q - 3 \frac{\alpha_s}{2 \pi} \Delta g\right)_{partons} + C_{\infin}
$$
(for more on where this comes from, Aidala et al. (2013) recommends reviewing Altarelli and Ross (1988), Efremov and Teryaev (1988), Carlitz et al. (1988), Bass et al. (1991) and Bass (2005)).

Here, $\Delta g _{partons}$ represents the spin carried by polarized gluons in the polarized proton, where $\alpha_s \Delta g ~$ is approximately constant as $Q^2 \rightarrow \infin$ (Aidala et al., 2013). $\Delta q _{partons}$ represents the spin carried by the quarks (and anti-quarks). $C_{\infin}$ relates to non-perturbative QCD processes and is discussed in section VI of Aidala et al. The remainder of the paper focuses on polarized strange contributions and polarized glue.

​	In SIDIS experiments, when a pion (made of an up anti-down pair or anti-up down par) or kaon (strange anti-strange pair) is reconstructed in the final state, the hadron most likely contains the struck quark. We can use this hadron to tag the flavor of the struck quark and calculate information relevant to that quark. One can calculate the virtual photon-proton double-spin asymmetry from SIDIS data, which is shown in Aidala et al. 16. The SMC and HERMES experiments have led this particular field of experimentation (Aidala et al. 16). Both COMPASS and HERMES have presented results regarding the sum of strange and anti-strange polarization which is plotted in figure Z (**Need to put figure from page 18 of aidala et al)**. The results suggest that there is no evidence for polarized strangeness in the nucleon across $x_{Bj}$ values. However, these calculations depend on fragmentation functions which describe the processes that occur when a quark is knocked out of one hadron and creates a new hadron. Future improvements to these fragmentation functions could alter the calculations of $\Delta s$ (Aidala et al., 2013). A potential future approach for measuring the strange-quark polarization would involve elastic scattering neutrinos off of protons. These experiments could avoid SU(3) assumptions, and hence would provide an independent outlook on the strangeness of the proton. Pagliaroli et al. (2012) provides a suggestion for such an experiment.

​	Another way to increase our understanding off the effect of polarized glue on the proton's spin involves polarized proton-proton scattering. This sort of scattering is sensitive to the ratio of polarized to unpolarized glue $\frac{\Delta g}{g}$, making proton-proton collisions an important part of proton spin studies. COMPASS, HERMES, and the SMC have made measurements of this fraction. These experiments reconstruct a charmed meson or high momentum hadron in the final state (see Adolph et al., 2012d and Alekseev et al., 2009c for charmed meson production and Ageev et al., 2006 for high momentum hadron studies) (Aidala et al. 2013). These studies have shown no evidence for non-zero gluon polarization in the phase space they were conducted in. See figure (**delta g/g table on page 20**) for a table of the data. Despite this, results from CERN's RHIC provided the first non-zero measurements of polarized glue in the proton. The value of $\Delta g$ measured at these detectors would not make up for all of the missing proton spin, but would contribute a significant portion:
$$
\Delta g \approx 0.2 - 0.3
$$
(Aidala et al., 2013). This measurement concludes the experimental discussion in the present paper, and theoretical aspects of these properties are discussed in Aidala et al. (2013) Section VI.

#### V. Conclusion

​	(**keep short**)Although physicists have not yet found where all of the proton's spin comes from, global studies on the matter have improved understanding significantly over the past four decades since the publishing of the EMC results. Current experiments are actively building off of the work described in this paper, and many future experiments are planned to continue the studies. The experiments discussed have evolved our understanding about spin and the structure of the proton and illustrates the process by which physics

#### References

Adolph, C., et al. (COMPASS Collaboration) (2012d), arXiv:1211.6849 [hep-ex].

Ageev, E. S., et al. (COMPASS Collaboration) (2006), *Physics Letters* **B633**, 25.

Aidala, Christine A., Steven D. Bass, Delia Hasch, and Gerhard K. Mallot. (2013). The Spin Structure of the 

​		Nucleon. *Reviews of Modern Physics* **85**, 655, pp 1-20.

Alekseev, M., et al. (COMPASS Collaboration) (2009c), *Physics Letters* **B676**, 31.

Altarelli, G., R. D. Ball, S. Forte, and G. Ridolfi (1997), *Nuclear Physics* **B496**, 337.

Bass, S. D. (2005), The Spin Structure of the Proton *Review of Modern Physics* **77**, 1257.

Bass, S. D., B. L. Ioffe, N. N. Nikolaev, and A. W. Thomas (1991), *Journal of Moscow Physical Society* **1**, 317.

Carlitz, R. D., J. C. Collins, and A. H. Mueller (1988), *Physics Letters* **B214**, 229.

Dotson, Andrew. (2020). What IS a Cross Section pt. 2: Differential Cross Sections in Particle Physics. 

​		*Youtube.com*. https://www.youtube.com/watch?v=ojPQN86BW9o&ab_channel=AndrewDotson.

Efremov, A. V., and O. V. Teryaev (1982), *Soviet Journal of Nuclear Physics* **36**, 140.

EMC (European Muon Collaboration). (1988). A measurement of the spin asymmetry and determination of 

​		the structure function $g_1$ in deep inelastic muon-proton scattering. *Physics Letters B* **206** 2. pp 364-370.

Jaffe, Robert L. (1995). Where Does the Proton Really Get Its Spin?. *Physics Today* **48**, 9, 24-30.

Moses, Clement J., Curt A. Moyer, and Raymond A. Serway. (2005). Modern Physics. *Thomson Learning*. pp 

​		304-306.

Pagliaroli, G., C. Lujan-Peschard, M. Mitra, and F. Vissani (2012), Neutrinos from Pion Decay at Rest to Probe 

​		the Proton Strangeness in an Underground Lab. arXiv:1210.4225 [hep-ph].



