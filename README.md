# **BrainWave-Scattering Net: A Lightweight Network for EEG-based Motor Imagery Recognition**

##Journal of Neural Engineering (JNE)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Published in Journal of Neural Engineering (<strong>JNE</strong>), 2023 - [Paper](https://iopscience.iop.org/article/10.1088/1741-2552/acf78a)

Authors: <strong>Konstantinos Barmpas</strong>, Yannis Panagakis, Dimitrios Adamos, Nikolaos Laskaris and Stefanos Zafeiriou 

---

Brain-computer interfaces (BCIs) enable a direct communication of the brain with the external world, using one's neural activity, measured by electroencephalography (EEG) signals. In recent years, Convolutional Neural Networks (CNNs) have been widely used to perform automatic feature extraction and classification in various EEG-based tasks. However, their undeniable benefits are counterbalanced by the lack of interpretability properties as well as the inability to perform sufficiently when only limited amount of training data is available. In this work, we introduce a novel, lightweight, fully-learnable neural network architecture that relies on Gabor filters to delocalize EEG signal information into scattering decomposition paths along frequency and slow-varying temporal modulations. We utilize our network in two distinct modeling settings, for building either a generic (training across subjects) or a personalized (training within a subject) classifier. In both cases, using two different publicly available datasets and one in-house collected dataset, we demonstrate high performance for our model with considerably less number of trainable parameters as well as shorter training time compared to other state-of-the-art deep architectures. Moreover, our network demonstrates enhanced interpretability properties emerging at the level of the temporal filtering operation and enables us to train efficient personalized BCI models with limited amount of training data.

---
