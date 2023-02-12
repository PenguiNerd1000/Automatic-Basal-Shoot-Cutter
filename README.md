# automatic_basal_shoot_cutter

Git clone model-master
https://github.com/tensorflow/models.git

pip install TensorFlow==1.15 lxml pillow matplotlib jupyter contextlib2 cython tf_slim

Download ssd_mobilenet_v1_coco_2018_01_28.tar.gz
Extract to models folder

Git clone labelImg
https://github.com/heartexlabs/labelImg 

Import openCV
Using YOLO architecture
R-CNN


generate_tfrecord.py
  Usage:
    # From tensorflow/models/
    # Create train data:
    python generate_tfrecord.py --csv_input=data/train_labels.csv  --output_path=train.record
    # Create test data:
    python generate_tfrecord.py --csv_input=data/test_labels.csv  --output_path=test.record
    python generate_tfrecord.py --csv_input=data/test_labels.csv  --output_path=data/test.record --image_dir=images/

  xml_to_csv.py
    import os
    import glob
    import pandas as pd
    import xml.etree.ElementTree as ET


virtualenv.exe venv3
pip install opencv-python
pip install tensorflow-intel


# Install Anaconda
https://www.anaconda.com/products/distribution
C:\Users\jovan\anaconda3\condabin\conda install -c anaconda openssl

C:\Users\jovan\anaconda3\condabin\conda update --all
C:\Users\jovan\anaconda3\condabin\conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0

LINUX
Install Ubuntu 22.04.1-live-server-amd64

sudo apt update
sudo apt install python3-dev python3-pip python3-venv
sudo apt-get install python3-opencv

python3 -m venv virtualenv
source virtualenv/bin/activate

pip install --upgrade pip
pip install --upgrade TensorFlow
pip install opencv-python
pip install Pillow
pip install object-detection


FireDaemon OpenSSL Binary Distribution

For help and support please see:
https://kb.firedaemon.com/support/solutions/articles/4000103749

For installation instructions please see:
https://kb.firedaemon.com/support/solutions/articles/4000121705
