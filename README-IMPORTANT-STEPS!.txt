Prerequisites
--------------
You’ll need to install some python packages to be able to run this advanced python project. You can do this with pip:

pip install numpy opencv-python pillow tensorflow keras imutils scikit-learn matplotlib

------------------------------------------------------------
STEPS:
------
1 - Download and unzip the project at your desired location

2 - inside the inner "breast-cancer-classification-using-deeplearning" directory, create directory "datasets" inside this, create directory "original"

3 -  Download the dataset from the link below:
"https://www.kaggle.com/paultimothymooney/breast-histopathology-images/"

4 - Unzip the dataset in the original directory. To observe the structure of this directory, you can use the tree command:

	1. cd YOUR_PROJECT_DIRECTORY\datasets\original
	2. tree

5 - Run the script build_dataset.py