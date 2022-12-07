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


In this data set $5,000 to $108,590 reflecting various loan types for each applicant. As you the Density graph implicates in the visual the application type in value counts. The density upward swing peeks at 0.00010 at 0. 

<img width="462" alt="image" src="https://user-images.githubusercontent.com/107796290/205516413-cd5550f0-336b-4070-af87-22c9af6666b4.png">

There are two additional approaches, to collapse the rare data values into “other” category. The second approach would be to provide the data points new corresponding values to classify the dataset. These two approaches are known as bucketing. This wraps up the categorical variables for the loan type. 


The table shows the results of the binning approach:
<img width="379" alt="image" src="https://user-images.githubusercontent.com/107796290/205516429-87c48c0f-8146-426c-9ace-48100d8ecc22.png">

The density plot most common unique values have more than 0 instances within the dataset. The bucket appears less than 0 times in any data set. 

<img width="514" alt="image" src="https://user-images.githubusercontent.com/107796290/205516463-f3fa91d5-5f82-416a-ba02-01fa62815c98.png">


Visualize the value counts of CLASSIFICATION 

One-hot encoding was to identify the unique column value to split the categorical column values. This process accelerates the memory course the data difficulty to navigate during the filtering process. This will fit our values to run the dataset. This process was to join the two data frames. 
 
<img width="1335" alt="image" src="https://user-images.githubusercontent.com/107796290/205516477-07edff13-fe03-4e39-bfea-9da91e909b35.png">


The Results:

As you have reviewed several of the most common scaffold processes to organize the neutral network testing and training using bucketing and encoding as with as other techniques to demonstrate where to make investments for loan prediction risk analysis that would be accurate and implicate the potential losses.

The next process is to compile, train and evaluate the model the dataset. Basic neutral networking with several neurons to create a deeper understanding with hidden layers to deep operational changes to neural networking. This was done twice to compare the accuracy and loss of potential credit risk and investment.
This was the  
<img width="537" alt="image" src="https://user-images.githubusercontent.com/107796290/205516482-50cebc10-a1f0-4d90-ac2e-38024674e5e0.png">
 
As we review the deep learning in the model performance metric, the model identify employees who's application is at risk approximately ____ of the time. As you can see the performance of the second test designs results are shared in the below summary results. 


Summary results:

In conclusion, the prediction of application type expressed in the table below indicating the type pf appplication. 

 <img width="1277" alt="image" src="https://user-images.githubusercontent.com/107796290/205516496-4109dedc-e972-428c-965a-03eeda019064.png">
 
  The results for the network can evaluate high order nonlinear reoccurrences of the data value weight or density subsequently conducting a potential superior outcome.  The hidden nodes layers are indicated below for two node layers an outer layer. As you can see based on the compilation, train and evaluation model based on the results the overarching accuracy is 0.729912519454956 which is close to the target predictive accuracy 75% however not optimized achievement. 
<img width="574" alt="image" src="https://user-images.githubusercontent.com/107796290/205516544-f12a4856-db21-425e-831e-7b2d8e236be9.png">

  As opposed to the next compilation, train and evaluation model using several nodes and accuracy results were processed with 5 node layers. 

 <img width="558" alt="image" src="https://user-images.githubusercontent.com/107796290/205516577-e416627a-65ed-4651-8601-8fac7ebadb6f.png">
<img width="614" alt="image" src="https://user-images.githubusercontent.com/107796290/205516564-00203312-94f1-41ca-b1d2-4f9e3d4008ef.png">

The potential loss indicated 0.5543 and the prediction for accuracy 0.7301457524299622 which is close to the target predictive accuracy 75% however to optimize achievement. 

We are comparing both models predictive accuracy and the calcuations are veryt similar., Either model will be able to prediction the risk of the loan ore than 70% of the time. As you recall the logical regression model vs the neutral network are more like to overfit and can be more difficult to trian than the logical regresssion. Hoverever the neural network thrive in larger data set similarly to the data we have been using a predictive model across neurons  due to deep learning evaulation of every interaction. 
