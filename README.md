# Fourier_Radial_Error_Spectrum_Plot

Author: Kanghyun Ryu (kanghyun@stanford.edu)

Python version of Fourier Radial Error Spectrum Plot in 

T. H. Kim and J. P. Haldar, “The Fourier Radial Error Spectrum Plot: A More Nuanced Quantitative Evaluation of Image Reconstruction Quality,” 2018 Ieee 15th Int Symposium Biomed Imaging Isbi 2018, vol. 2018, pp. 61–64, 2018.

The original MATLAB code can be downloaded from : https://mr.usc.edu/download/esp/ (with request)

This is my rough python code that similarily replicates the MATAB code above.

Usage: 
xi, err_i = esp(im_corrupted, im_ref)
plt.plot(xi,err_i)
