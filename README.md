# BPASS_GridFit
### Code to fit measured line fluxes to a grid of photoionization models

This repository contains the grid and emission-line fitting code utilized in Pless+2026 (https://arxiv.org/abs/2610.21232v1).

The theoretical emission line grid samples different values of metallicity $Z$, ionization parameter $\log(U)$, metal-to-dust ratio $\xi$, hydrogen density $\log(n_\text{H})$, and C/O fraction, based on the methodology introduced in Gutkin_2016 (10.1093/mnras/stw1716).
The code then aims to calculate the best-fitting ISM parameters for a given target based on its optical emission lines, compared to a grid of theoretical flux predictions.

The code is optimized for the following emission line grid:

- Stellar population models

  BPASS

  Eldridge+2017

  (https://arxiv.org/abs/1710.02154)

- Photoionization code

  cloudy

  Chatzikos+2023

  (https://arxiv.org/pdf/2308.06396)
