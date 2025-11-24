# Deep Learning

This course was one of my first introductions to deep learning and machine learning in the MSc program. It explored fundamental neural network concepts and practical model building, giving me hands-on experience with designing, training, and evaluating models. The assignments introduced me to both classic and modern deep learning workflows.


## Assignments / Projects

### 1. [Neural Network from Scratch](./dl_assignment1.ipynb)
Built a neural network from scratch for classification, extended it with an additional layer and a ReLU activation, and designed a custom architecture to achieve a smooth decision boundary. The model was trained and tested, with classification accuracy reported.

### 2. [Facial Point Detection](./dl_assignment2.ipynb)
Improved a baseline model for facial landmark detection using:

- Data augmentation (flipped images, greyscale editing, etc.)  
- Learning rate and momentum scheduling  
- Regularization techniques (Dropout)  
- Specialist networks for subsets of target features (eyes, mouth, etc.)  

The assignment aimed to increase prediction accuracy and model robustness.

### 3. [Uncertainty Prediction](./dl_assignment3.ipynb)
Developed a linear model (non-neural network) to classify images as correctly or incorrectly classified using prediction uncertainty. Explored multiple metrics to quantify uncertainty:

- Entropy of predicted probabilities  
- Variation ratio across stochastic passes  
- Maximum-minimum probability differences  
- Least confidence  
- Margin of confidence  

The goal was to evaluate model reliability and identify uncertain predictions.
