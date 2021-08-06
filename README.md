# FireDetection-TensorFlowAPI
**Comprehensive Analysis of Forest Fire Detection using Deep Learning Models and Conventional Machine Learning Algorithms**
> Zeynep Hilal Kilimci and Süha Berk Kukuk

> Paper : [International Journal of Computational and Experimental Science and Engineering](https://doi.org/10.22399/ijcesen.950045)
 
 > Abstract : Forest fire detection is a very challenging problem in the field of object detection.
Fire detection-based image analysis have advantages such as usage on wide open
areas, the possibility for operator to visually confirm presence, intensity and the
size of the hazards, lower cost for installation and further exploitation. To
overcome the problem of fire detection in outdoors, deep learning and
conventional machine learning based computer vision techniques are employed to
determine the fire detection when indoor fire detection systems are not capable.
In this work, we propose a comprehensive analysis of forest fire detection using
conventional machine learning algorithms, object detection techniques, deep and
hybrid deep learning models. The contribution of this work to the literature is to
analyze different classification and object detection techniques in more details that
is not addressed before in order to detect forest fire. Experiment results
demonstrate that convolutional neural networks outperform other methods with
99.32% of accuracy result.

# Folders 
> ObjectDetection-TensorFlowAPI.zip folder contains :
 <p align="center">
    <img src="https://github.com/shbkukuk/FireDetection-TensorFlowAPI/blob/main/images/Ekran%20g%C3%B6r%C3%BCnt%C3%BCs%C3%BC%202021-08-06%20115128.png"> <br />
    <em> 
    </em>
</p>

1. Fire folder contains the dataset

2. Models folder contains Single Shot Detector and Faster R-CNN that are Object detection Applications

3. Preparing-Dataset contains codes that need to convert folders types

# Dataset 
> This is a dataset that I collected to train my own Fire detector with [TensorFlow's Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection). Images are from Google and Pixabay. In total, there are 10.000 images.

# Preparing-Dataset 
> preparing dataset is used the LabelImg Applications. LabelImg is a graphical image annotation tool. [tzutalin/labelImg](https://github.com/tzutalin/labelImg)
 <p align="center">
    <img src="https://github.com/shbkukuk/FireDetection-TensorFlowAPI/blob/main/images/Ekran%20G%C3%B6r%C3%BCnt%C3%BCs%C3%BC%20(11).png" width="800"> <br />
    <em> 
    </em>
</p>

# Training 
> PC requirements that have Intel (R) Core (TM) i5-7200U CPU @ 2.50GHz   2.71 GHz process unit and NVIDIA GeForce 940MX graphic card in Windows 10 operation system.
<p align="center">
    <img src="https://github.com/shbkukuk/FireDetection-TensorFlowAPI/blob/main/images/Ekran%20G%C3%B6r%C3%BCnt%C3%BCs%C3%BC%20(12).png" width="800"> <br />
    <em> 
    </em>
</p>

# RESULT
> Model is Tested On Raspberry Pi 4 8 GB ram
<p align="center">
    <img src="https://github.com/shbkukuk/FireDetection-TensorFlowAPI/blob/main/images/rpi-fire-detect.jpg" width="800"> <br />
    <em> 
    </em>
</p>
