[pictures_dataset]: ./assets/processed_face_data.png "Pre-processed pictures of celebrities"
[generated_faces]: ./generated_faces.png "Generated Faces"

# Face Generation, using DCGAN (Deep Convolutional Generative Adversarial Networks)
Udacity Deep Learning nanodegree project: `Face Generation`

## Introduction
In this project, you'll define and train a DCGAN on a dataset of faces. Your goal is to get a generator network to generate new images of faces that look as realistic as possible!

The project will be broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the notebook, you'll be able to visualize the results of your trained Generator to see how it performs; your generated samples should look like fairly realistic faces with small amounts of noise.

## Training dataset
You'll be using the [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) to train your adversarial networks.

[This dataset](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip) is more complex than the number datasets (like MNIST or SVHN) you've been working with, and so, you should prepare to define deeper networks and train them for a longer time to get good results. It is suggested that you utilize a GPU for training.

Since the project's main focus is on building the GANs, we've done some of the pre-processing for you. Each of the CelebA images has been cropped to remove parts of the image that don't include a face, then resized down to 64x64x3 NumPy images. Some sample data is show below.

![Pre-processed pictures of celebrities][pictures_dataset]

## Example of generated faces

![Generated Faces][generated_faces]
