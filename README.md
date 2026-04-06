# Automatic Number Plate Recognition

![dataset-cover](https://user-images.githubusercontent.com/57320216/166916670-03dfabe1-8c6c-471a-875c-8715354aa957.jpg)

**Automatic Number Plate Recognition (ANPR)** is the process of reading the characters on the plate with various optical character recognition (OCR) methods by separating the plate region on the vehicle image obtained from automatic plate recognition.

## Table of Content

- [Automatic Number Plate Recognition](#automatic-number-plate-recognition)

  * [What will you learn this project ](#what-will-you-learn-this-project)
  * [Dataset](#dataset)
  * [Project architecture](#project-architecture)
  * [Some Result](#some-result)
  * [Source](#source)
  * [Licence](#licence)


## What will you learn this project 

* Custom Object Detection
* Scene Text Detection
* Scene Text Recognation
* Optic Character Recognation
* EasyOCR, PaddleOCR
* Database,CSV format
* Applying project in Real Time
* Flask
## Dataset
The dataset I use for license plate detection:  

https://www.kaggle.com/datasets/andrewmvd/car-plate-detection

## Project architecture

The pipeline in the project is as follows:  

![images](https://github.com/mftnakrsu/Automatic-number-plate-recognition-YOLO-OCR/blob/main/imgs/flowchart.png)

- Custom object detection with plate extraction using yolov5
- Apply the extracted plate to EasyOCR and PaddleOCR
- Get plate text
- Filter text
- Write Database and CSV format
- Upload to Flask  


## Source  
- https://docs.python.org/3/library/csv.html  
- https://github.com/ultralytics/yolov5  
- https://github.com/PaddlePaddle/PaddleOCR
- https://medium.com/move-on-ai/yolov5-object-detection-with-your-own-dataset-6e3823a8f66b  
- https://github.com/JaidedAI/EasyOCR  
-     https://www.researchgate.net/publication/319198085_License_Number_Plate_Recognition_System_using_Entropy_basedFeatures_Selection_Approach_with_SVM/figures?lo=1&utm_source=google&utm_medium=organic

## To Do 
- [ ] use fcaykon pip yolo instead of hardcoded yolo files
- [ ] hugging face
