# Acoustic-Source-Localization

Hi all! 
I am trying to build a deep learning framework for localization of monopole acoustic sources as an alternative 
to the conventional method of acoustic beamforming. I am using a microphone array to gather information about the 
sources in the form of the cross-spectral matrix and then using it to train the neural network. The area over 
which the sources are distributed (1m x 1m) is divided into a uniform grid. Each model is trained for a particular
number of sources and a particular frequency. 
