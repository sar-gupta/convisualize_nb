# convisualize
Visualizations for Convolutional Neural Networks (CNNs) in Pytorch

The corresponding article can be found [here](https://medium.com/@thesemicolonguy/dl05-convolutional-neural-networks-1d3bb7fff586)!

## Requirements:
* Pytorch
* Torchvision
* Numpy
* Matplotlib
* Pillow

Note: In case you don't have a GPU, remove all instances of "cuda" and "cpu" from the notebook before running.

## TODO
- [X] Layer Outputs at all layers
- [X] Filter outputs at a given layer
- [X] Filter visualization at a given layer
- [X] Image heatmap using Occlusion
- [ ] Image heatmap using Grad Cam
- [X] Class specific saliency maps
- [X] SmoothGrad
- [ ] Semantic segmentation using GrabCut
- [X] Visualization of class models (Gradient Ascent)
- [ ] Regularization techniques for class models (L2, Clip, Blur, etc.)
- [ ] Guided Backprop
- [ ] Filter visualization (Gradient Ascent)
- [ ] Neural Texture Synthesis
- [ ] Deep Dream
- [ ] Neural Style Transfer

## References
* [cs231n](http://cs231n.github.io/understanding-cnn/ "Stanford's cs231n course")
* [cs231n Lecture 12](http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture12.pdf "Visualizing and Understanding")
* [Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps](https://arxiv.org/abs/1312.6034) Karen Simonyan, Andrea Vedaldi, Andrew Zisserman
* [Visualizing and Understanding Convolutional Networks](https://arxiv.org/abs/1311.2901) Matthew D Zeiler, Rob Fergus
* [SmoothGrad: removing noise by adding noise](https://arxiv.org/abs/1706.03825) Daniel Smilkov, Nikhil Thorat, Been Kim, Fernanda Viégas, Martin Wattenberg
* [Texture Synthesis Using Convolutional Neural Networks](https://arxiv.org/abs/1505.07376) Leon A. Gatys, Alexander S. Ecker, Matthias Bethge
