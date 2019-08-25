## TCS Humain 2019 Submission

### Introduction

The repository features notebooks for contest submission for **Tata Consultancy Services Humain 2019** for the problem statement **Vehicle Number Plate Detection**. 

### Prerequisites

+ Python 3
+ Scikit learn
+ Tensorflow
+ Matplotlib
+ OpenCV
+ Imutils
+ Mahotas
+ Pytesseract

### Notebooks

+ `initial_work.ipynb`

    The notebook displays initial working approach to find the best approach to preprocess data in order to arrive at a cleaner image for processing. Some of these approaches have been discarded in final version due to inconsistency with the dataset. 

    **Inconsitency**: Morphological Operations for OCR on data and plot of **Histogram of Oriented Graph (HOG)** did not present fruitful result but may prove useful with other operations.

+ `lpr_preprocess.ipynb`

    A formalized notebook for the above less clutter.

+ `lic_plate_detection.ipynb`

    The final demonstration of the Vehicle number plate detection notebook with techniques used as:

    - Adaptive thresholding
    - Find Contours
    - Pytesseract
  
### Datasets and models

+ Used pretrained models from [tesseract](https://github.com/tesseract-ocr/tessdata/blob/master/kor.traineddata).

+ Dataset URL [here](https://github.com/Biswajee/TCSHumain19LPR/blob/master/Indian_Number_plates.json).