# DeepLearningGAN
Generative Adversarial Networks project. From Photograph to Comic using Pix2PixGAN. 

# Learning Process
I didn't want to implement a deep learning model which i didn't know so I have looked at different GAN or Deep Learning Models. After all this literature review, I finally understand what is going on in deep learning and what is used for those lines, how I can give my pictures to model etc. 
I started with a Fashion Gan model training using MNIST dataset.
GAN is a deep learning model that goals to create a picture which is looks like given dataset but a totally new picture. Two deep learning model fighting in this model and we want generator to win.
## Fashion GAN
#### DATASET (MNIST)
![Fashion Gan](https://github.com/EreenKara/DeepLearningGAN/assets/103642801/dcc04df0-7c12-4cbb-aa1e-7f77f7f82d61)
#### After a few epochs. It is doing bad.
![image](https://github.com/EreenKara/DeepLearningGAN/assets/103642801/632a6b32-3863-4715-ab28-745175219db4)
#### And final form, it is done. It can create new pictures that looks like MNIST but it is not MNIST.
![image](https://github.com/EreenKara/DeepLearningGAN/assets/103642801/760dd50f-1659-4b97-8713-54113af3e4d2)        

## CNN Example
I wanted to know how CNN works because FASHION GAN example used convolution in it as layers. I searched other layers and some of them are very basic and understandable, but convolution was different so I read articles about it. It is a mathematical operation like summation or subtraction but it is used to extract information from photo, and to reduce photo's resolution to be faster.
#### DATASET ( FROM INTERNET )
![image](https://github.com/EreenKara/DeepLearningGAN/assets/103642801/f37df7bf-8649-4f66-aa82-ddd3ecdaf6b4)
#### AFTER TRAINING
![image](https://github.com/EreenKara/DeepLearningGAN/assets/103642801/12c8b4dc-9e7e-4bd0-9444-cbd527060014)

## Another GAN example that different from first one
This project was my first deep learning project even fist machine learning project so all of those things were new to me. First GAN didn't satisfy me. I want to take a look to another example. S
#### DATASET (CIFAR10)
![image](https://github.com/EreenKara/DeepLearningGAN/assets/103642801/e57269a1-e007-442a-860f-2dc34ec90e5d)
#### First generation of photos.
![image](https://github.com/EreenKara/DeepLearningGAN/assets/103642801/15e76dd4-33f8-4280-8437-0c19c937a344)
#### Final
  
## Conditional GAN
GAN but it is know what image is what. If we want to create a truck and give truck number's to model, it will create a truck rather than rest of them. Normal GAN doesn't have such a that feature.
#### DATASET 
![image](https://github.com/EreenKara/DeepLearningGAN/assets/103642801/de1a5e7b-ec64-4b4c-9497-89713070890f)
#### First example
![image](https://github.com/EreenKara/DeepLearningGAN/assets/103642801/debfafa2-e049-45e3-a800-0a8b902319ff)
I didn't train the model. Conditional GAN wasn't my purpose. 





