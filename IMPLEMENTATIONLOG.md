# COMP8740-NEURAL_NETWORK_PROJECT

- **Datasets**
	-  Fruit-360 Dataset

- **Main Goal**
	- Train ResNet50 with the dataset and compare the performance with out pwn model.
	- Explore custom loss function, different activation functions, data augmentation (if needed), learning rate scheduling and callbacks. 

- **Hyper-Parameter Optimization**
	- Activation Function (ReLu, LeakyReLu- will tune the threshold here)
	- Generalized Loss Function (Categorical, sparse_categorical)
	- We'll try to define our Loss function (Later)
	- Learning Rate Scheduling
	- Optimizer (Adam, RMSProp, SGD)
	- Normalization (with different Data distribution) (Later)
	- Number of Hidden Layers (Need to optimize)
	- Number Units of each Hidden Layers(Need to find optimal hidden units)
	- Regularization (L2, Dropout)
	- Initializer (Xaiver, He norma)
	- Data Augmentation



- **Create Hybrid model (Our Model + GAN)**


- **Define Tasks Step-by-step**
  - 1. define all necessary libraries (On the Fly)
  - 2. Load datasets
  - 3. Preprocess data
  - 4. Define Hyperparameters
  - 5. Define Model
  - 6. Comple and fit dataset
  - 7. Call backs
  - 8. Write code to get the optimal set of hyperparameter using Random Search
  - 9. Do Grid Search For selecting Number of Hidden layers
