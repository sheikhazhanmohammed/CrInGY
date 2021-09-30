<h4 align="center">
  CrInGY: Cropped Image Enhancement using GANs for YOLO
</h4>

<p align="center">
    <a href="https://colab.research.google.com/github/sheikhazhanmohammed/CrInGY/"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>
    <a href="https://circleci.com/gh/huggingface/transformers">
        <img alt="Build" src="https://img.shields.io/badge/python-3%2B-brightgreen?logo=Python">
    </a>
    <a href="https://circleci.com/gh/huggingface/transformers">
        <img alt="Build" src="https://img.shields.io/badge/git-2.29.2-brightgreen?logo=git">
    </a>
</p>

## <div align="center">Overview</div>

Objection detection is one of the most challenging tasks in the field of Computer Vision. What makes the task more challenging is the prescence of small objects in large images. Detecting small objects in such images still remains a very difficult task till date. This Hacktober, let us all come together to find a solution to this problem. We aim to crop images into smaller bits and enhance the image quality using Generative adversarial networks. These enchanced images can then undergo object detection and stitching the smaller patches back together gives us the original image again.

## Current Goals

- [ ] Add dataset creator for Image enhancement GAN.
- [ ] Test out various GANs to see which model suits the purpose.
- [ ] Create dataset_generator.py that takes in an input image folder and patch size and returns source and target images for training the GAN Network.
- [ ] Create gan_trainer.py that takes in source training folder, source label folder, model name, and other hyper-parameters and trains a GAN model.
- [ ] Test the performance of pre-trained YOLO v5 models on original images and compare them with enhanced images.
- [ ] Add a Colab notebook to demonstrate how to use the functions for custom usage.

## Contributing

`CrInGY` would love to see you contribute to our opensource project. To become a contributor, put an email to azhanmohammed1999@gmail.com or mohd.abbas.ansari.2001@gmail.com and wait till the current maintainers assign a use-case to you.


