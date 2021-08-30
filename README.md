# VinBigData Chest XRay - Object Detection - Pytorch
<p align="center">
  <img width="1080" height="auto" src="https://user-images.githubusercontent.com/58674441/131401004-d0442fab-316b-47ce-9a9d-7ffeea9ee038.png">
</p>

These are my notebooks for the VinBigData Chest XRay competition: "Automatically localize and classify thoracic abnormalities from chest radiographs"

## Model
I used an ensemble of a 2Class CNN Classifier from Pytorch (Classifies if any disease is present in the Image) and a Faster-RCNN Model from Pytorch on a custom 1024x1024 Dataset

## Results
This gave results anywhere from 0.102 to 0.235 with mAP 0.4

## Future Ideas/Projects:
* Use an ensemble of Detectron, Faster-RCNN, and 2Class for potentially better results

