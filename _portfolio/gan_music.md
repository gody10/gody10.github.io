---
title: "Generative Adversarial Networks for Music Generation"
excerpt: "In this project Generative Adversarial Networks are trained on classical music in order to learn to produce music [(github repository)](https://github.com/GradientSEALs/gan_music): **Generative Adversarial Networks, Deep Machine Learning, Vision**<br/><img src='/images/mozzart_requiem.jpg' width='700'>"
collection: portfolio
---

## Producing Music with Generative Adversarial Networks (GANs)

### Description
This project explores the ability of GANs to study a music mp3 dataset and learn how to compose music similar to the examples given to it. More specifically, the dataset trained on is one of the most famous piano datasets (https://magenta.tensorflow.org/datasets/maestro) available. One interesting aspect of this experiment is the way the problem was formulated. Instead of using the sound data, we used a library that translates mp3 files to images. Then we trained our GANs based on the images produced. Therefore, the GANs learn in a task that they have been proven to be good in (based on bibliography) and we simply translate the image back to an mp3 form. This was a really exciting project that taught me a lot and forced me to grow as a researcher by getting me into contact with hard and previously unknown concepts.


### Implementation Details

We implemented, trained and tested the GANs using Pytorch. We also made use of midi2img and img2midi python scripts that tranform mp3 files to pictures and vice versa. The results of the GANs are located on the music_folder.

### Technologies Used

- **Deep Machine Learning** – Experimented with advanced Machine Learning Models such as GANs.
- **Problem Restructuring** – Restructured the problem of mp3 creation to the problem of image creation that is well suited for this architecture.
- **Cutting-Edge Libraries** – Utilized Pytorch and Jupyter Notebook to build and present this project.