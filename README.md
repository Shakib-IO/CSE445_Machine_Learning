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

Video Lecture Link:

| Lecture No        | Link     | 
| ------------- |:-------------:| 
| Lecture 01 | [Introduction](https://drive.google.com/file/d/1RQYDUTRqfnSorJB1tkNUGbg_y6ZiY1Dn/view?usp=sharing)
| Lecture 02 | [Supervised](https://drive.google.com/file/d/1Y67CkvH-Qs_W9Mt39m5tcgQDBlCZCbd8/view?usp=sharing)|   
| Lecture 03 | [ZeroR classifier](https://drive.google.com/file/d/17YJ9KX9210_gZTDvlD8M9tB65tWCV29z/view?usp=sharing)|
| Lecture 04 | [OneR classifier](https://drive.google.com/file/d/1qy7S4wbVfWFVHg_FjQLGinPDRKH-bhNe/view?usp=sharing)|
| Lecture 05 | [Decision Tree](https://drive.google.com/file/d/15BUqkuiyZHUcalAL7bNEEe2B-4x4U-Q_/view?usp=sharing)|
| Lecture 06 | [Decision Tree Basic](https://drive.google.com/file/d/1r1V-K1HMTX0Mr9A72p-Jt0_tHO6TPra_/view?usp=sharing)|
| Lecture 07 | [Decision Tree Math](https://drive.google.com/file/d/1iXJeMBr5JOkNbMSbg0oDLD208n6J1G8p/view?usp=sharing)|
| Lecture 08 | [Practical aspects of ML](https://drive.google.com/file/d/11gDuct8jt8O6wVeU0_PBj9A9kai71rKg/view?usp=sharing)|
| Lecture 09 | [K-Fold Validation](https://drive.google.com/file/d/1m3yAiZCa3TuVYGjCTd18yKoaM_udIkuq/view?usp=sharing)|
| Lecture 10 | [Data Visualization](https://drive.google.com/file/d/1uP99mvxoxo1kw1mbKVngXnyU5irg__WB/view?usp=sharing)|
| Lecture 11 | [KNN & Scaling](https://drive.google.com/file/d/1EPz2H2y5ZSHmEAPU34CY_PEuoPxR8Jlw/view?usp=sharing)|
| Lecture 12 | [Imbalance class prbolem, Precision, Recall, F1-Score](https://drive.google.com/file/d/1XHRGxMRz6v2_tsrRTBBwDHw8MfH6gTxg/view?usp=sharing)|
| Lecture 13 | [Accuracy metrics & AUC ROC curve](https://drive.google.com/file/d/17Ycffc7TWVbsQTxKSHF1whvihNxOlj_c/view?usp=sharing)|
| Lecture 14 | [Notebook Example](https://drive.google.com/file/d/19rtGIAMWuHaqIhTOPEzbMmwDqh-MduW4/view?usp=sharing)|

