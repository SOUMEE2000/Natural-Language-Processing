# Description of the Files:
* This contains an implementation of the [**Spatial Attention U-Net paper**](https://arxiv.org/ftp/arxiv/papers/2004/2004.03696.pdf). The model has been tried on the DRIVE Dataset. This is basically an attention based Convolutional Neural Network model. It is a derivative of the conventional U-net model already in use. Various data augmentation strategies have been used. The images of the test set formed therof are also present in the respective folders. 
* KNN on pixelwise classification of Retinal images on DRIVE Dataset. Considered the RGB channels only. Random undersampling and oversampling is done to fix the ratio of non blood vessel pizels and blood vessel pixels which are originally in the ratio of 1:10. SMOTE algorithm might also be helpful but that is left for experimentation in the near future.