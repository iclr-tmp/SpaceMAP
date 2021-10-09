# SpaceMAP

This repo is the implementation of SpaceMAP for the ICLR 2022 submission: 'SpaceMAP: Visualizing Any Data in 2-dimension by Space Expansion' 
* link: https://openreview.net/forum?id=wmQCFqV9r8L

SpaceMAP IS a novel dimensionality reduction method based on space geometry and hierarchical manifold approximation.💫

It can handle both clustered and continuous datasets with both local and global structure preserved.🍀 The computational performence is also competitive.🚀

## Key Features

SpaceMAP holds two ideas: 
1. Space geometry is all you need (to map any data in any dimension).
2. Datasets are mostly hierarchical and lie on manifolds with different scales.

## Embedding Results

### Results comparison

* t-SNE method is initialized with PCA. UMAP is initialized with Spectral Embedding.

![result 1](/images/multi-datasets-results.png)

### Portrait of A Million

* The implementation is derived from the UMAP paper and the following link: https://johnhw.github.io/umap_primes/index.md.html

SpaceMAP shows amazing fractal-like embedding result according to the divisibility by primes. Intuitively, fractal is the space projection of chaos, and chaos is the time expression of fractal. The fractal shape provided by SpaceMAP shows the divisibility chaos when it comes to large numbers.

![result 1](/images/1e6.png)

### GoogleNews word2vec

While being glued with each other in UMAP, the hierarchical structure of the subclusters is well preserved by SpaceMAP. As for the country names, SpaceMAP gather most of the them in a huge cluster and then separate them into sub-clusters based on the geographic and culture relationships between the countries. 

![result 1](/images/w2v.png)


