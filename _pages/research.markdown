---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults


author_profile: true
classes: wide
title: Research
permalink: /research/

---

# Multifidelity uncertainty quantification in nuclear fusion devices

During nuclear fusion, highly energetic alpha particles will be randomly born as a byproduct of the primary deuterium-tritium reaction. Such particles pose a danger to successful nuclear fusion, as they can escape the confining magnetic field which leads to both fusion plasma cooling as well as potential damage to the fusion device.

<img align="right" width="400" src="images/passing-trapped-3D.png">

Metrics of confinement for these energetic particles, such as loss fraction, require propagating the initial uncertainty in energetic particle birth position and velocity through their governing dynamics. Subsequently, standard Monte Carlo (MC) estimation of confinement properties is costly for even a single configuration, and thus infeasible for outer-loop applications. As a result, estimating energetic particle confinement is currently one of the most costly aspects of stellarator optimization.

To accelerate estimating confinement, we utilize the multifidelity Monte Carlo (MFMC) estimator, which leverages a surrogate model to provide variance reduction compared to MC. Since traditional sources of surrogate models are inappropriate for energetic particle dynamics, we employ a data-driven surrogate model designed specifically for use in a multifidelity context.  This approach has been successful for speeding up estimation of various metrics of confinement across multiple particle tracing times on a single configuration (Wistell-A).

Current work is focused on extending our multifidelity methodology to construct new estimators which can simultaneously leverage multiple sources of variance reduction, with the goal of yielding sufficient speedup to rend tractable outer-loop applications, namely stellarator optimization.

<sup>Relevent publications:</sup>\
&nbsp;&nbsp;&nbsp;&nbsp; <sup> F. Law, A. Cerfon, B. Peherstorfer (2022) Accelerating the estimation of collisionless energetic particle confinement</sup>\
&nbsp;&nbsp;&nbsp;&nbsp; <sup> statistics in stellarators using multifidelity Monte Carlo, *Nucl. Fusion* **62** 076019 [doi.org/10.1088/1741-4326/ac4777](https://doi.org/10.1088/1741-4326/ac4777) </sup>
