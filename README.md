# Image Colorization

## Project Description

Our project focuses on colorizing gray-scale images using state-of-the-art deep learning techniques. Taking inspiration from recent advancements in this field, we have implemented a model that combines a deep Convolutional Neural Network (CNN) trained from scratch with high-level features extracted from the pre-trained Inception-ResNet-v2 model. By utilizing a fully convolutional architecture, our encoder-decoder model is capable of effectively processing images of varying sizes and aspect ratios.
   
Furthermore, we have created a diverse range of applications for our model, with a particular emphasis on colorizing historical photographs. This allows us to bring vibrant and lifelike colors to black-and-white images from the past, preserving their historical significance while also providing a visually captivating experience.

## Inputs:
  1. [Dataset Link](https://drive.google.com/drive/folders/1I3m-xlb6zsDQySI5roOxI9BclVaFfnqs?usp=share_link)
  2. [Resnet weights](https://drive.google.com/drive/folders/1ZrHKLRYePs2n2uBnEgGli4xTJhTasJdo?usp=share_link)

## Steps to run:
  1. add the dataset and wts to your google drive as a shortcut.
  2. Change image_folder_url to the dataset in your google drive.
  3. Change inception.load_weights path to Resnet wts in your drive.
  4. Run the code.
