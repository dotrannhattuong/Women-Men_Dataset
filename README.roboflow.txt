
Women/Men - v1 2022-08-08 3:22pm
==============================

This dataset was exported via roboflow.com on September 16, 2022 at 9:27 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 2656 images.
- are annotated in YOLO v7 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Fit (black edges))

The following augmentation was applied to create 3 versions of each source image:
* Random rotation of between -20 and +20 degrees
* Random shear of between -13° to +13° horizontally and -13° to +13° vertically
* Random brigthness adjustment of between -20 and +20 percent
* Random Gaussian blur of between 0 and 2 pixels
* Salt and pepper noise was applied to 8 percent of pixels


