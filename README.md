# Optimizer Digit Recognition Project

This project is part of the course Eleven consulting super-case - MSc Data Science for Business - HEC Paris and École Polytechnique.

## Problem statement

The problem emerged from the need to automate the tracking of oil consumption in mining sites. Our goal is to detect the number of liters of oil consumed that are recorded on images taken by employees. Since the conditions on mines are harsh, photos have different illumination conditions and problematics.

So our problem is reduced to detecting a sequence of numbers in a image. We have taken two approaches:
- Cropping method: we try to find each digit, crop it into individual digits and identify each with a NN.
- End-to-end method: we built a NN that receives the full image with all digits and identify the full sequence.

## Given dataset

We were given with a small dataset with images in different conditions.

- Digital number images:
  - HQ images: 219 images
  - MQ images: 226 images
  - LQ images: 331 images
- Analog number images:
  - HQ images: 160 images
  - LQ images: 891 images

# Team members and contribution

Ching-yu Lin / Project management, Data curation/labelling, Model architecture

Fernando Perez / End-to-end model training and fine-tuning

Jorgen Lund / Data augmentation and generation and End-to-end model training

Jiahao Wang / Image processing and digit cropping for analog and digital images

Akshay Sundar / Digital number images' screen cropping and processing and digit recognition model training

# Duration

This project was conducted between 2019-Sept-18 to 2019-Sept-24.

# Final Result

We tried two different digit recognition pipelines:

1. Cropping method
2. End-to-end solution

with various data augmentation / creation techniques.

We achieved 64.99% accuracy on digital digit test-set and 59.45% on analog test-set.

Our team won the first place in the technical aspect.
