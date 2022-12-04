# Neural_Network_Charity_Analysis
Alphabet Soup Charity

  The purpose of this project was to process the data for neutral network, test the data to predict where to make investments for loan prediction risk analysis that would be accurate and implicate the potential losses.
•	In the first neutral network model preprocessing we were to create a density plot for column values, 
•	create binds for low counts.
•	place rare categorical values in a separate column.
•	create an instance of OneHotEncoder and fit the values of the encoder.
•	merger and drop the original column for EID and Name in the DataFrame.
•	use standardize the numerical value using the StandardScaler model. 
•	create a categorized variable list.
•	process and split data into target features arrays to scale the dataset.
•	This was completed in two environments one the jupyter notebook using python until the kernel indicated were dead resulting the use of google colab python3 to process the data for neutral network. 

  First steps were to read the Charity data csv file to a panda DataFrame to the variables to determine and consider the features for the targets of the model. In doing so I had to drop the EIN and name column since they were not relevant to the data and decide to use unique values, to filter the data. Next, density plot to create a column for distinctive variables in a new column and review if binning outcome. In addition, to place the data in a new DataFrame by creating a variable entity to encode one-hot conversion to merge the two DataFrames the original and the one-hot encoded DataFrame. 
There are 17 a
Accouraging to the data set reflecting 17 application types with 2 special considerations and 2 successful out of 9 applicants who have income. 

 As you can view below the two merged DataFrames:
 <img width="1221" alt="image" src="https://user-images.githubusercontent.com/107796290/205516347-3114d9c0-dc6a-4caa-8365-a47c15576d9f.png">


In this data set we can see the various types of loans amounts from $5,000 to $108,590 reflecting various loan types for each applicant.

 
As you the Density graph implicates in the visual the application type in value counts. The density upward swing peeks at 0.00010 at 0. 




 




There are two additional approaches, to collapse the rare data values into “other” category. The second approach would be to provide the data points new corresponding values to classify the dataset. These two approaches are known as bucketing.   This wraps up the categorical variables for the loan type. 

The table shows the results of the binning approach:

 

The density plot most common unique values have more than 0 instances within the dataset. The bucket appears less than 0 times in any data set. 


 

Visualize the value counts of CLASSIFICATION 

One-hot encoding was to identify the unique column value to split the categorical column values. This process accelerates the memory course the data difficulty to navigate during the filtering process. This will fit our values to run the dataset. This process was to join the two data frames. 
 


The Results:

As you have reviewed several of the most common scaffold processes to organize the neutral network testing and training using bucketing and encoding as with as other techniques to demonstrate where to make investments for loan prediction risk analysis that would be accurate and implicate the potential losses.

The next process is to compile, train and evaluate the model the dataset. Basic neutral networking with several neurons to create a deeper understanding with hidden layers to deep operational changes to neural networking. This was done twice to compare the accuracy and loss of potential credit risk and investment.
This was the  
 



Summary of results:

In conclusion, the prediction of application types were expressed in the below table 

 
  
  The results for the network can evaluate high order nonlinear reoccurrences of the data value weight or density subsequently conducting a potential superior outcome.  The hidden nodes layers are indicated below for two node layers an outer layer. As you can see based on the compilation, train and evaluation model based on the results the overarching accuracy is 0.729912519454956 which is close to the target predictive accuracy 75% however not optimized achievement. 


  As opposed to the next compilation, train and evaluation model using several nodes and accuracy results were processed with 5 node layers. 


 

The potential loss indicated 0.5543 and the prediction for accuracy 0.7301457524299622 which is close to the target predictive accuracy 75% however to optimize achievement. 


 




![image](https://user-images.githubusercontent.com/107796290/205516315-549f3fc6-24e6-4a1a-92a6-8ccb89b4bbda.png)
