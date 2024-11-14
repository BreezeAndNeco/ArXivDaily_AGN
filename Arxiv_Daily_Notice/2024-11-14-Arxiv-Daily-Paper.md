# Showing new listings for Wednesday, 13 November 2024
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['AGN', 'active galactic nuclei', 'outflow', 'Feedback', 'quenching', 'IFU', 'Hot DOG', 'Obscured AGN', 'molecular gas', 'inoized gas', 'Little Red Dot']


Excluded: []


### Today: 23papers 
#### The Impact of Star Formation and Feedback Recipes on the Stellar Mass and Interstellar Medium of High-Redshift Galaxies
 - **Authors:** Harley Katz, Martin P. Rey, Corentin Cadiou, Taysun Kimm, Oscar Agertz
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2411.07282

 - **Pdf link:** https://arxiv.org/pdf/2411.07282

 - **Abstract**
 We introduce MEGATRON, a new galaxy formation model for cosmological radiation hydrodynamics simulations of high-redshift galaxies. The model accounts for the non-equilibrium chemistry and heating/cooling processes of $\geq 80$ atoms, ions, and molecules, coupled to on-the-fly radiation transfer. We apply the model in a cosmological setting to the formation of a $10^9\ {\rm M_{\odot}}$ halo at $z=6$, and run 25 realizations at pc-scale resolution, varying numerous parameters associated with our state-of-the-art star formation, stellar feedback, and chemical enrichment models. We show that the overall budget of feedback energy is the key parameter that controls star formation regulation at high redshift, with other numerical parameters (e.g. supernova clustering, star formation conditions) having a more limited impact. As a similar feedback model has been shown to produce realistic $z=0$ galaxies, our work demonstrates that calibration at $z=0$ does not guarantee strong regulation of star formation at high-redshift. Interestingly, we find that subgrid model variations that have little impact on the final $z=6$ stellar mass can lead to substantial changes on the observable properties of high-redshift galaxies. For example, different star formation models based on, e.g. density thresholds or turbulence inspired criteria, lead to fundamentally distinct nebular emission line ratios across the interstellar medium (ISM). These results highlight the ISM as an important resource for constraining models of star formation, feedback, and galaxy formation in the JWST era, where emission line measurements for $>1,000$ high-redshift galaxies are now available.
#### Type IIn Supernovae. I. Uniform Light Curve Characterization and a Bimodality in the Radiated Energy Distribution
 - **Authors:** Daichi Hiramatsu, Edo Berger, Sebastian Gomez, Peter K. Blanchard, Harsh Kumar, Wasundara Athukoralalage
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2411.07287

 - **Pdf link:** https://arxiv.org/pdf/2411.07287

 - **Abstract**
 We present the largest uniform study to date of Type IIn supernovae (SNe IIn), focusing in this first paper on the multi-band optical light curves of $487$ SNe IIn. The sample, constructed from multiple surveys, extends to $z \approx 0.8$, with the majority of events at $z \lesssim 0.3$. We construct uniform multi-band and bolometric light curves using Gaussian process regression, and determine key observed properties in the rest-frame (e.g., peak luminosity, timescales, radiated energy). We find that SNe IIn span broad ranges in peak luminosity ($\sim 10^{42}-10^{44}$ erg s$^{-1}$) and timescales ($\sim 20-300$ days above 50% of peak luminosity), but the sample divides into two clear groups in the luminosity-timescale phase-space around the median peak luminosity ($\approx 10^{43}$ erg s$^{-1}$): faint-fast and luminous-slow groups. This leads to a strong bimodality in the radiated energy distribution, with peaks at $\sim 10^{49}$ and $\sim 2\times10^{50}$ erg, with the latter events having a characteristic timescale of $\sim 100$ days, and the former appearing to bifurcate into two branches with timescales of $\sim 40$ and $\sim 70$ days. Therefore, SNe IIn exhibit at least two dominant groupings, and perhaps three, which are likely reflective of different progenitor and/or circumstellar medium formation pathways. We do not find any obvious transition in SN IIn properties at the arbitrary cut-off of $\approx -20$ mag used for the designation "Type II Superluminous Supernovae", and we argue that this classification should be abandoned. The absence of SNe IIn with timescales of $\lesssim 14$ days defines the region occupied by fast transients with evidence for interaction with hydrogen-poor circumstellar medium.
#### PICZL: Image-based Photometric Redshifts for AGN
 - **Authors:** William Roster, Mara Salvato, Sven Krippendorf, Aman Saxena, Raphael Shirley, Johannes Buchner, Julien Wolf, Tom Dwelly, Franz E. Bauer, James Aird, Claudio Ricci, Roberto J. Assef, Scott F. Anderson, Xiu Liu, Andrea Merloni, Jochen Weller, Kirpal Nandra
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Instrumentation and Methods for Astrophysics (astro-ph.IM); Machine Learning (stat.ML)
 - **Arxiv link:** https://arxiv.org/abs/2411.07305

 - **Pdf link:** https://arxiv.org/pdf/2411.07305

 - **Abstract**
 Computing photo-z for AGN is challenging, primarily due to the interplay of relative emissions associated with the SMBH and its host galaxy. SED fitting methods, effective in pencil-beam surveys, face limitations in all-sky surveys with fewer bands available, lacking the ability to capture the AGN contribution to the SED accurately. This limitation affects the many 10s of millions of AGN clearly singled out and identified by SRG/eROSITA. Our goal is to significantly enhance photometric redshift performance for AGN in all-sky surveys while avoiding the need to merge multiple data sets. Instead, we employ readily available data products from the 10th Data Release of the Imaging Legacy Survey for DESI, covering > 20,000 deg$^{2}$ with deep images and catalog-based photometry in the grizW1-W4 bands. We introduce PICZL, a machine-learning algorithm leveraging an ensemble of CNNs. Utilizing a cross-channel approach, the algorithm integrates distinct SED features from images with those obtained from catalog-level data. Full probability distributions are achieved via the integration of Gaussian mixture models. On a validation sample of 8098 AGN, PICZL achieves a variance $\sigma_{\textrm{NMAD}}$ of 4.5% with an outlier fraction $\eta$ of 5.6%, outperforming previous attempts to compute accurate photo-z for AGN using ML. We highlight that the model's performance depends on many variables, predominantly the depth of the data. A thorough evaluation of these dependencies is presented in the paper. Our streamlined methodology maintains consistent performance across the entire survey area when accounting for differing data quality. The same approach can be adopted for future deep photometric surveys such as LSST and Euclid, showcasing its potential for wide-scale realisation. With this paper, we release updated photo-z (including errors) for the XMM-SERVS W-CDF-S, ELAIS-S1 and LSS fields.
#### Physics of radio antennas
 - **Authors:** Mohammad Ful Hossain Seikh
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2411.07507

 - **Pdf link:** https://arxiv.org/pdf/2411.07507

 - **Abstract**
 Radio antennas are widely used in the field of particle astrophysics in searches for ultra-high energy cosmic rays (UHECR) and neutrinos (UHEN). It is therefore necessary to properly describe the physics of their response. In this article, we summarize the mathematics underlying parameterizations of radio antennas. As a paradigm, we focus on a half-wave dipole and also discuss measurements of characteristics, performed in an electromagnetic (EM) anechoic chamber.
#### A halo model approach for mock catalogs of time-variable strong gravitational lenses
 - **Authors:** Katsuya T. Abe, Masamune Oguri, Simon Birrer, Narayan Khadka, Philip J. Marshall, Cameron Lemon, Anupreeta More, the LSST Dark Energy Science Collaboration
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2411.07509

 - **Pdf link:** https://arxiv.org/pdf/2411.07509

 - **Abstract**
 Time delays in both galaxy- and cluster-scale strong gravitational lenses have recently attracted a lot of attention in the context of the Hubble tension. Future wide-field cadenced surveys, such as the LSST, are anticipated to discover strong lenses across various scales. We generate mock catalogs of strongly lensed QSOs and SNe on galaxy-, group-, and cluster-scales based on a halo model that incorporates dark matter halos, galaxies, and subhalos. For the upcoming LSST survey, we predict that approximately 3500 lensed QSOs and 200 lensed SNe with resolved multiple images will be discovered. Among these, about 80 lensed QSOs and 10 lensed SNe will have maximum image separations larger than 10 arcsec, which roughly correspond to cluster-scale strong lensing. We find that adopting the Chabrier stellar IMF instead of the fiducial Salpeter IMF reduces the predicted number of strong lenses approximately by half, while the distributions of lens and source redshifts and image separations are not significantly changed. In addition to mock catalogs of multiple-image lens systems, we create mock catalogs of highly magnified systems, including both multiple-image and single-image systems. We find that such highly magnified systems are typically produced by massive galaxies, but non-negligible fraction of them are located in the outskirt of galaxy groups and clusters. Furthermore, we compare subsamples of our mock catalogs with lensed QSO samples constructed from the SDSS and Gaia to find that our mock catalogs with the fiducial Salpeter IMF reproduce the observation quite well. In contrast, our mock catalogs with the Chabrier IMF predict a significantly smaller number of lensed QSOs compared with observations, which adds evidence that the stellar IMF of massive galaxies is Salpeter-like. Our python code SL-Hammocks as well as the mock catalogs are made available online. (abridged)
#### The Dependence of Dark Matter Halo Properties on the Morphology of Their Central Galaxies from Weak Lensing
 - **Authors:** Zhenjie Liu, Kun Xu, Jun Zhang, Wenting Wang, Cong Liu
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2411.07525

 - **Pdf link:** https://arxiv.org/pdf/2411.07525

 - **Abstract**
 Xu \& Jing (2022) reported a monotonic relationship between host halo mass (\(M_h\)) and the morphology of massive central galaxies, characterized by the Sérsic index (\(n\)), at fixed stellar mass, suggesting that morphology could serve as a good secondary proxy for halo mass. Since their results were derived using the indirect abundance matching method, we further investigate the connection between halo properties and central galaxy morphology using weak gravitational lensing. We apply galaxy-galaxy lensing to measure the excess surface density around CMASS central galaxies with stellar masses in the range of \(11.3 < \log M_*/{\rm M_\odot} < 11.7\), using the HSC shear catalog processed through the Fourier\_Quad pipeline. By dividing the sample based on \(n\), we confirm a positive correlation between \(n\) and \(M_h\), and observe a possible evidence of the positive correlation of \(n\) and halo concentration. After accounting for color, we find that neither color nor morphology alone can determine halo mass, suggesting that a combination of both may serve as a better secondary proxy. In comparison to hydrodynamic simulations, we find that TNG300 produce much weaker correlations between \(M_h\) and \(n\). Furthermore, disabling jet-mode active galactic nuclei feedback in SIMBA simulations results in the disappearance of the positive \(n-M_h\) relationship, suggesting that the star formation history influenced by black holes may be a contributing factor.
#### Nuclear burning in an accretion flow around a stellar-mass black hole embedded within an AGN disk
 - **Authors:** Zifan Tang, Yang Luo, Jian-Min Wang
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2411.07531

 - **Pdf link:** https://arxiv.org/pdf/2411.07531

 - **Abstract**
 A stellar-mass black hole, embedded within the accretion disk of an active galactic nuclei (AGN), has the potential to accrete gas at a rate that can reach approximately $\sim 10^9$ times the Eddington limit. This study explores the potential for nuclear burning in the rapidly accreting flow towards this black hole and studies how nucleosynthesis affects metal production. Using numerical methods, we have obtained the disk structure while considering nuclear burning and assessed the stability of the disk. In contrast to gas accretion onto the surface of a neutron star or white dwarf, the disk remains stable against the thermal and secular instabilities because advection cooling offsets the nuclear heating effects. The absence of a solid surface for a black hole prevents excessive mass accumulation in the inner disk region. Notably, nuclear fusion predominantly takes place in the inner disk region, resulting in substantial burning of $\rm ^{12}C$ and $\rm ^{3}He$, particularly for black holes around $M = 10\, M_\odot$ with accretion rates exceeding approximately $\sim 10^7$ times the Eddington rate. The ejection of carbon-depleted gas through outflows can lead to an increase in the mass ratio of oxygen or nitrogen to carbon, which may be reflected in observed line ratios such as $\rm N\, V/C\, IV$ and $\rm O\, IV/C\, IV$. Consequently, these elevated spectral line ratios could be interpreted as indications of super-solar metallicity in the broad line region.
#### Multiphase Gas Nature in the Sub-parsec Region of the Active Galactic Nuclei. III. Eddington Ratio Dependence on the Structures of Dusty and Dust-free Outflows
 - **Authors:** Yuki Kudoh, Keiichi Wada, Nozomu Kawakatu, Mariko Nomura
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2411.07736

 - **Pdf link:** https://arxiv.org/pdf/2411.07736

 - **Abstract**
 We investigated the influence of the Eddington ratio on sub-parsec-scale outflows in active galactic nuclei (AGNs) with supermassive black holes (SMBHs) masses of $10^7$ M$_{\odot}$ using two-dimensional radiation hydrodynamics simulations. When the range of Eddington ratio, $\gamma_{\rm Edd} > 10^{-3}$, the radiation force exceeds the gas pressure, leading to stronger outflows and larger dust sublimation radius. Although the sub-parsec-scale outflows is a time-dependence phenomena, our simulations demonstrated that the radial distributions can be well explained by the steady solutions of the spherically symmetric stellar winds. The dynamic structure of sub-parsec-scale outflows is influenced by the dust sublimation radius and the critical radii determined by the dynamical equilibrium condition. Although significantly affecting the outflow velocity, the Eddington ratio exerts minimal effects on temperature and number density distribution. Furthermore, our analytical solutions highlight the importance of the dust sublimation scale as a crucial determinant of terminal velocity and column density in dusty outflows. Through comparisons of our numerical model with the obscuring fraction observed in nearby AGNs, we revealed insights into the Eddington ratio dependence and the tendency towards the large obscuring fraction of the dusty and dust-free gases. The analytical solutions are expected to facilitate an understanding of the dynamical structure and radiation structures along the line of sight and their viewing angles from observations of ionized outflows.
#### Characterising high and low accretion states in VY Scl CVs using ZTF and TESS data
 - **Authors:** C. Duffy, Kinwah Wu, G. Ramsay, Matt A. Wood, Paul A. Mason, Pasi Hakala, D. Steeghs
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2411.07744

 - **Pdf link:** https://arxiv.org/pdf/2411.07744

 - **Abstract**
 VY Scl binaries are a sub-class of cataclysmic variable (CV) which show extended low states, but do not show outbursts which are seen in other classes of CV. To better determine how often these systems spend in low states and to resolve the state transitions we have analysed ZTF data on eight systems and TESS data on six systems. Half of the sample spent most of the time in a high state; three show a broad range and one spends roughly half the time transitioning between high and low states. Using the ZTF data we explore the colour variation as a function of brightness. In KR Aur, we identify a series of repeating outburst events whose brightness appears to increase over time. Using TESS data we searched for periods other than the orbital. In LN UMa we find evidence for a peak whose period varies between 3-6 d. We outline the current models which aim to explain the observed properties of VY Scl systems which includes disc irradiation and a white dwarf having a significant magnetic field.
#### Broad-Line Region Characterization in Dozens of Active Galactic Nuclei Using Small-Aperture Telescopes
 - **Authors:** Catalina Sobrino Figaredo, Doron Chelouche, Martin Haas, Michael Ramolla, Shai Kaspi, Swayamtrupta Panda, Martin W. Ochmann, Shay Zucker, Rolf Chini, Malte A. Probst, Wolfram Kollatschny, Miguel Murphy
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2411.07847

 - **Pdf link:** https://arxiv.org/pdf/2411.07847

 - **Abstract**
 We present the results of a nearly decade-long photometric reverberation mapping (PRM) survey of the H$\alpha$ emission line in nearby ($0.01\lesssim z \lesssim0.05$) Seyfert-Galaxies using small ($15\,\mathrm{cm}-40\,\mathrm{cm}$) telescopes. Broad-band filters were used to trace the continuum emission, while narrow-band filters tracked the H$\alpha$-line signal. We introduce a new PRM formalism to determine the time delay between continuum and line emission using combinations of auto- and cross-correlation functions. We obtain robust delays for 33/80 objects, allowing us to estimate the broad-line region (BLR) size. Additionally, we measure multi-epoch delays for 6 objects whose scatter per source is smaller than the scatter in the BLR size-luminosity relation. Our study enhances the existing H$\alpha$ size-luminosity relation by adding high-quality results for 31 objects, whose nuclear luminosities were estimated using the flux-variation gradient method, resulting in a scatter of 0.26dex within our sample. The scatter reduces to 0.17dex when the 6 lowest luminosity sources are discarded, which is comparable to that found for the H$\beta$ line. Single-epoch spectra enable us to estimate black hole masses using the H$\alpha$ line and derive mass accretion rates from the iron-blend feature adjacent to H$\beta$. A similar trend, as previously reported for the H$\beta$ line, is implied whereby highly accreting objects tend to lie below the size-luminosity relation of the general population. Our work demonstrates the effectiveness of small telescopes in conducting high-fidelity PRM campaigns of prominent emission lines in bright active galactic nuclei.
#### Temperature and density profiles in the corona of main-sequence stars induced by stochastic heating in the chromosphere
 - **Authors:** Luca Barbieri, Lapo Casetti, Andrea Verdini, Simone Landi
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2411.07868

 - **Pdf link:** https://arxiv.org/pdf/2411.07868

 - **Abstract**
 All but the most massive main-sequence stars are expected to have a rarefied and hot (million-Kelvin) corona like the Sun. How such a hot corona is formed and supported has not been completely understood yet, even in the case of the Sun. Recently, Barbieri et al. (A&A 2024, J. Plasma Phys. 2024) introduced a new model of a confined plasma atmosphere and applied it to the solar case, showing that rapid, intense, intermittent and short-lived heating events in the high chromosphere can drive the coronal plasma into a stationary state with temperature and density profiles similar to those observed in the solar atmosphere. In this paper we apply the model to main-sequence stars, showing that it predicts the presence of a solar-like hot and rarefied corona for all such stars, regardless of their mass. However, the model is not applicable as such to the most massive main-sequence stars, because the latter lack the convective layer generating the magnetic field loop structures supporting a stationary corona, whose existence is assumed by the model. We also discuss the role of stellar mass in determining the shape of the temperature and density profiles.
#### From Dark Matter Minihalos to Large-Scale Radiative Feedback: A Self-Consistent 3D Simulation of the First Stars and Galaxies using Neural Networks
 - **Authors:** Colton Feathers, Mihir Kulkarni, Eli Visbal
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2411.07875

 - **Pdf link:** https://arxiv.org/pdf/2411.07875

 - **Abstract**
 A key obstacle to accurate models of the first stars and galaxies is the vast range of distance scales that must be considered. While star formation occurs on sub-parsec scales within dark matter (DM) minihalos, it is influenced by large-scale baryon-dark matter streaming velocities ($v_{\rm bc}$) and Lyman-Werner (LW) radiative feedback which vary significantly on scales of $\sim$100 Mpc. We present a novel approach to this issue in which we utilize artificial neural networks (NNs) to emulate the Population III (PopIII) and Population II (PopII) star formation histories of many small-scale cells given by a more complex semi-analytic framework based on DM halo merger trees. Within each simulation cell, the NN takes a set of input parameters that depend on the surrounding large-scale environment, such as the cosmic overdensity, $\delta(\vec{x})$, and $v_{\rm bc}$ of the cell, then outputs the resulting star formation far more efficiently than is possible with the semi-analytic model. This rapid emulation allows us to self-consistently determine the LW background intensity on $\sim$100 Mpc scales, while simultaneously including the detailed merger histories (and corresponding star formation histories) of the low-mass minihalos that host the first stars. Comparing with the full semi-analytic framework utilizing DM halo merger trees, our NN emulators yield star formation histories with redshift-averaged errors of $\sim$10.2\% and $\sim$9.2\% for PopII and PopIII, respectively. When compared to a simpler sub-grid star formation prescription reliant on halo mass function integration, we find that the diversity of halo merger histories in our simulation leads to enhanced spatial fluctuations, an earlier transition from PopIII to PopII dominated star formation, and more scatter in star formation histories overall.
#### Bidirectional propagating brightenings in arch filament systems observed by Solar Orbiter/EUI
 - **Authors:** Yajie Chen, Sudip Mandal, Hardi Peter, Lakshmi Pradeep Chitta
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2411.07876

 - **Pdf link:** https://arxiv.org/pdf/2411.07876

 - **Abstract**
 Arch filament systems (AFSs) are chromospheric and coronal manifestations of emerging magnetic flux. Using high spatial resolution observations taken at a high cadence by the Extreme Ultraviolet Imager (EUI) on board Solar Orbiter, we identified small-scale elongated brightenings within the AFSs. These brightenings appear as bidirectional flows along the threads of AFSs. For our study, we investigated the coordinated observations of the AFSs acquired by the EUI and the Atmospheric Imaging Assembly (AIA) on board SDO on 2022 March 4 and 17. We analyzed 15 bidirectional propagating brightenings from EUI 174 Å images. These brightenings reached propagating speeds of 100-150 km/s. The event observed on March 17 exhibits blob-like structures, which may be signatures of plasmoids and due to magnetic reconnection. In this case, we also observed counterparts in the running difference slit-jaw images in the 1400 Å passbands taken by the Interface Region Imaging Spectrograph (IRIS). Most events show co-temporal intensity variations in all AIA EUV passbands. Together, this implies that these brightenings in the AFSs are dominated by emission from cool plasma with temperatures well below 1 MK. The magnetograms taken by the Polarimetric and Helioseismic Imager (PHI) on board Solar Orbiter show signatures of flux emergence beneath the brightenings. This suggests that the events in the AFSs are triggered by magnetic reconnection that may occur between the newly emerging magnetic flux and the preexisting magnetic field structures in the middle of the AFSs. This would also give a natural explanation for the bidirectional propagation of the brightenings near the apex of the AFSs. The interaction of the preexisting field and the emerging flux may be important for mass and energy transfer within the AFSs.
#### Multi-spacecraft observations of the decay phase of solar energetic particle events
 - **Authors:** R. A. Hyndman, S. Dalla, T. Laitinen, A. Hutchinson, C. M. S. Cohen, R. F. Wimmer-Schweingruber
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Space Physics (physics.space-ph)
 - **Arxiv link:** https://arxiv.org/abs/2411.07903

 - **Pdf link:** https://arxiv.org/pdf/2411.07903

 - **Abstract**
 Context: Parameters of solar energetic particle (SEP) event profiles such as the onset time and peak time have been researched extensively to obtain information on acceleration and transport of SEPs. Corotation of particle-filled magnetic flux tubes with the Sun is generally thought to play a minor role in determining intensity profiles. However recent simulations have suggested that corotation has an effect on SEP decay phases, depending on the location of the observer with respect to the active region (AR) associated with the event. Aims: We aim to determine whether signatures of corotation are present in observations of decay phases of SEP events and study how the parameters of the decay phase depend on the properties of the flares and coronal mass ejections (CMEs) associated with the events. Methods: We analyse multi-spacecraft observations of SEP intensity profiles from 11 events between 2020 and 2022, using data from SOLO, PSP, STEREO-A, and SOHO. We determine the decay time constant, \tau in 3 energy channels; electrons ~ 1 MeV, protons ~ 25 MeV, and protons ~ 60 MeV. We study the dependence of \tau on the longitudinal separation, \Delta \phi, between source active region (AR) and the spacecraft magnetic footpoint on the Sun. Results: Within individual events there is a tendency for the decay time constant to decrease with increasing $\Delta \phi$, in agreement with test particle simulations. The intensity of the associated flare and speed of the associated CMEs have a strong effect on the measured $\tau$ values and are likely the cause of the observed large inter-event variability. Conclusions: We conclude that corotation has a significant effect on the decay phase of a solar energetic particle event and should be included in future simulations and interpretations of these events.
#### Rising Near-Ultraviolet Spectra in Stellar Megaflares
 - **Authors:** Adam F. Kowalski (1,2,3), Rachel A. Osten (4), Yuta Notsu (3,2), Isaiah I. Tristan (1,3,2), Antigona Segura (5), Hiroyuki Maehara (6), Kosuke Namekata (7,8,9), Shun Inoue (8) ((1) University of Colorado, (2) National Solar Observatory, (3) Laboratory for Atmospheric and Space Physics, (4) Space Telescope Science Institute, (5) Universidad Nacional Autonoma de Mexico, (6) Subaru Telescope Okayama Branch Office, National Astronomical Observatory of Japan, (7) The Hakubi Center for Advanced Research, Kyoto University (8) Department of Physics, Kyoto University, (9) Division of Science, National Astronomical Observatory of Japan)
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2411.07913

 - **Pdf link:** https://arxiv.org/pdf/2411.07913

 - **Abstract**
 Flares from M-dwarf stars can attain energies up to $10^4$ times larger than solar flares but are generally thought to result from similar processes of magnetic energy release and particle acceleration. Larger heating rates in the low atmosphere are needed to reproduce the shape and strength of the observed continua in stellar flares, which are often simplified to a blackbody model from the optical to the far-ultraviolet (FUV). The near-ultraviolet (NUV) has been woefully undersampled in spectral observations despite this being where the blackbody radiation should peak. We present Hubble Space Telescope NUV spectra in the impulsive phase of a flare with $E_{\rm{TESS}} \approx 7.5 \times 10^{33}$ erg and a flare with $E_{\rm{TESS}} \approx 10^{35}$ erg and the largest NUV flare luminosity observed to date from an M star. The composite NUV spectra are not well represented by a single blackbody that is commonly assumed in the literature. Rather, continuum flux rises toward shorter wavelengths into the FUV, and we calculate that an optical $T=10^4$ K blackbody underestimates the short wavelength NUV flux by a factor of $\approx 6$. We show that rising NUV continuum spectra can be reproduced by collisionally heating the lower atmosphere with beams of $E \gtrsim 10$ MeV protons or $E \gtrsim 500$ keV electrons and flux densities of $10^{13}$ erg cm$^{-2}$ s$^{-1}$. These are much larger than canonical values describing accelerated particles in solar flares.
#### The impact of water clouds on the prospective emission spectrum of Teegarden's Star b as observed by LIFE
 - **Authors:** Ryan Boukrouche, Rodrigo Caballero, Markus Janson
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP)
 - **Arxiv link:** https://arxiv.org/abs/2411.07922

 - **Pdf link:** https://arxiv.org/pdf/2411.07922

 - **Abstract**
 Non-transiting terrestrial planets will be accessible by upcoming observatories of which LIFE is an example. Planet b orbiting Teegarden's Star is one of the optimal targets for such missions. We use a one-dimensional atmospheric model with real-gas radiation, a multi-species pseudo-adiabatic convection-condensation scheme, and a water cloud scheme, to estimate the impact of the cloud coverage on the emission spectrum of the target, as well as to assess how sensitive LIFE could be to changes in outgoing flux caused by these clouds. Though the emergent flux decreases with a higher cloud coverage, it does not decrease by more than one order of magnitude as the coverage increases from 0% to 90%. This allows LIFE to retain a high sensitivity to the cloud cover fraction for wavelengths longer than 7 microns. In this spectral range, with at least 1 bar of N2, LIFE is able to distinguish cloud cover fractions as small as 10% given an integration time of 24 hours, and yields much better precision with a week-long integration. An integration time of one week also allows the resolution of local variations in spectral flux, which can lead to an easier molecule identification. This ability remains if the planet is a CO2-dominated Venus analog. Partial pressures of N2 lower than 1 bar may create a degeneracy with the cloud cover fraction. LIFE shows promising potential for detecting and characterizing atmospheres even with a high cloud coverage, and retaining a fine sensitivity to relatively small differences in cloud cover fractions.
#### Numerical simulation of electron magnetohydrodynamics with Landau-quantized electrons in magnetar crusts
 - **Authors:** Peter B. Rau, Ira Wasserman
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2411.07948

 - **Pdf link:** https://arxiv.org/pdf/2411.07948

 - **Abstract**
 In magnetar crusts, magnetic fields are sufficiently strong to confine electrons into a small to moderate number of quantized Landau levels. This can have a dramatic effect on the crust's thermodynamic properties, generating field-dependent de Haas-van Alphen oscillations. We previously argued that the large amplitude oscillations of the magnetic susceptibility could enhance the Ohmic dissipation of the magnetic field by continuously generating small-scale, rapidly dissipating field features. This could be important to magnetar field evolution and contribute to their observed higher temperatures. To study this, we performed quasi-3D numerical simulations of electron MHD in a representative volume of neutron star crust matter, for the first time including the magnetization and magnetic susceptibility resulting from Landau quantization. We find that the potential enhancement in the Ohmic dissipation rate due to this effect can be a factor $\sim 3$ for temperatures of order $10^8$ K and $\sim 4.5$ for temperatures of order $5\times 10^7$ K, depending on the magnetic field configuration. The nonlinear Hall term is crucial to this amplification: without it the magnetic field decay is only enhanced by a factor $\lesssim 2$ even at $5\times 10^7$ K. These effects generate a high wave number plateau in the magnetic energy spectrum associated with the small-scale de Haas--van Alphen oscillations. Our results suggest that this mechanism could help explain the magnetar heating problem, though due to the effect's temperature-dependence, full magneto-thermal evolution simulations in a realistic stellar model are needed to judge whether it is viable explanation.
#### The Hubble constant anchor galaxy NGC 4258: metallicity and distance from blue supergiants
 - **Authors:** Rolf-Peter Kudritzki, Miguel A. Urbaneja, Fabio Bresolin, Lucas M. Macri, Wenlong Yuan, Siyang Li, Gagandeep S. Anand, Adam G. Riess
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2411.07974

 - **Pdf link:** https://arxiv.org/pdf/2411.07974

 - **Abstract**
 A quantitative spectroscopic study of blue supergiant stars in the Hubble constant anchor galaxy NGC 4258 is presented. The non-LTE analysis of Keck I telescope LRIS spectra yields a central logarithmic metallicity (in units of the solar value) of [Z] = -0.05\pm0.05 and a very shallow gradient of -(0.09\pm0.11)r/r25 with respect to galactocentric distance in units of the isophotal radius. Good agreement with the mass-metallicity relationship of star forming galaxies based on stellar absorption line studies is found. A comparison with HII region oxygen abundances obtained from the analysis of strong emission lines shows reasonable agreement when the Pettini & Pagel (2004) calibration is used, while the Zaritsky et al. (1994) calibration yields values that are 0.2 to 0.3 dex larger. These results allow to put the metallicity calibration of the Cepheid Period--Luminosity relation in this anchor galaxy on a purely stellar basis. Interstellar reddening and extinction are determined using HST and JWST photometry. Based on extinction-corrected magnitudes, combined with the stellar effective temperatures and gravities we determine, we use the Flux-weighted Gravity--Luminosity Relationship (FGLR) to estimate an independent spectroscopic distance. We obtain a distance modulus m-M = 29.38\pm0.12 mag, in agreement with the geometrical distance derived from the analysis of the water maser orbits in the galaxy's central circumnuclear disk.
#### What drives the HI content of central galaxies -- A comparison between hydrodynamic simulations and observations using Random Forest
 - **Authors:** Xiao Li, Cheng Li, Houjun Mo
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2411.07977

 - **Pdf link:** https://arxiv.org/pdf/2411.07977

 - **Abstract**
 We investigate the driving mechanisms for the HI gas content in star-forming central galaxies at low redshift, by examining the HI-to-stelalr mass ratio ($M_{\rm HI}/M_\ast$) in both the state-of-the-art hydrodynamic simulations, IllustrisTNG (TNG) and EAGLE, and the xGASS sample. We quantify the correlations of $M_{\rm HI}/M_\ast$ with a variety of galaxy properties using the random forest regression technique, and we make comparisons between the two simulations, as well as between the simulations and xGASS. Gas-phase metallicity is found to be most important in both simulations, but is ranked mildly for xGASS, suggesting that metals and gas driven by feedback effects in real galaxies is not as tightly coupled as in the simulations. Beyond that, the accretion rate of supermassive black holes is the most important feature in TNG, while specific star formation rate is the top ranked in EAGLE. This result can be understood from the fact that the HI gas is regulated mainly by thermal-mode AGN feedback in TNG and by stellar feedback in EAGLE. Although neither simulation can fully reproduce the feature importance obtained for real galaxies in the xGASS, EAGLE performs better than TNG in the sense that the observationally top-ranked property, $u-r$, is also highly ranked in EAGLE. This result implies that stellar feedback plays a more dominant role than AGN feedback in driving the HI gas content of low-redshift galaxies.
#### Observing the Meissner effect in neutron stars
 - **Authors:** S. K. Lander, K. N. Gourgouliatos, Z. Wadiasingh, D. Antonopoulou
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2411.08020

 - **Pdf link:** https://arxiv.org/pdf/2411.08020

 - **Abstract**
 We explore the consequences of a new mechanism for the rapid onset of the Meissner effect in a young neutron star, via an interplay of field-line advection by fluid motion and magnetic reconnection. This mechanism provides the first justification for an assumption at the centre of magnetar simulations. Reconnection leads to a characteristic release of energy, which can be used to constrain superconducting gap models. Our model provides a natural explanation for the recently discovered long-period radio sources, and also has important implications for neutron-star rotational evolution and gravitational-wave emission. The Meissner effect is only operative for field strengths $10^{12}\,\mathrm{G}\lesssim B\lesssim 5\times 10^{14}\,\mathrm{G}$.
#### The Meissner effect in neutron stars
 - **Authors:** S. K. Lander
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2411.08021

 - **Pdf link:** https://arxiv.org/pdf/2411.08021

 - **Abstract**
 We present the first model aimed at understanding how the Meissner effect in a young neutron star affects its macroscopic magnetic field. In this model, field expulsion occurs on a dynamical timescale, and is realised through two processes that occur at the onset of superconductivity: fluid motions causing the dragging of field lines, followed by magnetic reconnection. Focussing on magnetic fields weaker than the superconducting critical field, we show that complete Meissner expulsion is but one of four possible generic scenarios for the magnetic-field geometry, and can never expel magnetic flux from the centre of the star. Reconnection causes the release of up to $\sim 5\times 10^{46}\,\mathrm{erg}$ of energy at the onset of superconductivity, and is only possible for certain favourable early-phase dynamics and for pre-condensation fields $10^{12}\,\mathrm{G}\lesssim B\lesssim 5\times 10^{14}\,\mathrm{G}$. Fields weaker or stronger than this are predicted to thread the whole star.
#### The discovery and characterization of minimoon 2024 PT$_5$
 - **Authors:** Bryce T. Bolin, Larry Denneau, Laura-May Abron, Robert Jedicke, Kristin Chiboucas, Carl Ingerbretsen, Brian C. Lemaux
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP)
 - **Arxiv link:** https://arxiv.org/abs/2411.08029

 - **Pdf link:** https://arxiv.org/pdf/2411.08029

 - **Abstract**
 Minimoons are asteroids that become temporarily captured by the Earth-Moon system. We present the discovery of 2024 PT$_5$, a minimoon discovered by the Asteroid Terrestrial-impact Last Alert System (ATLAS) Sutherland telescope on 2024 August 7. The minimoon with heliocentric semi-major axis, $a$$\sim$1.01 au, and perihelion, $q$$\sim$0.99 au, became captured by the Earth-Moon system on 2024 September 29 and left on 2024 November 25 UTC. Visible g, r, i, and Z spectrophotometry was obtained using Gemini North/Gemini Multi-Object Spectrograph (GMOS) on 2024 September 27. The color indices are g-r = 0.58$\pm$0.04, r-i = 0.29$\pm$0.04, i-Z = -0.27$\pm$0.06, and the spectrum best matches lunar rock samples followed by S-complex asteroids. Assuming an albedo of 0.21 and using our measured absolute magnitude of 28.64$\pm$0.04, 2024 PT$_5$ has a diameter of 5.4$\pm$1.3 m. We also detect variations in the lightcurve of 2024 PT$_5$ with a 0.28$\pm$0.07 magnitude amplitude and a double-peaked period of $\sim$2600$\pm$500 s. We improve the orbital solution of 2024 PT$_5$ with our astrometry and estimate the effect of radiation pressure on its deriving an area-to-mass ratio of 7.02$\pm$2.05$\times$10$^{-5}$ m$^2$/kg, implying a density of $\sim$3.9$\pm$2.1 g/cm$^3$, compatible with having a rocky composition. If we assume 2024 PT$_5$ is from the NEO population, its most likely sources are resonances in the inner Main Belt by comparing its orbit with the NEO population model, though this does not exclude a lunar origin.
#### Simulating continuum-based redshift measurement in the \textit{Roman's} High Latitude Spectroscopy Survey
 - **Authors:** Zhiyuan Guo, Bhavin Joshi, Chris. W. Walter, M.A.Troxel
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2411.08035

 - **Pdf link:** https://arxiv.org/pdf/2411.08035

 - **Abstract**
 We investigate the capability of the \textit{Nancy Grace Roman Space Telescope's (Roman)} Wide-Field Instrument (WFI) G150 slitless grism to detect red, quiescent galaxies based on the current reference survey. We simulate dispersed images for \textit{Roman} reference High-Latitude Spectroscopic Survey (HLSS) and analyze two-dimensional spectroscopic data using the grism Redshift and Line Analysis (\verb|Grizli|) software. This study focus on assessing \textit{Roman} grism's capability for continuum-level redshift measurement for a redshift range of $0.5 \leq z \leq 2.5$. The redshift recovery is assessed by setting three requirements of: $\sigma_z = \frac{\left|z-z_{\mathrm{true}}\right|}{1+z}\leq0.01$, signal-to-noise ratio (S/N) $\geq 5$ and the presence of a single dominant peak in redshift likelihood function. We find that, for quiescent galxaies, the reference HLSS can reach a redshift recovery completeness of $\geq50\%$ for F158 magnitude brighter than 20.2 mag. We also explore how different survey parameters, such as exposure time and the number of exposures, influence the accuracy and completeness of redshift recovery, providing insights that could optimize future survey strategies and enhance the scientific yield of the \textit{Roman} in cosmological research.


by olozhika (Xing Yuchen). 


2024-11-14
