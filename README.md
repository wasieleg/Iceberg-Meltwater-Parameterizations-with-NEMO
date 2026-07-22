# ANHA4 Iceberg Meltwater Parameterizations

This repository contains the analysis and post-processing notebook developed to investigate the impact of two different iceberg meltwater release parameterizations in the NEMO ocean model.

The analyses compare two simulations:

* **ANHA4-EJM010**: iceberg meltwater is released at the ocean surface.
* **ANHA4-EJM012**: iceberg meltwater is distributed vertically along the iceberg keel.

The objective of this repository is to provide the codes used to process the model outputs, perform the analyses, and generate the diagnostics used to investigate the physical and biogeochemical differences arising from these two representations of iceberg meltwater release.

## Model configuration

Both simulations were performed with **NEMO v3.6** (Madec and the NEMO Team, 2008), coupled to the **LIM2** sea ice model (Fichefet and Maqueda, 1997) and the **Biogeochemistry with Light, Iron, Nutrients and Gases (BLING)** model (Galbraith et al., 2010).

The simulations use the **Arctic and Northern Hemisphere Atlantic (ANHA4)** configuration, with a horizontal resolution of **1/4°** and **50 vertical levels**. The computational domain covers the Arctic Ocean and the North Atlantic, with open boundaries at the **Bering Strait** and at **20°S** in the Atlantic Ocean.

The scripts included in this repository reproduce the analyses presented in the associated manuscript and are intended to facilitate transparency and reproducibility of the study.

