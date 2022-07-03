# WebMarket_Object_Detection_Project

**Deliverable expected from this project:**

1. Follow ML model training paradigms.
2. Code quality
3. A utility script that takes the model's weight file, a folder name as input, does inference on the images in the folder, and plots the results with corresponding confidence scores.
4. Any other utility scripts that could help train, evaluate, or analyse the model easily.


**About Data**
## 1. What we have is:
### Images : I have downloaded the dataset on Kaggle - ![Kaggle Link]([https://www.kaggle.com/manikchitralwar/webmarket-dataset]) 

and their 
### Annotation in csv format : ![Annotations](https://github.com/ParallelDots/generic-sku-detection-benchmark/tree/master/annotations/WebMarket)

## Data format we have :
![](https://github.com/Pushpadant07/WebMarket_Object_Detection_Project/blob/main/Images/1.PNG)

## 2. The data format we want :
![](https://github.com/Pushpadant07/WebMarket_Object_Detection_Project/blob/main/Images/2.PNG)

To modify the csv file to required format:
* First I have read the data.
* Extract the integers from the `filename` coloumn and created a new coloumn and added into the dataset 
* `Sorted` the whole data from that new coloumn in ascending order.
* See all the Code step by step in ![ Modify CSV file jupyter Notebook](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Modify%20CSV%20file.ipynb)


## 3. Generating a YOLO v5 PyTorch file for the model

* First `Create an account` on ![Roboflow](https://roboflow.com/) and create a `new project` and `upload` all the images with their annotations

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Images/3.PNG)

* Split the data into `70 (train)-20 (test)-10 (test)` 

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Images/6.PNG)

* export the file in `YOLO v5 PyTorch format`

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Images/4.PNG)


## 4. Model Selection

The YOLOv5 PyTorch training and architecture conversion was the most notable contribution, making YOLO easier than ever to train, speeding up training time 10x relative to Darknet.

![](https://blog.roboflow.com/content/images/2020/12/image.png)

## 5. Model Training:


Every thing is explained in the ![ Colab Notebook ](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/WebMarket_Scaled_YOLOv4.ipynb)


## 6 Results:
![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(1).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(2).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(3).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(4).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(5).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(6).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(7).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(8).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(9).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(10).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(11).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(12).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(13).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(14).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(15).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(16).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(17).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(18).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(19).jfif)
==============================================================================================================

![](https://github.com/ChitralwarManik/WebMarket_Object_Detection/blob/main/Results/download%20(20).jfif)


I can also deploy this project and create a web app if you want i also have some experience with API tool like flask and Streamlit, please let me know Thank You...
`````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
