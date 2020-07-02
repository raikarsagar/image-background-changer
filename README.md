# Background Changer using Semantic Segmentation with Tensorflow

This script changes the background of an input image with given background. You can read more about segmentation [here](http://colab.research.google.com/github/tensorflow/models/blob/master/research/deeplab/deeplab_demo.ipynb)

### Setup
The script setup.sh downloads the trained model and sets it up so that the seg.py script can understand. 
>	./setup.sh

### Running the script
For better accuracy (slower approach) :
>	python3 seg_chng_background.py sample.jpg sample_background.jpeg sample_bgchanged.jpeg accurate

Use the script as specified below, to execute fast but lower accuracy model:
>	python3 seg_chng_background.py sample.jpg sample_background.jpeg sample_bgchanged.jpeg

### Dependencies
>	tensorflow, PIL

### Sample Result
[Input](https://github.com/raikarsagar/image-background-changer/blob/master/sample.jpeg)

[Background](https://github.com/raikarsagar/image-background-changer/blob/master/sample_background.jpeg)

[Image with Background](https://github.com/raikarsagar/image-background-changer/blob/master/sample_bgchanged.jpeg)

### Credits to 
[Susheelsk](https://github.com/susheelsk)
Code is originally utilized from https://github.com/susheelsk/image-background-removal