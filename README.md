# road_sign_detection_on_arduino_with_tensorflow
Building a ML model for road sign detection on arduinos. Challenges include limited memory, limited computing power and limited energy. Final project in the course ML for IoT, EITP40, 2023. C++ code for the Arduino devices provided by the teacher assistent was developed by Nikhil Challa and Simon Erlandsson as part of the course ML in IOT, 2022 (https://github.com/niil87/Machine-Learning-for-IOT---Fall-2022-Batch-Lund-University). 


## Project done by: Joel Bengs & Fabian Rosén

## Overview of the Project
This project centers on crafting an intelligent traffic sign recognition model that can run on Arduino devices. Starting from the GTSRB roadsign dataset, we create seven distinct datasets for training, validation, and testing. A Convolutional Neural Network was trained (in Kaggle) and then used to process data, creating 64-feature representations compatible with the limited memory on the Arduino. Small Multi-layer Perceptrons were trained on the device and evaluated both against a high-quality dataset and images captured with the Arduino’s own camera.
Results showcased successful single-device training and improved performance in distributed training. Challenges arose from low-quality Arduino-captured images. In summary, the project successfully demonstrated machine learning integration on Arduino for practical traffic sign recognition and the benefit of distributed learning.

