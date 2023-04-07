# Project Definition

The goal is to classify input images into one of two categories thats nike or adidas shoes.

Why CNN vs ViT

Convolutional Neural Networks (CNNs) have been the widely used architecture for image categorization and object recognition applications in computer vision. However, a new design called Vision Transformer (ViT), which is based on the Transformer architecture used in Natural Language Processing (NLP) activities, has recently developed.

With ViT, the convolutional layers in a CNN are swapped out for a self-attention mechanism that enables the model to recognise global rather than just local relationships between picture pixels. In image classification tasks, this has showed encouraging results, and it has been demonstrated to outperform CNNs on various benchmarks.

In this study, we examine how well a CNN model and a ViT model perform on a particular picture classification problem. By doing this, we expect to learn more about the advantages and disadvantages of each design and choose which is most appropriate for this particular task.

To do this, we first used the Keras toolkit to create a CNN model and trained it on a dataset. Then, utilising the Transformers library, we created a ViT model and trained it using the same dataset. We evaluated how well these two models performed in terms of accuracy and training time. We may deduce which model performed better from the findings and make judgements about each model's applicability for this task.
