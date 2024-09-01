# Cat_VS_Dogs
This is a classification of cats and dogs
I used the dataset that i receive from kaggle

step by step we compare VGG pretrained(98%), our custom network(82%), resnet18, densenet121
![image](https://github.com/user-attachments/assets/b51473a2-526a-44ad-8e82-4da721992e34)


- Data Acquisition and Preparation:
    - Download Cats vs. Dogs dataset from Kaggle
    - Organize dataset into appropriate directory structure
    - Split data into training, validation, and test sets
- Custom DataLoader Development:
    - Create a custom Dataset class
        - Implement **init**, **len**, and **getitem** methods
    - Define data augmentation transforms
    - Create DataLoader instances for training, validation, and test sets
- Custom CNN Architecture Design:
    - Define the CNN structure
        - Convolutional layers
        - Pooling layers
        - Fully connected layers
    - Implement forward pass
    - Initialize weights
- Model Training:
    - Set up training loop
        - Define loss function and optimizer
        - Implement epoch iterations
        - Forward pass, loss calculation, backpropagation, and optimization
    - Implement validation loop
- Model Evaluation:
    - Evaluate model on test set
    - Calculate and report metrics (accuracy, precision, recall, F1-score)
    - Generate confusion matrix
- Prediction :
    - Load trained model
    - Implement preprocessing for new images
    - Create prediction function
    - Return classification result and confidence score
