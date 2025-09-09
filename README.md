# MIR-Extinction

This package provides the raw fitting package used to derived the Galactic Center MIR extinction, which was published in von Fellenberg et al. 2025, and Michail et al. 2025. 
It uses the nifty frame work to fit flexible Gaussian Fields modeling the dust opactiy function $\tau(\lambda)$ and the dust temperature optical depth at $\lambda=9.8 \mu m$ ($\Psi(T,\tau_{9.8}$)). It is based upon Donnan et al. 2024 and references therein.

Please feel free to make use of this code as you see fit, please reference the von Fellenberg et al. 2025, Michail et al. 2025, as well as the nifty packages and Donnan et al. 2024. 

The code illustrates how to fit a dust continuum model. We do not model PHA emission and stellar contributions. However, the code could easily be extended to model this emission components as well. In its current format it fits only 1D spectra. With extra work, it could be extended to fit full 3D data cubes.

