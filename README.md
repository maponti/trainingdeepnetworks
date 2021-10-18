# Training Deep Networks from Zero to Hero: avoiding pitfalls and going beyond

### A Tutorial presented at SIBGRAPI 2021

### Moacir Antonelli Ponti, Fernando Pereira dos Santos, Leo Sampaio Ferraz Ribeiro, Gabriel Biscaro Cavallari

Paper (extended version): https://arxiv.org/abs/2109.02752

**Abstract**: Training deep neural networks may be challenging in real world data. Using models as black-boxes, even with transfer learning, can result in poor generalization or inconclusive results when it comes to small datasets or specific applications. This tutorial covers the basic steps as well as more recent options to improve models, in particular, but not restricted to, supervised learning. It can be particularly useful in datasets that are not as well-prepared as those in challenges, and also under scarce annotation and/or small data. We describe basic procedures: as data preparation, optimization and transfer learning, but also recent architectural choices such as use of transformer modules, alternative convolutional layers, activation functions, wide and deep networks, as well as training procedures including as curriculum, contrastive and self-supervised learning.

## Content

1. How to Start: Basic Checklist - [slides](1_How-to-start_Common-issues/sibgrapi_tutorial_21_Part_1_Moacir.pdf)
	1. Data quality
	2. Normalization
	3. Input representation valid
	4. Loss function and evaluation choice
	5. Model tuning
	6. Feature projection/visualization
	7. Internal and External validation and evaluation

	Notebook:
	* [notebook: Normalization, Loss and Evaluation](1_How-to-start_Common-issues/tdnn_sibgrapi_1_data.ipynb)

2. Common Issues - [slides](1_How-to-start_Common-issues/sibgrapi_tutorial_21_Part_1_Moacir.pdf)
	1. Data quality and Small datasets
	2. Imbalanced data
	3. Bias-variance dillema in DNNs: overfitting/underfitting
	4. Sensitivity to attack

	Notebooks:
	* [notebook: Overfitting case](1_How-to-start_Common-issues/tdnn_sibgrapi_2_1_overfitting.ipynb)
	* [notebook: Reducing Overfitting](1_How-to-start_Common-issues/tdnn_sibgrapi_2_2_reducedmodel.pynb)
	* [notebook: DNN under attack](1_How-to-start_Common-issues/tdnn_sibgrapi_2_3_attack.pynb)
	* [notebook: Small data scenario](1_How-to-start_Common-issues/tdnn_sibgrapi_3_smalldata.pynb)


3. Architecture Options - [notebook](<3. Architecture Options/>)
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
	* Contrastive Learning - [notebook](<6.2. Contrastive Learning/>)
	* Self-supervising Learning
	
7. Improving predictions
	* Novel activation functions
	* Test augmentation


