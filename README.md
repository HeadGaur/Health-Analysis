# Health-Analysis

About this Dataset
## Health - Care

Health is very first base of every creature. It doesn't matter if it is human, Animal, Trees or crops. But in todays hectic life we have forgotten about this basic thing. 
Here is the dataset of various employees and their response + score and question that we asked.
This Dataset is regarding the Data gathered from various employees and there daily routine + their body checkups + other related information.

## Dataset -

hra_qna_scores.csv : This csv file contains Question Id and related Score. 
hra_responses.csv : This csv file contains response of the user, when response is stored and how related question Id and user Id. 
users_data.csv : Here This csv file contains user data and when the user account is created.
sponsor_data.csv : This csv file is contains the sponsors.

## Acknowledgements

A Very Big Thank to all the users that took time to fill all the details.

## Inspiration

EDA.
Prediction of different disease for users.
Creativity of the data scientist is welcomed.
Al the best. 
Happy learning!

## Notebook 
I have used here python with SQL in this notebook. This is how we can use Pandasql to write mysql queries. 
Although using pandasql is not recommended because it reduces the performance and for large dataset it will be slow, so always try to use pandas to play with merging datasets etc. thats more easy to use too.

I have scratched different insights from the dataset eg. how many person smoke and how many males and females are there. 

Also, I have predicted the diabetes patient who never took the diabetes assessment to check. For which i got a good output as i have used Logistic Regression here and type-1 error can be negalected in confusion matrix in the end. Why?

Because if model says that perticular person is having diabetes but in actual person is negative for it then thats fine. 
But if person is Actually Diabetes +ve and model predicted it as Diabetes -ve then thats type-2 error and that is more dangerous for someone's life.

here type-2 error is none.


# NOTE : In Github, Plotly library does not work , so if you want to see the every visualization please visit following Link
https://www.kaggle.com/kartikgo/health-care-notebook/notebook
