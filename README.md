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
| Lecture 01 | [Introduction](https://drive.google.com/file/d/1XH7uXanUyS10BDMVwq9_jwLudx3hVMVh/view?usp=sharing)
| Lecture 02 | [Supervised](https://drive.google.com/file/d/19fyNkr9SXeC5T7ipyDDXY1MQW0t4Y2aJ/view?usp=sharing)|   
| Lecture 03 | [ZeroR classifier](https://drive.google.com/file/d/1ZddUv4K4JnyHPjEE0L6otqdANQI4Vikt/view?usp=sharing)|
| Lecture 04 | [OneR classifier] (https://drive.google.com/file/d/1HlqzIcMkwxTqEjwstqAcVR0hBL_OPgCJ/view?usp=sharing)|
| Lecture 05 | [Target output calculated output](https://drive.google.com/file/d/1MxyLektiQLYlDKv2jBg4hcypNiqjoVCv/view?usp=sharing)|
| Lecture 06 | [Gradient Derivative](https://drive.google.com/file/d/1324nGDz1Xk2X5H21DoU3lcOvXJItb96k/view?usp=sharing)|
| Lecture 07 | [Supervised, Unsupervised](https://drive.google.com/file/d/1Zh75PxmrzoyPC0nvZL2y1l_1fkD5cdi8/view?usp=sharing)|
| Lecture 08 | [Softmax](https://drive.google.com/file/d/1F4PIYP1pr456YS2p0BbfiRyapOsYivUB/view?usp=sharing)|
| Lecture 09 | [GEntropy, Cross-Entropy, KL-Divergence](https://drive.google.com/file/d/1EmL51b7FRsXOWgig9j2BBpbz31-88KnN/view?usp=sharing)|
| Lecture 10 | [AutoEncoder](https://drive.google.com/file/d/1ul6XZzecj_a4LnBUyZaFEQRlVUp91vXw/view?usp=sharing<br>)|
| Lecture 11 | [Intro to CNN](https://drive.google.com/file/d/1yZmDtrA2Pb7ipktO8mSXQPxSR-6rGINr/view?usp=sharing)|
| Lecture 12 | [Kernel , Filter , AlexNet Paper](https://drive.google.com/file/d/1mIEH3_RJaxlsR1H9forDzCydZO5ZMuCr/view?usp=sharing)|
| Lecture 13 | [Calculate the Shpae of CNN (Alexnet Papaer)](https://drive.google.com/file/d/1jcE5c8wjvLRBj7elgIMsye6LNsKEAW1V/view?usp=sharing)|
| Lecture 14 | [CNN padding, stride](https://drive.google.com/file/d/1rybGxgY8YluSySNux_Sn1zHD17FzjTJ4/view?usp=sharing)|
| Lecture 15 | []()|
| Lecture 16 | [Siamese Network](https://drive.google.com/file/d/1_zcTrOfoU0mAm5sLidlOnqK31X2NBTQ0/view?usp=sharing)|
| Lecture 17 | [Triplet loss](https://drive.google.com/file/d/1GM0yzHq9uuY_TcFIbvjAHNg1js1SCZdC/view?usp=sharing)|
| Lecture 18 | [RNN](https://drive.google.com/file/d/1-scEA6TxRU4IEwQ30QqnQOoO0p8X7cLm/view?usp=sharing )|
| Lecture 19 | [Transformer](https://drive.google.com/file/d/1qh6ujiEVvE9kuarVLrNHT9U3PMfk2wJp/view?usp=sharing)|
| Lecture 20 | [LSTM](https://drive.google.com/file/d/1womR3T5yaFhtXoOxqP2oKd4wXgnTAJ2n/view?usp=sharing)|
| Lecture 21 | [Assessment discussion](https://drive.google.com/file/d/13MGWK-_v-WwBA-OykoLdGl7W0ig_SmLI/view?usp=sharing)|



Lecture 01 : Introduction https://drive.google.com/file/d/1XH7uXanUyS10BDMVwq9_jwLudx3hVMVh/view?usp=sharing <br>
Lecture 02 : Supervised https://drive.google.com/file/d/19fyNkr9SXeC5T7ipyDDXY1MQW0t4Y2aJ/view?usp=sharing <br>
Lecture 03 : ZeroR classifier https://drive.google.com/file/d/1ZddUv4K4JnyHPjEE0L6otqdANQI4Vikt/view?usp=sharing <br>
Lecture 04 : OneR classifier https://drive.google.com/file/d/1HlqzIcMkwxTqEjwstqAcVR0hBL_OPgCJ/view?usp=sharing <br>
Lecture 05 : Decision Tree https://drive.google.com/file/d/1Dg4wCa8fxJhjz3qnk8jOnmGhQi383fjJ/view?usp=sharing<br>
Lecture 06 : Decision Tree Basic https://drive.google.com/file/d/1r1V-K1HMTX0Mr9A72p-Jt0_tHO6TPra_/view?usp=sharing<br>
Lecture 07 : Decision Tree Math https://drive.google.com/file/d/1iXJeMBr5JOkNbMSbg0oDLD208n6J1G8p/view?usp=sharing <br>
Lecture 08 : Practical aspects of ML https://drive.google.com/file/d/11gDuct8jt8O6wVeU0_PBj9A9kai71rKg/view?usp=sharing<br>
Lecture 09 : K-Fold Validation https://drive.google.com/file/d/1nsRi3iTBBht4nFd_HQ0ZgHWKVO54awDr/view?usp=sharing <br>
Lecture 10 : Data Visualization https://drive.google.com/file/d/11RtXAuTgRPKZmySrPM6L1u4sunpwEkpk/view?usp=sharing <br>
Lecture 11 : KNN & Scaling https://drive.google.com/file/d/1eUQyWoKx4RmkzQreUs_RgWSz558sGWEU/view?usp=sharing <br>
Lecture 12 : Imbalance class prbolem, Precision, Recall, F1-Score https://drive.google.com/file/d/1IKpEsJhFls50DKSKvE6xedUsv93mZsjF/view?usp=sharing <br>
Lecture 13 : Accuracy metrics & AUC ROC curve https://drive.google.com/file/d/1Ltzb-iQdtAhagX9-yi8gNGDbUMXGfMzv/view?usp=sharing<br>
Lecture 14 : Notebook Example https://drive.google.com/file/d/1PhKw66PqujW5WQ9avuFU7qC8Ge6TIoZJ/view?usp=sharing <br>
