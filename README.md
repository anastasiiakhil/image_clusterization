# Images clusterization

This project is based on the [article](https://towardsdatascience.com/how-to-cluster-images-based-on-visual-similarity-cd6e7209fe34).
The main purpose is to use a pre-trained neural network to extract a feature vectors from images and cluster the images based on how similar the feature vectors are.
So in this research, I use the __VGG16__, __VGG19__, __ResNet50__ neural networks for feature extraction, __PCA__ for reducing the dimensions of our feature vectors and the __KMeans__ algorithm for clustering.

### Environment settings and running jupyter notebook

```
virtualenv venv -p python3
. venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```
### Result 
Unsupervised dividing of input images into classes based on visual similarity.