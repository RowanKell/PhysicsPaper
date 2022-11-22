# A Brief Introduction to the Proton Spin Puzzle

##### Rowan Kelleher

##### Prof. Glenn Edwards

##### Physics 264L

##### November 22, 2022

------

#### I. Introduction

​	Particle physics aims to describe the fundamental building blocks that make up every part of the universe. Physicists have developed our understanding of particles tremendously over the past few centuries, from the structure of the atom to now the structure of protons and neutrons. One subfield concerns the spin structure of the proton and aims to describe how quarks and gluons (referred to collectively as partons) make up the nucleons. The quark model of the proton began as a simple collection of three static quarks and has since evolved into a complicated model comprised of a sea of quark anti-quark pairs orbiting at high speeds inside the nucleon (see appendix I for visual representation). The first indication that the initial quark model was incorrect came in 1988 when the European Muon Collaboration (EMC) published results that disagreed with the assumptions underlying this model (EMC, 1988). The proton's three valence quarks (non-sea quarks) appeared to not contribute much of the total spin of the proton. This result spurred a global effort to describe the dynamics and structure of the proton.

​	First, the present paper provides an overview of spin for elementary particles and how the quantity can be used to describe composite particles. I will then discuss the Bjorken and Ellis-Jaffe sum rules and their relevance to nucleon spin, as well as the experiments that tested their validity. These experiments lead into the current topics in proton spin studies where the paper concludes.

------

#### II. What is Spin? From Electrons to Protons

​	Before the discovery of electron spin, physicists knew the electron had orbital angular momentum resulting from its orbit around the nucleus. In 1921 Otto Stern devised an experiment that Walther Gerlach tested in 1922 (The Stern-Gerlach experiment) that produced evidence of another source of angular momentum. In this experiment, a beam of silver atoms are sent through a non-uniform magnetic field and deposited onto a glass plate for observation (see appendix II for experimental setup diagram). The physicists used a non-uniform field to exert a force on any particle with a magnetic moment. During flight, the atoms are deflected by the non-uniform field depending on the alignment of the particle's magnetic moment. The physicists intended to show the quantization of space caused by discrete levels of alignment creating discrete collections on the observation plate. Under the assumption that the electron's magnetic moment depends solely on orbital angular momentum, they expected to see $(2l + 1)$ deposits on the plate. The silver atoms used in the experiment had no angular momentum in their ground state, corresponding to $l = 0$, providing an expectation of one discrete deposit. This expectation differs from the classical expectation as classically there is no restriction on number of deposits, suggesting an expectation of a continuous spectrum. The results did not follow either theory, however, and instead two distinct components showed on the plate. The present theory of quantized orbital angular momentum had no explanation for the two components, suggesting the electron may have another contribution to its magnetic moment (Moses et al. 2005).

​	Data from a 1927 recreation of the Stern-Gerlach experiment performed by T. E. Phipps and J. B. Taylor using hydrogen atoms produced the same result. This confirmed that there exists another source of the electron's magnetic moment. Graduate students at the University of Lieden developed a theory to explain the phenomena and suggested the magnetic moment was a result of the electron spinning on its axis (Moses et al. 2005). Although they were incorrect about the electron spinning, the name stuck and thus the theory of spin angular momentum was born. The students conjectured that the moment obeyed the same space quantization rules as orbital angular momentum, producing a formula for the number of components of spin angular momentum for a particle: $(2s + 1)$. In both the previously mentioned experiments, the results showed two discrete components which indicates the value for the spin quantum number: $s = \frac{1}{2}$ (see appendix III for result showing split components). Furthermore, they gave formulas for the z-component and magnitude of spin angular momentum:
$$
S_z = m_s \hbar \\

\vert S \vert = \sqrt{s(s+1)\hbar} = \frac{\sqrt{3}}{2} \hbar
$$
Here, $m_s = \pm \frac{1}{2}$. Because the magnitude of the spin angular momentum depends only only constants, the spin magnetic moment must be an intrinsic property of the electron (Moses et al. 2005).

​	Decades after the Stern-Gerlach experiment, the EMC created an experiment to investigate the spin makeup of the proton. The quark models of the time predicted that the three valence quarks' spin accounted for all of the proton's spin angular momentum. However, the EMC results showed that only a small portion of proton spin can be attributed to the valence quarks. Just as Gerlach found that the current models did not account for the total angular momentum of the electron, the simple quark model of the proton did not account for the total spin. In a sense, the proton spin puzzle can be thought of as a continuation of the Stern-Gerlach result at a more fundamental level. 

------

#### III. Beginnings of the Proton Spin Crisis

​	In order to discuss the theory and experiments that caused the spin crisis, one must develop a basic understanding of key concepts in scattering experiments. The 1988 EMC experiment employed deep inelastic scattering to probe the proton. Inelastic scattering refers to experiments where a particle collides with another particle, and through the transfer of momentum, "breaks" the particle into different particles. In these experiments physicists accelerate leptons (electrons and muons) to high energies and "shoot" them at a target (often a proton). Quantum electrodynamics tells us that the collision is mediated by a virtual photon produced by the lepton and absorbed by the proton. At sufficiently high energies, the virtual photon resolves an individual quark and can knock the quark out of the nucleon. However, quarks cannot exist alone and instead must be part of a hadron, or a group of two (mesons) or three (baryons) quarks, due to the strength of the strong nuclear force. Because of this, the scattered quark fragments into a new hadron. This process is described by quantum chromodynamics (QCD). We refer to scattering experiments as deep if the square of the momentum transferred from the lepton to the hadron, $Q^2$, is large. When only the incident and scattered lepton are measured in the experiment, the process is called inclusive; if at least one high energy hadron is measured in the final state (such as the hadron created by the struck quark), then the experiment is semi-inclusive. Thus we describe experiments such as that conducted by the EMC as inclusive deep inelastic scattering (DIS), and studies at COMPASS, HERMES, and JLab as semi-inclusive DIS, (SIDIS) (See appendix IV for a diagram of a typical SIDIS event). All of the kinematics of DIS experiments are contained in two quantities: the momentum transfer, $Q^2$, and the energy transferred between the lepton and the target, $\nu$. SIDIS experiments utilize more complex kinematics by introducing hadronic variables.

​	It may also be informative to understand the concepts of cross sections. A cross section (in particle physics) refers to the probability of a certain event happening. When one quantum particle approaches another, there is a non-zero probability that the two do not interact. Hence, the total cross section for a particle collision describes the probability of measuring a specific endstate given an interaction. For example, we could find a cross section that describes the probability of measuring four leptons in the final state of a proton-proton collision. The differential cross section describes the probability of measuring an endstate within a range of a kinematic variable (Dotson, 2020). Differential cross sections are important observables used to calculate asymmetries that help describe the structure of the proton. Although complex, these processes and variables are necessary for physicists to understand the proton as color confinement makes it impossible to study individual quarks or gluons

​	The next step in our story of proton spin physics occurs in 1966 when James Bjorken theorized that the operators mediating the electromagnetic interaction may obey the same rules as free-field operators. This theory led to a sum rule for DIS of polarized leptons off polarized protons and neutrons. This rule, called the Bjorken sum rule, describes the relationship between the structure functions $g_1^p$ (proton) and $g_1^n$ (neutron)  and DIS kinematics:
$$
\int_0^{\infin} \frac{Q^2}{M \nu^2}d\nu \Bigl( g_1^p(Q^2,\nu) - g_1^n(Q^2,\nu)\Bigl ) = \frac{g_A}{3} \space \space \space \space (eq\space  1)
$$
where $M$ represents the target proton's mass. There are four total structure functions that together summarize the composition of the proton. Here, $g_1$ is proportional to the polarization asymmetry, which is defined as the difference of the cross sections where nucleon and lepton spins are parallel and antiparallel. Bjorken's sum rule predicts that the cross sections contained in $g_1$ do not depend on $Q^2$, shown by the lack of $Q^2$ on the right side of the equation (Jaffe 1995). This prediction suggests that the size of the probed object doesn't affect the cross section, meaning that the quarks and gluons must behave as point-like objects. The cross section then depends only on the scaling variable $x_{Bj}$:
$$
x_{Bj} = \frac{Q^2}{2M\nu}
$$
In electron-proton DIS experiments, $x_{Bj}$ can be thought of as the fraction of the proton's momentum attributed to the quark about to be struck by the incident electron (viewed in a frame where the proton has high momentum). Bjorken scaling allows us to think of the structure functions as probability distributions in $x_{Bj}$ for the quarks inside the nucleon (Jaffe 1995). When labeled by flavor (see appendix V for a diagram showing quark flavors), we find:
$$
g_1^p(x_{Bj}) = \frac{4}{9}\Delta u (x_{Bj}) + \frac{4}{9}\Delta \bar u (x_{Bj}) + \frac{1}{9}\Delta d (x_{Bj}) + \frac{1}{9}\Delta \bar d (x_{Bj}) + \frac{1}{9}\Delta s (x_{Bj}) + \frac{1}{9}\Delta \bar s (x_{Bj}) \space \space \space \space (eq\space  2)
$$
where $\Delta u(x_{Bj})$ (and each term for the other flavors) represents the difference between up quark $x_{Bj}$ distributions for quarks with spin parallel and antiparallel to the spin of the proton. QED dictates that each term is multiplied by the square of its charge. While we do not find $Q^2$ dependence for the structure function here, it is important to note that QCD radiative effects introduce $Q^2$ dependence at high momentum transfer. Radiative effects occur when the target proton emit(s) gluon(s) that are unmeasured, altering the energy and momentum of the system. By integrating the structure function over all $x_{Bj}$ we find:
$$
\int _0 ^1 g^p _1 (x_{Bj})dx_{Bj} = \frac{1}{2}\Bigl( \frac{4}{9} \Delta u + \frac{1}{9} \Delta d + \frac{1}{9} \Delta s \Bigl)\space \space \space \space (eq\space  3)
$$
QCD flavor symmetry shows that matrix elements F and D can be related to $\Delta u - \Delta s$ and $\Delta u - \Delta d$, allowing substitutions leading to:
$$
18 \int _0 ^1 g_1 ^p (x_{Bj})dx_{Bj} = 3F + D + 2\Sigma \space \space \space (eq 4)
$$
(Jaffe 1995). Here, $\Sigma$ corresponds to the sum $\Delta u + \Delta d + \Delta s$, the contribution of all the light quarks to the proton's spin. 

​	As mentioned earlier, the simplest quark model of the proton consists of two up quarks and one down quark. In 1973, Arthur Jaffe and John Ellis theorized that unpolarized strange quarks may inhabit the nucleon. They thought that these quarks, which are much more massive than up and down quarks, may not contribute a significant amount to the proton's total spin, leading them to approximate the strange contribution as 0 in equation 3. They then calculated a value for the structure function $g_1^p$ using current experimental values for F and D as well as QCD radiative corrections:
$$
\int _0 ^\infin g_1 ^p (x_{Bj},Q^2)dx_{Bj} = 0.176 \pm 0.006   \space \space \space (eq        \space 5)
$$
(Jaffe 1995). This sum rule became known as the Ellis-Jaffe sum rule, and was tested by DIS experiments conducted by the EMC and SLAC.

​	The first DIS experiments began in the 1970s, but they could not produce measurements in low enough $x_{Bj}$ to investigate the Bjorken and Ellis-Jaffe sum rules. By the end of the decade, Vernon Hughes had begun an experiment capable of evaluating the sum rules. His group measured:
$$
\int _0 ^1 g^p _1 (x_{Bj})dx_{Bj} = 0.17 \pm 0.05
$$
While this result agreed with the Ellis-Jaffe sum rule, the scattering events occurred at low $Q^2$ leaving ambiguity about results closer to $x_{Bj} = 0$. Following this experiment at SLAC, CERN produced the next results at the super Proton Synchrotron. This experiment was conducted by the EMC where high energy muons were scattered off of unpolarized proton targets. Through decaying pions they achieved 80% polarization and energy levels as high as 100 GeV, much higher than previous experiments. Their results published in 1988 found the structure function to be much less than that measured by SLAC and the prediction from the Ellis-Jaffe sum rule:
$$
\int _0 ^1 g^p _1 (x_{Bj})dx_{Bj} = 0.126 \pm 0.018
$$
(Jaffe 1995). This measurement corresponds to $\Sigma = 0.120 \pm 0.16$, suggesting that, within error, none of the proton's spin comes from the spin of the light quarks' inside it. Additionally, the result suggested that a significant portion of the proton's spin comes from strange quark-antiquark pairs with a value of:
$$
\Delta s = -0.190 \pm 0.056
$$
(Jaffe 1995). Ellis and Jaffe had conjectured this value to be zero and thus the EMC data shows a violation of their sum rule.

​	The spin muon collaboration (SMC) succeeded the EMC and set out to further explain nucleon spin structure through measurements of the neutron structure function. SLAC followed suit and worked to measure the structure function as well, and both groups announced their first results in 1993. Assuming no contribution from the strange quark, the theoretical value (from the neutron-spin sum rule) is $\int _0 ^1 g^n _1 (x_{Bj})dx_{Bj} = -0.002 \pm 0.005$. The SMC reported an inconsistent value of $\int _0 ^1 g^n _1 (x_{Bj})dx_{Bj} = -0.08 \pm 0.04$. SLAC reported a value of $\int _0 ^1 g^n _1 (x_{Bj})dx_{Bj} = -0.022 \pm 0.011$ (Jaffe 1995). Recalling the Bjorken sum rule, we can write a new integral which is equal to $1/2$ the left side of equation 1:
$$
\int^1_0 (g(x_{Bj})_1^p - g(x_{Bj})_1^n)dx_{Bj} \space \space \space \space (eq\space  6)
$$
The results from both experiments proved consistent with expected values, confirming Bjorken's rule.

------

#### IV. Current Solutions and Problems

This section is devoted to recent developments regarding the proton's spin structure. The structure function $g_A^{(0)}$ represents the same quantity as $\Sigma$ in equation four, and differs only by convention. We can attempt to explain its small experimental value through theoretical QCD, accounting now for other effects:
$$
g_A^{(0)} = \left( \sum_q \Delta q - 3 \frac{\alpha_s}{2 \pi} \Delta g\right)_{partons} + C_{\infin}
$$
(for more on where this comes from, Aidala et al. (2013) recommends reviewing Altarelli and Ross (1988), Efremov and Teryaev (1988), Carlitz et al. (1988), Bass et al. (1991) and Bass (2005)).

The current value for $g_A^{(0)}$ (now referred to as the flavor singlet axial-charge) is approximately $0.35$. Here, $\Delta g _{partons}$ represents the spin carried by polarized gluons in the polarized proton, where $\alpha_s \Delta g ~$ is approximately constant as $Q^2 \rightarrow \infin$ (Aidala et al., 2013). $\Delta q _{partons}$ represents the spin carried by the quarks (and anti-quarks). $C_{\infin}$ relates to non-perturbative QCD processes and is discussed in section VI of Aidala et al. (2013). The remainder of the paper focuses on polarized strange contributions and polarized glue. As one can see, $g_A^{(0)}$ is much higher than the initial values of $\Sigma$ measured by the EMC as we now know that gluon spin and QCD effects contribute significantly to proton spin. Despite the higher value, we still have the majority of the proton spin unaccounted for by these factors.

​	Technological advances allow for more sophisticated SIDIS experiments, where a pion (meson with either an up anti-down or anti-up down pair) or kaon (meson with up anti- strange or anti-up strange pair) is reconstructed in the final state. These hadrons most likely contain the struck quark as we expect the struck quark to have high energy. We can use this hadron to tag the flavor of the struck quark and calculate information relevant to that quark. One can calculate the virtual photon-proton double-spin asymmetry from SIDIS data, which is shown in Aidala et al. (2013). The SMC and HERMES experiments have led this particular field of experimentation (Aidala et al. 2013). Both COMPASS and HERMES have presented results regarding the sum of strange and anti-strange polarization which is plotted in appendix VI. The results suggest that there is no evidence for polarized strangeness in the nucleon across $x_{Bj}$ values. However, these calculations depend on fragmentation functions which describe the processes that occur when a quark is knocked out of one hadron and creates a new hadron. Future improvements to these fragmentation functions could alter the calculations of $\Delta s$ (Aidala et al., 2013). A potential future approach for measuring the strange-quark polarization would involve elastic scattering of neutrinos off of protons. These experiments could avoid SU(3) assumptions, and hence would provide an independent outlook on the strangeness of the proton. Pagliaroli et al. (2012) provides a suggestion for such an experiment.

​	Another clue to solving the proton spin puzzle may lie in the polarized glue binding the proton together. Polarized proton-proton scattering gives us access to information regarding polarized gluons in the proton, and hence is an important topic of study. This sort of scattering is sensitive to the ratio of polarized to unpolarized glue, $\frac{\Delta g}{g}$, an important variable in understanding gluon contributions to proton spin. COMPASS, HERMES, and the SMC have made measurements of this fraction. These experiments reconstruct a charmed meson or high momentum hadron in the final state (see Adolph et al., 2012d and Alekseev et al., 2009c for charmed meson production and Ageev et al., 2006 for high momentum hadron studies) (Aidala et al. 2013). These studies have shown no evidence for non-zero gluon polarization in the phase space they were conducted in. See appendix VII for a table of the data. Despite this, results from CERN's RHIC provided the first non-zero measurements of polarized glue in the proton. The value of $\Delta g$ measured at these detectors would not make up for all of the missing proton spin, but would contribute a significant portion:
$$
\Delta g \approx 0.2 - 0.3
$$
(Aidala et al., 2013). This measurement concludes the discussion of proton spin physics in the present paper, but theoretical aspects of these properties are discussed in Aidala et al. (2013) Section VI.

------

#### V. Conclusion

​	Although physicists have not yet found where all of the proton's spin comes from, global studies on the matter have improved understanding significantly over the past four decades since the publishing of the EMC results. Current experiments are actively building off of the work described in this paper, and many future experiments are planned to continue the studies. Furthermore, many contributions to the proton spin were not discussed in this paper, but show promise in explaining the puzzle.

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

Hobbs, Bernie. (2017). The Standard Model of particle physics is brilliant and completely flawed. *ABC*

​		*Science*. https://www.abc.net.au/news/science/2017-07-15/the-standard-model-of-particle-physics-expl

​		ained/7670338

Jaffe, Robert L. (1995). Where Does the Proton Really Get Its Spin?. *Physics Today* **48**, 9, 24-30.

Moses, Clement J., Curt A. Moyer, and Raymond A. Serway. (2005). Modern Physics. *Thomson Learning*. pp 

​		304-306.

Pagliaroli, G., C. Lujan-Peschard, M. Mitra, and F. Vissani (2012), Neutrinos from Pion Decay at Rest to Probe 

​		the Proton Strangeness in an Underground Lab. arXiv:1210.4225 [hep-ph].

Stanford Encyclopedia of Philosophy (2019). Appendix 5: Right Experiment, Wrong Theory: The Stern-

​		Gerlach Experiment. https://plato.stanford.edu/entries/physics-experiment/app5.html

The Information Philosopher. Public Domain. https://www.mpoweruk.com/figs/Stern-Gerlach.htm

US Dept. of Energy. (2016). Zooming in on Gluon's Contribution to Proton Spin. https://www.energy.gov/sci

​	ence/np/articles/zooming-gluons-contribution-proton-spin

#### Appendix I: Evolution of the Proton Structure

![nucleon-large](/home/rowan/Documents/PhysicsPaper/nucleon-large.jpg)

The left diagram shows the original quark model where the quarks spin adds up to the proton spin ($\frac{1}{2} + \frac{1}{2} - \frac{1}{2} = \frac{1}{2}$). The left diagram shows the current model of the proton where the quarks are bound by gluons, orbit inside the proton, and are surrounded by a sea of quark anti-quark pairs. (US Dept. of Energy 2016)

#### Appendix II: Stern-Gerlach Experimental Setup

![Stern-Gerlach](/home/rowan/Documents/PhysicsPaper/Stern-Gerlach.gif)

(The Information Philosopher)

#### Appendix III: Stern-Gerlach Result

![Stern-Gerlach](/home/rowan/Documents/PhysicsPaper/Stern-Gerlach.jpg)

The right photo shows the result discussed above where there are two distinct components (Stanford Encyclopedia of Philosophy 2019)

#### Appendix IV: SIDIS Diagram

![Screenshot from 2022-11-21 23-07-35](/home/rowan/Pictures/Screenshots/Screenshot from 2022-11-21 23-07-35.png)

General example of electron-proton DIS. Initial and final electron energy (E, E') and momentum (k, k') are shown and would be measured in inclusive DIS. SIDIS experiments also reconstruct the $\pi^+$ meson (Aidala 2013).

#### Appendix V: Standard Model of Particle Physics



![2c70e6d5c36be4979a8f1be0e10d3810](/home/rowan/Documents/PhysicsPaper/2c70e6d5c36be4979a8f1be0e10d3810.jpeg)

This diagram shows the different elementary particles that make up all matter. The quarks are divided into six flavors, where each column is a different generation (Hobbs 2017).

#### Appendix VI: $x \Delta s$ Results from COMPASS and HERMES

![Screenshot from 2022-11-21 23-18-26](/home/rowan/Pictures/Screenshots/Screenshot from 2022-11-21 23-18-26.png)

(Aidala 2013)

#### Appendix VII: $\Delta g/g$ Data From Various Experiments

![Screenshot from 2022-11-21 23-22-41](/home/rowan/Pictures/Screenshots/Screenshot from 2022-11-21 23-22-41.png)

(Aidala 2013)
