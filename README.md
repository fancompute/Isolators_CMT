# Optical isolators through dynamic modulation

We compute the transmission spectra within coupled-mode theory for the ring-based optical isolators discussed in:

```
[1] Yu and Fan, Nature Photonics, 3 (2009)
[2] Shi et al. IEEE JSTQE, 24 (2018)
[3] Sounas et al., Nature Comm., 4 (2013)
[4] Sounas and Alu, ACS Photonics, 1 (2014)
```

In the notebook `Yu_and_Shi`, we reproduce the results from [1]-[2]. It is found that the theory of [2] is incomplete as it does not include the coupling through the environment due to emission in the same waveguide. This can be neglected in many cases, and we reproduce the result of [2] within that framework. However, even though the system is essentially the same, the theory of [2] yields unphysical results for the system of [1]. We then analyze [1] within rotating-wave approximation, and also within a "fixed" version of the theory of [2].

In the notebook `Sounas` we reproduce the results for the system of [3]-[4] using the CMT equations given in the SI of [4]. We use the same variables and units as in our analysis of [1]-[2] for easier comparison.
