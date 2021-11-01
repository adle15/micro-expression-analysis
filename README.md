#Micro Expression Analysis with SMIC Database
##This repo contains my final project to obtain Bachelor Degree

I was using SMIC-Cropped dataset (can requested [here](https://www.oulu.fi/cmvs/node/41319) for research purpose only) .
CNN VGG19 (feature extractor) and Random Forest (classifier) is used for this project.

You need some python library:
>numpy, tensorflow, matplotlib, open-cv2, keras, seaborn, etc

There's 3 different camera in the database. 

![alt text](https://github.com/adle15/micro-expression-analysis/blob/master/reg_06387.bmp)
![alt text](https://github.com/adle15/micro-expression-analysis/blob/master/reg_06524.bmp)
![alt text](https://github.com/adle15/micro-expression-analysis/blob/master/reg_image036237.bmp).

First one is NIR camera, second one is VIS camera, and the last one is HS camera.

For detailed dataset please visit the official dataset link which I already mentioned.

>This project do analysis for each camera.

>Split the dataset for every 10%, start from 50:50

>Do feature extraction with CNN

>Do classification with Random Forest.

There's example result of the analysis

![alt text](https://github.com/adle15/micro-expression-analysis/blob/98380a79198f311770f0c359d03a0b511b893f6a/result-sample.png)
