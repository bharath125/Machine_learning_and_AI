PHASE 1 — Complete ML Fundamentals (4 weeks)
─────────────────────────────────────────────
Week 1: PyTorch
  → rebuild your neural network in PyTorch
  → understand autograd — how gradients computed automatically
  → understand optimizer, loss, backward()
  → compare PyTorch gradients with your manual gradients
  → they should match exactly

Week 2: Tree-based algorithms
  → Decision Tree from scratch
  → how splitting by questions works
  → Random Forest — why many trees beat one tree
  → XGBoost intuition
  → why trees beat neural nets on tabular data

Week 3: Unsupervised Learning
  → K-Means clustering from scratch
  → PCA — dimensionality reduction
  → when you have data but no labels

Week 4: Real Kaggle Competition
  → Titanic submission — beat 83.2%
  → feature engineering
  → model comparison
  → ensemble methods

PHASE 2 — Deep Learning (4 weeks)
──────────────────────────────────
Week 5: CNNs
  → why images need different architecture
  → convolution from scratch
  → MNIST with CNN
  → feature maps, pooling

Week 6: NLP Basics
  → text as numbers
  → word embeddings
  → sentiment classification
  → your first text classifier

Week 7: Modern architectures
  → Transformers intuition
  → attention mechanism
  → why GPT works the way it does

Week 8: End-to-end project
  → pick one real problem
  → data collection → cleaning → model → evaluation → deployment

PHASE 3 — Professional Skills (ongoing)
────────────────────────────────────────
  → Git and version control for ML projects
  → ML experiment tracking
  → Model deployment — Flask API
  → Docker basics
  → Reading research papers



## What I haven't learnt in Supervised Learning

  ○ Support Vector Machines (SVM)
  → finds maximum margin boundary between classes
  → powerful for small datasets

○ Naive Bayes
  → probability-based classifier
  → very fast, good for text

○ K-Nearest Neighbors (KNN)
  → classify by looking at K nearest examples
  → simplest possible classifier

○ XGBoost / Gradient Boosting
  → most powerful tabular algorithm
  → wins most Kaggle competitions
  → builds trees sequentially, each fixing previous errors

○ Multi-class classification
  → you did binary (0 or 1)
  → multi-class is 3+ categories (cat, dog, bird)

○ Regression metrics
  → MAE, RMSE, R² score
  → you know MSE but not the others

○ Time series
  → predicting future from past sequences
  → stock prices, weather, sales forecasting

○ Imbalanced datasets
  → SMOTE, class weights
  → when 95% of data is one class

## What I haven't learnt in Unsupervised Learning


  ○ DBSCAN
  → clustering without choosing K
  → finds arbitrarily shaped clusters
  → handles noise/outliers

○ Hierarchical Clustering
  → builds tree of clusters
  → dendrogram visualization

○ t-SNE / UMAP
  → better than PCA for visualization
  → preserves local structure
  → standard in modern ML

○ Autoencoders
  → neural network that compresses and reconstructs
  → learns representations unsupervised
  → foundation of generative AI

○ Anomaly Detection
  → finding unusual data points
  → fraud detection, system monitoring
