# MEA-10-by-10
1. Generate recordings for 3 different cells population low(10), medium(20), high(30) and for each 10 different cells distribution on MEA 10 by 10.
2. As the STFT gives a better performance than, the original data and Fourier/wavelet thresholding, compare the generated data with 
different window lengths by spikesorting and classification.
3. For window lengths compare the STFT thresholding with the original data. In this case, the performance is at least equal to the original data with
1%-sparsity(in some cases for the right choice of the window length and type even better). Moreover, removing detected cells with lower SNR values via 
spike sorting gives a complete match with the ground truth data given by neuron classification.
