# Latent-Manifold-Visualization
Source code for the [Medium story](https://medium.com/@thienan092/manifold-visualization-9ea16f93f675) "How to visualize Latent Manifold without an Embedding Layer"

## Reproduction
- Step 1: Run `train-model.ipynb` for reconstructing manifold of CIFAR-10 dataset via a resnet18 model. 
- Step 2: Run `sampling.ipynb` for evaluating cohesive values of all pairs of data points that are used to visualize the latent manifold.
- Step 3: Run `Latent Manifold visualization.ipynb` to project cohesive values to n-d Euclidean space.
