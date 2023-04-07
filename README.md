# Advacned Maths Project

CNN & Vit Our project is based on image classification of Nike and Adidas using CNN and ViT (Visual transformers) The goal is to classify input images into one of two categories. The CNN model and the Vision Transformer (ViT) model were both trained and evaluated on the same dataset to compare their performance in terms of accuracy and loss.

For preprocessing we used data generators, we have a CNN architecture consists of several convolutional layers followed by a pooling, dense, flattening layer and a few fully connected layers Model is trained using the adam optimizer sparse categorical crossentropy loss function Hyperparameter tuning is also done for better accuracy

Next we used ViT for better accuracy As we all know transformer-based model is more effective at capturing long-range dependencies in the images so resulting model should have higher accuracy than the previous model. The ViT model uses a transformer architecture that processes the input image using attention mechanisms. Both models were trained using the Adam optimizer with different learning rates and other hyperparameters.

We have used pre defined methods of ViT with the help of youtube videos.