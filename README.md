# CSE445_Machine_Learning

# Project Title: Image Denoise with AutoEncoder

**Introduction:**<br>
Image denoising is an old but still a running research topic in computer vision. Though modern cameras are very powerful, they still suffer while taking pictures in dark or low light conditions. The denoising system re-processes the images and cleans them from the noisy obstacles. They mostly rely on certain assumptions on noise distributions or previously provided data on ground truth clean images to create optimized models. Denoising in Deep learning uses convolutional neural networks to learn the models from a large number of noise-free and noisy images. It actually learns from a large data of denoised clear images and cleanses the ground truth from the noisy images. Denoising using an autoencoder is mainly a modification on the network to prevent it from learning the identity function. The autoencoder sometimes becomes so big that it only learns the data and makes the output as input. It doesn’t perform any dimension reduction rather corrupts the input data by adding some noise or mask in the input values.

**Dataset**
To  train  our  model  for  image  denoising tasks,  we use 320 high-resolution images of the SIDD dataset . SIDD datasets consist of real images. This dataset consists of noisy images and ground truth images. In this dataset there are 160 noisy images and 160 ground truth images [1]. We split the dataset for training and testing. Our training dataset contains 128 images and the test dataset contains 32 images. 

Sample of the dataset:

<img src = "https://github.com/Shakib-IO/CSE445_Machine_Learning/blob/main/images/noisy_image.png"> 

Noisy Image

<img src = "https://github.com/Shakib-IO/CSE445_Machine_Learning/blob/main/images/GT_images.png"> 

Ground Truth Image

**Class Lecture**

Lecture 01 : <br>
Lecture 02 : <br>
Lecture 03 : ZeroR classifier <br>
Lecture 04 : OneR classifier <br>
Lecture 05 : <br>
Lecture 06 : <br>
Lecture 07 : <br>
Lecture 08 : <br>
Lecture 09 : K-Fold Validation https://drive.google.com/file/d/1nsRi3iTBBht4nFd_HQ0ZgHWKVO54awDr/view?usp=sharing <br>
Lecture 10 : Data Visualization https://drive.google.com/file/d/11RtXAuTgRPKZmySrPM6L1u4sunpwEkpk/view?usp=sharing <br>
Lecture 11 : KNN & Scaling https://drive.google.com/file/d/1eUQyWoKx4RmkzQreUs_RgWSz558sGWEU/view?usp=sharing <br>
Lecture 12 : Imbalance class prbolem, Precision, Recall, F1-Score https://drive.google.com/file/d/1IKpEsJhFls50DKSKvE6xedUsv93mZsjF/view?usp=sharing <br>
Lecture 13 : Accuracy metrics & AUC ROC curve<br>
