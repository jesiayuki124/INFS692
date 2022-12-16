Jesia Quader Yuki
261000586

                                                   Capstone Project


The models have been divided into three parts such as Model 1, Model 2 and Model 3.

Model 1- Based on three ensemble classification model.
A stacked ensemble is trained using Random Forest, Generalised Logistic Model (glm) and Generalized Boosted Model (gbm).

Model 2- Based on a  neural network-based classification model .

Model 3- Based on K-Means, Hierarchical and Model Based.


Packages that are required to run the model:-

# Helper packages
 
library(rsample)  # for data splitting

# Modeling packages
library(caret)    # for classification and regression training
library(kernlab)  # for fitting SVMs
library(modeldata) #for attrition data

# Model interpretability packages
library(pdp)      # for partial dependence plots, etc.
library(vip)      # for variable importance plots


library(readr)
library(dplyr)
library(plyr)


library(rmarkdown)
library(ggplot2)     # data visualization
library(h2o) # performing dimension reduction
library(RIA)
library(recipes)   # for minor feature engineering tasks
library(stringr)     # for string functionality
library(gridExtra)   # for manipulaiting the grid

# Modeling packages
library(tidyverse)  # data manipulation
library(cluster)     # for general clustering algorithms
library(factoextra)  # for visualizing cluster results
library(mclust)   # for fitting clustering algorithms

library(tensorflow)
library(keras)


How to make PDF
Open Capstone.Rmd file and then on the top select Knit to PDF to form PDF file. (PDF file attached as Capstone.pdf)

Notes:
1) All codes are completed in the file "Capstone.Rmd" including models- Model 1, Model 2 and Model 3.
2) The PDF file contains the output for Model 1 and Model 3 only. This is beacuse I 
have some issues in R studio to run neural network model. As disscussed in class, R studio fails to connect to local host. 
This OOPENSSL problem is ongoing, thus Windows doesn't have solution till now. 
3) Please consider for skipping Model 2 while generating the PDF. I believe, it is common problem for window users as
seen different people discussing on different platforms such as StackOverFlow etc on this issue.

