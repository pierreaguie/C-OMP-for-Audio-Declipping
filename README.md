# C-OMP-for-Audio-Declipping

The project comprise the following

- .ipynb file implementing Gabor dictionnary and Constrained OMP algorithm enabling sparse representation of clipped time series. The notebook also runs the experiments leading to the results presented in the report
- A processed_sounds folder, containing :
        - a speech folder : 50 ten secondes speech, sampling frequency = 16kHz
        - a music folder : 5 recordings per instrument, including cello, violin, piano or accoustic guitar (8 instruments).
- A results folder containing the SNRm and SDR of different instruments' singnals
- A large_inpainting folder containing the inpainted wav files of larger signals (use of OLA and C-OMP).  


