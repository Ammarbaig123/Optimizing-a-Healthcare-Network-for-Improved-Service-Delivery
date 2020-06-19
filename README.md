# Optimizing-a-Healthcare-Network-for-Improved-Service-Delivery

# Overview
The Washington State Health Ministry would like to optimally upgrade staff or resources in existing facilities across Washington so that they can allocate resources to where they are most needed, based on demand for services in different geographic regions/areas. The document proposes the following solutions to address this problem 

•	Optimizing the resource allocation process by increasing the resources capacity in some facilities and decreasing capacity in others to allocate resources where they are most needed, hence making services more accessible to patients.

•	Calculating the travel time from one area facility to another, and visualizing the distance on map so that people only travel to their nearby facility, therefore minimizing the time and distance cost.

# About Files
Data_preprocessing.ipynb inputs poverty_status.csv and Age_data.csv data from Area zip code folders,preprocesses the data and outputs Structured_data.csv file.

Optimizing-a-Healthcare-Network-for-Improved-Service-Delivery.ipynb reads Structured_data.csv file,allocates staff optimally,calculate distances from one facilitiy to another and visualize the distances on map. 

Distance_Matrix_API.ipynb make use of google distance matrix api to create a matrix of duration and distances bewteen facilities.The output is a Distance_matrix.csv file

Calculate_Travel_Time.ipynb prints a pivot table demonstrating travel time between facilities using different travel modes





