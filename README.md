# README #
## Software Product: ##

Language: Python

### Convolutional Neural Network for Classifying Pink Salmon ###

* This repository holds the code for a tool that classifies a photo of a salmon as either a Pink Salmon or not. The Pink Salmon (Oncorhynchus gorbuscha) is native to the Pacific, but was introduced into Russian rivers in the 1950s (Gordeeva et al.). The population migrated west to Norway by the 60s and established a self-sustaining population there (Mo et al.). In 2017, the Pink Salmon begun to be reported in alarming numbers in the Scottish waters and Scotland launched a program to study the population to determine if it is self-sustaining or simply roaming (Armstrong et al.). Fishermen are asked to submit photos of Pink Salmon that they catch in order to track where they are appearing in Scotland. This classifier hopes to take an image of any salmon caught and classify it as a Pink Salmon or not. 

<figure>
    <img src="Fish_Classifier/fish-photos/all-fish/salmon (107).jpg" alt="drawing" width="200"/>
    <figcaption>Photo of Pink Salmon</figcaption>
</figure>

## Libraries ##

* Pytorch Lightning - [Pytorch Lightning](https://www.pytorchlightning.ai/) is a framework that organizes models into easy to understand code that runs more like a software program than a script. Lightningt will handle the creation, organization, logging and displaying of the model

## Folder Structure ##
* /Dissertation: This folder includes the final written report for the project.
* /Fish_Classifier: This folder includes the code for the project.
  * /Fish_Classifier: This folder contains the Django API and UI project. There is an additional readme in that folder for the Django project.
  * /fish-photos: This folder contains the photos of the fish used in the project as well as the .csv files for the labels. For the purposes of turing the project in, the photos have been removed as they cause the file to exceed the size limit.
  * /Model_Trainers: This folder contains the jupyter files used to train the FTFM and PSIM.
* /yolov5: This folder is a local copy of the ultralytics yolov5 github repository copied to allow for work without an internet connection. The project should be setup to use the actual repository in order to get the latest code. It can be found here: https://github.com/ultralytics/yolov5

### Who do I talk to? ###

* Sam Vogel
* MSc student at University of Glasgow
* 2591247v@student.gla.ac.uk