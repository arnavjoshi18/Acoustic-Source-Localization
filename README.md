# Acoustics-Based Detection and Tracking of Aircraft Wakes

Hi all! 

I am trying to build a deep learning framework for localization of monopole acoustic sources as an alternative 
to the conventional method of acoustic beamforming. I am using a virtual microphone array to gather information about the 
sources in the form of the cross-spectral matrix which is then used to train the neural network. The model prediction is 
compared against the ground-truth matrix. Each model is trained for a particular number of sources and a particular frequency. 
