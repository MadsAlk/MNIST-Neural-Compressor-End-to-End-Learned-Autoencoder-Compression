# MNIST-Neural-Compressor-End-to-End-Learned-Autoencoder-Compression
A TensorFlow implementation of learned lossy compression for MNIST digits, optimizing the rate-distortion tradeoff using autoencoders and entropy coding.


![Example Compression Results](compression.png)

Overview
This project implements a neural data compression system specifically designed for MNIST handwritten digits. The model combines an autoencoder architecture with entropy coding to achieve efficient compression while maintaining reconstruction quality. Key capabilities include optimizing the rate-distortion tradeoff through differentiable training, a complete compression/decompression pipeline, and visualization tools to compare original and reconstructed digits. The system also exhibits generative properties - feeding random bitstrings through the decoder produces novel digit-like images. Compression strength can be precisely controlled via the lambda hyperparameter, allowing users to balance between compression ratio and reconstruction fidelity for their specific needs.
