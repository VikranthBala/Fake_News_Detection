# Fake_News_Detection
Model that can classify whether news given is Real or Fake

In this project, I am making a model which can classify fake news and real news in Python.

* The dataset used for this project is a news Dataset that has title, content of various news articles and whether they are true or not.

### Data Preprocessing:
* The dataset chosen is clean so there is no need for data prepreocessing

### Data Analysis:
* The dataset has 4 columns, out of which one is the label and the columns title and unnamed: 0 are not giving any useful information. So the only useful column is text column which has the content of the news articles.

### Model Selection:

* Size of training data = 80% of news dataset :::: size of test dataset  = 20% of news dataset
* As the data is text, the frequency with which words repeat is the basis of classificaion. The model used is PassiveAggressiveClassifier.

### Result:

* The model was about to classify the news with an accuracy of around 94%

## Look for the data set [here](https://drive.google.com/drive/folders/1_3dXHmZUSEWCMJOiWziJSRzvxBKhHS-c?usp=sharing)

(The Dataset does not belong to me) 
