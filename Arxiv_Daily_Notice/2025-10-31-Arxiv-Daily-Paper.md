# Showing new listings for Friday, 31 October 2025
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['AGN', 'active galactic nuclei', 'outflow', 'Feedback', 'quenching', 'IFU', 'Hot DOG', 'Obscured AGN', 'molecular gas', 'inoized gas', 'Little Red Dot']


Excluded: []


### Today: 38papers 
#### Pulsar Detection with Deep Learning
 - **Authors:** Manideep Pendyala
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/2510.25774

 - **Pdf link:** https://arxiv.org/pdf/2510.25774

 - **Abstract**
 Pulsar surveys generate millions of candidates per run, overwhelming manual inspection. This thesis builds a deep learning pipeline for radio pulsar candidate selection that fuses array-derived features with image diagnostics. From approximately 500 GB of Giant Metrewave Radio Telescope (GMRT) data, raw voltages are converted to filterbanks (SIGPROC), then de-dispersed and folded across trial dispersion measures (PRESTO) to produce approximately 32,000 candidates. Each candidate yields four diagnostics--summed profile, time vs. phase, subbands vs. phase, and DM curve--represented as arrays and images. A baseline stacked model (ANNs for arrays + CNNs for images with logistic-regression fusion) reaches 68% accuracy. We then refine the CNN architecture and training (regularization, learning-rate scheduling, max-norm constraints) and mitigate class imbalance via targeted augmentation, including a GAN-based generator for the minority class. The enhanced CNN attains 87% accuracy; the final GAN+CNN system achieves 94% accuracy with balanced precision and recall on a held-out test set, while remaining lightweight enough for near--real-time triage. The results show that combining array and image channels improves separability over image-only approaches, and that modest generative augmentation substantially boosts minority (pulsar) recall. The methods are survey-agnostic and extensible to forthcoming high-throughput facilities.
#### Tidally driven inertial waves enhance eccentricity damping and spin evolution in planets and stars
 - **Authors:** Janosz W. Dewberry
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Earth and Planetary Astrophysics (astro-ph.EP)
 - **Arxiv link:** https://arxiv.org/abs/2510.25812

 - **Pdf link:** https://arxiv.org/pdf/2510.25812

 - **Abstract**
 Tidal interactions influence the orbital motions of binary star systems and extrasolar planets alike. Tides also affect stellar and planetary rotation rates. We demonstrate that in addition to altering spin synchronization and pseudosynchronization, tidally driven inertial waves in the convective envelopes of low-mass stars and gas giant planets can enhance tidal eccentricity damping. Analytically, we find that eccentricity damping by inertial waves can be orders of magnitude faster than equilibrium tides, independent of any eddy viscosity prescription. We use simplified numerical experiments to demonstrate this enhancement, and to explore the effects of different mixing length treatments of convective turbulence, as well as a spin-down torque from magnetic braking. These calculations demonstrate that tidally driven inertial waves can produce an extended cool core of nearly circular binaries, helping to reconcile a longstanding discrepancy between observed and predicted main-sequence binary circularization. Our calculations additionally suggest that tidally driven inertial waves may leave identifiable signatures in the ratios of orbital to rotation periods for stellar binaries, including synchronous and sub-synchronous rotation periods reminiscent of populations identified in Kepler, TESS, and Gaia data.
#### The Ray Tracing Sampler: Bayesian Sampling of Neural Networks for Everyone
 - **Authors:** Peter Behroozi
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/2510.25824

 - **Pdf link:** https://arxiv.org/pdf/2510.25824

 - **Abstract**
 We derive a Markov Chain Monte Carlo sampler based on following ray paths in a medium where the refractive index $n(x)$ is a function of the desired likelihood $\mathcal{L}(x)$. The sampling method propagates rays at constant speed through parameter space, leading to orders of magnitude higher resilience to heating for stochastic gradients as compared to Hamiltonian Monte Carlo (HMC), as well as the ability to cross any likelihood barrier, including holes in parameter space. Using the ray tracing method, we sample the posterior distributions of neural network outputs for a variety of different architectures, up to the 1.5 billion-parameter GPT-2 (Generative Pre-trained Transformer 2) architecture, all on a single consumer-level GPU. We also show that prior samplers including traditional HMC, microcanonical HMC, Metropolis, Gibbs, and even Monte Carlo integration are special cases within a generalized ray tracing framework, which can sample according to an arbitrary weighting function. Public code and documentation for C, JAX, and PyTorch are available at this https URL
#### Unveiling Extended Components of 'Little Red Dots' in Rest-Frame Optical
 - **Authors:** Yiyang Zhang, Xuheng Ding, Lilan Yang, Erini Lambrides, Hollis Akins, Andrew J. Battisti, Caitlin M. Casey, Chang-hao Chen, Isa Cox, Andreas Faisst, Maximilien Franco, Aryana Haghjoo, Luis C. Ho, Kohei Inayoshi, Shuowen Jin, Mitchell Karmen, Anton M. Koekemoer, Jeyhan S. Kartaltepe, Kai Liao, Ghassem Gozaliasl, Masafusa Onoue, Vasily Kokorev, Namrata Roy, R. Michael Rich, John D. Silverman, Takumi S. Tanaka, Bei You, Hassen M. Yesuf, Jorge A. Zavala
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.25830

 - **Pdf link:** https://arxiv.org/pdf/2510.25830

 - **Abstract**
 Recent JWST observations have revealed a population of red, compact, high-redshift objects called 'Little Red Dots'(LRD), whose host components have remained largely unconstrained, possibly due to their extreme compactness. Current morphological studies have been limited by small samples, as well as by insufficient imaging depth, which may not allow reliable separation between point-like and extended components, leaving the existence and properties of extended components in LRD largely unconstrained. Here, we perform the image stacking analysis of 217 LRDs in four NIRCam bands, representing the largest and homogeneous sample observed from COSMOS-Web survey to date. Our results reveal an unambiguous detection of faint extended emission in the F444W band, with a typical size of ~200 parsecs and magnitude of ~27.7 AB at z~6.5. We perform four-band photometric SED fitting based on galaxy templates and derive a stellar mass of 8.91+-~0.1 logM_sun. Given this stellar mass, the host galaxy is compact, i.e., ~2.5 times smaller than star-forming populations at similar mass, and the typical black hole mass of LRDs is elevated by ~1.5 dex above the local MBH-M* relation. This work provides direct observational evidence for the existence of LRD host galaxies and offers crucial insights into the growth of the host galaxy and the co-evolution of galaxies and their black holes within the first billion years after the Big Bang.
#### Demystifying flux eruptions: Magnetic flux transport in magnetically arrested disks
 - **Authors:** Jonatan Jacquemin-Ide, Mitchell C. Begelman, Beverly Lowell, Matthew Liska, Jason Dexter, Alexander Tchekhovskoy
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2510.25842

 - **Pdf link:** https://arxiv.org/pdf/2510.25842

 - **Abstract**
 Magnetically arrested disks (MADs) are a compelling model for explaining variability in low-luminosity active galactic nuclei (AGN), including horizon-scale outbursts like those observed in Sagittarius A*. MADs experience powerful flux eruptions-episodic ejections of magnetic flux from the black hole horizon-that may drive the observed luminosity variations. In this work, we develop and validate a new formalism describing large-scale magnetic field transport in general relativistic magnetohydrodynamic simulations of MADs with geometrical thicknesses of $h/R=0.1$ and $h/R=0.3$. We introduce a net flux transport velocity, $v_\Phi$, which accounts for both advective and diffusive processes. We show that MADs maintain a statistical quasi-steady state where advection and diffusion nearly balance. Flux eruptions appear as small deviations from this equilibrium, with $v_\Phi/V_k\ll1$, where $V_k$ is the local Keplerian velocity. Using this framework, we analytically derive a recurrence timescale for flux eruptions, $t_{\rm rec}\sim1500\, r_g/c$. This timescale closely matches simulation results. The smallness of $v_\Phi$ explains the long recurrence times of flux eruptions compared to other system timescales. We also take a closer look at the diffusion of the magnetic field by performing the first measurement of turbulent resistivity in MADs. We then estimate the turbulent magnetic Prandtl number, defined as the ratio of turbulent viscosity to turbulent resistivity. We find $\mathcal{P}_m\sim3$, consistent with shearing-box simulations of magneto rotational instability-driven turbulence. While flux eruptions excite large-scale non-axisymmetric modes and locally enhance turbulent resistivity, magnetic field diffusion is dominated by smaller-scale turbulent motions. These results provide new insight into the nature of AGN variability and the fundamental physics of magnetic field transport.
#### Figuring Out Gas & Galaxies In Enzo (FOGGIE) XI: Circumgalactic O VI Emission Traces Clumpy Inflowing Recycled Gas
 - **Authors:** Cassandra Lochhaas, Molly S. Peeples, Brian W. O'Shea, Jason Tumlinson, Lauren Corlies, Vida Saeedzadeh, Nicolas Lehner, Anna C. Wright, Jessica K. Werk, Cameron W. Trapp, Ramona Augustin, Ayan Acharyya, Britton D. Smith
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.25844

 - **Pdf link:** https://arxiv.org/pdf/2510.25844

 - **Abstract**
 The circumgalactic medium (CGM) is host to gas flows into and out of galaxies and regulates galaxy growth, but the multiphase, diffuse gas in this region is challenging to observe. We investigate the properties of gas giving rise to O VI emission from the CGM that upcoming missions, such as the Aspera SmallSat, will be able to map in local galaxies. We use the FOGGIE simulations to predict the O VI emission from edge-on galaxies across the redshift range $z=1\rightarrow0$. O VI emission is brightest surrounding small, clumpy structures near the galaxy where the gas density is high. Most of the O VI surface brightness originates from collisionally ionized, $T\sim10^{5.5}$ K, inflowing gas and is not preferentially aligned with the major or minor axis of the galaxy disk. Simulated galaxies with higher halo masses, higher median CGM gas density, and higher star formation rates produce brighter and more widespread O VI emission in their CGM. We show that while O VI emission primarily originates in inflowing gas, turning off outflows in a simulation without star formation feedback eliminates most of the O VI emission. Enrichment from feedback is necessary to mix with the inflowing gas and allow it to glow in O VI. Collectively, our findings point towards a picture where O VI emission traces warm, ionized envelopes of cooler clouds that are accreting onto the galaxy in a metal-enriched galactic fountain. Finally, we show that the detection limit of Aspera is sufficient to detect O VI emission tens of kpc from the galaxy center for $\sim L^\star$ galaxies.
#### Cosmological Simulations of Weakly Collisional Plasmas with Braginskii Viscosity in Galaxy Clusters
 - **Authors:** Tirso Marin-Gilabert, Ulrich P. Steinwandel, Milena Valentini, John A. ZuHone, Klaus Dolag
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Cosmology and Nongalactic Astrophysics (astro-ph.CO); Astrophysics of Galaxies (astro-ph.GA); Plasma Physics (physics.plasm-ph)
 - **Arxiv link:** https://arxiv.org/abs/2510.25847

 - **Pdf link:** https://arxiv.org/pdf/2510.25847

 - **Abstract**
 We present the implementation of an anisotropic viscosity solver within the magnetohydrodynamics (MHD) framework of the TreeSPH code OpenGadget3. The solver models anisotropic viscous transport along magnetic field lines following the Braginskii formulation and includes physically motivated limiters based on the mirror and firehose instability thresholds, which constrain the viscous stress in weakly collisional plasmas. To validate the implementation, we performed a suite of standard test problems -- including two variants of the sound-wave test, circularly and linearly polarized Alfven waves, fast magnetosonic wave, and the Kelvin-Helmholtz instability -- both with and without the plasma-instability limiters. The results show excellent agreement with the AREPO implementation of a similar anisotropic viscosity model (Berlok et al. 2019), confirming the accuracy and robustness of our method. Our formulation integrates seamlessly within the individual adaptive timestepping framework of OpenGadget3, avoiding the need for subcycling. This provides efficient and stable time integration while maintaining physical consistency. Finally, we applied the new solver to a cosmological zoom-in simulation of a galaxy cluster, demonstrating its capability to model anisotropic transport and plasma microphysics in realistic large-scale environments. Our implementation offers a versatile and computationally efficient tool for studying anisotropic viscosity in magnetized astrophysical systems.
#### Spiral Structure Diversity in Milky Way Analogs from TNG50: The Role of Gas and Disk Dynamics
 - **Authors:** Soumavo Ghosh, Elena D'Onghia
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.25848

 - **Pdf link:** https://arxiv.org/pdf/2510.25848

 - **Abstract**
 The generation of spiral arms and the mechanisms controlling their properties within a realistic cosmological framework - the complete understanding is still beyond our grasp. Using a statistically significant sample of Milky Way- and Andromeda-like (MW/M31) analogs from the high-resolution TNG50 cosmological simulation, we carry out the first systematic investigation of spiral-arm formation, their observable properties, and the underlying physical drivers. The selected analogs predominantly exhibit two-armed ($m = 2$) spirals in both stars and gas, while the gaseous disks often display stronger, more tightly wound, and multi-armed patterns ($m>2$). Spiral features appear across stellar populations of different ages, confirming their density-wave nature and producing coherent spirals in both metallicity and mean stellar age distributions-consistent with recent Gaia observations of the Milky Way. Our analysis reveals a diverse dynamical scenario for spiral generation: gas content, disk coldness, and shear jointly regulate the growth and morphology of spiral perturbations. We find that the gas content and the dynamical coldness of the disk jointly regulate spiral growth: galaxies with higher gas fractions and colder disks develop more prominent spirals. The measured relation between spiral pitch angle and disk shear shows significant scatter around the analytic prediction, likely due to the combined influence of bars, gas inflows, and feedback. These results demonstrate that spiral density waves can persist in fully cosmological disks, linking internal dynamical processes to galaxy assembly and offering testable predictions for present and future surveys such as JWST and Roman.
#### WOCS XCIII: NGC 7789: the Evolution of Li, Stellar Rotation, and Extended Main Sequence Turnoffs
 - **Authors:** Barbara J. Anthony-Twarog, Samantha W. Brunker, Constantine P. Deliyannis, Evan Rich, Aaron Steinhauer, Qinghui Sun, Bruce A. Twarog
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2510.25862

 - **Pdf link:** https://arxiv.org/pdf/2510.25862

 - **Abstract**
 Precision UBVRI photometry of NGC 7789 is combined with Gaia data to map reddening variations across the cluster face. HYDRA spectra, Gaia astrometry, and isochrone fitting constrain the absolute reddening, apparent modulus, and age to E(B-V) = 0.30 +/- 0.02, (m-M)=12.51 +/- 0.06, and 1.46 +/- 0.02 Gyr for [Fe/H] between -0.2 and solar; the spectroscopic [Fe/H] = -0.13 +/- 0.068 (MAD) from 156 single-star members. Corrections for variable reddening reduce the scatter in the unevolved main sequence below the turnoff. A(Li) is derived for only single star members from the G-dwarf Li-Plateau to the tip of the red giant branch. Giants separate into two distinct groups, probable first-ascent giants with detectable Li that declines with evolution toward the red giant tip and stars within the clump and the asymptotic giant branch which only exhibit upper limits. A(Li) structure from the turnoff to the unevolved main sequence, including the Li-Dip, and the presence of an extended color spread among the upper main sequence stars are attributed to the V_ROT distribution, indicating the wall of the Li-Dip as the true hot boundary of the Kraft break. Differences in the color-magnitude diagram topology of NGC 7789 and NGC 752 are explored and attributed to differences in the individual cluster V_ROT distributions. Prior indications that main sequence stars more massive than the Li-Dip evolve redward across the Li-Wall, undergoing rotational spindown and Li depletion like stars within the Li-Dip, are confirmed.
#### Chemical separation of stellar populations: analytic solutions for chemical evolution models with metallicity-dependent yields
 - **Authors:** Jason L. Sanders
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.25876

 - **Pdf link:** https://arxiv.org/pdf/2510.25876

 - **Abstract**
 Stellar abundances of elements with production channels that are metallicity-dependent (most notably aluminium) have provided an empirical route for separating different Galactic components. We present 'single-zone' analytic solutions for the chemical evolution of galaxies when the stellar yields are metallicity-dependent. Our solutions assume a constant star formation efficiency, a constant mass-loading factor and that the yields are linearly dependent on the interstellar medium abundance (with the option of a saturation of the yields at high metallicity). We demonstrate how the metallicity dependence of the yields can be mathematically considered as a system-dependent delay time (approximately equal to the system's depletion time) that, when combined with system-independent delay times arising from stellar evolutionary channels, produces the separation of different systems based on their star formation efficiency and mass-loading factor. The utility of the models is highlighted through comparisons with data from the APOGEE spectroscopic survey. We provide a comprehensive discussion of the chemical evolution models in the [Al/Fe]-[Mg/Fe] plane, a diagnostic plane for the separation of in-situ and accreted Galactic components. Extensions of the models are presented, allowing for the modelling of more complex behaviours largely through the linear combination of the presented simpler solutions.
#### A three-dimensional reconstruction of the interstellar magnetic field toward a star-forming region
 - **Authors:** Katia Ferrière, Ludovic Montier, Jean-Sébastien Carrière
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.25879

 - **Pdf link:** https://arxiv.org/pdf/2510.25879

 - **Abstract**
 Context. The polarized thermal emission from interstellar dust offers a valuable tool for probing both the dust and the magnetic field in the interstellar medium (ISM). However, existing observations only yield the total amount of dust emission along the line of sight (LoS), with no information on its LoS distribution. Aims. We present a new method designed to give access to the LoS distribution of the dust emission, both in terms of intensity and polarization. Methods. We relied on three kinematic gas tracers (HI, 12CO, and 13CO emission lines) to identify the different clouds present along the LoS. We decomposed the measured intensity of the dust emission, $I_d$, into separate contributions from these clouds. We performed a similar decomposition of the measured Stokes parameters for linear polarization, $Q_d$ and $U_d$, to derive the polarization parameters of the different clouds, and from this we inferred the clouds' magnetic field orientations. Results. We applied our method to a $3~{\rm deg}^2$ region of the sky, centered on $(l,b) = (139°30',-3°16')$ and exhibiting signs of star formation activity. We found this region to be dominated by an extended and bright cloud with nearly horizontal magnetic field, as expected from the nearly vertical polarization angles measured by Planck. More importantly, we detected the presence of two smaller, depolarizing molecular clouds with very different magnetic field orientations in the plane of the sky ($\simeq 65°$ and $\simeq 45°$ from the horizontal). This is a novel and viable result, which cannot be directly read off the Planck polarization maps. Conclusions. The application of our method to the G139 region convincingly demonstrates the need to complement 2D polarization maps with 3D kinematic information when looking for reliable estimates of magnetic field orientations.
#### Mitigating gain calibration errors from EoR observations with SKA1-Low AA*
 - **Authors:** Eeshan Beohar, Abhirup Datta, Anshuman Tripathi, Samit Kumar Pal, Rashmi Sagar
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2510.25886

 - **Pdf link:** https://arxiv.org/pdf/2510.25886

 - **Abstract**
 The observation of the redshifted 21-cm signal from neutral hydrogen is a promising probe for understanding the phase transition of the early universe and its evolution during the Cosmic Dawn and the Epoch of Reionisation (EoR). One of the primary obstacles to the statistical detection of the target signal is the presence of residual foreground, which arises from gain calibration errors. Previous studies have shown that gain calibration errors as small as 0.01% can lead to a biased interpretation of the observed signal power spectrum estimation, by nearly an order of magnitude. A recent study further highlights that to retrieve astrophysical parameters accurately, the threshold gain calibration error should be lower than 0.01%. In this work, we develop a post-calibration mitigation strategy that combines foreground subtraction techniques with foreground avoidance to address residual contamination arising from gain calibration errors. We use an end-to-end pipeline 21cmE2E to simulate a realistic sky model and telescope configuration within the 138-146 MHz frequency range. To assess the impact of residual antenna-based gain calibration errors, we perform a detailed power spectrum analysis across several threshold levels. Our analysis shows that the extraction of the target signal over the wavenumber range $0.05 \leq k \leq 0.5$ Mpc$^{-1}$ is possible with a threshold gain calibration error of 1%, although with a significant SNR tradeoff on larger scales. Moreover, this work also offers a comparative assessment of foreground removal and avoidance techniques in the context of future SKA1-Low AA* observations.
#### On the Universality of the Relation Between Magnetic Fields and Star Formation in Galaxies
 - **Authors:** Davide Belfiori, Sergio Martin-Alvarez, Enrique Lopez-Rodriguez, Rosita Paladino
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.25909

 - **Pdf link:** https://arxiv.org/pdf/2510.25909

 - **Abstract**
 The interstellar medium (ISM) is permeated by magnetic fields that affect gas dynamics and star formation. These fields correlate with supernova (SN)-driven turbulence, but whether the scaling is universal across galaxy properties, ISM phases, and energy budgets remains unclear. We quantify the dependence of magnetic fields on star formation activity including both regular and starburst galaxies. We analyse 19 spiral disks from the cosmological RTnsCRiMHD Azahar suite, deriving line-of-sight integrated maps to measure median magnetic-field strength ($B$), specific energies (thermal, turbulent, magnetic, and cosmic-ray), and star formation rate (SFR), star formation surface density ($\Sigma_{\mathrm{SFR}}$) and specific SFR (sSFR). We find an almost universal magnetic-field-SFR scaling with slope $\alpha \approx 0.2$-$0.3$ across galaxy mass and ISM phases. The $B$-$\Sigma_{\mathrm{SFR}}$ slope ($\alpha \approx 1/3$) supports an SN-driven, turbulence-regulated origin. Neutral gas is generally turbulence-dominated and in near equipartition with magnetic energy for systems with sSFR $\gtrsim 0.1$ Gyr$^{-1}$ and SFR $\gtrsim 1$ $M_\odot$ yr$^{-1}$. The simulated trends match observations with similar slopes ($\alpha \approx 0.25$-$0.35$), indicating that SN-driven turbulence is the main amplification mechanism behind the near-universal $B$-SFR relation.
#### TRIShUL: Technique for Reconstructing magnetic Interstellar Structure Using starLight polarization
 - **Authors:** Namita Uppal, Konstantinos Tassis, Vasiliki Pavlidou, Vincent Pelgrims, Myrto Falalaki
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2510.25911

 - **Pdf link:** https://arxiv.org/pdf/2510.25911

 - **Abstract**
 We present a novel technique to decompose line-of-sight (LOS) stellar polarization as a function of distance, aimed at reconstructing three dimensional (3D) plane-of-sky (POS) magnetic structures in the interstellar medium (ISM). The method assumes that the observed polarization arises from discrete, thin dust layers located at varying distances along the LOS. Using a simple frequentist framework, it identifies structural changes in the distance-sorted cumulative Mahalanobis distance of Stokes parameters (q and u) to detect the locations of dust layers and estimate their associated physical properties (parallax and Stokes parameters) necessary to construct 3D maps. We benchmark the method using mock datasets representative of high-Galactic-latitude regions, incorporating realistic Gaia parallax uncertainties and polarization expected from the upcoming Pasiphae survey. Tests show that the method reliably recovers dust cloud distances and polarization properties when the polarization exceeds 0.1%, and the effective background-star fraction is greater than 10% in samples of about 345 stars. The dependence on background fraction decreases as the intrinsic polarization amplitude of the dust field increases. We apply our method to existing polarization data from two illustrative sightlines, one at intermediate-high Galactic latitude and one near the Galactic plane, with known tomographic solutions, finding excellent agreement with the literature and demonstrating its accuracy across both regions. Comparing with the BISP-1 approach, both methods effectively recover dust cloud properties, but our approach is prior-free and computationally more efficient in determining the optimal number of clouds along the LOS. These advantages make it flexible and broadly applicable for multi-layer dust cloud reconstruction for the upcoming era of large-scale stellar polarization surveys.
#### Lyman-$α$ radiation pressure regulates star formation efficiency
 - **Authors:** D. Manzoni, A. Ferrara
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.25950

 - **Pdf link:** https://arxiv.org/pdf/2510.25950

 - **Abstract**
 Order-unity star formation efficiencies (SFE) in early galaxies may explain the overabundance of bright galaxies observed by JWST at high redshift. Here we show that Lyman-$\alpha$ (Ly$\alpha$) radiation pressure limits the gas mass converted into stars, particularly in primordial environments. We develop a shell model including Ly$\alpha$ feedback, and validate it with one-dimensional hydrodynamical simulations. To account for Ly$\alpha$ resonant scattering, we adopt the most recent force multiplier fits, including the effect of Ly$\alpha$ photon destruction by dust grains. We find that, independently of their gas surface density $\Sigma_g$, clouds are disrupted on a timescale shorter than a free-fall time, and even before supernova explosions if $\Sigma_g \gtrsim 10^3\,M_{\odot}\ \rm pc^{-2}$. At $\log(Z/Z_{\odot}) = -2$, relevant for high-redshift galaxies, the SFE is $0.01 \lesssim \hat{\epsilon}_{*} \lesssim 0.66$ for $10^3 \lesssim\Sigma_g [M_{\odot}\ \rm pc^{-2}] \lesssim 10^5$. The SFE is even lower for decreasing metallicity. Near-unity SFEs are possible only for extreme surface densities, $\Sigma_{g} \gtrsim 10^5\;M_{\odot}\ \rm pc^{-2}$, and near-solar metallicities. We conclude that Ly$\alpha$ radiation pressure severely limits a possible extremely efficient, feedback-free phase of star formation in dense, metal-poor clouds.
#### Gravitational-Wave Constraints on Neutron-Star Pressure Anisotropy via Universal Relations
 - **Authors:** Victor Guedes, Siddarth Ajith, Shu Yan Lau, Kent Yagi
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); General Relativity and Quantum Cosmology (gr-qc)
 - **Arxiv link:** https://arxiv.org/abs/2510.26042

 - **Pdf link:** https://arxiv.org/pdf/2510.26042

 - **Abstract**
 Neutron stars may exhibit pressure anisotropy arising from various physical mechanisms, such as elasticity, magnetic fields, viscosity, and superfluidity. We compute the tidal deformability and the $f$-mode oscillation frequency of anisotropic neutron stars using a phenomenological quasi-local model characterized by a single dimensionless anisotropy parameter. We find that while the relation between the tidal deformability and the $f$-mode frequency depends on the degree of anisotropy, it remains largely insensitive to variations in the equation of state (the relation between radial pressure and energy density) for a fixed anisotropy parameter, similar to the isotropic case. Leveraging this anisotropy-dependent universal relation within a statistical framework, we place constraints on the anisotropy parameter using both the gravitational wave observation of GW170817 and simulated data for a GW170817-like event observed by a future network of detectors. We find that the anisotropy parameter can be constrained to order unity with current data, and the bounds remain comparable with future detector sensitivities. Importantly, these constraints are only weakly affected by uncertainties in the neutron-star equation of state.
#### Accretion rates of stellar-mass compact objects embedded in AGN discs
 - **Authors:** Cheng-Liang Jiao, Liying Zhu, Er-gang Zhao, Jia Zhang
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26111

 - **Pdf link:** https://arxiv.org/pdf/2510.26111

 - **Abstract**
 Stellar-mass compact objects (COs) embedded in active galactic nucleus (AGN) discs are commonly assumed to accrete via Bondi or Bondi-Hoyle-Lyttleton (BHL) prescriptions, neglecting gas angular momentum. We show that differential rotation in AGN discs can impart non-negligible angular momentum, in which case accretion proceeds through a viscous disc rather than Bondi/BHL flow. Our model provides a new framework estimating the CO accretion rate as $\dot{M}_\mathrm{CO} = \min\{\dot{M}_\mathrm{vis}, \dot{M}_\mathrm{BHL}\}$, where the viscous rate $\dot{M}_\mathrm{vis}$ accounts for gas--CO relative motion decomposed into a local gradient term (due to differential rotation) and bulk motion (from differing orbital parameters). This rate can be expressed as $\dot{M}_\mathrm{vis} = \alpha \xi (r_\mathrm{H}/r_\mathrm{BHL})^3\dot{M}_\mathrm{BHL}$, where $\xi$ is a coefficient of order unity. It can also be approximately scaled to the global AGN accretion rate as $\dot{M}_\mathrm{vis} \propto \dot{M}_1$, with the scaling coefficients in both forms determined by the specific dynamical configuration. The accretion is viscosity-limited when $q > [\alpha \xi(1+\mathcal{M}^2)^{3}/3]^{1/2} h^3$, where $q$ is the mass ratio between the CO and the supermassive black hole, $\alpha$ the viscosity parameter, $\mathcal{M}$ the Mach number of the bulk relative motion, and $h$ the aspect ratio of the AGN disc. In thin AGN discs this condition is satisfied for most stellar-mass or more massive COs. Our framework also naturally allows for the inclusion of established outflow corrections, thereby enabling a more realistic treatment of super-Eddington flows. Our formulation thus improves upon Bondi/BHL prescriptions and offers a more physically motivated basis for studying CO evolution in AGN environments.
#### Multi-Faceted Emission Properties of PSR J2129+4119 Observed with FAST
 - **Authors:** Habtamu Menberu Tedila, Di Li, Pei Wang, Rai Yuen, Ziwei Wu, Shijun Dang, Jianping Yuan, Na Wang, Marilyn Cruces, Jun Shuo Zhang, Juntao Bai, De Zhao, FAST Collaboration
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2510.26209

 - **Pdf link:** https://arxiv.org/pdf/2510.26209

 - **Abstract**
 We present a detailed single-pulse study of the long-period pulsar PSR J2129+4119 using high-sensitivity FAST observations. Despite locating well below the traditional death line, the pulsar exhibits sustained and multi-modal emission behavior, including nulls, weak pulses, regular emission, and occasional bright pulses. The nulling fraction is measured to be $8.13\% \pm 0.51\%$, with null durations typically under four pulse periods. Fluctuation spectral analysis reveals both phase-modulated subpulse drifting and intermittent beat-like modulation. At the same time, polarization profiles show high linear polarization and stable polarization position angle (PPA) swings consistent with a near-tangential sightline geometry. Quasi-periodic microstructures are detected in 11.54\% of regular pulses, with a mean periodicity and width of 4.57 ms and 4.30 ms, respectively. A well-defined scintillation arc in the secondary spectrum confirms the presence of a localized scattering screen. These results indicate that PSR J2129+4119 remains magnetospherically active and coherently emitting despite its low energy loss rate, offering key insights into pulsar emission physics near the death line.
#### Rotation Measure Analysis of Shocks and Sloshing Fronts in a Galaxy Cluster Merger Simulation
 - **Authors:** Jia-Rou Liou, Alvina Y. L. On, H. -Y. Karen Yang, J. A. ZuHone
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Cosmology and Nongalactic Astrophysics (astro-ph.CO); Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26218

 - **Pdf link:** https://arxiv.org/pdf/2510.26218

 - **Abstract**
 Recent observations of the Fornax cluster show depolarization signatures on megaparsec scales, which may be associated with shocks and/or sloshing motions during cluster merger and/or in-fall. To investigate the possible reasons behind the depolarization, we carry out analytical and full polarized radiative transfer (PRT) calculations of radio point sources behind a merging galaxy cluster simulated using the FLASH code. With uniform background light, we analyzed the rotation measure (RM) morphology near the shock front and the cluster center, where sloshing cold fronts appear. For the shock scenario, we find a local RM enhancement by $\sim56\%$ behind the shock front on megaparsec scales, arising from the compression of hot gas and magnetic field lines. Behind the sloshing cold front, the cluster center shows decrement in RM magnitude by $\sim23.3\%$, as a result of the cancellation effect of randomly-oriented magnetic fields induced by sloshing-driven turbulence. We find that beam depolarization increases behind shock fronts and across sloshing cold fronts, indicating enhanced magnetic field fluctuations across the plane of the sky in both scenarios. By fully accounting for all radiative transfer coefficients in the PRT calculations, the uniform background light becomes more depolarized near the cluster center, with the effect growing more pronounced as background intensity decreases. This suggests that synchrotron emission and Faraday rotation of the intracluster medium can significantly influence the polarization of background sources.
#### The role of black hole feedback on galaxy star formation and the degeneracy with halo quenching
 - **Authors:** Hao Fu, Francesco Shankar, Feng Yuan, Daniel Roberts, Lumen Boco, Andrea Lapi, Pablo Corcho-Caballero, Mohammadreza Ayromlou, Antonis Georgakakis, Brivael Laloux, Iván Muñoz Rodríguez, Yingjie Peng
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26305

 - **Pdf link:** https://arxiv.org/pdf/2510.26305

 - **Abstract**
 The interplay between the accretion of supermassive black holes (SMBHs) and the stellar mass growth of the host galaxies is still a matter of hot debate. The accretion of the SMBHs is expected to release energy under the form of AGNs. This energy is believed to impact the star formation activity and contribute to the quenching of galaxies. Here, we address this key unsolved issue with our cosmological semi-empirical model DECODE. In DECODE, we grow galaxies with their SFR linked to halo accretion rate distributions via abundance matching. SMBHs are evolved following the stellar mass growth of their host galaxies by assigning an accretion rate at each redshift from the empirical Eddington ratio distributions and duty cycles. We test the assumption that galaxies permanently quench when their central SMBHs approach the limit imposed by the observed $M_{\rm BH} - \sigma_\star$ relation, as a proxy of SMBH disruptive feedback. We find that simply imposing the $M_{\rm BH} - \sigma_\star$ condition is sufficient to generate a fraction of quenched galaxies consistent with current data, including the newest ones from Euclid. In addition, our minimal, data-driven model, also predicts SMBH scaling relations consistent in slope and normalisation with those observed, and an $M_{\rm BH} - M_\star$ relation weakly evolving with redshift. The model also naturally generates SMBH accretion rates peaking within 1 Gyr of their host SFHs. We note that all the main predictions on galaxy quenched fractions and SMBH growth histories and scaling relations are degenerate with those expected in a halo quenching model. The comprehensive data-driven model presented in this work represents an invaluable tool to investigate SMBH demography across time and environments in an accurate, physically motivated manner, ideally suited to rapidly explore the implications from large surveys, such as Euclid and Rubin-LSST.
#### Apsidal Motion in O-Star Binaries: GENEC rotating binary models put to the k2-test
 - **Authors:** Sophie Rosu, Luca Sciarini, Sylvia Ekström, Raphaël Hirschi
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2510.26306

 - **Pdf link:** https://arxiv.org/pdf/2510.26306

 - **Abstract**
 Unveiling massive stars' internal structure and the physical origin and efficiency of the internal mixing processes? It is now possible using the apsidal motion rate in close eccentric binaries! The apsidal motion rate depends on the tidal interactions occurring between the stars and is proportional to k2, a measure of the star's inner density profile. Confronting standard stellar models with observations reveals the famous k2-discrepancy: models predict too high a k2 for the stars, that is to say, stars with too low a density contrast between their core and envelope. We built bespoke GENEC stellar evolution models including tidal mixing for the twin massive binary HD 152248. The models reveal the instabilities allowing to reproduce the stellar density profiles: advecto-diffusive models better reproduce k2 than magnetic models. A large overshooting is necessary to converge towards the observed k2, yet alone is not sufficient. While a change in metallicity or mass-loss rate has no significant impact on k2, a larger initial helium abundance allows us to better reproduce the k2. Yet, a super-solar helium abundance is not observationally supported. Our analyses highlight the need for a process in the stars that slows down the radial expansion.
#### Shock-driven heating in the circumnuclear star-forming regions of NGC 7582: Insights from JWST NIRSpec and MIRI/MRS spectroscopy
 - **Authors:** Oscar Veenema, Niranjan Thatte, Dimitra Rigopoulou, Ismael García-Bernete, Almudena Alonso-Herrero, Anelise Audibert, Enrica Bellocchi, Andrew J. Bunker, Steph Campbell, Francoise Combes, Ric I. Davies, Daniel Delaney, Fergus Donnan, Federico Esposito, Santiago García-Burillo, Omaira Gonzalez Martin, Laura Hermosa Muñoz, Erin K. S. Hicks, Sebastian F. Hoenig, Nancy A. Levenson, Chris Packham, Miguel Pereira-Santaella, Cristina Ramos Almeida, Claudio Ricci, Rogemar A. Riffel, David Rosario, Lulu Zhang
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26321

 - **Pdf link:** https://arxiv.org/pdf/2510.26321

 - **Abstract**
 We present combined JWST NIRSpec and MIRI/MRS integral field spectroscopy data of the nuclear and circumnuclear regions of the highly dust obscured Seyfert 2 galaxy NGC 7582, which is part of the sample of AGN in the Galaxy Activity, Torus and Outflow Survey (GATOS). Spatially resolved analysis of the pure rotational H$_2$ lines (S(1)-S(7)) reveals a characteristic power-law temperature distribution in different apertures, with the two prominent southern star-forming regions exhibiting unexpectedly high molecular gas temperatures, comparable to those in the AGN powered nuclear region. We investigate potential heating mechanisms including direct AGN photoionisation, UV fluorescent excitation from young star clusters, and shock excitation. We find that shock heating gives the most plausible explanation, consistent with multiple near- and mid-IR tracers and diagnostics. Using photoionisation models from the PhotoDissociation Region Toolbox, we quantify the ISM conditions in the different regions, determining that the southern star-forming regions have a high density ($n_H \sim 10^{5}$ cm$^{-3}$) and are irradiated by a moderate UV radiation field ($G_0 \sim 10^{3}$ Habing). Fitting a suite of Paris-Durham shock models to the rotational H$_2$ lines, as well as rovibrational 1-0 S(1), 1-0 S(2), and 2-1 S(1) H$_2$ emission lines, we find that a slow ($v_s \sim 10$ km/s) C-type shock is likely responsible for the elevated temperatures. Our analysis loosely favours local starburst activity as the driver of the shocks and circumnuclear gas dynamics in NGC 7582, though the possibility of an AGN jet contribution cannot be excluded.
#### Tracing the evolution of brightest galaxies and diffuse light in galaxy groups
 - **Authors:** B. Bilata-Woldeyes, J. D. Perea, J. M. Solanes
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26329

 - **Pdf link:** https://arxiv.org/pdf/2510.26329

 - **Abstract**
 We present a suite of 100 cosmologically motivated, controlled N-body simulations designed to advance the understanding of the role of purely gravitational dynamics in the early formation of low-mass galaxy groups (~ 1-5 x 10^13 M_sun). In this work, we investigate the temporal evolution of key indicators of dynamical relaxation, with particular emphasis on the secular growth of the diffuse intragroup light (IGL), the four major group galaxies, and the mass distributions of their progenitors. We also assess the diagnostic power of several magnitude gaps between top-ranked galaxies as proxies for dynamical age. As in our previous study, we compare outcomes from three group classes defined by the number of brightest group galaxies (BGGs) present at the end of the simulations. The early assembly of galaxy groups is consistent with a stochastic Poisson process at an approximately constant merger rate. Various dynamical diagnostics - including galaxy pairwise separations, velocity dispersions, and the offset of the first-ranked galaxy from the group barycentre - indicate that single-BGG groups evolve more rapidly towards virialisation than double- and especially non-BGG systems. We further find that first-ranked group members and the IGL, follow distinct growth histories, with the IGL assembled from a more numerous and systematically lower-mass population than the central object. This distinction is particularly pronounced in non-BGG systems, where about one third of the IGL originates from small galaxies, each contributing less than 5% to this component. Among the tested magnitude gaps, the difference between the first- and fourth-ranked galaxies, $\Delta M4-1$, proves a more robust indicator of dynamical age for low-mass groups than the conventional $\Delta M2-1$ gap. The $\Delta M5-1$ and $\Delta M6-1$ gaps also perform well and may be preferable in certain contexts.
#### oMEGACat. VIII. A Subpopulation Census of ω Centauri
 - **Authors:** C. Clontz, A. C. Seth, Z. Wang, M. Haeberle, M. S. Nitschai, N. Neumayer, P. J. Smith, M. Latour, A. Feldmeier-Krause, M. Libralato, A. Bellini
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26341

 - **Pdf link:** https://arxiv.org/pdf/2510.26341

 - **Abstract**
 An understanding of the assembly history of the complex star cluster Omega Centauri has long been sought after, with many studies separating the stars on the color-magnitude diagram into multiple groupings across small magnitude ranges. Utilizing the oMEGACat combined astro-photometric and spectroscopic dataset we parse 14 subpopulations from the upper red-giant branch to below the main-sequence turnoff. We combine our results with previous works to estimate the age and age spread of each population. We find that the chemically enhanced (P2) populations are all ~1 Gyr younger (~11.6 Gyr old) and have significantly higher intrinsic age spreads (0.6 Gyr) than the primordial (P1) populations (~12.6 Gyr old, 0.3 Gyr spread), with the intermediate (Im) populations falling in between the two. Additionally, we connect for the first time the Chromosome Diagram to the two-stream age-metallicity relation, allowing us to link the P1 and P2 stars to the distinct star formation tracks, proposed to be in-situ and ex-situ contributions to the cluster's assembly. Our results are consistent with some suggested formation models and rule out others but no current model can explain all observed features of the subpopulations.
#### XRISM Observations of The Prototypical Cold Front in Abell 3667
 - **Authors:** Yuki Omiya, Yuto Ichinohe, Kazuhiro Nakazawa, Hisamitsu Awaki, Dominique Eckert, Yutaka Fujita, Isamu Hatsukade, Maxim Markevitch, François Mernier, Ikuyuki Mitsuishi, Naomi Ota, Aurora Simionescu, Yuusuke Uchida, Shutaro Ueda, Irina Zhuravleva, John Zuhone
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26405

 - **Pdf link:** https://arxiv.org/pdf/2510.26405

 - **Abstract**
 We present high-resolution X-ray spectroscopy of the merging galaxy cluster Abell 3667 with \textit{XRISM}/Resolve. Two observations, targeting the cluster X-ray core and the prototypical cold front, were performed with exposures of 105 ks and 276 ks, respectively. We find that the gas in the core is blueshifted by $v_z\sim-200$ km s$^{-1}$ relative to the brightest cluster galaxy, while the low-entropy gas inside the cold front is redshifted by $v_z\sim 200$ km s$^{-1}$. As one moves further off-center across the front, the line-of-sight (LoS) velocity changes significantly, by $\Delta v_z=535^{+167}_{-154}$ km s$^{-1}$, back to the value similar to that in the core. There are no significant LoS velocity gradients perpendicular to the cluster symmetry axis. These features suggest that the gas forming the cold front is flowing in the plane oriented along the LoS, supporting an offset merger scenario in which the main cluster has passed in front of the subcluster and induced rotation of the core gas in the plane perpendicular to the sky. The region just inside the front exhibits the largest LoS velocity dispersion seen across two pointings, $\sigma_z\sim420$ km s$^{-1}$, which can be interpreted as a developing turbulence or a projection of the LoS velocity shear within the front. The large LoS velocity jump across the cold front, combined with the lack of Kelvin-Helmholtz instability on the surface of the front, suggests some mechanism to suppress it. For example, a magnetic field with $B>5\,\mu$G is required if the cold front is stabilized by magnetic draping.
#### Joint Analysis of Optical, Near-Infrared And Mid-Infrared Variability of 4 Quasars at Redshift < 1
 - **Authors:** Lin Long, Zhen-ya Zheng, Ning Jiang, Chun Xu, Jiaqi Lin, Fang-Ting Yuan, Chunyan Jiang, Ruqiu Lin, Hai-Cheng Feng, Hengxiao Guo, Xiang Ji
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26435

 - **Pdf link:** https://arxiv.org/pdf/2510.26435

 - **Abstract**
 Amid rapid advances in time-domain astronomy, multi-wavelength (e.g., optical and infrared) time-domain studies of quasars remain scarce. Here we present a systematic analysis of four quasars initially selected by their Ks-band variability amplitudes in the VISTA Variables in the V\'ıa Láctea Survey (VVV/VVVX). For these objects, we obtain complementary optical light curves from Pan-STARRS1 (PS1) and the Zwicky Transient Facility (ZTF), and W1-band light curves from the Wide-field Infrared Survey Explorer (WISE). We perform correlation analysis to study the time lags between different bands, which may be directly related to the size of the dust torus. After correcting for infrared flux contamination from the accretion disk and accounting for the redshift effect, we measure the Ks-optical and W1-optical lags for the targets VVV J1834-2925 and VVV J1845-2426. Using typical sublimation temperatures and reverberation time lags, we obtain a graphite-to-silicate grain size ratio of $\frac{a_C}{a_S}\sim$ 0.4. Through SED fitting, we determine the luminosities of these quasars and find that their dust torus sizes follow the established $R_{dust}-L_{AGN}$ relation reported in previous studies.
#### Optimizing Long-term Variability of AGN Light Curves. I. A Case Study with ZTF Observations in the EGS Field
 - **Authors:** Jiaqi Lin, Zhen-Ya Zheng, Bin Ma, Lin Long, Yangfan Xie, Pu Lin, Ruqiu Lin, Xiang Ji
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2510.26436

 - **Pdf link:** https://arxiv.org/pdf/2510.26436

 - **Abstract**
 Optical variability is a key observational probe for studying the accretion dynamics and central engine physics of Active Galactic Nuclei (AGNs). The quality and completeness of light curves have a direct impact on variability studies, particularly for faint AGNs and high-redshift AGNs. To improve the quality of long-term light curves for AGNs, we bin and stack multi-epoch images balancing the image depths and temporal resolution. As a case study, we apply this method to Zwicky Transient Facility (ZTF) observations in the Extended Groth Strip (EGS) field, where the overlapping region covers an area of about 370 arcmin$^2$ and includes $g$-band and $r$-band data taken from March 2018 to December 2024. The co-added images are approximately 2.0 to 2.5 magnitudes deeper than the ZTF single-epoch images. With co-added images, we construct light curves for 73 AGNs in the EGS field. Compared to the traditional ZTF light curves, our light curves maintain consistent long-term variability trends but with higher photometric precision. Furthermore, this method can help detect AGNs with weak variability which are missed from the traditional ZTF data due to the noisy light curves or below the detection limit in ZTF's single-epoch exposure. Among the 73 AGNs, the majority exhibit a bluer-when-brighter (BWB) trend on long-term timescales, which is consistent with previous studies. This work offers insights for optimizing AGN light curves in both current and upcoming all-sky time-domain surveys.
#### In space there will be no need to scream - Limits to the presence of giant planets in the $ζ^2$ Ret system
 - **Authors:** A. Suárez Mascareño
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP)
 - **Arxiv link:** https://arxiv.org/abs/2510.26483

 - **Pdf link:** https://arxiv.org/pdf/2510.26483

 - **Abstract**
 The search for life beyond our Solar system has been a long and difficult endeavour. The majority of current efforts are focused on the potential detection of biosignatures. However, their detection and interpretation are extremely challenging. Technosignatures appear as an attractive alternative, given their expected univocal interpretation. In recent years, the number of publications discussing them have skyrocketted, both in their more rigurous and speculative sides. In this article, we explore the 28.8 years of archival radial velocity data of $\zeta^2$ Ret with the aim of detecting the proposed giant planet Calpamos, suspected source of a signal of technological origin. We performed a global model fitting the radial velocity data along with activity indicators and modelled the stellar magnetic cycle and rotation. The analysis rules out the presence of the proposed planet, as well as of any other planets more massive than 2-20 $\mathrm{M}_\oplus$ $m_{p}$ sin $i$, depending on orbital period. We show that the previously identified long-period RV signal is definitively caused by the magnetic cycle of the star.
#### CROCODILE-DWARF: Assembly and Kinematics of Field Dwarf Galaxies with GADGET4-OSAKA
 - **Authors:** Kazuki Tomaru, Yuri Oku, Daisuke Toyouchi, Kentaro Nagamine
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26513

 - **Pdf link:** https://arxiv.org/pdf/2510.26513

 - **Abstract**
 We present results from CROCODILE-DWARF, a suite of cosmological zoom-in hydrodynamic simulations of isolated field dwarf galaxies with halo masses of $\sim10^{10}\,M_\odot$ at $z=0$, performed with the \textsc{gadget4-osaka} code. The simulations include detailed modeling of star formation, chemical enrichment, and supernova feedback using the \textsc{CELib} and \textsc{grackle} libraries, achieving baryonic resolutions of $\sim2\times10^3\,M_\odot$. Our study focuses on how assembly history governs the structural and kinematic diversity of dwarf galaxies within the $\Lambda$CDM framework. The simulated galaxies reproduce the observed stellar-to-halo mass, mass--metallicity, and size--mass relations, yielding stellar masses of $10^6-10^8\,M_\odot$ and metallicities consistent with those of Local Group dwarf galaxies. The galaxies display a broad range of rotational support, where gas is generally more rotationally supported than stars. Differences in morphology and kinematics primarily reflect variations in halo assembly timescales and merger activity. Early-assembling, high-concentration halos form stars efficiently and become gas-poor by $z=0$, while late-assembling, low-concentration halos remain gas-rich due to delayed star formation and rejuvenated gas accretion. We identify a clear anti-correlation between rotational support and the cumulative merger mass fraction, demonstrating that dynamical heating by mergers is the dominant factor shaping kinematic diversity. In some cases, late-time mergers induce the formation of extended gas disks by delivering fresh gas and angular momentum. These results demonstrate that assembly history, rather than halo mass alone, critically shapes the present-day kinematic and morphological diversity of dwarf galaxies.
#### A test of invariance of halo surface density for FIRE-2 simulations with cold dark matter and self-interacting dark matter
 - **Authors:** Sujit K. Dalui, Shantanu Desai
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2510.26545

 - **Pdf link:** https://arxiv.org/pdf/2510.26545

 - **Abstract**
 Numerous observations have shown that the dark matter halo surface density, defined as the product of core radius and halo central density of cored dark matter haloes is nearly constant and independent of galaxy mass over a whole slew of galaxy types. Here we calculate the surface density in cold dark matter(CDM) and self-interacting dark matter (SIDM) models including baryons, as well as SIDM without baryons, for dwarf galaxies of masses $\approx 10^{10} M_{\odot}$ using mock catalogs obtained from simulations as part of the Feedback In Realistic Environments project. We find that the dark matter surface density and column density are nearly constant for CDM and SIDM for this mass range. The halo surface density obtained from the Burkert profile fit is consistent with galactic-scale observations within $1\sigma$. We also computed the empirical scaling relations between the central surface density and maximum velocity using the best-fit dark matter profiles, and found that they agree with observations of Milky Way and M31 dwarfs.
#### The $N_H$ Distribution of Hard X-ray Selected AGN in the NEP Field
 - **Authors:** Samantha Creech, Francesca Civano, Daniel R. Wik, Ross Silver, Xiurui Zhao, Rafael Ortiz III, Tonima Ananna, Normal A. Grogin, Rolf Jansen, Christopher N.A. Willmer, Rogier A. Windhorst
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2510.26554

 - **Pdf link:** https://arxiv.org/pdf/2510.26554

 - **Abstract**
 X-ray surveys are one of the most unbiased methods for detecting Compton Thick (CT; $N_{\mathrm{H}} \geq 10^{24}$ cm$^{-2}$) AGN, which are thought to comprise up to $60\%$ of AGN within $z \lesssim 1.0$. These CT AGN are often difficult to detect with current instruments, but the X-ray data within the JWST-North Ecliptic Pole (NEP) Time Domain Field (TDF) present a unique opportunity to study faint and obscured AGN. The NEP contains the deepest NuSTAR survey to date, and Zhao et al. (2024) detected 60 hard X-ray sources from the combined exposure of NuSTAR's Cycle 5 and 6 observations. In this work, we utilize the NuSTAR Cycle 5+6+8+9 data and simultaneous XMM-Newton observations in order to perform the first spectroscopic analysis of the 60-source catalog. We present this analysis and measure the $N_{\mathrm{H}}$ distribution of the sample. We measure an observed CT fraction of $0.13_{-0.04}^{+0.15}$ down to an observed $8-24$ keV flux of $6.0 \times 10^{-14}$ erg/s/cm$^{2}$, and we correct our analysis for absorption bias to estimate an underlying CT fraction of $0.32_{-0.08}^{+0.23}$. The derived obscuration distribution and CT fraction are consistent with population synthesis models and previous surveys.
#### The magnetic fields of the dusty nuclei and molecular outflows of Arp 220
 - **Authors:** Enrique Lopez-Rodriguez, Josep M. Girart, Miguel Pérez-Torres, Mar Mezcua, Gemma Busquet, Rubén Herrero-Illana, Antxon Alberdi, José M. Torrelles
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26570

 - **Pdf link:** https://arxiv.org/pdf/2510.26570

 - **Abstract**
 Galaxy mergers trigger starburst activity and galactic outflows that enrich the circumgalactic medium, profoundly impacting galaxy evolution. These phenomena are intrinsically linked to the physical conditions of the medium, which is permeated by magnetic (B) fields affecting its transport and dynamics. Here, we spatially resolve, $0.24$" (96 pc), the B-fields in the dusty and molecular outflows of Arp 220, the closest ($78$ Mpc) Ultra-Luminous Infrared Galaxy hosting two interacting nuclei, denoted as East and West. We perform ALMA $870~\mu$m dust continuum polarization and CO(3-2) emission line polarization, and report the first detection of CO(3-2) emission line polarization through the Goldreich-Kylafis effect in an outflow. Dust polarization shows that Arp 220 E has a spiral-like B-field on the disk with a linear polarization fraction of $0.4\pm0.1$% that may produce the detected circular polarization passing through foreground aligned dust grains. Arp 220 W reveals a B-field parallel to the red- and blueshifted outflows in both the dust and emission line polarization maps. The outflows show a dust polarization of $0.2$%, while the CO(3-2) emission line polarization is $1-2$% at $4-6\sigma$ significance across independent velocity channels. A highly polarized ($3-5$%) dusty bridge has a B-field orientation of $\sim110^{\circ}$ connecting both nuclei. Mean B-field strengths of $1.6$ mG and $8$ mG for the blue- and redshifted outflows, respectively, are estimated. These strong B-fields are attributed to amplification by compression in nuclear clouds and supernova remnants. This amplified B-field is likely sustained by the turbulent kinetic energy in the outflow and may be critical in directing the transport of metals and cosmic rays into the circumgalactic medium.
#### The second data release of the Indian Pulsar Timing Array: Investigating the Effect of Coronal Mass Ejection on PSR J1022+1001 and a Possible Mode Change of PSR J2145-0750
 - **Authors:** Shaswata Chowdhury, M. A. Krishnakumar, Manjari Bagchi, Bhal Chandra Joshi, Nobleson K., Jibin Jose, Shantanu Desai, Manpreet Singh, Vaishnavi Vyasraj, Kuldeep Meena, Amarnath, Manoneeta Chakraborty, Shubham Kala, Debabrata Deb, Zenia Zuraiq, Arul Pandian B, Neelam Dhanda Batra, Churchil Dwivedi, Sushovan Mondal, Avinash Kumar Paladi, Kaustubh Rai, Abhimanyu Susobhanan, Adya Shukla, Aman Srivastava, Mayuresh Surnis, Hemanga Tahbildar, Keitaro Takahashi, Pratik Tarafdar, Prabu Thiagaraj, Kunjal Vara
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2510.26594

 - **Pdf link:** https://arxiv.org/pdf/2510.26594

 - **Abstract**
 The Indian Pulsar Timing Array (InPTA) has recently published its second data release (DR2), comprising the timing analysis of seven years of data on 27 millisecond pulsars (MSPs), observed simultaneously in the 300-500 MHz (band 3) and 1260-1460 MHz (band 5), using the upgraded Giant Metrewave Radio Telescope (uGMRT). The low-frequency data, particularly in band 3, is highly sensitive to propagation effects such as dispersion measure (DM) fluctuations, which can be imprints of some astrophysical phenomena (scientific outliers). Here, we analyze the two outliers of possible astrophysical origin coming from the band 3 DM time series of two pulsars: PSR J1022+1001, with an ecliptic latitude of -0.06 degree , and PSR J2145-0750, one of the brightest MSPs, with multi-component profile morphology. Our study reveals compelling evidence for a coronal mass ejection (CME) event traced in the data of PSR J1022+1001, and reports evidence for a potential mode-changing event in PSR J2145-0750. Extending the analyses presented here to the full sample of InPTA-DR2 pulsars is expected to reveal additional CME events, and possible mode-changing events. Such detections will not only improve our understanding of solar and pulsar magnetospheric plasma interactions but will also enable more accurate modelling of DM variations, leading to improved pulsar timing solutions, which are crucial for high-precision Pulsar Timing Array (PTA) science.
#### The 2024 July 16 Solar Event: A Challenge To The Coronal Mass Ejection Origin Of Long-Duration Gamma-Ray Flares
 - **Authors:** Alessandro Bruno, Melissa Pesce-Rollins, Silvia Dalla, Nicola Omodei, Ian G. Richardson, James M. Ryan
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2510.26666

 - **Pdf link:** https://arxiv.org/pdf/2510.26666

 - **Abstract**
 We present a multi-spacecraft analysis of the 2024 July 16 Long-Duration Gamma-Ray Flare (LDGRF) detected by the Large Area Telescope on the Fermi satellite. The measured >100 MeV $\gamma$-ray emission persisted for over seven hours after the flare impulsive phase, and was characterized by photon energies exceeding 1 GeV and a remarkably-hard parent-proton spectrum. In contrast, the phenomena related to the coronal mass ejection (CME)-driven shock linked to this eruption were modest, suggesting an inefficient proton acceleration unlikely to achieve the energies well-above the 300 MeV pion-production threshold to account for the observed $\gamma$-ray emission. Specifically, the CME was relatively slow (~600 km/s) and the accompanying interplanetary type-II/III radio bursts were faint and short-duration, unlike those typically detected during large events. In particular, the type-II emission did not extend to kHz frequencies and disappeared ~5.5 hours prior to the LDGRF end time. Furthermore, the associated solar energetic particle (SEP) event was very weak, short-duration, and limited to a few tens of MeV, even at magnetically well-connected spacecraft. These findings demonstrate that a very-fast CME resulting in a high-energy SEP event is not a necessary condition for the occurrence of LDGRFs, challenging the idea that the high-energy $\gamma$-ray emission is produced by the back-precipitation of shock-accelerated ions into the solar surface. The alternative origin scenario based on local particle trapping and acceleration in large-scale coronal loops is instead favored by the observation of giant arch-like structures of hot plasma over the source region persisting for the entire duration of this LDGRF.
#### The ODYSSEUS Survey. Spatial correlation of magnetospheric inclinations points to parsec-scale star-cloud connection
 - **Authors:** Caeley V. Pittman, Catherine C. Espaillat, Thanawuth Thanathibodee, Nuria Calvet, Lee W. Hartmann, Sylvie Cabrit
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Earth and Planetary Astrophysics (astro-ph.EP); Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26687

 - **Pdf link:** https://arxiv.org/pdf/2510.26687

 - **Abstract**
 The properties of stars and planets are shaped by the initial conditions of their natal clouds. However, the spatial scales over which the initial conditions can exert a significant influence are not well constrained. We report the first evidence for parsec-scale spatial correlations of stellar magnetospheric inclinations ($i_{\rm mag}$), observed in the Lupus low-mass star forming region. Applying consensus clustering with a hierarchical density-based clustering algorithm, we demonstrate that the detected spatial dependencies are stable against perturbations by measurement uncertainties. The $i_{\rm mag}$ correlation scales are on the order of ~3 pc, which aligns with the typical scales of the Lupus molecular cloud filaments. Our results reveal a connection between large-scale forces -- in the form of expanding shells from the Upper Scorpius and Upper-Centaurus-Lupus regions -- and sub-au scale system configurations. We find that Lupus has a non-uniform $i_{\rm mag}$ distribution and suggest that this results from the preferential elongation of protostellar cores along filamentary axes. Non-uniformity would have significant implications for exoplanet occurrence rate calculations, so future work should explore the longevity of these biases driven by the star-cloud connection.
#### Flinch: A Differentiable Framework for Field-Level Inference of Cosmological parameters from curved sky data
 - **Authors:** Andrea Crespi, Marco Bonici, Arthur Loureiro, Jaime Ruiz-Zapatero, Ivan Sladoljev, Zack Li, Adrian Bayer, Marius Millea, Uroš Seljak
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2510.26691

 - **Pdf link:** https://arxiv.org/pdf/2510.26691

 - **Abstract**
 We present Flinch, a fully differentiable and high-performance framework for field-level inference on angular maps, developed to improve the flexibility and scalability of current methodologies. Flinch is integrated with differentiable cosmology tools, allowing gradients to propagate from individual map pixels directly to the underlying cosmological parameters. This architecture allows cosmological inference to be carried out directly from the map itself, bypassing the need to specify a likelihood for intermediate summary statistics. Using simulated, masked CMB temperature maps, we validate our pipeline by reconstructing both maps and angular power spectra, and we perform cosmological parameter inference with competitive precision. In comparison with the standard pseudo-$C_\ell$ approach, Flinch delivers substantially tighter constraints, with error bars reduced by up to 40%. Among the gradient-based samplers routinely employed in field-level analyses, we further show that MicroCanonical Langevin Monte Carlo provides orders-of-magnitude improvements in sampling efficiency over currently employed Hamiltonian Monte Carlo samplers, greatly reducing computational expense.
#### Active Dwarf Galaxy Database II: Connections between Host Galaxy Properties and Black Hole Accretion Signatures
 - **Authors:** Erik J. Wasleske, Vivienne F. Baldassare, Christopher M. Carroll
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26716

 - **Pdf link:** https://arxiv.org/pdf/2510.26716

 - **Abstract**
 We investigate the connection between accretion signatures and host galaxy properties in the context of how active dwarf galaxies are identified. We use the database constructed in Wasleske & Baldassare (2024) which contains dwarf galaxies that were selected as active galaxies by optical spectroscopy, infrared colors, X-ray brightness, and photometric variability. Multi-wavelength archival data was used to consistently apply all of these methods to every galaxy within this compiled set. The cross application of these methods resulted in a diversity of sub-populations identified as active by some set of these techniques. In this paper, we estimate host galaxy properties from spectral energy distribution models. We connect the active galactic nuclei (AGN) signatures to our estimated host galaxies' properties using statistical dimensionality reduction methods. We find that dwarf AGN selected by infrared colors are the most distinct population, with the highest star formation rates and lowest stellar masses. We also find some other key population differences, such as the broad line AGN having significantly higher AGN luminosities. X-ray and variability selected AGN have higher average star formation rates than those selected with optical narrow line spectroscopic diagrams. Our connections to the host galaxy parameters potentially point to the sub-populations representing different epochs of the evolution of accretion.
#### Compact Accretion Disks in the Aftermath of Tidal Disruption Events: Parameter Inference from Joint X-ray Spectra and UV/Optical Photometry Fitting
 - **Authors:** M. Guolo, A. Mummery, S. van Velzen, S. Gezari, M. Nicholl, Y. Yao, M. Karmen, Y. Ajay, T. Wevers, N. LeBaron, R. Chornock
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2510.26774

 - **Pdf link:** https://arxiv.org/pdf/2510.26774

 - **Abstract**
 We present a multi-wavelength analysis of 14 tidal disruption events (TDEs)-including an off-nuclear event associated with an ultra-compact dwarf galaxy-selected for having available thermal X-ray spectra during their late-time UV/optical plateau phase. We show that at these stages, the full spectral energy distribution - X-ray spectra and UV/optical photometry - is well described by a compact, yet standard accretion disk, the same disk which powers the X-rays at all times. By fitting up to three three epochs per source with a fully relativistic disk model, we show that many system properties can be reliably recovered, including importantly the black hole mass ($M_{\bullet}$). These accretion-based $M_{\bullet}$ values, which in this sample span nearly three orders of magnitude, are consistent with galactic scaling relations but are significantly more precise (68\% credible interval $ < \pm 0.3$ dex) and physically motivated. Expected accretion scaling relations (e.g., $L_{Bol}^{ disk} / L_{Edd} \propto T_p^4 \propto M_{\bullet}^{-1}$), TDE-specific physics correlations ($L_{plat} \propto M_{\bullet}^{2/3}$ and $R_{out}/r_g \propto M_{\bullet}^{-2/3}$) and black hole-host galaxy correlations ($M_{\bullet}$-$M_{\star}$ and $M_{\bullet}$-$\sigma_{\star}$) naturally emerge from the data and, for the first time, are self-consistently extended into the intermediate-mass (IMBH, $M_{\bullet} < 10^{5}$) regime. We discuss the implications of these results for TDE physics and modeling. We also review and discuss different methods for $M_{\bullet}$ inference in TDEs, and find that approaches based on physical models of the early-time UV/optical emission are not able to recover (at a statistically significant level) black hole-host galaxy scalings.


by olozhika (Xing Yuchen). 


2025-10-31
