# Image-Generation-Face-Generation-with-GANs

## Description of work:
Dataset: Celeba https://www.kaggle.com/datasets/jessicali9530/celeba-dataset

Dataset preparation: using a detector/segmentator to pre-cut out people’s faces.

Training GAN for unconditional face generation task.

And then converting the same grid into a conditional one and training it for the task of conditionally generating faces based on a person’s gender (or any other characteristic).

Metrics: calculate FID and IS, show learning curves.

Loading Dataset:
~~~
!kaggle datasets download -d jessicali9530/celeba-dataset
~~~

Unconditional GAN results:

![image](https://github.com/ghfranj/Image-Generation-Face-Generation-with-GANs/assets/98123238/123c75a4-d79d-4c81-97c2-a53cfba62f96)

Conditional GAN results:

![image](https://github.com/ghfranj/Image-Generation-Face-Generation-with-GANs/assets/98123238/61cce0f0-61bc-4ad3-97ae-f373937b7cef)
