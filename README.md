# Advanced Maths Project1

Best Hotel classifier using Transformers
This project aims to classify if the hotel is best or not using a pre-trained Transformer model from the Hugging Face Transformers library. The model is fine-tuned on a dataset of hotel reivews and ratings for accuracy. The project is implemented in Python using TensorFlow and the Hugging Face Transformers library.

Dataset:

The dataset used for training and evaluation consists of 20k reviews crawled from Tripadvisor, from where  you can explore what makes a great hotel and maybe even use this model in your travels.

Pre-processing:

The reviews are pre-processed using the transformers library. The reviwes are tokenized and encoded using the DistilBertTokenizer from the Transformers library. The encoded reviews are then padded to a fixed length and converted to TensorFlow Dataset objects.

Model:

The pre-trained DistilBert model from the Hugging Face Transformers library is used as the base model. The model is fine-tuned on the pre-processed dataset using the TFTrainer class from the transformers library.