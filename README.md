# Sewar

Sewar is a python package aims to compare images' similarity using variety of performance metrics. 


## Implemented metrics
- [x] Mean Squared Error (MSE) 
- [x] Root Mean Sqaured Error (RMSE)
- [x] Peak Signal-to-Noise Ratio (PSNR) [[1]](https://ieeexplore.ieee.org/abstract/document/1284395/)
- [x] Structural Similarity Index (SSIM) [[1]](https://ieeexplore.ieee.org/abstract/document/1284395/)
- [x] Universal Quality Image Index (UQI) [[2]](https://ieeexplore.ieee.org/document/995823/)
- [x] Multi-scale Structural Similarity Index (MS-SSIM) [[3]](https://ieeexplore.ieee.org/abstract/document/1292216/)
- [x] Erreur Relative Globale Adimensionnelle de Synthèse (ERGAS) [[4]](https://hal.archives-ouvertes.fr/hal-00395027/)
- [x] Spatial Correlation Coefficient (SCC) [[5]](https://www.tandfonline.com/doi/abs/10.1080/014311698215973)
- [x] Relative Average Spectral Error (RASE) [[6]](https://ieeexplore.ieee.org/document/1304896/)
- [x] Spectral Angle Mapper (SAM) [[7]](https://ntrs.nasa.gov/search.jsp?R=19940012238)
- [ ] Visual Information Fidelity (VIF) [[8]](https://ieeexplore.ieee.org/abstract/document/1576816/)

## Installation
Just as simple as
```
pip install sewar
```
## Example usage
a simple example to use UQI
```python
>>> from sewar import uqi
>>> uqi(img1,img2)
0.9586952304831419
```
## References
[1] "Image quality assessment: from error visibility to structural similarity." 2004)
[2] "A universal image quality index." (2002)
[3] "Multiscale structural similarity for image quality assessment." (2003)
[4] "Quality of high resolution synthesised images: Is there a simple criterion?." (2000)
[5] "A wavelet transform method to merge Landsat TM and SPOT panchromatic data." (1998)
[6] "Fusion of multispectral and panchromatic images using improved IHS and PCA mergers based on wavelet decomposition." (2004)
[7] "Discrimination among semi-arid landscape endmembers using the spectral angle mapper (SAM) algorithm." (1992)
[8] "Image information and visual quality." (2006)
