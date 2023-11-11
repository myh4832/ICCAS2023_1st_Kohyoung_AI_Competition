# ICCAS2023_1st_Kohyoung_AI_Competition
## Problems
Problem: Large Scale Optical Text Incremental Learning
All images of each folder are assigned one designated label. It means that each folder is associated with a certain label. For convenience, it can be said that all images of the folder named 59 are labeled with 59. Design a total of ten network models that take one image of a prescribed pixel size as input and return its label as output. A first network model is trained on data labeled 1 to 100, and tested on data from the same classes. A second network model initialized with the first one is additionally trained on data labeled 101 to 200 and tested on data labeled 1 to 200. In the same way, a third network model initialized with the second one is additionally trained on data labeled 201 to 300 and tested on data labeled 1 to 300. Repeating this produces a total of 10 network models and the 10 resulting test scores.

![image1](https://github.com/myh4832/ICCAS2023_1st_Kohyoung_AI_Competition/blob/main/Koh_Young_AI_data/1/0.png)
![image2](https://github.com/myh4832/ICCAS2023_1st_Kohyoung_AI_Competition/blob/main/Koh_Young_AI_data/14/0.png)