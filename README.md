# CNN_Study  
In this project, I built a convolutional neural network (CNN) using PyTorch to classify facial emotions as either happy or sad. I used a labeled image dataset from Kaggle containing various facial expressions and filtered it to include only the two target classes. The images were preprocessed by resizing, normalization, and converting to grayscale. The CNN architecture consisted of two convolutional layers with ReLU activations and max pooling, followed by a fully connected layer and a sigmoid output for binary classification. I trained the model using binary cross-entropy loss and optimized it with Adam, applying backpropagation and gradient descent over five epochs. During training, the model achieved steadily improving performance:

- Epoch 1: Loss = 0.5774, Accuracy = 69.51%

- Epoch 2: Loss = 0.4748, Accuracy = 76.23%

- Epoch 3: Loss = 0.4132, Accuracy = 80.27%

- Epoch 4: Loss = 0.3656, Accuracy = 82.83%

- Epoch 5: Loss = 0.3102, Accuracy = 85.98%

After training, I evaluated the model on a held-out test set and achieved a test accuracy of 80.04%.
