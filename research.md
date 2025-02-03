---
layout: page
title: Research
---

## Summary
I am broadly interested in galactic archaeology. My graduate work has led to a focus on observed multi-element stellar abundance patterns and scatter across the Milky Way, and interpreting them to understand the chemical evolution of the Galaxy and nucleosynthetic origins of the elements.

Read below for more details on my research! I also have an ADS library of my first-author papers [here](https://ui.adsabs.harvard.edu/search/q=docs(library%2FF836HkVxQEuV4XQMSlMtdQ)&sort=date%20desc%2C%20bibcode%20desc&p_=0).

### Abundance Variations in the High-α Plateau
Stars in the Milky Way disk exhibit a bimodal distribution in [α/Fe], with "high-α" stars commonly being associated with the older kinematic thick disk. The higher [α/Fe] ratios of these stars are indicative of more chemical enrichment from core-collapse supernovae (CCSN) relative to Type Ia supernovae (SNIa), but it is unclear whether this elevated ratio reflects pure CCSN enrichment or a mix of CCSN and SNIa. Patterns in the abundance variations between elements with different nucleosynthetic origins can help distinguish these scenarios. 

In this work, we use the two-process model (see [Weinberg et al. 2022](https://ui.adsabs.harvard.edu/abs/2022ApJS..260...32W/abstract)), which expresses a star’s multi-element abundance pattern as a sum of a prompt CCSN process and a delayed SNIa process, on calibrated abundances from APOGEE DR17 ([Sit et al. 2024](https://ui.adsabs.harvard.edu/abs/2024ApJ...970..180S/abstract)) to investigate the origin of abundance scatter within the high-α MW disk. The two-process model predictions are independent of the [Mg/Fe] ratio associated from pure CCSN enrichment. Within the high-α population, the observed abundance scatter of the Fe-peak elements is correlated with the SNIa/CCSN ratio inferred by the two-process model, indicating that variation in SNIa/CCSN is a significant source of scatter in this population. Many elements show additional scatter that may be explained by underestimated observational uncertainty or additional enrichment processes. Covariances between different elements may contain information on additional processes, but are difficult to interpret when current measurement errors are of similar magnitude to the variation.

Paper: coming soon!

### Calibrated abundances and two-process parameters for APOGEE DR17
Stellar abundance measurements are subject to systematic errors that induce extra scatter and artificial correlations in elemental abundance patterns. We derived empirical calibration offsets to remove the systematic trends with *log(g)* in 17 elemental abundances of 288,789 evolved stars from APOGEE DR17. We fit these corrected abundances with a two-process model (see [Weinberg et al. 2022](https://ui.adsabs.harvard.edu/abs/2022ApJS..260...32W/abstract)), recasting each star’s measurements into "process amplitudes" that correspond to a prompt CCSN process and a delayed SNIa process, and the element-by-element residuals from this fit.

The catalog with corrected APOGEE abundances, two-process amplitudes, and residual abundances is 8 times larger than that of previous analyses that used a restricted *log(g)* range. As a first application of this larger catalog, we examined the median residual abundances of 14 open clusters, 9 globular clusters, and 4 dwarf satellite galaxies, but we hope it will be useful for many more studies on abundance patterns in different stellar populations or across the Milky Way, identifying additional enrichment channels, and testing galactic chemical evolution models. The catalog is publicly available on [Zenodo](https://doi.org/10.5281/zenodo.10659204).

Paper: [Sit et al. 2024, ApJ, 970, 180](https://ui.adsabs.harvard.edu/abs/2024ApJ...970..180S/abstract)

### Previous Projects
Below you can find summaries of my undergraduate and post-baccalaureate projects.
<details><summary style="font-size:1rem; font-weight:bold">Long-rising Type II (1987A-like) supernovae in the Zwicky Transient Facility</summary>

SN 1987A was an unusual hydrogen-rich core-collapse supernova originating from a blue supergiant star. Similar blue supergiant explosions are a small family of events, and are broadly characterized by their long rises to peak brightness. The Zwicky Transient Facility Census of the Local Universe (CLU) experiment aims to construct a spectroscopically complete sample of transients occurring in galaxies from the CLU galaxy catalog. We identify 13 long-rising (>40 days) Type II SNe from the volume-limited CLU experiment during a 3.5 year period from 2018 June to 2021 December, approximately doubling the previously known number of these events. We present photometric and spectroscopic data of these 13 events, finding peak r-band absolute magnitudes ranging from -15.6 to -17.5 mag and the tentative detection of Ba II lines, which were unusually strong in SN 1987A, in nine events. Using our CLU sample, we derive a the first volumetric rate of these events from a large, systematic, volume-limited experiment and find that long-rising Type II SNe occur at ≈1.4% of the total CCSN rate.

Paper: <a href="https://ui.adsabs.harvard.edu/abs/2023ApJ...959..142S/abstract">Sit et al. 2023, ApJ, 959, 142</a>

</details>

<details><summary style="font-size:1rem; font-weight:bold">Halo RR Lyrae in CFTLS Deep Field photometry</summary>

RR Lyrae are old, short-period variable stars that are excellent tracers of the Milky Way's stellar halo because they are standard candles through their period-luminosity-metallicity relation and have a characteric light curve shape that makes them relatively easy to identify. We use the multi-band timeseries data from the Canada-France-Hawaii Telescope Legacy Survey (CFHTLS) Deep Fields to find RR Lyrae and separate them from active galactic nuclei (AGN) and quasars, which are significant sources of contamination when identifying faint RR Lyrae. Objects likely to have true intrinsic variation are identified through error characteriziation and sigma clipping. The Lomb-Scargle periodogram is used to detect periodic signals in these objects, and the periods are then used to create phase-folded light curves for visual vetting and further analysis. As a proof of concept, two known RR Lyrae from the Pan-STARRS1 (PS1) 3π survey were identified in the CFHTLS data and processed to produce high-cadence phase-folded light curves.

A poster of this work was presented at AAS 240 in June 2022 by high school students Joanne Zhao and Christopher Donnelly, who I mentored through UC Santa Cruz's <a href="https://sip.ucsc.edu/">Science Internship Program</a> in summer 2021!

</details>

<details><summary style="font-size:1rem; font-weight:bold">The age distribution of stars in the MW bulge</summary>

Data-driven methods and large surveys enable stellar ages and precision chemical abundances to be determined for vast regions of the Milky Way. We use the data-driven approach of <a href="https://ui.adsabs.harvard.edu/abs/2015ApJ...808...16N/abstract"><em>The Cannon</em></a> to infer the ages and abundances for 125,367 stars using spectra from APOGEE DR14. We examine the ages and metallicities of 1654 bulge stars within a Galactic radius of 3.5 kpc and found that stars in the bulge are about twice as old compared to those in the solar neighborhood, with a larger scatter in metallicity [Fe/H]. The age gradient comes primarily from the low-α stars. Along the Galactic plane, the most central field in the bulge shows by far the largest dispersion in [Fe/H] and line-of-sight velocity, and simultaneously the smallest dispersion in age. Moving out in Galactic longitude, the stars become kinematically colder and less dispersed in [Fe/H], but show a much broader range of ages.

Paper: <a href="https://ui.adsabs.harvard.edu/abs/2020ApJ...900....4S/abstract">Sit & Ness 2020, ApJ, 900, 1</a>

</details>

<details><summary style="font-size:1rem; font-weight:bold">Data-driven methods of measuring stellar compositions from Keck spectroscopy</summary>

Stellar abundances are traditionally measured from spectra by fitting the observed line strengths to synthetic spectra, which partially depend on highly uncertain atomic data and make assumptions that can be overly simplistic. On the other hand, data-driven methods to measure abundances do not rely directly on the underlying physics of stellar spectra. In this project, we used the data-driven code <a href="https://ui.adsabs.harvard.edu/abs/2015ApJ...808...16N/abstract"><em>The Cannon</em></a> to measure the abundances of stars observed by the DEIMOS spectrograph on the Keck telescope. We create a combined dataset of DEIMOS spectra of stars from nearby globular clusters and dwarf galaxies with known abundance measurements from <em>ab initio</em> spectral synthesis, then train <em>The Cannon</em> on the highest signal-to-noise spectra. We assess the ability of <em>The Cannon</em> to recover the effective temperatures, metallicities, and the abundances of Mg, Si, Ca, and Ti by comparing the original values to those returned by <em>The Cannon</em> and find that <em>The Cannon</em> performs more poorly than expected at lower signal-to-noise.

</details>