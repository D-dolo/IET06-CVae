# EEG Signal Classification Using Conditional Variational Autoencoders
## Overview
This repository contains the code and dataset for our project on using machine learning for the classification of EEG signals. Our work focuses on leveraging Conditional Variational Autoencoders (CVAEs) along with advanced feature extraction techniques to accurately classify EEG signals for different health conditions.

## Abstract
Machine learning (ML) offers great potential in healthcare, especially in the analysis of complex physiological signals like electroencephalography (EEG). EEG recordings hold valuable insights into neurological function and can aid in diagnosing various conditions. In this work, we explore the use of a Conditional Variational Autoencoder (CVAE) coupled with advanced feature extraction techniques for accurate classification of EEG signals.

Our study involved collecting an EEG dataset and systematically applying diverse feature extraction methods. These methods included Short-time Fourier Transform, Hurst Exponent, Detrended Fluctuation Analysis (DFA), Correlation Dimension (CD), Kolmogorov-Sinai Entropy, and their combinations, which distill distinct characteristics from the EEG signals. The CVAE model was then trained on the extracted features, leveraging the conditional input to learn representations specific to different health conditions.

We rigorously evaluated the performance of our CVAE model in combination with each feature extraction technique. Notably, the methods used enabled the CVAE to achieve remarkable 90-93% results on the unseen test split of the dataset.

These results highlight the promise of CVAEs and the significance of well-suited feature extraction for robust EEG classification. This work could contribute to the development of automated healthcare diagnostic tools.
The CVAE model, combined with our feature extraction techniques, achieved an accuracy of 90-93% on the unseen test split of the EEG dataset.

## Contributing
We welcome contributions to this project. If you have any ideas or improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgements
We thank all contributors and supporters of this project. Special thanks to the authors of the feature extraction methods and the developers of the libraries used in this project.

