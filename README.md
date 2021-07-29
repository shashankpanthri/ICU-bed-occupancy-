# ICU-Bed-Occupancy
Prediction for free beds available for ICU using various features.

I.	ABSTRACT

Predicting the bed occupancy of intensive care unit (ICU) is a dynamic task. The uncertainty associated with critically ill patient and random arrival patient, severity of new patient leads to the bed capacity problem, and we need to take productive measure to improve the condition. In this project, we work toward creating predictive model using regression model and improving the prediction with minimizing loss.

 
II.	Introduction

In the current era there is increase in monitoring patient’s details in digital form with the improvement in the technology we can further improve the hospital facilities by predicting ICU beds availability. Predicting free beds availability can be difficult task because of the unexpected arrival of the patients and dynamic reasons. The development of an automated model will assist physician in these matter and there will be a clear understanding of the beds availability.
In this section, we stimulate a mathematical mode to predict the ICU bed occupancy.
Even though the model can be applied to any unit, but we believe that it is reasonable to focus more on ICU beds availability as ICU is more critical since it is expensive and its important block of hospitals.
This section is divided into 2 sections in which first we introduce the concept of linear regression on which the model is based and second is to retrieve the data and process the hospitals records then formulating linear regression model to predict ICU occupancies.

Linear regression 
Linear regression is a ML algorithm user for supervised learning. Linear regression perform task to predict a dependent variable (Target) based on the given independent variable. So this regression technique is find out a linear relation between dependent and independent variable 
 

III.	Problem Description
In the study we address scheduling problem of beds, which hospitals faced during unavailability of beds However, in real-life hospitals, not all patients are of the same medical specialty and not all patients of the same medical specialty take the same path. Hence, we deal with a wide variety of different patient paths and different LOS in each unit.
Therefore, this in particular is a mathematical model for simulating daily bed occupancy in an intensive care unit.

IV.	Methodology

In this section we will discuss how we acquire data set and how is data processed. Next, we proceed by introducing algorithm we used in our work.
Data Extraction 
The data concern all adults’ patients and we have nearly 4000 entries which comprises data from hospitals from multiple countries like Los Angeles, Contra Costa, Alameda, Fresno, Imperial, Inyo and more these records are from year 2005 to 2015.
The data comprises of following features like, year, COUNTY, OSHPD_ID, Facility Name, Licensed Bed Classification, License Bed Designation, Licensed Bed Day, Discharges, Census Day, Intra Hospital Transfer from Critical Care, available beds, County labels, Facility Label, Beds Required.

Data pre-processing for extraction of features and labels
1)	We will look for null values and we will manage the null values either by dropping complete row or by filling null values with mean as required.
2)	Now we will remove columns, which have no effect on prediction and will remove those columns.
3)	We will identify target class and visualization is performed as required.
4)	Further, with this, we will be having a trend of patients and according to that after splitting data, we will further move to the implementation part of model.
5)	At last, we will predict the availability of model with the help of our stimulation model.

