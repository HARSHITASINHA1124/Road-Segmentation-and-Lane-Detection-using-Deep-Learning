# Road-Segmentation-and-Lane-Detection-using-Deep-Learning

1. Project Overview

This project has two parts:
Image Segmentation (using SegNet / CNN + MobileNetV2 encoder)
Goal: Automatically separate (segment) different objects in a road scene — e.g., roads, cars, trees, sky — pixel by pixel.
Lane Detection (classic computer vision approach)
Goal: Detect the lanes on a road image using image processing techniques (edges, lines, slopes).

2. Dataset and Setup

You are using the CamVid dataset, which is a dataset of road images and their corresponding masks (annotated images where each pixel has a class label like road, car, sky, pedestrian).
train/ → training image
trainannot/ → masks for training images
val/ → validation images
valannot/ → masks for validation images

Why masks?
Each pixel in the mask has a number representing the object class (road=0, car=1, etc.)
This is called semantic segmentation because we are labeling each pixel with its "semantic" meaning.
