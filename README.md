# ml-project-2-lateregistration

## Introduction 
Second Machine Learning Project, in collaboration with [CHILI Lab at EPFL] (https://www.epfl.ch/labs/chili/) using original data collected by our team from their lab. The goal is to develop a model capable of correctly classifying images of a 4-disk [Hanoi Tower game] (https://en.wikipedia.org/wiki/Tower_of_Hanoi), i.e. define for any given image in which of the possible legal states the game is currently at. This includes processing the data, augmenting it, implementing and optimizing Convolutional Neural Networks. The aim of the project is to be used with a NAO robot at the lab's disposal, for educational purposes.

## How to run our project ? 
First download the training and test data from our [Drive] (https://drive.google.com/drive/folders/1k5WwpX7hf63v9wG9r0P4flNw1rXXEO-a?usp=sharing), and include the folders BBtrD and BBTeD inside the `data folder`.

CHILI Lab provided us with a useful Graphical Interface to be used while testing our models, with the following requirements to run:
* OS -> Ubuntu 20.04
* Language -> Python 3+
* ROS -> Noetic

## Project Structure
* `data folder`  : Contains the training data, the test data, and the categories' .txt file (we put a placeholder to create the folder on git, this is to be replaced by the actual data folders). 
* `util folder` : Contains some modules that we used to format the data to our expected wants
* `HanoiTower.ipynb` : Contains our CNN implementation 
* `HanoiTower_ResNet_50.ipynb` : Contains the ResNet transfer learning implementation
* `TransferLearning.ipynb` : Contains the VGG16 transfer learning implementation

## Contributors 
* **Izellalen Youssef**
* **Khoneisser Cyril**
* **Laarous Hamza**
