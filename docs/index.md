# Dimensionality Reduction using Autoencoders and t-SNE

WIP (Being continuously updated)

Autoencoders are an effective way to learn representations, and reduce them to a latent representation. The decoder part of an autoencoder reduces the input to a latent representation of size less than the input dimensions. The latent representation should be large enough so that the decoder part of the autoencoder can reconstruct the input from the latent space. Therefore, we need to use t-SNE to further reduce the representation to 2 or 3 dimensions so that we can visualize it and figure out how the autoencoder groups the inputs.