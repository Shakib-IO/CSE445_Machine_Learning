# CSE445_Machine_Learning

# Project Title: Image Denoise with AutoEncoder

**Introduction:**<br>
Image denoising is an old but still a running research topic in computer vision. Though modern cameras are very powerful, they still suffer while taking pictures in dark or low light conditions. The denoising system re-processes the images and cleans them from the noisy obstacles. They mostly rely on certain assumptions on noise distributions or previously provided data on ground truth clean images to create optimized models. Denoising in Deep learning uses convolutional neural networks to learn the models from a large number of noise-free and noisy images. It actually learns from a large data of denoised clear images and cleanses the ground truth from the noisy images. Denoising using an autoencoder is mainly a modification on the network to prevent it from learning the identity function. The autoencoder sometimes becomes so big that it only learns the data and makes the output as input. It doesn’t perform any dimension reduction rather corrupts the input data by adding some noise or mask in the input values.

**Dataset**
To  train  our  model  for  image  denoising tasks,  we use 320 high-resolution images of the SIDD dataset . SIDD datasets consist of real images. This dataset consists of noisy images and ground truth images. In this dataset there are 160 noisy images and 160 ground truth images [1]. We split the dataset for training and testing. Our training dataset contains 128 images and the test dataset contains 32 images. 

Sample of the dataset:

