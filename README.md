# Sign-Language-to-Text-Covertor
Real-time true action-detection based Sign Language to Text Covertor


## Mediapipe Dataset is available at Kaggle
[https://www.kaggle.com/datasets/amanbind/mp-data-no-face](https://www.kaggle.com/datasets/amanbind/mp-data-no-face)<br>
To know how to use this dataset read the comments in the jupyter files from 1 to 6<br>
You can also [this video](https://www.youtube.com/watch?v=doDUihpj6ro&t=8s), I created this project from here itself.<br>

## Videos Dataset is Available at kaggle 
[https://www.kaggle.com/datasets/amanbind/smallwlasl/](https://www.kaggle.com/datasets/amanbind/smallwlasl/)<br>
To know how to use video dataset read the comments in 2 and 3 jupiter files. I have tried to explain there.<br>
If You are using Video Dataset use 3rd script (3 Flip videos horizontally.ipynb) to increase the number of videos and workable for left hand users. <br>

If you want to train the model yourself you can run the 5th jupyter file or use [this](https://www.kaggle.com/code/amanbind/training-and-testing-no-face) file on kaggle i have created. I recommend you use kaggle with free GPU for processing if you do not have any PC with GPU.


The requirements.txt file is for conda on M1 Silicon<br>
If You are using M1 based mac, you have to download download the following libraries
1. tensorflow-macos
2. mediapipe-silicon
3. opencv-python
4. jupyter
5. numpy
6. matplotlib

You can also use leverage apple metal gpu by using tensorflow-metal, but then you will have to first download and install miniconda.<br>
Steps of installation are given [here](https://github.com/mrdbourke/m1-machine-learning-test/blob/main/README.md#how-to-setup-a-tensorflow-environment-on-m1-m1-pro-m1-max-m1-ultra-m2-using-miniforge-shorter-version)


# If you are using any other system then you can simply install the following libraries through pip
1. tensorflow
2. tensorflow-gpu (optional, ie., if you have cuda GPU)
3. mediapipe
4. opencv-python
5. jupyter
6. numpy
7. matplotlib

