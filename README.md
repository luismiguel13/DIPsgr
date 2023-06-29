# DIPsgr

This repository pertains to the paper titled "Shot-gather Reconstruction using a Deep Data Prior-based Neural Network Approach" and serves as an example, documenting the outcomes of the synthetic seismic data acquisition in split-spread geometry.

## Content

* <span id="Notebook">Notebook</span>

* <span id="Data">Data</span>

## Summary

We propose DIPsgr, a seismic shot-gather reconstruction method that uses only the incomplete seismic acquisition measurements to estimate their missing information employing unsupervised deep learning with a U-Net 3D architecture. 

![Aquí la descripción de la imagen por si no carga](https://github.com/luismiguel13/DIPsgr/blob/main/images/sland.png)

Numerical experiments on three databases demonstrate that DIPsgr recovers the complete set of traces in each shot-gather, with preserved information and seismic events.

![Aquí la descripción de la imagen por si no carga](https://github.com/luismiguel13/DIPsgr/blob/main/images/sland.png)

Figure. (a) Ground truth for the shot-gather 8 in Dataset I: Synthetic split-spread, and the interpolation results with (b) DIPsgr (proposed), (c) IL, (d) DSPRecon, and (e) CE method. (f-i) Normalized difference for each method, respectively.

