# kaggle-image-classification-2

**The aim is the predict the labels for the #D apparel images in the test dataset.**

<br>Below are the step by step approaches done on the dataset for prediction: 
* Created a sample folder with 3 subfolders (train/test/val) and placed all training images inside respective labels 
* Used VGG16 model without output layer 
* Externally added an output layer with 11 units 
* Used ImageDatagGenerator to preprocess and use the images from respective directories 
* Trained the model in GPU 
* Predicted the test images

The notebook is available in [kaggle](https://www.kaggle.com/code/dhanalakshmic/image-classification-nb) 
