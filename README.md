# Acoustic-Source-Localization

Hi all! 
I am trying to create a deep learning framework to for localization of monopole acoustic sources. I am using a microphone array to gather information
about the sources in the form of the cross-spectral matrix and then using it to train the neural network. The area over which the sources are distributed
(1m x 1m) is divided into a uniform grid. Each model is trained for a particular number of sources and a particular frequency. 
