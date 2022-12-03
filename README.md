# AIMLCCE_Final-Project
<h1>Ingredient Analyser
for Consumables</h1>

<ul>Description</ul>
This tool aims to provide a means to judge the safety of consumable products based on the additives present in the ingredient list.
It uses a ML classification model to effiently rank the product on a scale of 1 to 5. 5 being the safest.

<ul>Steps to test the tool</ul>
[Click here to open the web service](http://swathi071094.pythonanywhere.com/)
1. Copy the ingredient list of the chosen product from any shopping service/ingredient database and click on the
“Classifier” link.
OR
Click on the “Sample ingredients” link and copy any ingredient list from the list provided and click on the “Go to Classifier”
link below the table.
2. Paste the ingredient list in the form box and click classify to see how safe the product is ranked on a scale of 1-5 where 5
is the safest.

<ul>Stages invovled in the project</ul>

Data Collection
A collection of 10000 consumable products with their full ingredient list was obtained.

Data Preparation
Unwanted features were dropped and missing values were handled.

Labeling Records
Each Record is labeled intuitively on a scale of 1 to 5 based on the position and importance of the ingredients. Features are extracted from the ingredient list to train the ml model.

Training Classification Models
The data is split into training and testing subsets. Logistic Regression, Naive-Bayes     Classifier, K-Nearest Neighbors, SVM, Random Forest Classifier and  Decision Tree Classifier models are used to build classification models on the training data set.

Choosing the best Model
Performance metrics of the classification models are analyzed to choose the best model.

Serialization/Pickling
The trained model is saved into a file using Pickle module.

Designing a Web Service
A simple flask application is developed to take inputs from the user and provide the  classification.

Deploying
An HTML interface is built and hosted for ease of use.

<ul>Future Scope:</ul>
More samples should be collected and more features should be fed to the model to cover more scenarios and increase efficiency.
A mobile application which scans ingredients using image to text conversion should be built using the existing API.

Authored by:
Swathi Venugopal
[mail](mailto:swa094@gmail.com)

