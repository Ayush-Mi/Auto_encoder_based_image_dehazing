# Auto_encoder_based_image_dehazing

This is an implementation of autoencoders using Convolutional Neural Networks in Tensorflow for image enhancement. It uses four layers as encoders and four layers as decoders. The datastet for this is taken from [IndoorCVPR Dataset](https://www.kaggle.com/datasets/itsahmad/indoor-scenes-cvpr-2019) and is transformed using Gaussian Blur filter in OpenCV before passing it to the auto-encoder network. The notebook is just meant to demonstrate the use of autoencoders in a simplest way.

## Dependencies
* Jupyter Notebook
* Python 3.*
* [IndoorCVPR Dataset](https://www.kaggle.com/datasets/itsahmad/indoor-scenes-cvpr-2019)
* The other required libraries can be installed using ``` pip install -r requirements.txt ```

## Results
The network here is shallow and hence the filters are not that efficient in capturing various information present in the dataset and hence the results are not that appealing. However, it can be improved by modifying the architecture.

[Model Training and Validation loss](https://github.com/Ayush-Mi/Auto_encoder_based_image_dehazing/blob/main/loss.png)

[Model Results](https://github.com/Ayush-Mi/Auto_encoder_based_image_dehazing/blob/main/results.png)
