# Deeplearning_ECG
Code to the paper "A novel application of Deep Learning for single-lead ECG Classification"

Abstract: Detecting and classifying cardiac arrhythmias is critical to the diagnosis of patients with cardiac abnormalities. In this paper, a novel approach based on deep learning methodology is proposed for the classification of single-lead electrocardiogram (ECG) signals. We demonstrate the application of the Restricted Boltzmann Machine (RBM) and deep belief networks (DBN) for ECG classification following detection of ventricular and supraventricular
heartbeats using single-lead ECG. The effectiveness of this proposed algorithm is illustrated using real ECG signals from the widely-used MIT-BIH database. Simulation results demonstrate that with a suitable choice of
parameters, RBM and DBN can achieve high average recognition accuracies of ventricular ectopic beats (93.63%) and of supraventricular ectopic beats (95.57%) at a low sampling rate of 114 Hz. Experimental results indicate
that classifiers built into this deep learning-based framework achieved state-of-the-art performance models at lower sampling rates and simple features when compared to traditional methods. Further, employing features
extracted at a sampling rate of 114 Hz when combined with deep learning provided enough discriminatory power for the classification task. This performance is comparable to that of traditional methods and uses a much lower
sampling rate and simpler features. Thus, our proposed deep neural network algorithm demonstrates that deep learning-based methods offer accurate ECG classification and could potentially be extended to other physiological
signal classifications, such as those in arterial blood pressure (ABP), nerve conduction (EMG), and heart rate variability (HRV) studies.


Dataset I used while implementing: MIT-BIH Arrhythmia Database https://physionet.org/content/mitdb/1.0.0/
