# Projects



---
# [AI Hack 2019 - Overall Winners - Machine Learning for Train Route Planning](https://github.com/leonjwu/AIHack)

## Overview
- Placed 1st out of 50 teams in the AI Hackathon, competing against students from the best universities in the UK
- Submitted a project on graph-based route planning that was chosen for presentation at Google DevFest
- Utilised graph-based clustering, graph theory and large datasets for train route planning
 

Poster
:-----------------------------------:
![](https://github.com/leonjwu/AIHack/blob/master/poster.jpg)
---





# [Computational PDEs: 1D and 2D Wave Equations](https://leonjwu.github.io/comp-pdes/)

## Overview
- Implemented finite difference schemes for 1D and 2D Wave Equations
- Designed boundary conditions to allow for reflecting and non-reflecting boundaries (Neumann and Dirichlet)
- Created visualisations of 1D and 2D waves using Matplotlib Animations


2D Wave - Single  |  2D Wave - Multi
:-------------------------:|:-------------------------:
![](https://github.com/leonjwu/comp-pdes/blob/master/2D_Wave_Symetric_Single.gif)  |  ![](https://github.com/leonjwu/comp-pdes/blob/master/2D_Wave_Symmetric_Multi.gif)
---





---
# [Volatility Surface Simulator](https://leonjwu.github.io/volatility-simulator/)

## Overview
- Created a webapp for options trading and pricing, enabling market makers and traders to visualise real-time and historical simulations of volatility surfaces, market quotes, and trades
- Using the tool, you can view proprietary implied volatility surface marks generated from my own model, and explore live or historical volatility surfaces in 2D or 3D through simulation
- Also built a volatility surface simulator - an internal backtesting tool to backtest and benchmark my own improvements to the production volatilty model

 
2D Volatility Surface  |  3D Volatility Surface
:-------------------------:|:-------------------------:
![](https://github.com/leonjwu/volatility-simulator/blob/master/2D.png)  |  ![](https://github.com/leonjwu/volatility-simulator/blob/master/3D.png)
---






# [Exploring unsupervised graph-based learning methods, clustering methods and neural networks for clothing image classification and academic paper clustering in Python](https://github.com/leonjwu/Data-Science/blob/master/Graph-Cluster-NN/)

## Overview
- Clustering of academic papers using K-Means, comparing different scoring metrics and analyzing optimal number of clusters and randomness in K-Means
- Graph-based learning methods for clustering including community detection and centrality measures
- Image classification of clothing items using unsupervised methods
- Used PCA to visualise clustering of clothing items and centroids
- Comparison of kNN, hierachical clustering and neural networks for supervised image classification
- Comparison of MLP neural networks and CNNs
- Alteration of CNNs using dropout, other layers and alterations to kernel sizes to increase accuracy
- K-Fold Stratified Cross-Validation used throughout

Community Detection using CNM  |  Clustering visualised with PCA
:-------------------------:|:-------------------------:
![](https://github.com/leonjwu/Data-Science/blob/master/Graph-Cluster-NN/Project%203_files/Project%203_73_0.png)  |  ![](https://github.com/leonjwu/Data-Science/blob/master/Graph-Cluster-NN/Project%203_files/Project%203_121_0.png)
---






---
# [Exploring supervised Random Forests, Support Vector Machines and Neural Network in-depth for classification on noisy data in Python](https://github.com/leonjwu/Data-Science/blob/master/RF-SVM-NN/)

## Overview
- Data Balancing and Standardisation Methodologies for predicting car ratings
- Explaining K-Fold Stratified Cross-Validation
- Random Forest optimasation for number of trees, depth and number of split predictors
- Support Vector Machines: optimisation of kernels (linear, polynomial and RBF)
- Neural Network optimsation for batch size, learning rate and dropout

Number of Trees for Random Forest  |  Hyperparameters of RBF kernel SVM
:-------------------------:|:-------------------------:
![](https://github.com/leonjwu/Data-Science/blob/master/RF-SVM-NN/Project%202_files/Project%202_32_0.png)  |  ![](https://github.com/leonjwu/Data-Science/blob/master/RF-SVM-NN/Project%202_files/Project%202_71_0.png)
---




---
# [Exporing regression and classification methods including ridge and logitstic regression and Naïve Bayes classifiers in Python](https://github.com/leonjwu/Data-Science/blob/master/Regression-Classification/)

## Overview
- Goal: Predicting climbing success rate from weather predictors
- Data cleaning using Pandas
- Exploratory data analysis
- Compared regression methods including linear and ridge
- Compared classifiers including Logistic Regression and Naïve Bayes using different metrics

Ridge Regression hyperparameter tuning (CV)  |  Ridge Predictors against penalty parameter
:-------------------------:|:-------------------------:
![](https://github.com/leonjwu/Data-Science/blob/master/Regression-Classification/Project%201_files/Project%201_25_1.png)  |  ![](https://github.com/leonjwu/Data-Science/blob/master/Regression-Classification/Project%201_files/Project%201_25_2.png)
---

---
# [Recommender System for Academic Papers using Multidimensional Scaling in R](https://github.com/leonjwu/Paper-Configurations)

## Overview
- Goal: Reveal configurations of academic papers so that a user can find targeted lists of research materials
- Dissimilarity measures
- Data scraping using unix and Google Scholar
- Classical and Ordinal Scaling, analysis of eigenvalues
- K-Means Clustering of final configurations for labelling

Word Counts in Papers  |  Heatmap of Word Frequencies for Each Paper
:-------------------------:|:-------------------------:
![](https://github.com/leonjwu/Paper-Configurations/blob/master/figures/1.jpg)  |  ![](https://github.com/leonjwu/paper-configurations/blob/master/figures/2.png)
---




---
# [Simulating Fluid Flow PDEs with Finite Differences and Simulating Weakly-Coupled Oscillattors on a network (Parallel Fortran (OMP and MPI))](https://github.com/leonjwu/Computing/blob/master/Fluid-Oscillators/)

## Overview
- Simulated blood flow through a deformed artery
- Designed fast sparse matrix solvers in parallel Fortran code (OMP) to speedup the bottleneck in the finite-difference schemes by 100x
- Simulated Weakly-Coupled Osicalltors on a network using 1D and 2D decompositions for MPI parallel Computing in Fortran.
- Setup communication effectively between multiple processes on a grid using appropriate MPI directives
- Implemented finite difference methods in Python

 

Fortran vs Python Speedup  |  Number of Threads Speedup
:-------------------------:|:-------------------------:
![](https://github.com/leonjwu/Computing/blob/master/Fluid-Oscillators/speedup.png)  |  ![](https://github.com/leonjwu/Computing/blob/master/Fluid-Oscillators/threads.png)
---









# [Scientific Computing: Multidimensional SVD, Image Repair Algorithm, Chaotic Systems and Path-Finding Algorithms (Python)](https://github.com/leonjwu/Computing/blob/master/Scientific-Computing/)

## Overview
- Designed multidimensional SVD techniques to reduced dataset storage by 95%
- Optimised code for repairing images through vectorisation
- Reformulated matrix computations for most efficient use of Python vectorisation
- Simulated Chaotic Bacteria Interactions through PDEs and Finite Differences
- Implemented banded matrix solvers using SciPy to massively speed up simulations 
- Designed fast path-finding algorithms utilising dequeues, hash tables and binary heaps
- Modified BFS, DFS and Dijkstra algorithms for specific path-finding problems



Chaotic System Contours  |  Repaired Image
:-------------------------:|:-------------------------:
![](https://github.com/leonjwu/Computing/blob/master/Scientific-Computing/Chaos.png)  |  ![](https://github.com/leonjwu/Computing/blob/master/Scientific-Computing/Repaired_Image.png)
---






