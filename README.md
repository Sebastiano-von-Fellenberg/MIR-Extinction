# MIR Extinction Fitting Package

This package provides the raw fitting code used to derive the Galactic Center MIR extinction, as published in:

- von Fellenberg et al. (2025)  
- Michail et al. (2025)

It uses the **NIFTy framework** ([https://gitlab.mpcdf.mpg.de/ift/nifty](https://gitlab.mpcdf.mpg.de/ift/nifty), specifically *nifty8.re*) to fit flexible Gaussian fields modeling:

- the dust opacity function $\(\tau(\lambda)\)$  
- the dust temperature–optical depth at $\(\lambda = 9.8\,\mu\text{m}\), \(\Psi(T, \tau_{9.8})\)$

The methodology is based on Donnan et al. (2024) and references therein.

---

## 📖 Citation

If you make use of this code, please cite:

- von Fellenberg et al. (2025)  
- Michail et al. (2025)  
- the NIFTy packages  
- Donnan et al. (2024)

---

## ✨ Features

- Illustrates how to fit a dust continuum model  
- Does **not** model PAH emission or stellar contributions (though the framework could be extended to include these)  
- Currently fits **1D spectra**  
- With additional work, could be extended to fit full **3D data cubes**

---

## ⚙️ Environments

We provide the conda environments used to run this code:

- `<nifty_conda_env.txt>` – the exact, cluster-specific environment file  
- `<nifty.yml>` – a standard, cross-platform conda environment specification

# MIT License
Copyright (c) 2025 Sebastiano von Fellenberg
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction...
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND...





