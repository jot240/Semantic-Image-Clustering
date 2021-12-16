# Semantic-Image-Clustering
Using transformer to group captioned images

This notebook embeds image captions generated from a CNN-LSTM image caption generator using a transformer neural network. We used this CNN-LSTM model: https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/03-advanced/image_captioning . We then use these embedding for image grouping and querying. 

The sample.py is a script to generate the captions using the CNN-LSTM network. We use the generated captions in imageindexing.py to semantically index the images.
