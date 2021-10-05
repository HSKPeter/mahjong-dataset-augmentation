# Mahjong Dataset Augmentation

## Introduction
* This repository uses *Python* and *OpenCV* to augment an image dataset of Chinese mahjong tiles.
* The application would generate images where mahjong tiles would be rotated and placed on a random background.

    <img src="samples/2021-10-04-23-43-28-615868.jpg" width="200" alt="Sample dataset image" />

## Application of dataset
* The application could generate a dataset with tens of thousands of images and annotations.
* The application would export a *csv file* that saves the detailed annotation information of the images in the dataset. The *csv file* is compiled in the format that confroms to the guideline of **AutoML Vision of Google Cloud Platform** ([Link](https://cloud.google.com/vision/automl/object-detection/docs/csv-format)).

* With the *csv file*, the image dataset could be  used to train an object detection model in the **AutoML Vision of Google Cloud Platform** .  The trained object detection model could identify and locate mahjong tiles within a live streaming video.

    <img src="samples/object-detection.gif" width="200" alt="Sample GIF that demonstrates the object detection feature of the trained model"/>

## Credits
* Describable Textures Dataset ([Link](https://www.robots.ox.ac.uk/~vgg/data/dtd/))
* Mahjong Dataset created by Camerash ([Link](https://github.com/Camerash/mahjong-dataset))