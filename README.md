# Diagonal Cross Generation

This project aims to develop a deep learning model that effectively integrates and learns from multimodal biological data—specifically RNA sequencing data and antibody-derived tags (ADT). The ultimate goal is to predict ADT outputs based on RNA inputs, which can have significant implications in understanding cellular functions and interactions in biological research.

I implemented a variational autoencoder (VAE) architecture, which includes separate encoders and decoders for RNA and ADT data modalities. The encoders transform the input data into a latent space representation, capturing the essential features of each modality. The decoders then attempt to reconstruct the original input from these latent space representations.
