# U2E-Net
Requirements Python Tensorflow >= 1.10.0 numpy, PIL

Descriptions: This project is the implementation of the Uneven to Enliven-Network (U2E-Net) for the low light image enhancement. We aim to enhance the images captured in
the dim or weak-illumination conditions. We propose a deep hybrid U2E-Net and an enhancement strategy to upgrade the low light images for pleasing visual quality. 
We propose to learn through the correlation consistency of the decomposed data itself. The model implemented in this regard comprises a simple and lightweight image
U2E-Net with an Uneven-Net (to divide the image into reflection and illumination) and use an encoder-decoder (3x3 up-down sampling) unit as Enliven-Net to repair ill-illumination.
It is the first method capable of working with and without paired training data supervision.

Dataset:

The datasets used for comparison include LOL dataset, DILCOD dataset, and UXOV dataset captured in low and ill-illumination conditions, arranged as under-exposes to well exposed.
Test and GT images: We presented evaluation on test images from our data set, whereas the dataset contains many sample images with reference images, and in each case,
high exposure can act as a reference GT for the low exposure test image. We have presented the separate files for test and training data, 
where every scene has a separate folder with multiple exposures.

Dataset-Link: The whole training dataset, along with test images, is available at the following google drives link:

https://drive.google.com/drive/u/1/folders/1uj8MGHWtRMbeuh8VZemmIv-wqUqVNdo6
https://drive.google.com/drive/folders/18Bz2m2bWFXL7kBkt-UzKStRIj_ss_LbI
<img src="https://github.com/imrizvankhan/U2E-Net/blob/main/Figures-U2E-Net/U2E-Net.png">
![](https://github.com/imrizvankhan/U2E-Net/blob/main/Figures-U2E-Net/Signal+amplification.png)
![](https://github.com/imrizvankhan/U2E-Net/blob/main/Figures-U2E-Net/gamma.png )
<img src="https://github.com/imrizvankhan/U2E-Net/blob/main/Figures-U2E-Net/images%205%20K.png">
<img src="https://github.com/imrizvankhan/U2E-Net/blob/main/Figures-U2E-Net/bird.png">
<img src="https://github.com/imrizvankhan/U2E-Net/blob/main/Ablation%20U2E-rev.png">
<img src="https://github.com/imrizvankhan/U2E-Net/blob/main/Figures-U2E-Net/PSNR+SSIM+LL+NL.png">
<img src="https://github.com/imrizvankhan/U2E-Net/blob/main/Various-methods-images.png">


