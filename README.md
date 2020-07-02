# Background Changer using Semantic Segmentation with Tensorflow

This script removes the background from an input image. You can read more about segmentation [here](http://colab.research.google.com/github/tensorflow/models/blob/master/research/deeplab/deeplab_demo.ipynb)

### Setup
The script setup.sh downloads the trained model and sets it up so that the seg.py script can understand. 
>	./setup.sh

### Running the script
For better accuracy (slower approach) :
>	python3 seg_chng_background.py sample.jpg sample_background.jpeg sample_bgchanged.jpeg accurate

Use the script as specified below, to execute fast but lower accuracy model:
>	python3 seg.py sample.jpg sample_background.jpeg sample_bgchanged.jpeg

### Dependencies
>	tensorflow, PIL

### Sample Result
Input: 
![alt text](https://github.com/raikarsagar/image-background-changer/raw/master/sample.jpg "Input")

Background:
![alt text](https://github.com/raikarsagar/image-background-changer/raw/master/sample_background.jpg "Background")

Output: 
![alt text](https://github.com/raikarsagar/image-background-changer/raw/master/sample_bgchanged.png "Output")
