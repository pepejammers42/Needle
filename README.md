# Needle

A small deep learning framework with GPU acceleration via Metal (Apple Silicon) and CUDA.

Good things that it does from scratch :D :
- **GPU Acceleration**: Metal and CUDA backends
- **Neural Networks**: Transformers, CNNs, RNNs, basic layers
- **Automatic Differentiation**: Built-in autograd system
- **Operations**: Matrix ops, convolutions, activations, losses

This is also a full writethrough of the dlsys course from CMU, but with a port to Metal kernel as well.

Unfortunately there are no checkpointing implemented, the transformer with the ptb dataset will _most likely_ run out of memory on your graphics card.