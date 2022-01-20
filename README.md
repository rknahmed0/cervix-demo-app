# Cervix Demo App - Cervix Detection

This includes an object detection app built on the [PyTorch Mobile](https://pytorch.org/mobile) platform. The most recent signed apk (trained on 100 epochs) can be found in app/build/outputs/apk/debug

### Cervix Detection

Demonstrates how to convert the popular [YOLOv5](https://pytorch.org/hub/ultralytics_yolov5/) model and use it in an Android app that assigns bounding boxes to the cervix from pictures in your photos, taken with camera, or with live camera. The trained model is the model file `best.torchscript.ptl` generated upon training using the YOLOv5 framework and can be found in app/src/main/assets. The sample images on the app have been replaced with publicly available images.