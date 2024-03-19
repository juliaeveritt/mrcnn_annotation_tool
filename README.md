# Mask R-CNN for Object Detection and Segmentation

This is an implementation of [Mask R-CNN](https://arxiv.org/abs/1703.06870) on Python 3, Keras, and TensorFlow. The model generates bounding boxes and segmentation masks for each instance of an object in the image. It's based on Feature Pyramid Network (FPN) and a ResNet101 backbone. 

This model was applied to the annotation of TEM images as part of my Undergraduate Thesis at Queen's University in collaboration with Queen's Computational Materials group (Professor Laurent Beland, Yezhou Ni, Jun-Tiang Zhang) and CNL. Tkinter was used to build a UI for reviewing model-generated annotation and revising them as needed.

* [hydride_prediction.ipynb](model/hydride_prediction.ipynb) gives an example of using mask r-cnn to annotate a single image. 
* [annotation_tool.ipynb](annotation_tool.ipynb) contains code for the GUI to annotate images using mask r-cnn and manually revise annotations as needed. Any annotation revisions are saved to a .csv file.
* [report.pdf](results/report.pdf) contains my final thesis report with more information on the project and its use.

## Installation
1. Clone this repository
2. Run setup from the repository root directory
```bash
$ conda create env -f environment.yml
```
