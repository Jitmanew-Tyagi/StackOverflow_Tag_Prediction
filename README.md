# StackOverflow_Tag_Prediction
StackOverflow Tag Prediction using multi_label classification.

## This is based on a recruiting drive by facebook carried around the globe for Data Scientist position.

The problem can be stated as multi-label classification problem where tags are the classes.
A question on StackOverflow can belong to more than one class simultaneously, or in other words can have more than on tag.
For example a question may belong to tags "Machine Learning","NLP","KNN".

### Description:
StackOverflow is a platform where programmers across the world ask their programming queries and other programmers help them to overcome it. 
To make this process fast we classify the problem into certain categories so that the programmers active in that categories can be shown the
question for fast answer.

### Things to be taken care of:

    Predicting as many tags as possible with high precision and recall.
    Wrong tags may result into bad user experience.
    No strict latency.

### Data Overview:

Train.csv contains 4 columns: Id,Title,Body,Tags.
Test.csv contains the same columns but without the Tags, which you are to predict.
Size of Train.csv - 6.75GB
Size of Test.csv - 2GB
Number of rows in Train.csv = 6034195

### Data Fields:

    ID: Unique identity of each question asked.
    Title: The heading or the brief description of the problem
    Body: Body of the question.
    Tags: The tags associated with the question.
    
    
