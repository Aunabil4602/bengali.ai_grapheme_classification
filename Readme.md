This is a project on Bengali Grapheme Classification that was going on Kaggle.

The first ipynb file contains the model, which is a multioutput CNN using keras, where each output model is similar to Lenet-5 architecture. At first, the image sets was extracted from parquet files to numpy array and size of of each image was reduced to 64x80. Then the model is trained on Google Colab. My accuracy stuck at 70% 

The second one is done using Transfer Learning from VGG16. The sample code for Transfer Learning is taken from another github source and is edited to complete our model. Here I got accuracy around 80%.

The p4_d3.ipynb file contains my best convnet model. Where I got 89.78% accuracy in the final test.

Sample source on transfer Learning: https://github.com/krishnaik06/TransferLearning/blob/master/face_Recognition.py

Competition link: https://www.kaggle.com/c/bengaliai-cv19
