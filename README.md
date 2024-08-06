# CLASSIFICATION WITH DEEP LEARNING

The "Male & Female height and weight" dataset from Kaggle is used for the project.

Dataset: https://www.kaggle.com/datasets/saranpannasuriyaporn/male-female-height-and-weight

Classification of gender is done based on height and weight.

The neural network contains,

input layer      - 2 input nodes 

1st hidden layer - 64 nodes      - Relu activation function

2nd hidden layer - 16 nodes      - Relu activation function

output layer     - 1 node        - sigmoid activation function



In the compiler,

optimizer        - Adam

learning rate    - 0.005

loss             - BinaryCrossentropy

metrics          - accuracy

      
model trained with 50 epochs

The scatter plot of the test dataset

<img src= "https://github.com/user-attachments/assets/ebe0af27-2fa4-4b80-8545-f8a540919cb5" width = "600">


## Without normalization

Loss and accuracy variation with epochs

<img src="https://github.com/user-attachments/assets/d1d23870-48e1-4ec2-8d3e-c2a4af19e7bc" width="600"/>


The scatter plot for predictions of the test dataset

<img src="https://github.com/user-attachments/assets/d24d5ca4-4e7e-4fea-b31c-24f04f88357f" width="600"/>


## With normalization

Loss and accuracy variation with epochs

<img src="https://github.com/user-attachments/assets/ed557064-9fd7-4284-b2b1-c353dc0336af" width="600"/>


The scatter plot for predictions of the test dataset

<img src="https://github.com/user-attachments/assets/1a4f6f53-1467-4026-8abf-2bf504fcc00f" width="600"/>







