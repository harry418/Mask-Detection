# Mask Detection
In corona pandemic time, mask is a useful and safety tool for everyone. and goverment make it necessary tool for everyone and put a fine on people who do not wear it. Mask help to get you Purified air and prevent from many disease.

## Dataset
You can download dataset from my kaggle account from this given link.
<p align="center">
  https://www.kaggle.com/harry418/dataset-for-mask-detection
</p>

## Model Approach
Our approach is to design a model using Transfer learning and opencv to detect masks or without masks. In our approach we used Mobilenetv2 as transfer learning. and train our model on Mobilenetv2. and we obtain approx 94.% accuracy sucessfully.

## Training and Validation Graph - 
<p align="center">
    <img src="https://github.com/harry418/mask-detection/blob/master/images/plot.png" alt="Image"  />
</p>


## Sample Input - 
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample/23.jpg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample/266.jpeg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample/302.jpeg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample/491.jpeg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample/496.jpeg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample/538.jpeg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample/590.jpeg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample/615.jpeg?raw=true)

## Sample Output - 
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample-output/23.jpg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample-output/266.jpeg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample-output/302.jpeg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample-output/491.jpeg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample-output/496.jpeg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample-output/538.jpeg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample-output/590.jpeg?raw=true)
![alt_text](https://github.com/harry418/mask-detection/blob/master/images/sample-output/615.jpeg?raw=true)

## Files Description - 
### google_collab_training.ipynb 
> This file contain mask detector training with CNN and Transfer learning on google collab.
> https://github.com/harry418/Mask-Detection/blob/master/google_collab_train.ipynb

### mask_detection_train.py
> This file contain mask detector training on spyder and this file is a another version of google_collab_training.ipynb.
> https://github.com/harry418/Mask-Detection/blob/master/mask_detection_train.py

### mask_model
> This is weight applied architecture used for future predictions.
> https://github.com/harry418/Mask-Detection/blob/master/mask_model

### mask_detect_img.py
> This file is used for real time mask detection on a single image.
> https://github.com/harry418/Mask-Detection/blob/master/mask_detect_img.py

### mask_detect_vid.py
> This file is used for real time mask detection on webcam or any other camera.
> https://github.com/harry418/Mask-Detection/blob/master/mask_detect_vid.py

[![license](https://img.shields.io/github/license/DAVFoundation/captain-n3m0.svg?style=flat-square)](https://github.com/harry418/mask-detection/blob/master/LICENSE)
## Author
>Harit Yadav

