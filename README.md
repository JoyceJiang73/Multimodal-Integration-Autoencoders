# Multimodal-Integration-Autoencoders

This repo contains code that supports the replication of the research article 'A Deep Neural Network Approach for Integrating Neural and Behavioral Signals: Multimodal Investigation with fNIRS Hyperscanning and Facial Expressions' (Miao, Jiang, Binnquist et al., 2024) for the Proceedings of the Annual Meeting of the Cognitive Science Society.

The multimodal integration pipeline comes with two steps:
1. **S2S-RNN-Autoencoder:** Vectorizes each modality separately (e.g., facial AUs and fNIRS) to the unimodal embeddings.
2. **FCN-Autoencoder:** Integrates the vectorized unimodal embeddings.

## Data Preprocess
This [notebook](https://github.com/JoyceJiang73/Multimodal-Integration-Autoencoders/blob/main/Data%20Preprocessing.ipynb) illustrates how to reshape extracted features to be prepared for S2S-RNN-Autoencoders.

## Autoencoder 
This [notebook](https://github.com/JoyceJiang73/Multimodal-Integration-Autoencoders/blob/main/Autoencoders%20(Unimodal%20and%20Multimodal).ipynb) contains the two models for unimodal and multimodal processing.
