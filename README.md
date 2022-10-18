# Music-Speech-Classification

A set of training and test examples of music and speech are
provided.
http : //www.leap.ee.iisc.ac.in/sriram/teaching/MLSP22/assignments/speechMusicData.tar.gz
Using these examples,
Generate spectrogram features - Use the log magnitude spectrogram as before with
a 64 component magnitude FFT (NFFT). In this case, the spectrogram will have
dimension 32 times the number of frames (using 25 ms with a shift of 10 ms).
Perform a K-means clustering on the spectrogram.

Using the above HMM model as initialization, perform the Baum-Welch reestimation
method to train HMMs with all the HMM training examples for speech and for music
(two different HMMs)
