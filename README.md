# Image-Colorization
A Deep Learning project for image colorization using convolutional autoencoders and generative adversarial networks

Image colorization is an emerging topic and a fascinating area of research in recent years. In this paper, we
implemented deep learning algorithms to colorize black and white images. Convolutional autoencoder neural network
and generative adversarial network (GAN) have been implemented on black and white images. The networks aim to
convert the black and white images to their respective color format. The color format used for the implementation of the
networks is RGB color space. The performance of the autoencoder model is evaluated using root means squared error,
means squared error, means absolute error and colorization accuracy. The data used for the implementation of the
networks consists of 7000 images in the RGB color space. The performance of the implemented autoencoder models and
generative adversarial network is measured using mean absolute error. The colorization performance of the generative
adversarial network is better that that of the autoencoder models. 

Dataset Link: https://www.kaggle.com/theblackmamba31/landscape-image-colorization

## Colorization Output
![output](https://user-images.githubusercontent.com/55061863/151605048-e3ec6164-f714-4e06-baac-a70566f16253.png)

Three autoencoders models and one ColorGAN model on a landscape image dataset to colorize black-and-white images
to color images are implemented. The two color space chosen for colorization is RGB and CIELAB. The AE-LAB
autoencoder model performed better than AE-RGB-1 and AE-RGB-2 autoencoder models in terms of RMSE, MSE and
MAE with values 0.0753, 0.0058, 0.0477 respectively. The performance of other two autoencoder models is at par. The
colorization accuracy of AE-LAB is better than AE-RGB-1 and AE-RGB-2 with an accuracy of 68.57%. The
performance of implemented ColorGAN model is best among all the other models implemented. The colorized images
presented above attribute to the better performance of ColorGAN model than autoencoder models. The MAE of
ColorGAN model is also better than those of the autoencoder models with a value of 0.006477. The results prove that
the implemented ColorGAN’s performance to colorize the grayscale images in better than those of the implemented
autoencoder models.
The use of deep learning to colorize black-and-white images has a huge potential. This can be attributed by the results
shown is this paper. The findings provided in this this paper will help to future researchers to develop deep learning
models for image coloration. The autoencoder models as well as ColorGAN model implemented in this project will help
to colorize any landscape image with a superior accuracy.
