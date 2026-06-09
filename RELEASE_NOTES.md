# Release notes

## astrosilicate

Standalone, self-contained rewrite of `NiftyCodeExample.ipynb` and a new extinction-law section.

- **Fully standalone notebook.** The example now reproduces the Galactic-Center (Sgr A\*) mid-infrared
  dust-continuum and dust-temperature-distribution model end-to-end with **no external files**. The
  observed spectrum, the silicate optical-depth template (Donnan 2023 / Smith), the dust emissivity
  (Li & Draine 2001, via Donnan 2023), the Fritz et al. 2011 law, and the von Fellenberg et al. 2025
  law are all baked in as inline arrays.
- **Variable silicate extinction.** A second correlated field models the multiplicative deviation
  $\Delta\tau(\lambda)$ from the silicate template, so the silicate profile is fit rather than fixed.
- **Derived extinction law.** A new section computes the MIR extinction
  $A(\lambda) = 2.5\,\log_{10}(F_\mathrm{intrinsic}/F_\mathrm{observed})$ from the posterior (median and
  16–84% band) and compares it **raw (uncalibrated)** to Fritz et al. 2011 and von Fellenberg et al. 2025.
  The absolute spectral calibration is performed in von Fellenberg et al. 2025 against hydrogen
  recombination-line ratios (see paper); only the shape is constrained here.

Please cite von Fellenberg et al. 2025, Michail et al. 2025, and nifty8.re.
