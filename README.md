# market-duke-attribute-recognition
Repository of annotation of attribute recognition for market, duke and PETA dataset.

This repository consists of csv annotations of market, duke and PETA dataset. Thanks to https://github.com/vana77/DukeMTMC-attribute and http://mmlab.ie.cuhk.edu.hk/projects/PETA.html for releasing annotations and dataset.


# DukeMTMC-attribute

## About dataset

There are 23 attributes for [DukeMTMC-reID](https://github.com/layumi/DukeMTMC-reID_evaluation), 
which  is a subset of the [DukeMTMC](http://vision.cs.duke.edu/DukeMTMC/). 
The original dataset contains 702 identities for training and 1110 identities for testing. 
The attributes are annotated in the identity level, thus the file contains 24 x 702 attributes for training and 24 x 1110 for test, where the label "image_index" denotes the identity. 
The annotations are contained in the file duke_attribute.mat.


The 23 attributes are: 

| attribute | representation in file | label |
| :----: | :----: | :----: |
| gender | gender | male(1), female(2) |
| length of upper-body clothing | top | short upper body clothing(1), long(2)    |
| wearing boots| boots| no(1), yes(2)    |
| wearing hat| hat | no(1), yes(2) |
| carrying backpack| backpack | no(1), yes(2) |
| carrying bag| bag | no(1), yes(2) |
| carrying handbag| handbag | no(1), yes(2) |
| color of shoes| shoes | dark(1), light(2) |
| 8 color of upper-body clothing| upblack, upwhite, upred, uppurple, upgray, upblue, upgreen, upbrown | no(1), yes(2) |
| 7 color of lower-body clothing| downblack, downwhite, downred, downgray, downblue, downgreen, downbrown | no(1), yes(2) |

Note that the though there are 7 and 8 attributes for lower-body clothing and upper-body clothing, only one color is labeled as yes (2) for an identity.
 
# PETA Dataset
Details of PETA in  http://mmlab.ie.cuhk.edu.hk/projects/PETA.html

## Evaluation 
To evaluate, please repfer to the code [here](https://github.com/vana77/Market-1501_Attribute) and http://mmlab.ie.cuhk.edu.hk/projects/PETA.html

## Citation

Please see original annotation creators website https://github.com/vana77/DukeMTMC-attribute/ and http://mmlab.ie.cuhk.edu.hk/projects/PETA.html

## Dataset Licence
Please follow the [LICENSE_DukeMTMC-attribute](https://github.com/vana77/DukeMTMC-attribute/blob/master/LICENSE_DukeMTMC-attribute.txt). You are free to share, create and adapt the DukeMTMC-reID dataset, in the manner specified in the license.

We also include the [LICENSE_DukeMTMC](https://github.com/vana77/DukeMTMC-attribute/blob/master/LICENSE_DukeMTMC.txt). If you want to share, create and adapt the DukeMTMC dataset, please follow this license.

The original DukeMTMC-attribute evaluation code is under the MIT License. We niether own or share resposiblity for the annotation errors.

The original PETA dataset is licensed in terms as specified by http://mmlab.ie.cuhk.edu.hk/projects/PETA.html, we neither own or share responsiblity for the annotations given here. Instead its a mere csv conversion of the mat files for ease of my personal use.

