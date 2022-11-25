# UNet-TGS-Salt-Identification
## Description
To implement image segmentation on Kaggle 2018 TGS Salt Identification Challenge [[1]](https://www.kaggle.com/competitions/tgs-salt-identification-challenge), a pytorch version of UNet [[2]](https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28) was built only for practicing. The model was designed to have fewer parameters than those in the original UNet model (maximal number of input channels is 64 in the designed model), and the training image size was 128.
## Training Samples and Model Predictions
![image_1](/images/image_1.png) | ![image_1](/images/image_1_true.png) | ![image_1](/images/image_1_predict.png)
## Reference
[[1] Kaggle 2018 TGS Salt Identification Challenge](https://www.kaggle.com/competitions/tgs-salt-identification-challenge)  
[[2] O. Ronneberger, P. Fischer, and T. Brox, “U-net: Convolutional networks for biomedical image segmentation,” in International Conference on Medical image computing and computer-assisted intervention, 2015, pp. 234–241.](https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28)  
