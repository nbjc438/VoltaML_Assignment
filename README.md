# Signboard Detection

Object detection is a computer vision technique for locating instances of objects in images or videos. Here in this project, the focus is on Road Sign Detection.
The underlying architecture is based on the VGGNet followed by two parallel stacks, one for sign recognition and the other for sign detection using a bounding-box.


### Dataset

The Road Sign Dataset can be found
[here](https://www.kaggle.com/datasets/andrewmvd/road-sign-detection
).

This dataset contains 877 images of 4 distinct classes for the objective of road sign detection.
Bounding box annotations are in the PASCAL VOC format.


### Training

- The test-train split was done on a 20-80 ratio.
- The model was trained for 25 epochs with a bath size of 16.

### Environment Details




### Results

The proposed model demonstrates a sign-recognition accuracy of 85.8% and a bounding box prediction accuracy of 77.8%. 

![accuracy-graph](https://user-images.githubusercontent.com/88189618/208253776-ae32bb2f-d6e8-4ea9-8872-27920dd79ff0.png)

