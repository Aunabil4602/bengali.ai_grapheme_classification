This is a project on Bengali Grapheme Classification that was going on Kaggle.

The first ipynb file contains the model, which is a multioutput CNN using keras, where each output model is similar to Lenet-5 architecture. At first, the image sets was extracted from parquet files to numpy array and size of of each image was reduced to 64x80. Then the model is trained on Google Colab. 

The second one is done using Transfer Learning from VGG16. The sample code for Transfer Learning is taken from another github source and is edited to complete our model. 

Sample cource on transfer Learning: https://github.com/krishnaik06/TransferLearning/blob/master/face_Recognition.py

Competition link: https://www.kaggle.com/c/bengaliai-cv19
