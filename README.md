# English

## Context of project

The main purpose of this competition is to make a GAN that will be able to generate between 7000 and 10000 images with the style of the famous painter Monet.

The generated images have to be jpg format with a size of 256x256x3 (RGB) and be zipped in a single file named images.zip.  
The evaluation metric used by kaggle to know if the image is considered good is MiFD: **Memorization-informed Fréchet Inception Distance**.  
The smaller MiFID is, the better your generated images are.  
More details can be found at: [Kaggle Competition](https://www.kaggle.com/competitions/gan-getting-started/overview/description).  

A notebook that allows to well start this challenge is the Notebook of de Amy Jang:

[https://www.kaggle.com/amyjang/monet-cyclegan-tutorial](https://www.kaggle.com/amyjang/monet-cyclegan-tutorial)

This notebook gives basis of how data will be loaded inside a kaggle notebook. The method used in this notebbok to kgenerate images is called cycleGAN, that we won't use for the time being.

Another notebook that allows to manage the development and the training of a GAN is from Tensorflow tutorial:

[Deep Convolutional Generative Adversarial Network  |  TensorFlow Core](https://www.tensorflow.org/tutorials/generative/dcgan?hl=en)

Some ideas of models to design for the generator and the discriminator of the GAN could be found at these links:

[Building a Generative Adversarial Network using Keras - GeeksforGeeks](https://www.geeksforgeeks.org/building-a-generative-adversarial-network-using-keras/)

[pix2pix: Image-to-image translation with a conditional GAN  |  TensorFlow Core](https://www.tensorflow.org/tutorials/generative/pix2pix?hl=en)

The table of content for the study of the notebook P8_GAN which goal is to load data, make the GAN and train is as follow:

    1. Introduction to GAN
    2. Competiton context
    3. Data preparation
    4. Model preparation
        4.1. Different type of Neural Networks
        4.2. Evaluation of time generation
        4.3. Build the GAN
    5. Train the GAN
    6. Test the GAN
	



# French

## Contexte du projet

L’objectif de la compétition consiste à réaliser un GAN capable de générer entre 7000 et 10000 images avec le style du peintre Monet.  
Les images générées doivent être au format jpg de taille 256x256x3 (RGB) et zippées dans un seul fichier nommé images.zip.  
La métrique d'évaluation utilisée par kaggle pour savoir si l'image générée est considérée bonne est la MiFD: **Memorization-informed Fréchet Inception Distance**.  
Plus la MiFD est petite, meilleur sont les images générées.  
Pour plus de détails, voir le lien suivant: [Kaggle Competition](https://www.kaggle.com/competitions/gan-getting-started/overview/description).

Un notebook permettant de bien commencer ce challenge est le Notebook suivant de Amy Jang:

[https://www.kaggle.com/amyjang/monet-cyclegan-tutorial](https://www.kaggle.com/amyjang/monet-cyclegan-tutorial)

Ce notebook donne les bases sur la manière dont les données seront chargées dans un notebook kaggle. La technique ensuite utilisée pour générée les images est un cycleGAN que nous n’utiliserons pas en premier lieu.

Un notebook permettant de gérer la modélisation et l’entraînement d’un GAN est celui du tutoriel de Tensorflow suivant:

[Deep Convolutional Generative Adversarial Network  |  TensorFlow Core](https://www.tensorflow.org/tutorials/generative/dcgan?hl=en)

Les liens suivants donnent des idées de modèles à réaliser pour les générateurs et discriminateurs du GAN.

[Building a Generative Adversarial Network using Keras - GeeksforGeeks](https://www.geeksforgeeks.org/building-a-generative-adversarial-network-using-keras/)

[pix2pix: Image-to-image translation with a conditional GAN  |  TensorFlow Core](https://www.tensorflow.org/tutorials/generative/pix2pix?hl=en)

Le plan d'étude du notebook P8_GAN dont l'objectif est lle chargement des données, la création du GAN et son entraînement est le suivant:

    1. Introduction to GAN
    2. Competiton context
    3. Data preparation
    4. Model preparation
        4.1. Different type of Neural Networks
        4.2. Evaluation of time generation
        4.3. Build the GAN
    5. Train the GAN
    6. Test the GAN
