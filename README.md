# Multimodal Representation 

This code is use for test the test dataset so you should have the model that had been trained before.
Code for Making Sense of Vision and Touch. 
https://sites.google.com/view/visionandtouch

Code written by: Matthew Tan, Michelle Lee, Peter Zachares, Yuke Zhu 
## Recommended System
* Ubuntu 18.04.6 LTS
* python 3.6.9
* install dependencies from requirements below

## requirements
`pip install -r requirements.txt`

## get dataset

```
cd multimodal/dataset
./download_data.sh
```
## run test

`python mini_main.py --config configs/training_default.yaml`


## ROBOT DATASET
----
action                   Dataset {50, 4}\
contact                  Dataset {50, 50}\ 
depth_data               Dataset {50, 128, 128, 1}\
ee_forces_continuous     Dataset {50, 50, 6}\
ee_ori                   Dataset {50, 4}\
ee_pos                   Dataset {50, 3}\
ee_vel                   Dataset {50, 3}\
ee_vel_ori               Dataset {50, 3}\
ee_yaw                   Dataset {50, 4}\
ee_yaw_delta             Dataset {50, 4}\
image                    Dataset {50, 128, 128, 3}\
joint_pos                Dataset {50, 7}\
joint_vel                Dataset {50, 7}\
optical_flow             Dataset {50, 128, 128, 2}\
proprio                  Dataset {50, 8}\

