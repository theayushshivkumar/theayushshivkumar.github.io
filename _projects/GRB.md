---
layout: page
title: Investigating the E<sub>peak</sub>–&alpha; Correlation in Gamma-Ray Burst Spectra
description: Minor Degree Project • IISER Thiruvananthapuram (2025–2026) • Submitted to The Astrophysical Journal
img: assets/img/Epeak-alpha_correlation.png
importance: 3
related_publications: false
---

## Overview

This project was carried out as part of my **Minor Degree in Data Science** at the **Indian Institute of Science Education and Research (IISER) Thiruvananthapuram**, under the supervision of **Dr. Shabnam Iyyani**.

The work was conducted in close collaboration with **Dr. Pragyan Pratim Bordoloi**, whose guidance and mentorship were invaluable throughout the project. His expertise in high-energy astrophysics and numerical modelling greatly shaped this work and made the project possible.

The resulting manuscript has been **submitted and is under review**. Currently available on **arXiv**.

---

## Scientific Motivation

Gamma-Ray Bursts (GRBs) are among the most energetic explosions observed in the Universe. Although their prompt emission spectra are commonly described using empirical models such as the Band function, the underlying physical processes responsible for these spectra remain an active area of research.

This project investigated the observed correlation between the spectral peak energy (E<sub>peak</sub>) and the low-energy spectral index (&alpha;) from a bottom-up radiative modelling approach, with the aim of determining whether this relationship naturally emerges from a physically motivated emission model based on **optically thin inverse Compton scattering (ICS)**.

---

## Techniques

During this project, I gained experience in

- Building a physically consistent bottom-up simulation framework for optically-thin GRBs
- Spectral fitting of Fermi-GBM observations with MCMC and Maximum Likelihood Estimation
- Temporal binning (Bayesian Block, Constant Fluence)
- Numerical radiative-transfer simulations
- Inverse Compton scattering modelling
- Parameter estimation and optimisation
  
---

## Key Findings

- Demonstrated that the observed E<sub>peak</sub>–&alpha; correlation can be naturally reproduced using an optically-thin inverse Compton scattering model without requiring ad hoc assumptions.
- Successfully modelled both **hard-to-soft** and **intensity-tracking** spectral evolution commonly observed in GRBs.
- Investigated the temporal evolution of several underlying physical parameters governing the emission region, providing a physically consistent interpretation of the observed spectral behaviour.
- Showed that empirical Band-function parameters can be linked to physically meaningful quantities within the emission model, offering improved insight into the origin of GRB prompt emission.

---

## Some Interesting Figures

<div class="row justify-content-center">

<div class="col-sm-10">

{% include figure.liquid
path="assets/img/temporal_bin_epeak.png"
class="img-fluid rounded z-depth-1"
%}

</div>

</div>

<div class="caption">

(Adopted directly from P. P. Bordoloi et al. (2026); under review) **Temporal Binning Scheme and Corresponding Epeak Evolution** Panels (a) and (b) show the hard-to-soft E<sub>peak</sub> evolution case, while panels (c) and (d) correspond to the intensity-tracking E<sub>peak</sub> evolution. In each panel, the green solid curve represents the underlying Norris pulse used to model the flux evolution, and the red solid curve represents E<sub>peak</sub> evolution. The vertical magenta dashed lines indicate the edges of the main time-resolved bins obtained using the two binning methods (constant fluence: (a), (c) and Bayesian blocks: (b), (d) ), whereas the thin grey vertical dotted lines mark the fine bins introduced within each main bin. The green points denote the average flux in each fine bin, and the red points indicate the corresponding average E<sub>peak</sub> values. The red shaded regions represent time intervals where the flux falls below the adopted detector threshold and are excluded from the analysis.

</div>

<br>

<div class="row justify-content-center">

<div class="col-sm-10">

{% include figure.liquid
path="assets/img/Band_fits.png"
class="img-fluid rounded z-depth-1"
%}

</div>

</div>

<div class="caption">

(Adopted directly from P.P.Bordoloi et al. (2026); under review) Counts and residual plots (left panels) and corresponding νFν spectra (right panels) for the peak bin in the hard-to-soft and intensity-tracking spectral-evolution cases using constant-fluence binning.

</div>

<br>

<div class="row justify-content-center">

<div class="col-sm-10">

{% include figure.liquid
path="assets/img/Epeak-alpha_correlation.png"
class="img-fluid rounded z-depth-1"
%}

</div>

</div>

<div class="caption">
 
(Adopted directly from P.P.Bordoloi et al. (2026); under review) (a) E<sub>peak</sub>–&alpha; correlation for the hard-to-soft E<sub>peak</sub> evolution case. Green circles and violet squares represent the results obtained using Bayesian block and constant-fluence binning, respectively. The corresponding dashed curves show the best-fit Hill functions. (b) Same as panel (a), but for the intensity-tracking E<sub>peak</sub> evolution case. Magenta pentagons and cyan squares denote the Bayesian block and constant-fluence binning results, respectively, with the dashed curves showing the corresponding best-fit Hill functions. 

</div>

---

## Skills Developed

- Numerical modelling techniques
- Bayesian analysis techniques
- Fitting techniques (MLE, MCMC)
- Parameter inference
- Link between numerical simulations and observed data
- Scientific writing
