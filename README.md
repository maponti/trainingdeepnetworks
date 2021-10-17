# Training Deep Networks from Zero to Hero: avoiding pitfalls and going beyond

### A Tutorial presented at SIBGRAPI 2021

### Moacir Antonelli Ponti, Fernando Pereira dos Santos, Leo Sampaio Ferraz Ribeiro, Gabriel Biscaro Cavallari

Paper (extended version): https://arxiv.org/abs/2109.02752

**Abstract**: Training deep neural networks may be challenging in real world data. Using models as black-boxes, even with transfer learning, can result in poor generalization or inconclusive results when it comes to small datasets or specific applications. This tutorial covers the basic steps as well as more recent options to improve models, in particular, but not restricted to, supervised learning. It can be particularly useful in datasets that are not as well-prepared as those in challenges, and also under scarce annotation and/or small data. We describe basic procedures: as data preparation, optimization and transfer learning, but also recent architectural choices such as use of transformer modules, alternative convolutional layers, activation functions, wide and deep networks, as well as training procedures including as curriculum, contrastive and self-supervised learning.

## Content

1. How to Start: Basic Checklist - [slides](Part1-Moacir/sibgrapi_tutorial_21_Part_1_Moacir.pdf)
	* Input representation
	* Normalization
	* Data quality
	* Loss function choice
	* Feature projection/visualization
	* Model tuning
	* Validation and evaluation

2. Common Issues - [notebooks](Part1-Moacir/)
	* Data quality 
	* Small datasets
	* Imbalanced data
	* Overfitting/underfitting
	* Sensitivity to attack

3. Architecture Options [notebook](3.\ Architecture\ Options/)
	* Convolutions
	* Width X Depth in Networks
	* Pooling and subsampling
	* Attention mechanism and transformers

4. Improving Optimization
	* Algorithms
	* Learning rate scheduling
	* Layer-wise normalization
	* Regularization and dropout
	* Data augmentation

5. Basic training procedures
	* Transfer learning and fine-tuning
	* Feature extraction

6. Advanced training procedures
	* Curriculum Learning
	* Contrastive Learning [notebook](6.2.\ Contrastive\ Learning/)
	* Self-supervising Learning
	
7. Improving predictions
	* Novel activation functions
	* Test augmentation


