Automatic Basal Shoot Cutter

Raspberry Pi 4b
Rasbian OS 32-bit, bullseye, Armv7l 

Git clone labelImg
https://github.com/heartexlabs/labelImg 

Gathered images from KingPLeather
Used LabelImg to gather get data in PASCAL VOC format

TFlite model maker
https://www.tensorflow.org/lite/models/modify/model_maker/object_detection
https://colab.research.google.com/github/tensorflow/tensorflow/blob/master/tensorflow/lite/g3doc/models/modify/model_maker/object_detection.ipynb 

jenga.tflite trained with:
efficientdet-lite0 architecture
jengaPlus.tflite trained with:
jenga.tflite + more images + efficientdet-lite4 architecture

lite-model_ssd_mobilenet_v1_1_metadata_2.tflite - gather from:
https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf1_detection_zoo.md#mobile-models

sudo pip3 install TFlite
sudo pip3 install TFlite-support
sudo pip3 install opencv-python
sudo pip3 install gstreamer-player
